# Projectile Motion & Frictional Forces Study Guide

## Quick Reference Table

| Concept           | Formula                      | Key Points                  |
| ----------------- | ---------------------------- | --------------------------- |
| Projectile Motion | v_y = v₀sinθ<br>v_x = v₀cosθ | Independent x and y motion  |
| Static Friction   | f_s ≤ μ_s N                  | Maximum force before motion |
| Kinetic Friction  | f_k = μ_k N                  | Force during motion         |

## Projectile Motion

### Key Equations & Variations

```
// Vertical Motion (y-direction)
y = y₀ + v₀_y t - ½gt²     // Position
v_y = v₀_y - gt            // Velocity
v₀_y = v₀sinθ             // Initial vertical velocity

// Horizontal Motion (x-direction)
x = x₀ + v₀_x t           // Position
v_x = v₀cosθ              // Velocity (constant)

// Time of Flight
t_flight = 2v₀sinθ/g      // For level ground
t_max_height = v₀sinθ/g   // Time to max height

// Maximum Height
h_max = (v₀sinθ)²/(2g)    // From ground level

// Range
R = v₀²sin(2θ)/g         // For level ground
```

### Visual Aid: Trajectory Components

```
    ↑ v₀_y = v₀sinθ
    │    ↗
    │  ↗  v₀
    │↗ θ
    └──────────→
     v₀_x = v₀cosθ

Path of Motion:
    ∩
   /  \
  /    \
 /      \
•────────•
```

### Important Points to Remember

1. **Independent Motion**:

   - Horizontal motion: constant velocity
   - Vertical motion: constant acceleration (g)
   - One doesn't affect the other

2. **Maximum Height**:

   - v_y = 0 at peak
   - Occurs at t = v₀sinθ/g
   - Symmetric descent

3. **Range Maximization**:
   - Maximum range at θ = 45°
   - Range proportional to v₀²
   - Range formula assumes same start/end height

## Frictional Forces

### Types of Friction

```
Applied Force (F) →  |→ f_s or f_k
                    ▭
                    ▭
                   ███
```

### Static Friction

1. **Formula Variations**:

   ```
   f_s ≤ μ_s N           // Inequality is important
   F_max = μ_s N         // Maximum static friction
   N = mg (flat surface) // Normal force
   ```

2. **Key Concepts**:
   - Prevents motion
   - Variable force
   - Maximum value: μ_s N
   - Always opposes motion tendency

### Kinetic Friction

1. **Formula Variations**:

   ```
   f_k = μ_k N           // Always equals
   f_k = μ_k mg          // On flat surface
   a = g(sinθ - μ_k cosθ) // On incline
   ```

2. **Key Concepts**:
   - During motion
   - Constant magnitude
   - Always less than static
   - Opposes motion direction

### Force Diagram Examples

```
Flat Surface:           Inclined Surface:
    f               mg sinθ
    ↓                 ↓
  →→▭←←           →→▭←←
    ↑               ↑  \
    N            N  θ  \
                      θ\
```

## Problem-Solving Strategy

### Projectile Motion

1. **Setup**:

   - Draw trajectory
   - Decompose vectors
   - Identify known variables

2. **Solution Steps**:
   - Separate x and y motion
   - Use appropriate time equation
   - Combine results if needed

### Friction Problems

1. **Setup**:

   - Draw force diagram
   - Identify friction type
   - List known forces

2. **Solution Steps**:
   - Calculate normal force
   - Apply friction formula
   - Solve for motion/equilibrium

## Common Mistakes to Avoid

1. **Projectile Motion**:

   - Forgetting air resistance exists
   - Mixing x and y components
   - Using wrong angle reference

2. **Friction**:
   - Using > instead of ≤ for static friction
   - Forgetting normal force changes on inclines
   - Assuming μ_s = μ_k

## Practice Problems

1. **Projectile Motion**:
   A ball is thrown at 20 m/s at 30°. Find:

   - Maximum height
   - Time of flight
   - Range

2. **Friction**:
   A 5kg block on 30° incline (μ_s = 0.4). Find:
   - Normal force
   - Maximum static friction
   - Will it slide?

## Real-World Applications

1. **Projectile Motion**:

   - Sports (basketball, football)
   - Artillery
   - Water fountains
   - Diving

2. **Friction**:
   - Car tires
   - Walking
   - Braking systems
   - Belt drives

## Additional Tips

1. **For Projectiles**:

   - Use symmetry for simple problems
   - Consider air resistance for real cases
   - Check reasonable answers

2. **For Friction**:
   - Always draw force diagram
   - Check friction direction
   - Consider surface conditions
