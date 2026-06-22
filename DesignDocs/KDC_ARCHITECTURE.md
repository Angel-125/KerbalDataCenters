# KDC_ARCHITECTURE.md

# Architectural Overview

## Major Layers

### Compute Layer
Tracks compute modules, compute capacity, power usage, and heat generation.

### Calibration Layer
Tracks commissioning state and recalibration requirements.

### Revenue Layer
Calculates Funds generated from effective compute capacity.

### Ownership Layer
Applies contract-based revenue sharing.

### Distance Layer
Maintains EMA-smoothed distance values and payout delays.

### Reliability Layer
Tracks faults, maintenance, uptime, and operational penalties.

### Dashboard Layer
Aggregates all KDC information into a player-facing UI.

## Revenue Model

Revenue generation and revenue payout are separate concepts.

Revenue Generation:
- Compute capacity
- Operational health
- Ownership factor
- Distance multiplier

Revenue Payout:
- Controlled by settlement delays
- Influenced by distance from Kerbin

## Distance System

Uses EMA (Exponential Moving Average) smoothing to avoid abrupt revenue changes.

Distance affects:
- Revenue multipliers
- Payout delays

EMA updates and payout timing are intentionally decoupled.

## Reliability Model

Goals:
- Reliable infrastructure
- Minimal micromanagement
- Meaningful maintenance decisions

Faults:
- Reduce efficiency
- Reduce profitability
- Rarely create catastrophic outcomes

## Science Mode

Science Mode converts compute resources into Science Data.

Science Data is intentionally distinct from Science and must be processed through existing science systems.

## Vessel Model

Vessel
- Compute Modules
- Calibration State
- Reliability State
- Ownership State
- Revenue State
- Distance State

## Technical Principles

- Modular PartModules
- Data-driven balancing
- Save compatibility
- Extensible architecture
- Loose coupling between systems
