fuel-kvm-local
========
Description
----------------------
This is a collection of scripts to deploy small Fuel clusters locally
with default for Fuel network configuration using KVM hypervisor
(similar to the VirtualBox scripts from fuel-main repo).
Currently the only supported distro is Ubuntu.

Fuel cluster deployment
----------------------
To deploy Fuel cluster with N slaves execute:
sudo bash deploy_fuel.sh <path-to-fuel-iso> <slaves-number>

Note that VMs' configuration can be changed in deploy_fuel.sh script

