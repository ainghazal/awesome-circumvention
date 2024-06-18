# Awesome Circumvention [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Censorship Circumvention resources (research, protocols, libraries, tools and events.)

## Contents

- [Protocols](#protocols)
- [Tools](#tools)
- [Libraries](#libraries)
- [Research](#research)
- [Discussion](#discussion)
- [Events](#events)
- [Contribute](#contribute)

## Protocols

> A survey of protocols being used in the wild.

### Tunneling protocols

- [OpenVPN](http://example.com)
- [WireGuard](http://example.com)

### Fully Obfuscated Protocols

- [Shadowsocks](http://example.com)
- [obfs4](http://example.com)
- [List item](http://example.com)

### Pluggable Transports

- [Pluggable Transport Specification](https://spec.torproject.org/pt-spec/)

## Tools

> Circumvention solutions, or tools that incorporate some form of circumvention.

### Provisioning

- [Outline Server](https://github.com/Jigsaw-Code/outline-server) An Outline server runs instances of Shadowsocks proxies and provides an API used by the Outline Manager application.

### Clients

- [AmneziaVPN](https://github.com/amnezia-vpn/amnezia-client) Amnezia is an
open-source VPN client, with a key feature that enables you to deploy your
own VPN server. It uses the OpenVPN, WireGuard, Shadowsocks, IKev2 and Cloak
protocols. 
- [psiphon](https://github.com/Psiphon-Inc/psiphon)
- [warp-plus](https://github.com/bepass-org/warp-plus) Warp-Plus is an
- open-source implementation of Cloudflare's Warp, enhanced with Psiphon
- integration for circumventing censorship. This project aims to provide a
- robust and cross-platform VPN solution that can use psiphon on top of warp
- and warp-in-warp for changing the user virtual nat location.

## Libraries

> Libraries and toolkits to build your own tools.

### Go

- [bepass][https://github.com/bepass-org/bepass] Bepass is an advanced tool designed to bypass Iran's Deep Packet Inspection (DPI) system using a TLS client hello splitting attack. It also enables the deployment of a VLESS-like proxy on Cloudflare Workers.
- [cloak](https://github.com/cbeuw/Cloak) A pluggable transport.
- [dnstt](https://www.bamsoftware.com/git/dnstt.git/) Userspace DNS tunnel with support for DoH and DoT
- [gluetun vpn client](https://github.com/qdm12/gluetun) Dockerized, multi-provider VPN.
- [gost](https://github.com/ginuerzh/gost) Go Simple Tunnel is a polyglot multi-purpose proxy that speaks differen obfuscation protocols. Has cool features like dynamic service configuration.
- [outline SDK](https://github.com/Jigsaw-Code/outline-sdk) A library to add network-level interference protection to existing apps.
- [snowflake](https://github.com/keroserene/snowflake) Pluggable Transport using WebRTC, inspired by Flashproxy.
- [swgp-go](https://github.com/database64128/swgp-go) 🐉 Simple WireGuard proxy with minimal overhead for WireGuard traffic.
- [v2ray-core](https://github.com/v2fly/v2ray-core) 
- [water](https://github.com/gaukas/water) W.A.T.E.R.: WebAssembly Transport Executables Runtime

### Python

- [DPYProxy](https://github.com/UPB-SysSec/DPYProxy) A python proxy that implements DPI evasion mechanisms. Currently, TLS record fragmentation and TCP Fragmentation are implemented.
- [geneva](https://github.com/Kkevsterrr/geneva) automated censorship evasion for the client-side and server-side.

### Rust

- [arti](https://tpo.pages.torproject.net/core/arti/) Tor, in rust.
- [proteus](https://github.com/unblockable/proteus) Programmable Protocols for Censorship Circumvention.

## Discussion

- [https://ntc.party](https://ntc.party/)
- [https://github.com/net4people/bbs](https://github.com/net4people/bbs)

## Research

### General View

- [RFC 9505: A Survey of Worldwide Censorship Techniques](https://datatracker.ietf.org/doc/rfc9505/?ref=internet.exchangepoint.tech)

### Paper Collections

- [CensorBib](https://censorbib.nymity.ch/)

### Theses

- [Measuring and circumventing Internet censorship](http://www.diva-portal.org/smash/get/diva2:758124/FULLTEXT01.pdf) Phillipp Winter (2014).
- [Towards more Effective Censorship Resistance Systems](https://uwspace.uwaterloo.ca/bitstream/handle/10012/9744/Elahi_MohammadTariq.pdf?sequence=1) Tariq Elahi (2015). 
- [Threat modeling and circumvention of Internet censorship](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2017/EECS-2017-225.html) David Fifield (2017). 
- [Recipes for Resistance: A Censorship Circumvention Cookbook](https://uwspace.uwaterloo.ca/handle/10012/13595) Cecylia Bocovich (2018). 

### Organizations 

- [Censored Planet](https://censoredplanet.org/)
- [CensorFail](https://censor.fail/)
- [Project X](https://xtls.github.io/en/) Home of XTLS, Xray, V2Ray
- [Roskomsvoboda](https://roskomsvoboda.org/en/)
- [OONI](https://ooni.org/)

## Events

- [FOCI](https://foci.community/) Free and Open Coomunications on the Internet

## Region specific

- [Great Firewall Report](https://gfw.report/)
- [DPI detector](https://dpidetector.org/en/) VPN Protocols Availability Monitoring in Russia

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
