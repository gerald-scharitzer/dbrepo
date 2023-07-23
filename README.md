# DBRepo by TU Wien

Get started with [DBRepo](https://www.ifs.tuwien.ac.at/infrastructures/dbrepo/) on Linux.

## Install Docker Engine

on Ubuntu Linux as in https://docs.docker.com/engine/install/ubuntu/.

Check that packages from other version are not installed.

	$ apt list --installed docker.io docker-doc docker-compose podman-docker containerd runc

should result in `Listing... Done` only.

### Install Docker Engine via Docker Desktop

on Linux as in https://docs.docker.com/desktop/install/linux-install/.

Load the KVM kernel module.

	$ modprobe kvm

Load the matching module based on your processor.

	$ modprobe kvm_amd    # for AMD processors
	$ modprobe kvm_intel  # for Intel processors

Check that KVM is supported.

	$ kvm-ok

Check that Docker Desktop is not installed already.

	$ apt list --installed docker-desktop
