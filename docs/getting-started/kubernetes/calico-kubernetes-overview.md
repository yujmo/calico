---
title: Overview of Kubernetes with Calico Networking
---

# Kubernetes with Calico networking
Calico can be used as a network plugin for Kubernetes to provide connectivity and network policy in a Kubernetes cluster. 
Calico allows you to enforce fine-grained network security policy natively in Kubernetes. The video below shows a quick demonstration of Calico policy in action.

[![IMAGE ALT TEXT](http://img.youtube.com/vi/OE1n5PWtvMM/0.jpg)](http://www.youtube.com/watch?v=OE1n5PWtvMM "Calico network policy on Kubernetes")

# Getting Started
The following guides help you get started with Calico.

Quick-start guides
------------------
These guides let you get a cluster set up quickly, and walk you through using Calico for networking and network policy.
- [CoreOS Vagrant](vagrant-coreos/VagrantCoreOS.md)
- [CoreOS on GCE](GCE.md)
- [CoreOS on AWS](AWS.md)

Bare-metal guides
-----------------
These guides walk you through setting up a Kubernetes cluster with Calico.
- [Integration Guide](KubernetesIntegration.md) (Recommended) - Discusses adding Calico to an existing cluster.
- [CoreOS bare-metal](http://kubernetes.io/docs/getting-started-guides/coreos/bare_metal_calico/)
- [Ubuntu bare-metal](http://kubernetes.io/docs/getting-started-guides/ubuntu-calico/)

# Requirements
- The kube-proxy must be started in `iptables` proxy mode.  This is the default as of Kubernetes v1.2.0.

# Troubleshooting 
- [Troubleshooting](Troubleshooting-Calico-Kubernetes)
