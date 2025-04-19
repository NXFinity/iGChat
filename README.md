<p align="center">
  <a href="https://beamify.online" target="_blank">
    <img src="assets/icon.png" width="120" alt="Beamify Logo" />
  </a>
</p>

<h1 align="center">iGChat — Beamify Real-Time Chat Infrastructure</h1>
<p align="center">
  <strong>Secure, scalable messaging for the Beamify Network</strong><br/>
  Custom chat server, gateway, and delivery system with end-to-end encryption for live streams, community rooms, and beyond.
</p>

---

## 💬 What is iGChat?

**iGChat** is Beamify’s dedicated real-time communication platform — a standalone system built to power private messaging, public chat, and large-scale communication in **live streams**, **community rooms**, and **creator channels**.

Architected as a modular backend service with gateway logic, delivery queueing, and **end-to-end encryption**, iGChat ensures privacy, performance, and scalability across all Beamify apps — including iGApp on web, desktop, and mobile.

---

## 🔐 Key Features

- 🚀 **Real-Time Communication** – Powered by WebSockets or gRPC for low-latency message delivery
- 🌐 **Gateway + Delivery System** – Handles routing, broadcasting, queuing, and guaranteed delivery
- 🔐 **End-to-End Encryption (E2EE)** – Private messages are encrypted client-to-client for maximum security
- 🧩 **Cross-Platform Support** – Built to interface with iGApp on Web, Electron, and Cordova
- 🎥 **Live Stream Chat** – Optimized for real-time discussion in creator-led live experiences
- 🧠 **Scalable Architecture** – Horizontal scaling and load-balancing friendly
- 🏷 **Rooms, Channels, & Threads** – Flexible structures for 1:1, group, and broadcast-style communication
- 📜 **Moderation Tools** – (Planned) Filters, bans, reporting, and message retention control

---

## ⚙️ Technologies (Example Stack)

> Exact tech stack may vary — adjust this section as your implementation evolves.

- **Node.js** + **NestJS Gateway** – Scalable server foundation
- **WebSockets / gRPC** – Real-time transport layer
- **Redis / Message Broker** – Pub/Sub and delivery queues
- **PostgreSQL / MongoDB** – User, channel, and message metadata
- **Libsodium / AES** – End-to-end encryption library support
- **Rate Limiting / Guards** – Security and abuse prevention baked in

---

## 📦 Designed For:

- 🟣 **Beamify Live Streams** – Real-time chat during broadcasts with creator-moderated channels
- 🟠 **Community Rooms** – Persistent topic-based group chat spaces
- 🔵 **Private DMs** – Encrypted, peer-to-peer style messaging
- 🟢 **Global System Events** – Future support for system-wide alerts and updates

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🌐 Learn More

- 🌐 [Beamify Website](https://beamify.online)
- 🧠 [iGCore — Beamify API](https://github.com/NXFinity/iGCore)
- 🖥️ [iGApp — Beamify Frontend](https://github.com/NXFinity/iGApp)  
