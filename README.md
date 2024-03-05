# homelab-descheduler

This is a mirco-services repo for deploying
[descheduler](https://github.com/kubernetes-sigs/descheduler)
into [my homelab](https://github.com/charlesthomas/homelab).

"deschedule" (remove) pods violating _some_ policy

in particular, boot [zigbee2mqtt](https://github.com/charlesthomas/homelab-zigbee2mqtt/) if the zigbee dongle is moved to a different node

---
This repo is templated via
[homelab-template](https://github.com/charlesthomas/homelab-template)
and automatically updated via
[🤖 Templatron](https://github.com/charlesthomas/templatron).
