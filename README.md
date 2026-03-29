# OpenClaw-SafeBox-VM 🛡️

A hardened, zero-trust Ubuntu environment purpose-built for secure OpenClaw experimentation.

---

## 🚨 Why This Exists

Are you hesitant to run autonomous AI agents on your primary machine? You should be.  

Giving an experimental AI full access to your filesystem or local network is a **massive security risk**.

**OpenClaw-SafeBox-VM** solves this.

We use **UTM** to build a strict, **6-layer isolation protocol** that ensures autonomous agents remain entirely contained.

> An agent given full access to this Virtual Machine cannot read, write, or delete anything on your host machine — not through the filesystem, and not through the network.

---

## ✅ Key Features

- **100% Isolated**
- **Agent-Safe**
- **Clone-Protected**

---

## 🔒 Security Overview

This setup utilizes UTM's architecture to prioritize **strict isolation over host-sharing**, protecting your system via:

### 🧱 Air-gapped Filesystem
- Absolutely **no shared folders**
- Host machine files are **invisible and untouchable**

### 🌐 Emulated VLAN Network
- Outbound internet access enabled
- Your **local network and host system are completely isolated**

### 🔐 Internal Hardening
- Pre-configured firewalls
- SSH disabled
- Zero-cache sudo
- Prevents silent privilege escalation

### ♻️ Instant Recovery
- Clone-based backups
- Wipe compromised VM instantly
- Restore a clean, pristine state in seconds

---

## 📋 Prerequisites

Before you start, make sure you have:

1. **UTM** – Virtual machine hypervisor compatible with your host  

2. **Ubuntu Server ARM64 ISO** – The OS for the VM  

---

## 📥 Installation & Setup Guide

For the complete, step-by-step setup instructions, please refer to the **PDF document**.

### 📘 The guide covers:

- Exact **UTM configuration settings** required for true isolation  
- **Ubuntu Server ARM64 installation**  
- Terminal commands for **internal VM hardening**  
- Commands to **mathematically verify isolation is active and working**

---

## ⚠️ Final Note

This environment is designed with a **zero-trust mindset**.  
Treat every AI agent as potentially unsafe — and keep it contained.

---
