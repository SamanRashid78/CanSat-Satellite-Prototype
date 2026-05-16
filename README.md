# CanSat Satellite Prototype — SUPARCO Space Camp 2026

> **SUPARCO Space Camp Karachi · February 2026**
> Team project built and launched at the SUPARCO-organised aerospace camp, Karachi.

A functional can-sized satellite prototype built on ESP32, designed to collect and transmit real-time environmental telemetry during flight. The CanSat was successfully launched and recovered — actual flight data is included in this repo.

---

## What It Does

The CanSat reads altitude, temperature, and pressure during flight using onboard sensors, logs everything to an SD card, and transmits wirelessly to a ground station in real time. On recovery, the logged CSV contains the complete flight record.

---

## Hardware

| Component | Role |
|---|---|
| ESP32 | Main microcontroller + wireless telemetry |
| BMP280 / barometer | Altitude and pressure sensing |
| DHT sensor | Temperature and humidity |
| SD card module | Onboard data logging |
| Parachute system | Recovery mechanism |

---

## Flight Data

`cansat_log_20260211_131525.csv` contains real telemetry logged during the test flight on 11 February 2026. Each row is a timestamped sensor reading captured during ascent and descent.

**This is real flight data — not simulated.**

---

## Files

```
CanSat-Satellite-Prototype/
├── cansat_log_20260211_131525.csv        ← actual telemetry from test flight
├── Test-Flight-of-Cansat.jpeg            ← photo from launch day
├── CanSat-Prototype-Report.pdf           ← full project report
└── README.md
```

---

## Mission Results

- Successful launch and stable ascent recorded
- Real-time telemetry streamed to ground station during flight
- Parachute recovery executed successfully
- Full sensor log captured across complete flight duration

---

## What I Learned

- Embedded systems under real mission constraints — weight, power, size all matter
- Sensor fusion and onboard logging during dynamic flight conditions
- Wireless telemetry and ground station communication
- Subsystem integration and hardware debugging in field conditions without a lab
- Working under time pressure in a team with a real launch deadline
