# 🏠 Homelab

Welcome to my homelab! This is where I explore Kubernetes, DevOps, self-hosted apps, networking, and automation—all from home.

## 🌟 Goals
- Learn Kubernetes by building and maintaining a real-world setup.
- Deploy and manage custom Java and Go applications in a Kubernetes environment.
- Set up observability tools like Grafana and Prometheus for monitoring.
- Automate workflows using Bash scripts and Kubernetes manifests.
- Clearly document configurations, tools, and lessons learned along the way.

## 🖥️ Hardware

My homelab runs on a cluster of compact and power-efficient Lenovo mini PCs. These are ideal for experimenting with Kubernetes and self-hosted applications while keeping power usage low.

### Nodes

- **Lenovo ThinkCentre M910q** – Intel i7-6700 @ 3.40GHz / 16GB RAM / 480GB SSD
- **Lenovo ThinkCentre M910q** – Intel i7-6700 @ 3.40GHz / 16GB RAM / 480GB SSD
- **Lenovo ThinkCentre M910q** – Intel i7-6700 @ 3.40GHz / 16GB RAM / 480GB SSD

🏗️ Cluster Provisioning & Architecture
To gain a deep understanding of Kubernetes internals, I provisioned the cluster entirely by hand using the “Kubernetes the Hard Way” approach. Each machine runs Ubuntu, and I manually configured every component — from certificate generation and networking to control plane services and kubelet configuration.

The cluster consists of one control plane node and two worker nodes, mirroring a minimal but realistic production-grade topology. This hands-on setup has been instrumental in learning how Kubernetes works under the hood and how to manage it at the system level.
