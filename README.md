# Consul Experiment

Consul is a cluster management tool from Hashicorp and it is very useful for creating advanced micro-services architecture. Consul is a distributed configuration system which provides high availability, multi-data center, service discovery and High fault tolerance. So managing micro-services with consul is pretty easy and simple.

This playbook has a script for sample microservice environment provisined with vagrant.
## Installation:

1. Install Vagrant
2. Clone this repo and `cd consul_experiment` and run `vagrant up`
3. Download ansible role `ansible-galaxy install PrabhuVignesh.consul_installer`
5. Uncomment `host_key_checking = False` from "`/etc/ansible/ansible.cfg`" for disabling ssh key based auth.
4. Run the playbook from consul_experiment directory `ansible-playbook -i inventory consul_playbook.yml`

go to your browser and type http://172.28.128.14:8500/ui to see dashboard of consul client

**Please follow the article(http://devopscube.com/consul-service-discovery-beginners-guide/) for more detail**


## test
