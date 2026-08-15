# Homelab

A simple self-hosted homelab for running and managing services across my devices. The setup provides a central dashboard, home automation, file management, and secure remote access without exposing services directly to the public internet.

## Services

* **Homepage** — Central dashboard for accessing and monitoring homelab services.
* **Home Assistant** — Self-hosted home automation and smart device management.
* **File Browser** — Web-based interface for managing files on the server.
* **Tailscale** — Private mesh network connecting devices and providing secure remote access.

## Overview

The repository contains the configuration for the services running in my homelab.

```text
Homelab
├── Homepage
├── Home Assistant
└── File Browser
        │
        └── Accessible through Tailscale
```

The goal is to keep the setup simple, private, and easy to maintain while providing useful services that I can access from my devices anywhere.

