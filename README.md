# 👋 Hi, I'm Aidan Perry (aka Sive/UltraSive)

I'm a full-stack developer who enjoys building web apps, network control and data planes, as well as VM and container scheduling and orchestration.

---

## 🛠️ Projects

### 📦 [**Kubernetes Single Definition App Operator**](https://github.com/UltraSive/single-definition-app-operator)
A Kubernetes Kubebuilder operator that controls the state of other primitive resource types based on a easy to patch single custom resource definition. This is particularly designed for when I operated a app hosting platform on a wide kubernetes cluster spanning multiple regions so that i could use a single CRD and host an app across multiple regions.

### 📦 [**L4 TCP Geolocation Load Balancer**](https://github.com/UltraSive/L4GeoLB)
Rust based layer 4 proximity based multiple instance load balancer primarily for TCP connections.

### 📦 [**Ghostwire**](https://github.com/packetware/ghostwire/tree/sive)
I have a branch in Ghostwire used to improve the performance and make the YAML schema more simple to understand by using CIDRs and port ranges. It is based on the Rust Aya eBPF framework to control XDP and TC application by expanding the rules defined in the YAML definition to five tuples and to allow the reverse flows of outgoing connections to automatically be allowed back in when you define a default drop all on a destination address on the ingress interface.

### 📦 [**Fortified Firewall**](https://github.com/UltraSive/fortified-firewall)
This is a project I started based on Cilium's ebpf-go control plane for writing XDP ingress/TC egress firewalls and I planned on using Svelte 5/Sveltekit and a Postgres database as a additional UI layer for programming the control plane. 

### 📦 [**GoeBPF XDP Simple Firewall**](https://github.com/UltraSive/GoeBPF-XDP-Simple-Firewall)
This was my first ever XDP control plane based on Dropbox's framework for eBPF applications. Although there is no schema to define firewall rules you can still apply them in the golang control plane and attach it to a arbitrary Linux interface.

### 📦 [**goFilesAPI**](https://github.com/packetware/goFilesAPI)
This is a project similar to the Pterodactyl Wings daemon based on the Golang Gin web framework that will allow you to query details about a filesystem and make changes to it over a HTTP API. I used this with containers in order to build a app hosting platform with a clean web UI to allow users to make changes to the volumes attached to their services by having a instance of this binary bound to every volume.

### 📦 [**SvelteKit Looking Glass**](https://github.com/UltraSive/SvelteKit-Looking-Glass)
This is a project to create a network looking glass across multiple servers by using a monolith that can act as both a API to query its own endpoint and a frontend that can query other monoliths to get master trace route ping details to arbitrary endpoints from the monolith host.

### 📦 [**GoA2sCache**](https://github.com/UltraSive/GoA2sCache)
This is a simple steam A2s server list query cache to prevent resource exhaustion attacks by keeping a copy of the reply in a json object for a server and then also acting as a middleman to deliver the cached request to anyone querying the port.

### 📦 [**PteroRust**](https://github.com/UltraSive/pterorust.com)
I build a Svelte 4/Sveltekit Rust wipe scheduler that works based on a HTTP based cronjob to orchestrate automating Rust game servers that are hosted on Pterodactyl.

---

## 📫 Get in Touch

- Twitter: [@ultrasive](https://twitter.com/ultrasive)

---
*Thanks for stopping by! ⭐ If you like my work, consider giving a star or following me!*
