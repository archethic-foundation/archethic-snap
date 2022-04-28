# Archethic Snap Package

Welcome to the Archethic Node snap package! This tool enables you to install and run an Archethic node very easily. Archethic is a next generation of blockchain focused on rapid scalability and easy accessibility.

## Archethic features:

✅ Fast transaction processing (> 1M tps)

✅ Lower energy consumption than other blockchain

✅ Designed with a high level of security (ARCH consensus supporting 90% of maliciousness)

✅ Adaptive cryptographic algorithms (quantum resistant)

✅ Decentralised Identity and Self Sovereign Identity

✅ Smart contract platform powered by a built-in interpreter

✅ Strong scalability with geo secured sharding

✅ Soft-Real-Time P2P view with supervised networking


## Build Your Own Snap

First let's install Snapcraft to build our snap.

```sh
sudo snap install --classic snapcraft
```

We can use LXD containers to build our snap so that build dependencies do not conflict with the host environment. 

The easiest way to add LXD to your system is via its snap:

```sh
sudo snap install lxd
```

Now initialise LXD with the following command, accepting all the default options unless you have specific requirements:

```sh
sudo lxd init
```
> :warning: If the system you are installing LXD onto is using a network with a 10.x.x.x subnet then network creation may fail.

Finally to build our snap, go to project root and run:

```sh
snapcraft --use-lxd --debug
```
## Install your snap

After building the snap, a .snap file will be added in the project root. Install it by running:

```sh
sudo snap install --devmode archethic-node_${VERSION}_amd64.snap
```
> **VERSION** → Archethic snap version

## Coming Soon

- [ ] GitOps continuous delivery integration with archethic-node repository
- [ ] Stable channel release
