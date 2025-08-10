# 👋 Hi, I'm Aidan Perry (aka Sive/UltraSive)

I'm a full-stack developer who enjoys building web apps, network control and data planes, as well as VM and container scheduling and orchestration.

---

## 🛠️ Projects

### 📦 [**Sive Chat**](https://github.com/UltraSive/sive-chat)
A multi-model LLM chat interface application written in Svelte/Kit w/ Convex + Drizzle (Postgres) for the T3 Chat Cloneathon. You can sign in via Google OpenID Connect and chat data such as messages are streamed across devices when state changes. See live: [https://chat.ultrasive.com](https://chat.ultrasive.com)

### 📦 [**Kubernetes Single Definition App Operator**](https://github.com/UltraSive/single-definition-app-operator)
A Kubernetes Kubebuilder operator that controls the state of other primitive resource types based on a easy to patch single custom resource definition. This is particularly designed for when I operated a app hosting platform on a wide kubernetes cluster spanning multiple regions so that i could use a single CRD and host an app across multiple regions.

### 📦 [**Go Looking Glass Server**](https://github.com/UltraSive/go-looking-glass-api)
A lightweight, self-hosted Looking Glass REST API written in Go that allows users to run network diagnostic commands like ping and mtr on demand. Supports both streaming and non-streaming output modes.

### 📦 [**Libvirt QEMU Hypervisor Controller**](https://github.com/UltraSive/libvirt-hypervisor-controller)
I built a stateless way to control a hypervisor node running libvirt to provision, modify, and post common actions to from a central control plane over a REST API with some helpful features like caching of remote images for a week before replacing it with a new one in order to speed up provisioning.

### 📦 [**HTTP V8 Isolates**](https://github.com/UltraSive/http-v8-isolates)
This is a way to execute ephemeral JavaScript and WebAssembly code contexts in a V8 shared runtime environment based on http request triggers. It grabs the code from object storage based on the DNS A record of the request.

### 📦 [**L4 TCP Geolocation Load Balancer**](https://github.com/UltraSive/L4GeoLB)
Rust based layer 4 proximity based multiple instance load balancer primarily for TCP connections.

### 📦 [**Ghostwire**](https://github.com/packetware/ghostwire/tree/sive)
I have a branch in Ghostwire used to improve the performance and make the YAML schema more simple to understand by using CIDRs and port ranges. It is based on the Rust Aya eBPF framework to control XDP and TC application by expanding the rules defined in the YAML definition to five tuples and to allow the reverse flows of outgoing connections to automatically be allowed back in when you define a default drop all on a destination address on the ingress interface.

### 📦 [**VNC Websockify Proxy Controller**](https://github.com/UltraSive/vnc-websockify-proxies)
For each node running VMs to give access directly to the console of the VM we employ noVNC which turns a tcp connection into a websocket and displays it with Javascript. This will fetch the current configuration of port mappings from a web server and allow for CRUD operations for updating the proxies while its running.

### 📦 [**Fortified Firewall**](https://github.com/UltraSive/fortified-firewall)
This is a project I started based on Cilium's ebpf-go control plane for writing XDP ingress/TC egress firewalls and I planned on using Svelte 5/Sveltekit and a Postgres database as a additional UI layer for programming the control plane. 

### 📦 [**eBPF TC Traffic Accounting**](https://github.com/UltraSive/eBPF-TC-Traffic-Accounting)
This create a prometheus text format exporter for monitoring how much bandwidth and packets are going to a specific destination IP on ingress an opposite for egress. Very helpful for exporting data I use to clickhouse when scraping it intermittantly and I can later display it in a chart.

### 📦 [**goFilesAPI**](https://github.com/packetware/goFilesAPI)
This is a project similar to the Pterodactyl Wings daemon based on the Golang Gin web framework that will allow you to query details about a filesystem and make changes to it over a HTTP API. I used this with containers in order to build a app hosting platform with a clean web UI to allow users to make changes to the volumes attached to their services by having a instance of this binary bound to every volume.

### 📦 [**GoA2sCache**](https://github.com/UltraSive/GoA2sCache)
This is a simple steam A2s server list query cache to prevent resource exhaustion attacks by keeping a copy of the reply in a json object for a server and then also acting as a middleman to deliver the cached request to anyone querying the port.

### 📦 [**PteroRust**](https://github.com/UltraSive/pterorust.com)
I build a Svelte 4/Sveltekit Rust wipe scheduler that works based on a HTTP based cronjob to orchestrate automating Rust game servers that are hosted on Pterodactyl.

---

## 📫 Get in Touch

- Twitter: [@ultrasive](https://twitter.com/ultrasive)
- [LinkedIn](https://www.linkedin.com/in/ultrasive)

---
*Thanks for stopping by! ⭐ If you like my work, consider giving a star or following me!*
