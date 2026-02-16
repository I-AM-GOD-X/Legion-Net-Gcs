# ⚡ Legion Net GCS — Quick Start (30-Second Setup)

This guide gets you running fast without reading the full documentation.

---

## 1️⃣ Install

1. Go to **Releases**
2. Download the latest **EXE**
3. Install and launch Legion Net GCS

---

## 2️⃣ Choose Your Mode

### 🛰️ A) Live Telemetry Mode (Hardware Connected)

Use this if you have a flight computer or telemetry receiver.

* Output telemetry as **CSV serial data**
* Follow the CSV order defined in the main README
* Unused fields may be set to `0`

Example format:

```csv
phase,altitude,vSpeed,ax,ay,az,gx,gy,gz,...
```

---

### 🧪 B) Demo Mode (No Hardware Required)

If you do NOT have a telemetry device, you can still explore all visualizations.

A **sample telemetry log** is provided.

**Note:**
GPS data is removed for privacy reasons.

You can still test:

* Graphs
* Timeline playback
* Orientation panel
* 3D Plot window
* Flight state changes

#### How to use Demo Mode

1. Open Legion Net GCS
2. Click **Import** in the connection panel
3. Select the demo telemetry file
4. Scrub or play the timeline

---

## 3️⃣ Connect Hardware (Live Mode Only)

1. Connect your telemetry receiver to the PC
2. Select correct **COM Port**
3. Select correct **Baud Rate**
4. Click **Connect**

If successful, graphs should start moving immediately.

If not:

➡ Click **LIVE** on the timeline
(you are likely in scrub/playback mode)

---

## 4️⃣ During Flight

Monitor:

* Live telemetry graphs
* Orientation
* Map position
* Link quality
* Flight phase indicator

---

## 5️⃣ Save & Review

After flight:

1. Click **Save**
2. Scrub timeline to inspect data
3. Replay flight
4. Open **3D Plot** window to view trajectory

---

## 🖥️ Recommended Setup

For launch operations:

* Dual-monitor setup recommended
* Main GCS on one screen
* 3D Plot window on second screen

---

## 🚨 Display Requirement

Best experience:

* Resolution: **1920 × 1080**
* Display Scaling: **100%**

Higher scaling may cause UI gaps or misalignment.
