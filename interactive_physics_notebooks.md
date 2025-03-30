# Interactive Physics Notebooks

## Overview

These Jupyter notebooks provide interactive visualizations of key physics concepts. All notebooks can be viewed through [nbviewer.org](https://nbviewer.org/).

## Kinematics Visualizations

[View Notebook](https://nbviewer.org/github/eli-stewart/MCAT-Study-guides/blob/main/notebooks/kinematics.ipynb)

### Features:

- Interactive motion graphs with adjustable parameters
- Real-time SUVAT equation calculations
- Vector component visualization
- Animated particle motion

```python
# Example code snippet from kinematics.ipynb
import numpy as np
import matplotlib.pyplot as plt
from ipywidgets import interactive

def plot_motion(v0, a, t_max):
    t = np.linspace(0, t_max, 1000)
    x = v0*t + 0.5*a*t**2
    v = v0 + a*t

    fig, (ax1, ax2) = plt.subplots(2, 1, figsize=(10, 8))
    ax1.plot(t, x, 'b-', label='Position')
    ax2.plot(t, v, 'r-', label='Velocity')
    # ... more plotting code ...
```

## Projectile Motion

[View Notebook](https://nbviewer.org/github/eli-stewart/MCAT-Study-guides/blob/main/notebooks/projectile.ipynb)

### Features:

- Interactive trajectory plotting
- Angle optimization for maximum range
- Air resistance effects
- 3D projectile visualization

```python
# Example code snippet from projectile.ipynb
def plot_trajectory(v0, angle, height=0):
    theta = np.radians(angle)
    vx = v0*np.cos(theta)
    vy = v0*np.sin(theta)

    t_flight = (vy + np.sqrt(vy**2 + 2*g*height))/g
    t = np.linspace(0, t_flight, 1000)

    x = vx*t
    y = height + vy*t - 0.5*g*t**2
    # ... plotting code ...
```

## Forces and Newton's Laws

[View Notebook](https://nbviewer.org/github/eli-stewart/MCAT-Study-guides/blob/main/notebooks/forces.ipynb)

### Features:

- Interactive force diagrams
- Spring-mass oscillations
- Circular motion simulation
- Friction effects

```python
# Example code snippet from forces.ipynb
def spring_mass_motion(k, m, x0):
    omega = np.sqrt(k/m)
    t = np.linspace(0, 10, 1000)
    x = x0*np.cos(omega*t)

    fig = plt.figure(figsize=(10, 6))
    plt.plot(t, x)
    # ... animation code ...
```

## Work and Energy

[View Notebook](https://nbviewer.org/github/eli-stewart/MCAT-Study-guides/blob/main/notebooks/energy.ipynb)

### Features:

- Energy conservation demonstrations
- Work calculation visualizations
- Power and efficiency plots
- Roller coaster simulation

```python
# Example code snippet from energy.ipynb
def roller_coaster(height, track_shape):
    # Calculate potential and kinetic energy at each point
    PE = m*g*height
    v = np.sqrt(2*g*(max(height) - height))
    KE = 0.5*m*v**2

    # Plot energy transformations
    plt.plot(PE, label='Potential Energy')
    plt.plot(KE, label='Kinetic Energy')
    plt.plot(PE + KE, label='Total Energy')
```

## Thermodynamics

[View Notebook](https://nbviewer.org/github/eli-stewart/MCAT-Study-guides/blob/main/notebooks/thermo.ipynb)

### Features:

- Interactive PV diagrams
- Heat transfer animations
- Thermal expansion calculator
- Phase change visualizations

```python
# Example code snippet from thermo.ipynb
def plot_pv_diagram(process_type, initial_state, final_state):
    if process_type == 'isothermal':
        P = nRT/V
    elif process_type == 'adiabatic':
        P = P1*(V1/V)**gamma

    plt.plot(V, P)
    plt.fill_between(V, P, alpha=0.2)  # Work done
```

## Using These Notebooks

1. **Viewing**:

   - Click on the notebook links above to view in nbviewer
   - No installation required for viewing
   - Interactive elements work in nbviewer

2. **Running Locally**:

   ```bash
   git clone https://github.com/YourUsername/physics-notebooks
   cd physics-notebooks
   jupyter notebook
   ```

3. **Required Dependencies**:
   ```python
   numpy
   matplotlib
   ipywidgets
   scipy
   vpython  # For 3D visualizations
   ```

## Contributing

To contribute:

1. Fork the repository
2. Add your visualizations
3. Submit a pull request

## Tips for Best Experience

1. **Browser Support**:

   - Use Chrome or Firefox for best performance
   - Enable JavaScript for interactivity
   - Update browser if widgets don't load

2. **Interaction**:

   - Use sliders to adjust parameters
   - Click and drag to rotate 3D plots
   - Double-click to reset views

3. **Learning**:
   - Experiment with parameters
   - Observe relationships
   - Try to predict outcomes
