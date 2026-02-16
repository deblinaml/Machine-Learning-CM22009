# CM22009 Machine Learning — Visualisations (University of Bath)

A growing repository of **interactive visualisations** and **lecture assets** for **CM22009 Machine Learning** (University of Bath).  
The aim is to make key ML ideas more **intuitive, visual, and testable** in lectures and labs.

This repository will be **updated frequently** as the unit progresses and new lecture topics are introduced.

---

## What’s included (so far)

### 1) Optimisers Playground (interactive HTML demos)
A set of browser-based visualisations for optimisation and training dynamics, including:
- Gradient descent intuition (interactive)
- Convex vs non-convex loss landscapes
- SGD vs batch updates / noise intuition
- Momentum and Adam-style behaviour

**Files (HTML):**
- `optimization_visualizations_index.html` (entry point)
- `gradient_descent_interactive.html`
- `convex_nonconvex.html`
- `sgd_comparison.html`
- `momentum_adam.html`

### 2) Deep Learning Visual Aid: Composing Neural Networks (3D)
A **3D visualisation** that illustrates how **composing (stacking) shallow networks** can create more complex functions/decision boundaries via “folding” effects.

**File (HTML):**
- `composing_networks_3d.html`

---

## Quick start (no install)

These demos are designed to run locally in a web browser.

### Option A — open directly
- Double-click `optimization_visualizations_index.html`
- Double-click `composing_networks_3d.html`

### Option B — serve locally (recommended)
Some browsers restrict local file behaviour; serving avoids that.

```bash
# from the repo root
python3 -m http.server 8000

```
Then open:

```
http://localhost:8000/optimization_visualizations_index.html

http://localhost:8000/composing_networks_3d.html

```
## Attribution & third-party components

Some demos may rely on external libraries (e.g., JavaScript visualisation libraries).  
Any third-party code, assets, or datasets will be credited in the relevant folder and/or at the top of the file where used.

## Copyright

© Dr Deblina Bhattacharjee. All rights reserved.

Unless explicitly stated otherwise, all original code, figures, and teaching materials in this repository are the intellectual property of **Dr Deblina Bhattacharjee**.

See `LICENSE` for permitted use and distribution.
