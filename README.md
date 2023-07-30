# DBRepo by TU Wien

Get started with [DBRepo](https://www.ifs.tuwien.ac.at/infrastructures/dbrepo/) on Linux.

## Install Docker Engine

as in https://docs.docker.com/engine/install/.

### On Ubuntu Linux

as in https://docs.docker.com/engine/install/ubuntu/.

Check that packages from other version are not installed.

	$ apt list --installed docker.io docker-doc docker-compose podman-docker containerd runc

should result in `Listing... Done` only.

Add the Docker keyring.

Add the Docker repository.

Install the Docker Engine.

Configure the overlay2 storage driver as in https://docs.docker.com/storage/storagedriver/overlayfs-driver/.

Configure rootless Docker as in https://docs.docker.com/engine/security/rootless/.
