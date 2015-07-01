Apollo Aurora Plugin
====================

This is an Apollo Plugin for running [Apache Aurora Mesos Framework](http://aurora.apache.org/) inside a docker container by using [medallia/docker-aurora-scheduler.](https://github.com/medallia/docker-aurora-scheduler)

This plugin is untested and its use in a real environment is not yet recommended.

The main purpose of this plugin at the moment is to serve as an example for [developing and deploying plugins on top of Apollo.](https://github.com/Capgemini/Apollo/blob/master/CONTRIBUTING.md)

For seeing it in action:

* Go to [https://github.com/Capgemini/Apollo/tree/master/contrib-plugins/plugins.yml](https://github.com/Capgemini/Apollo/tree/master/contrib-plugins/plugins.yml) and uncomment the code.

* Go to [https://github.com/Capgemini/Apollo/tree/master/contrib-plugins/playbook.yml](https://github.com/Capgemini/Apollo/tree/master/contrib-plugins/plugins.yml) and uncomment the code.

* Run:

```bash
ansible-galaxy install -n -r contrib-plugins/plugins.yml
/bin/bash apollo_launch.sh
```