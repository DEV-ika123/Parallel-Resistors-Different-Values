# Parallel Resistors - Different Values

## Objective

To understand how current divides between parallel resistors with different resistance values and verify the results using Tinkercad simulation.

## Circuit

A 9V supply is connected to two parallel resistor branches:

- Branch 1: 1kΩ resistor
- Branch 2: 2kΩ resistor

Both branches are connected across the same 9V supply.

## Concept

In a parallel circuit:

- The voltage across each branch is the same.
- Current divides between the branches.
- The branch with lower resistance carries more current.

## Design Calculation

### 1. Equivalent Resistance

Rₜ = (R₁ × R₂) / (R₁ + R₂)

Rₜ = (1kΩ × 2kΩ) / (1kΩ + 2kΩ)

Rₜ ≈ 667Ω

### 2. Total Current

Iₜ = V / Rₜ

Iₜ = 9V / 667Ω

Iₜ ≈ 13.5mA

### 3. Branch Currents

For the 1kΩ branch:

I₁ = 9V / 1kΩ

I₁ = 9.00mA

For the 2kΩ branch:

I₂ = 9V / 2kΩ

I₂ = 4.50mA

### 4. Current Check

Iₜ = I₁ + I₂

Iₜ = 9.00mA + 4.50mA

Iₜ = 13.50mA

## Simulation Results

| Quantity | Calculated | Tinkercad |
|---|---:|---:|
| 1kΩ branch current | 9.00mA | 9.00mA |
| 2kΩ branch current | 4.50mA | 4.50mA |
| Total current | 13.50mA | 13.50mA |

## Observation

The 1kΩ resistor carries twice the current of the 2kΩ resistor.

This happens because both branches have the same voltage, but the 1kΩ resistor has lower resistance.

## What I Learned

- Parallel branches have the same voltage.
- Current divides between parallel branches.
- Lower resistance draws more current.
- Total current is the sum of the branch currents.
- The equivalent resistance of parallel resistors is less than the smallest resistor.

## Engineering Lesson

Parallel resistor networks are used in circuits where current needs to divide between different paths.

Understanding current division is important for circuit analysis and practical electronics design.

## Tools Used

- Tinkercad Circuits
- Multimeter
- 9V DC supply
- 1kΩ resistor
- 2kΩ resistor
