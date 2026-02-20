# Methodology

---

## Research Goal

To observe what information a modern mobile device reveals automatically after joining a nearby wireless network — without user interaction and without internet connectivity.

The experiment focuses on passive observation only.

---

## Ethical Constraints

The following strict rules were enforced:

* Closed laboratory environment only
* Only personally owned devices used
* No external networks involved
* No traffic interception or manipulation
* No credential harvesting
* No service impersonation
* Observer system remained passive

---

## Experimental Phases

---

### Phase 1 — Environment Preparation

A controlled wireless environment was created where:

* The network provided local connectivity only
* Internet routing was intentionally unavailable
* Devices could associate normally
* The environment simulated a typical public WiFi presence

Purpose:
To study device behavior under realistic but safe conditions.

---

### Phase 2 — Baseline Capture

Before any device connected:

* The observer recorded ambient wireless activity
* This established environmental noise levels
* Confirmed absence of unrelated traffic

Purpose:
To prove that later observations originate from the test device.

---

### Phase 3 — Association Event

The Android device connected to the wireless network.

No applications were manually opened.
No browsing was performed.

The device was left idle.

Purpose:
To study automatic operating system communication.

---

### Phase 4 — Passive Observation

The observer recorded only metadata patterns such as:

* Address resolution activity
* Name resolution requests
* Connectivity validation checks
* Background service discovery

No packet contents were modified or injected.

Purpose:
To measure exposure created purely by connection.

---

### Phase 5 — Timeline Correlation

A time anchor was introduced to align human observation and recorded data.

This allowed reconstruction of:

* Connection moment
* Background communication burst
* Stabilization phase

Purpose:
To demonstrate reproducibility.

---

### Phase 6 — Evidence Preservation

Captured data was preserved using integrity verification:

* Read-only storage
* Cryptographic hashing
* Structured documentation

Purpose:
To maintain research credibility.

---

## Key Principle Demonstrated

A device does not need active usage to communicate.

Association alone triggers automatic behavior that reveals patterns about the device environment and installed services.

---

## Reproducibility

The experiment can be reproduced by any researcher using:

* Two isolated systems
* One client device
* No internet access
* Passive monitoring only

Results should remain consistent across runs.

---

## Limitations

This experiment does NOT:

* Identify individuals
* Extract credentials
* Break encryption
* Access private content

It only studies metadata behavior generated automatically by modern devices.

---

## Conclusion

The exposure occurs at connection time, not user action time.

This shifts the traditional perception of when risk begins in wireless environments.
