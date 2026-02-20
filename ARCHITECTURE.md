# Architecture Design

---

## Lab Topology

The experiment was performed in a completely isolated wireless environment.

```
                ( Passive Monitoring )
                    Kali Linux #2
                     Observer
                         |
                         |
                ---------------------
                |                   |
                |  Controlled WiFi  |
                |   (No Internet)   |
                ---------------------
                         |
                         |
                   Kali Linux #1
                 Simulated Network
                    Access Point
                         |
                         |
                     Test Device
                     Android Client
```

---

## Role Separation

### Kali Linux #1 — Network Simulator

Responsible for providing a wireless environment that devices could voluntarily connect to.

Functions:

* Hosted the wireless network
* Provided local addressing
* Did not route to internet
* Did not intercept or modify traffic

This system behaved only as infrastructure.

---

### Kali Linux #2 — Observer

Performed passive observation only.

Functions:

* Monitored wireless frames
* Logged metadata patterns
* Stored capture files
* No packet injection performed

This system never interacted with the client device.

---

### Android Device — Test Client

A controlled device used to observe automatic network behavior.

Behavior Studied:

* Background connectivity checks
* Service discovery
* Application network patterns
* System identification requests

No manual browsing activity required.

---

## Data Flow Concept

1. Device joins nearby network
2. Operating system initiates background communication
3. Applications perform silent connectivity tests
4. Observer records metadata patterns

The important point:

The network does not need to provide internet access for information exposure to occur.

---

## Trust Boundary Model

```
User Trusts Network
        ↓
Device Shares Metadata
        ↓
Nearby Listener Learns Behavior
```

This experiment demonstrates that privacy exposure can occur before any attacker interaction.

---

## Why This Matters

Many users believe risk begins only after:

* entering credentials
* visiting websites
* installing malware

However, modern devices communicate automatically once connected.

The attack surface begins at association — not interaction.
