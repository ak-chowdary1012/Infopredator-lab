# Reproduction Guide (Academic Use Only)

---

## Purpose

This guide allows researchers to reproduce the experiment in a controlled laboratory environment to study automatic device behavior after wireless association.

This is NOT intended for real-world networks or unknown devices.

Only use personally owned hardware inside an isolated environment.

---

## Required Equipment

Minimum setup:

* Two Linux systems with wireless capability
* One client device (phone or laptop)
* No internet connection
* Closed indoor environment

All devices must belong to the researcher.

---

## Environment Conditions

The wireless network must:

* Provide local connectivity only
* Not route traffic to the internet
* Not connect to external infrastructure
* Exist only for the duration of testing

The observer system must remain passive.

---

## High Level Procedure

### Step 1 — Prepare Isolated Network

Create a nearby wireless network that allows device association but does not provide internet access.

Goal:
Simulate presence of a typical public network.

---

### Step 2 — Prepare Observer System

Start a passive packet capture system.

Requirements:

* No packet injection
* No impersonation
* No interference
* Record only metadata

Goal:
Observe natural device behavior.

---

### Step 3 — Baseline Recording

Record the environment before any device connects.

Goal:
Prove the network is initially silent.

---

### Step 4 — Association Event

Connect the test device to the network and leave it idle.

Do not open applications.
Do not browse.
Do not interact.

Goal:
Observe automatic operating system activity.

---

### Step 5 — Observation Period

Allow the device to remain connected for several minutes.

Record network activity continuously.

Goal:
Capture background communication patterns.

---

### Step 6 — Preservation

Stop capture and preserve files using integrity verification.

Goal:
Maintain research credibility.

---

## Expected Result

You should observe:

* Immediate communication attempts
* Repeated connectivity checks
* Background service activity
* Periodic retry behavior

All occurring without user interaction.

---

## What This Experiment Does NOT Do

This procedure does NOT:

* Decrypt protected communication
* Intercept credentials
* Break encryption
* Impersonate services
* Target other people

It only observes automatic behavior of owned devices.

---

## Ethical Reminder

Reproducing this experiment on networks you do not own may violate laws and ethical guidelines.

Always perform research responsibly.

---

## Key Takeaway

Wireless connection alone triggers communication.

User inactivity does not equal device inactivity.
