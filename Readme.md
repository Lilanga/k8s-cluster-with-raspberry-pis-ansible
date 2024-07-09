# Kubernetes cluster using Raspberry PI devices

This repository contains Ansible scripts to configure Raspberry PI devices to form a on premise Kubernetes cluster.

## Files

Repository contains two ansible playbooks

### Configure Raspberry PI Lite OS

We are using `config-network.yml` playbook to configure Raspberry PI Lite OS with nessasary configurations and packages. This is common playbook for all the Raspberry PI devices used for the cluster.

### Configure Control plane nodes

We are using `config-master.yml` playbook to configure Master node Raspberry devices to act as control plane. This is only intended for master node Raspberry PI devices.

### Inventory

We are using `hosts.yml` to configure Ansible inventory.

Please refer my blog post on [creating k8s cluster using Raspberry PI devices](https://bitsfactory.lilanga.me/posts/creating-on-prem-kubernetes-cluster-with-raspberry-pis/) for detailed guidelines.
