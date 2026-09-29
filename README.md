# Smart Pintle Valve for Precision Deep Throttling and Cavitation-Risk Avoidance

## Overview

The **Smart Pintle Valve** is a laboratory-scale research project focused on developing a closed-loop flow-control system inspired by deep-throttling requirements in liquid propulsion systems.

The project combines a **variable-area pintle valve**, real-time sensing, actuator control, and feedback-based monitoring to achieve controlled flow regulation over a wide operating range.

The prototype is designed to investigate how a pintle-based flow-control mechanism can be operated with improved precision while monitoring pressure conditions associated with potential cavitation risk.

> **Note:** This project is a laboratory-scale demonstrator and is not intended for direct use in flight-qualified rocket engines.

---

## Problem Statement

Liquid propulsion systems require accurate control of propellant flow and thrust during different operating conditions.

Deep throttling introduces several engineering challenges, including:

- Maintaining accurate flow control at reduced operating levels
- Controlling valve position precisely
- Monitoring pressure variations across the flow-control element
- Detecting operating conditions associated with cavitation risk
- Maintaining stable operation during throttle transitions
- Achieving reliable closed-loop control using low-cost instrumentation

Conventional laboratory flow-control systems may not provide an integrated and affordable platform for studying these challenges.

This project investigates a low-cost smart valve architecture that combines mechanical flow control with real-time sensing and feedback control.

---

## Proposed Solution

The proposed system uses a **variable-area pintle mechanism** driven by an electronically controlled actuator.

The system continuously monitors flow and pressure parameters and adjusts the pintle position according to the desired throttle condition.

### Basic Control Flow

```text
Target Throttle
       ↓
Controller
       ↓
Actuator
       ↓
Pintle Valve
       ↓
Flow System
       ↓
Flow + Pressure Sensors
       ↓
Feedback
       ↓
Controller

Key Features
Variable-area pintle-based flow control
Closed-loop control architecture
Real-time flow measurement
Upstream and downstream pressure monitoring
Differential-pressure calculation
Throttle control from 100% to 40% as a prototype target
Real-time cavitation-risk monitoring
Emergency-stop functionality
Simulation mode for development and testing
Live telemetry visualization
Data logging and CSV export
Dashboard-based monitoring
Future ESP32 and Firebase integration
