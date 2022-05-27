[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/archethic)

Welcome to Archethic blockchain. This snap installs and runs an Archethic node. Archethic is a next generation of blockchain focused on rapid scalability and easy accessibility.
  
Archethic features:

✅ Fast transaction processing (> 1M tps)

✅ Lower energy consumption than other blockchain

✅ Designed with a high level of security (ARCH consensus supporting 90% of maliciousness)

✅ Adaptive cryptographic algorithms (quantum resistant)

✅ Decentralised Identity and Self Sovereign Identity

✅ Smart contract platform powered by a built-in interpreter

✅ Strong scalability with geo secured sharding

✅ Soft-Real-Time P2P view with supervised networking

## Installation Instructions

#### 1. Install archethic snap

To join testnet, run:

```sh
sudo snap install archethic --channel=testnet/stable
```

To join mainnet, run:

```sh
sudo snap install archethic
```

#### 2. To configure ports (optional). Make sure UPnP/NAT-PMP is available otherwise the ports need to forwarded manually from router.

```sh
sudo snap set archethic ports.http=$HTTP_PORT
sudo snap set archethic ports.p2p=$P2P_PORT
```

#### 3. Finally start the service by running:

```sh
sudo snap start archethic
```
## Disclaimer
 
Please note that this is a pre-release version which is
still undergoing final testing before its official release. The
platform, its software and all content found on it are provided on an
“as is” and “as available” basis. Archethic does not give any warranties,
whether express or implied, as to the suitability or usability of the
website, its software or any of its content.

Should you encounter any bugs, glitches, lack of functionality or
other problems on the website, please let us know immediately so we
can rectify these accordingly. Your help in this regard is greatly
appreciated! You can write to us at this address dev@archethic.net.

## Maintained by:

 Archethic Foundation
 
 https://archethic.net
