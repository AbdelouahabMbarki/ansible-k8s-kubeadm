# Ansible-based Kubernetes cluster instalation with Kubeadm
This is a Kubernetes cluster installation using Ansible and Kubeadm .

## Quick Start Guide
  1. [Edit your invontory file](./inventory), adding your server ips to ansible_host

## Build and configure the envirenement 
  1. Run `ansible-playbook -i inventory  main.yml`