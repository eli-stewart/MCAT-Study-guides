# Kinematics & Linear Motion Study Guide

## Quick Reference Table

| Quantity     | Symbol | Units | Formula | Vector/Scalar |
| ------------ | ------ | ----- | ------- | ------------- | --- | ------ |
| Displacement | Δx     | m     | x₂ - x₁ | Vector        |
| Velocity     | v      | m/s   | Δx/Δt   | Vector        |
| Speed        | s      | m/s   |         | distance      | /Δt | Scalar |
| Acceleration | a      | m/s²  | Δv/Δt   | Vector        |
| Time         | t      | s     | -       | Scalar        |

## Key Equations & Their Variations

### Linear Motion Equations (SUVAT)

```
v = v₀ + at                  // Velocity-time relation
x = x₀ + v₀t + ½at²         // Position-time relation
v² = v₀² + 2ax              // Velocity-displacement relation
x = x̄t                      // Average velocity relation
x̄ = (v₀ + v)/2             // Average velocity calculation
```

### Equation Variations & Rearrangements

1. **Solving for time (t)**:

   ```
   t = (v - v₀)/a           // From v = v₀ + at
   t = [-v₀ ± √(v₀² + 2ax)]/a  // From quadratic solution
   t = 2x/(v₀ + v)         // From average velocity
   ```

2. **Solving for acceleration (a)**:

   ```
   a = (v - v₀)/t
   a = (v² - v₀²)/(2x)
   a = 2(x - x₀ - v₀t)/t²
   ```

3. **Solving for displacement (x)**:
   ```
   x = v₀t + ½at²
   x = vt - ½at²
   x = (v² - v₀²)/(2a)
   ```

## Visual Aids

### Motion Graphs

```
Velocity vs Time           Position vs Time         Acceleration vs Time
    v│   /                     x│    /                 a│ ___
     │  /                       │   /                   │
     │ /                        │  /                    │
     │/                         │ /                     │
     └──── t                    └──── t                 └──── t
   Constant a               Constant v               Constant a
```

### Sign Conventions

```
     +x →     ← -x
     +v →     ← -v
     +a →     ← -a
```

## Common Problem Types & Solution Strategies

1. **Finding Final Velocity**

   - Given: initial velocity, acceleration, time
   - Use: v = v₀ + at
   - Check: units match, direction considered

2. **Finding Displacement**

   - Given: initial velocity, acceleration, time
   - Use: x = x₀ + v₀t + ½at²
   - Check: quadratic solutions when needed

3. **Finding Time to Reach Position**
   - Given: initial/final positions, velocity
   - Use: quadratic equation from x = x₀ + v₀t + ½at²
   - Check: both positive and negative solutions

## Mnemonics & Memory Aids

### Remember SUVAT Equations:

- **S**pace equation: x = x₀ + v₀t + ½at²
- **U**niform acceleration: v = v₀ + at
- **V**elocity squared: v² = v₀² + 2ax
- **A**verage velocity: x̄ = (v₀ + v)/2
- **T**ime independent: v² = v₀² + 2ax

### Vector vs Scalar (SMAD):

- **S**peed is Scalar
- **M**agnitude is Scalar
- **A**cceleration is Vector
- **D**isplacement is Vector

## Practice Problems

1. A car accelerates from rest at 2 m/s². Find:

   - Velocity after 5s
   - Distance traveled
   - Average velocity

2. A train moving at 20 m/s brakes at -1.5 m/s². Calculate:
   - Time to stop
   - Distance covered while stopping
   - Average velocity during braking

## Common Mistakes to Avoid

1. **Sign Errors**:

   - Always establish coordinate system
   - Be consistent with signs
   - Check if acceleration opposes motion

2. **Unit Conversions**:

   - Convert all units before calculation
   - Common conversions:
     - km/h → m/s (÷3.6)
     - g → m/s² (×9.81)

3. **Vector/Scalar Confusion**:
   - Speed is scalar, velocity is vector
   - Distance is scalar, displacement is vector

## Real-World Applications

1. **Vehicle Motion**:

   - Braking distance calculations
   - Acceleration requirements
   - Speed limits and safety

2. **Sports Physics**:

   - Running acceleration
   - Jumping motion
   - Ball trajectories

3. **Transportation**:
   - Train scheduling
   - Aircraft takeoff calculations
   - Elevator motion

## Additional Tips

1. **Drawing Diagrams**:

   - Always start with a diagram
   - Label known quantities
   - Show coordinate system
   - Indicate directions

2. **Equation Selection**:

   - List known variables
   - List target variable
   - Choose equation with these variables
   - Check units match

3. **Solution Verification**:
   - Units make sense
   - Magnitude reasonable
   - Direction consistent
   - Answer matches physical reality
