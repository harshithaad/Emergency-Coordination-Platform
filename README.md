# 🌐 OfflineNet

### An offline emergency communication network powered by QR codes

Communication infrastructure is often the first casualty during disasters, conflicts, and large-scale outages.

OfflineNet enables people to exchange critical information without internet access, cellular networks, servers, or cloud services.

Messages are encoded into QR codes, transferred between devices through scanning, and stored locally, creating a decentralized communication network that continues operating even during complete connectivity blackouts.

---

## 📘 Overview

OfflineNet is built around a simple idea:

**Communication should remain possible even when the internet doesn't.**

Instead of relying on network infrastructure, information moves directly between devices through QR codes.

Each device becomes a communication node capable of creating, receiving, storing, and forwarding messages.

---

## ✨ Key Features

### 📡 Fully Offline Communication

No internet connection, backend server, or cloud infrastructure required.

### 🔲 QR-Based Message Transfer

Messages are converted into QR codes and exchanged directly between devices.

### 🔄 Decentralized Information Sharing

Every device can receive and forward messages, allowing information to spread organically across communities.

### 🛡️ Message Validation

Incoming messages are verified against a predefined schema before being accepted.

### 🚫 Duplicate Protection

Prevents the same message from being repeatedly propagated across the network.

### 📈 Hop Count Tracking

Tracks how many devices a message has passed through during distribution.

### 💾 Local Storage

Messages persist locally on the device even after the application is closed.

---

## 🧠 How It Works

1. User creates a message
2. Message is assigned a unique identifier
3. Message is encoded into a QR code
4. Another device scans the QR code
5. Message is validated and stored locally
6. The receiving device can forward the message further

The result is a human-powered communication network capable of functioning without traditional infrastructure.

---

## 🚨 Use Cases

* Disaster response
* Flood and earthquake recovery
* Conflict zones
* Emergency shelters
* Rural and remote communities
* Temporary network outages
* Humanitarian operations

---

## 🛠️ Tech Stack

**Frontend**

* React
* Vite

**QR Communication**

* qrcode
* html5-qrcode

**Data Management**

* UUID
* localStorage

**Browser APIs**

* Camera Access
* Canvas Rendering

---

## 🚀 Getting Started

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

### Build for Production

```bash
npm run build
```

Open the application in a modern browser and allow camera access when prompted for QR scanning.

---

### Built for situations where connectivity cannot be assumed.
