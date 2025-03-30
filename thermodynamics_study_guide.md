# Thermodynamics Study Guide

## Quick Reference Table

| Concept           | Formula    | Units  | Key Points          |
| ----------------- | ---------- | ------ | ------------------- |
| Thermal Expansion | ΔL = αL₀ΔT | meters | Linear expansion    |
| Volume Expansion  | ΔV = βV₀ΔT | m³     | Volume change       |
| Heat Transfer     | Q = mcΔT   | Joules | Temperature change  |
| First Law         | ΔU = Q - W | Joules | Energy conservation |

## Thermal Expansion

### Linear Expansion

```
ΔL = αL₀ΔT          // Length change
L = L₀(1 + αΔT)     // Final length
α = coefficient of linear expansion
```

### Volume Expansion

```
ΔV = βV₀ΔT          // Volume change
V = V₀(1 + βΔT)     // Final volume
β ≈ 3α              // For most materials
```

### Visual Aid

```
Original:     After Heating:
┌────┐        ┌──────┐
└────┘        └──────┘
  L₀             L₁

Mnemonic: "Heat Makes Big"
```

## Heat Transfer Methods

### 1. Conduction

```
Q = kA(T₂-T₁)t/L   // Heat transfer formula
k = thermal conductivity
A = cross-sectional area
L = thickness
```

### 2. Convection

```
Q = hA(T₂-T₁)t     // Heat transfer formula
h = convection coefficient
A = surface area
```

### 3. Radiation

```
P = εσAT⁴          // Power radiated
ε = emissivity
σ = Stefan-Boltzmann constant
```

## Specific Heat

### Basic Formula

```
Q = mcΔT           // Heat transfer
Q = mL             // Phase change
```

### Mnemonic: "McΔT"

- **m** = mass
- **c** = specific heat capacity
- **ΔT** = temperature change

### Phase Changes

```
Solid ↔ Liquid ↔ Gas
     L_f    L_v
```

## First Law of Thermodynamics

### Basic Equation

```
ΔU = Q - W         // Energy change
Q = heat added
W = work done by system
```

### Process Types

```
Process          First Law Becomes
Adiabatic (Q=0)  ΔU = -W
Constant V (W=0) ΔU = Q
Isothermal       Q = W
```

### Process Diagram

```
    P
    │
    │   Process
    │     →
    │
    └──────── V
```

## Common Processes Table

| Process    | Condition | First Law |
| ---------- | --------- | --------- |
| Adiabatic  | Q = 0     | ΔU = -W   |
| Isochoric  | ΔV = 0    | ΔU = Q    |
| Isothermal | ΔT = 0    | Q = W     |

## Problem-Solving Strategy

### 1. Thermal Expansion

1. **Identify**:

   - Initial dimensions
   - Temperature change
   - Material properties

2. **Apply**:
   ```
   Linear: ΔL = αL₀ΔT
   Volume: ΔV = βV₀ΔT
   ```

### 2. Heat Transfer

1. **Determine Method**:

   - Conduction (through material)
   - Convection (fluid flow)
   - Radiation (electromagnetic)

2. **Calculate**:
   ```
   Q = mcΔT (temperature change)
   Q = mL (phase change)
   ```

## Practice Problems

1. **Thermal Expansion**:

   - Metal rod heated from 20°C to 80°C
   - Initial length 2m
   - Find length change

2. **Heat Transfer**:

   - 100g water heated from 20°C to 80°C
   - Calculate heat needed
   - Find time if power is 1000W

3. **First Law**:
   - Gas expands adiabatically
   - Work done = 200J
   - Find internal energy change

## Common Mistakes to Avoid

1. **Sign Conventions**:

   - Q positive: heat added
   - W positive: work done by system
   - ΔT: final - initial

2. **Units**:

   - Temperature in Kelvin for radiation
   - Joules for energy
   - Watts for power

3. **Process Identification**:
   - Adiabatic vs Isothermal
   - Constant pressure vs volume
   - Reversible vs Irreversible

## Additional Tips

1. **Temperature Scales**:

   ```
   K = °C + 273.15
   °F = (°C × 9/5) + 32
   ```

2. **Phase Changes**:

   - No temperature change during phase transition
   - Different energy requirements for each phase
   - Pressure affects transition temperature

3. **Energy Conservation**:
   - System + Surroundings = Constant
   - Account for all energy forms
   - Check for work and heat separately

## Real-World Applications

1. **Engineering**:

   - Bridge expansion joints
   - Engine cooling systems
   - HVAC design

2. **Daily Life**:

   - Cooking and refrigeration
   - Home insulation
   - Thermos design

3. **Natural Phenomena**:
   - Weather patterns
   - Ocean currents
   - Greenhouse effect

## Memory Aids

1. **First Law**:

   ```
   "U Q W" (You Queue Work)
   ΔU = Q - W
   ```

2. **Heat Transfer**:

   ```
   "CCR" (Conduction, Convection, Radiation)
   Solid → Fluid → Space
   ```

3. **Phase Changes**:
   ```
   "Some Like It Hot"
   Solid → Liquid → Gas
   ```
