# Istio Demo 1.0

## This demo is based on istio-tutorial available at https://github.com/redhat-developer-demos/istio-tutorial/tree/1.0.

## Before you start

You can run this demo locally or remotely using one of these methods below:

* Local (minishift)
* Remote cluster

## Pre-req

* Maven
* siege
* minishift (if you want to run this demo in your machine)
* Openshift cluster (if you want to run this demo remotely)
* oc binary in your $PATH

## Minishift

Install Istio

    ansible-playbook playbook-setup.yml

Run Demo

    ansible-playbook playbook-demo.yml

## Remote cluster

Install Istio

    ansible-playbook playbook-setup-cloud.yml

Run Demo

    ansible-playbook playbook-demo-cloud.yml