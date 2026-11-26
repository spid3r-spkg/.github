<p align="center">

# 🕷️ Spid3r Package Registry

</p>

<p align="center">
  <strong>A secure, lightweight, and cryptographically verified package registry for the Spid3r ecosystem.</strong>
</p>

<p align="center">
  <a href="https://spid3r-spkg.github.io/">🌐 Live Registry</a>
  •
  <a href="#-quick-start">Quick Start</a>
  •
  <a href="#-features">Features</a>
  •
  <a href="#-security">Security</a>
</p>

---

## 🕸️ Overview

**Spid3r Package Registry (SPKG Registry)** is the official package index for the Spid3r ecosystem.

It provides a centralized location for discovering, accessing, and managing packages through the `spkg` package manager and `spid3r` runtime.

Built around a static registry architecture and **Ed25519 digital signatures**, Spid3r aims to provide a lightweight and verifiable foundation for package distribution.

🌐 **Official Registry:** https://spid3r-spkg.github.io/

---

## ✨ Features

- 🔐 **Cryptographic Verification** — Ed25519-signed registry index for package authenticity verification.
- 📦 **Package Discovery** — Search and discover available packages.
- ⚡ **Lightweight Architecture** — Static package index without requiring a traditional dynamic registry backend.
- 🛡️ **Security Focused** — Public-key-based registry verification.
- 🔎 **Package Search** — Find packages using the `spkg` command-line interface.
- 🚀 **Easy Installation** — Install packages directly through `spkg`.
- 🧩 **Spid3r Integration** — Designed to work with the Spid3r runtime and package management ecosystem.
- 🗑️ **Package Management** — Manage installed packages through the package manager.

---

## 🚀 Quick Start

Spid3r uses the official registry by default.

### 1. Install a package

```bash
spkg install hello
```

### 2. Search packages

```bash
spkg search
```

### 3. Verify the registry

```bash
spkg verify
```

### 4. Uninstall a package

```bash
spkg uninstall hello
```

### 5. Run your Spid3r project

```bash
spid3r run src/main.matrix
```

---

## 📋 Requirements

To interact with this registry, you need the Spid3r ecosystem tools:

| Component | Purpose |
|---|---|
| `spkg` | Package installation, searching, verification, and removal |
| `spid3r` | Spid3r project runtime |
| Internet connection | Access the hosted package registry |

---

## 🔐 Security

Security and package authenticity are important parts of the Spid3r Package Registry.

The registry uses **Ed25519 digital signatures** to provide cryptographic verification of its package index.

### Security Components

- **Ed25519 Public Key:** The registry exposes its public verification key through `registry.pub`.
- **Digital Signatures:** The signed registry index enables authenticity verification.
- **Registry Verification:** Use `spkg verify` to verify the registry.

Always use the official registry endpoint:

```text
https://spid3r-spkg.github.io/
```

Never trust an alternative registry or public key unless its authenticity has been independently verified.

---

<p align="center">
  <strong>🕷️ Spid3r Package Registry</strong>
  <br/>
  <sub>Secure. Lightweight. Verifiable.</sub>
  <br/><br/>
  <a href="https://spid3r-spkg.github.io/">Explore the Registry →</a>
</p>
