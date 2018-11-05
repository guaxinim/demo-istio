# Istio Demo 1.0

## This demo is based on istio-tutorial available at https://github.com/redhat-developer-demos/istio-tutorial/tree/1.0.

## There 2 versions of playbooks to setup and run demo.
* Local (minishift)
* Remote cluster

## Minishift
Install Istio
* ansible-playbook playbook-setup.yml

Run Demo
* ansible-playbook playbook-demo.yml

## Remote cluster
Install Istio
* ansible-playbook playbook-setup-cloud.yml

Run Demo
* ansible-playbook playbook-demo-cloud.yml



