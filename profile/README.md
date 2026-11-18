# syarc-oss

Open-source tools for off-grid, self-hosted community communication — no
cloud, no vendor servers. Built and battle-tested on a two-continent LoRa
mesh (MeshCore) with a Rust web console, internet-linked dens, and
 Codec2 voice / AV1 photo relay between isolated meshes.

## Projects

| Repo | What it does |
|------|--------------|
| [bearden-bridge](https://github.com/syarc-oss/bearden-bridge) | MeshCore LoRa room-server bridge: Matrix/XMPP backends, Open TAK voice (Codec2) & photo (AV1) clip relay, and a store-and-forward tunnel that links two isolated meshes over the internet |
| [syarc-console](https://github.com/syarc-oss/syarc-console) | Self-hosted Rust web console: accounts, messaging, LoRa mesh tooling, family media library, calendar, SQLCipher-encrypted ledgers, surveillance, offline knowledge base |

## Why

Ham radio and emergency-preparedness communities need software that keeps
working when the internet doesn't — and that still talks to the internet
when it does, on your own terms. Everything here runs on plain SQLite and
commodity hardware (a mini PC or LXC is plenty).

## Interop

We work with the MeshCore ecosystem, including Open TAK companion apps:
salted media retransmits, 0x72 gap-fetch, and prefix-tolerant envelope
parsing — see the discussion on
[jade-on-mesh/meshcore-open-tak#150](https://github.com/jade-on-mesh/meshcore-open-tak/issues/150).
