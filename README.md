# MedEquipTrack: Medical Equipment Maintenance & Calibration Tracking System

**Software Requirements Specification (SRS) v1.0 (Draft)**

[**View the live SRS**](https://mahalak20607-ux.github.io/medequiptrack-srs/)

## About

MedEquipTrack is a proposed cloud-hosted web and mobile platform that helps hospitals and biomedical engineering (BME) departments track, maintain, calibrate and audit medical devices such as ventilators, defibrillators, patient monitors, ECG machines and infusion pumps.

This repository contains the Software Requirements Specification for the system, written following IEEE 830 / ISO/IEC/IEEE 29148 (adapted).

## Problems addressed

- Uncalibrated or out-of-tolerance devices remaining in clinical use
- Missed preventive maintenance (PM) schedules
- Unknown equipment location and status
- Incomplete or alterable records during NABH, JCI, ISO 13485 or FDA audits
- Unexpected device downtime during surgeries and emergencies
- Lapsed vendor contracts and warranties

## Key features

| Area | Summary |
|---|---|
| Asset management | Digital passport per device, risk category, QR/RFID lookup, status tracking |
| PM & calibration scheduler | Risk-based intervals, alerts, grace periods, automatic quarantine of overdue devices |
| Breakdown ticketing | Fault reporting by ward staff, auto-assignment, SLA-tracked work order lifecycle |
| Calibration & certificates | Digital forms, pass/fail evaluation, reference-standard validity checks, e-signature, PDF certificates |
| Spare parts | Inventory linked to device models, low-stock and expiry alerts |
| Vendor & contracts | AMC/CMC tracking, SLA performance, warranty expiry notifications |
| Audit & compliance | Immutable audit trail, compliance dashboard, one-click audit reports |

## Document structure

1. Introduction
2. Overall Description
3. System Features and Functional Requirements
4. External Interface Requirements
5. Non-Functional Requirements
6. Data Requirements & Security Constraints
7. System Models & Data Flow (state, data-flow and ER diagrams)
8. Appendices & Regulatory Guidelines

## Repository contents

| File | Description |
|---|---|
| `index.html` | The SRS as a web page with clickable navigation and diagrams |
| `README.md` | This file |

## Viewing locally

Open `index.html` in any modern browser. An internet connection is needed to draw the diagrams.

## Regulatory note

This is a draft for technical and regulatory review. Compliance with FDA 21 CFR Part 11, ISO 13485 and ISO/IEC 17025 must be verified by Regulatory Affairs before use. Intervals, thresholds and retention periods in the document are illustrative defaults.

## Status

Version 1.0 (Draft). Not yet approved for implementation.