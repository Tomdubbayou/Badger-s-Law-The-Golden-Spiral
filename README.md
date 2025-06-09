# Badger’s Law — The Golden Spiral
_(nickname: “The Golden Spiral”)_

---

## 1 · Instant visual proof

![Circle vs Spiral](https://raw.githubusercontent.com/Tomdubbayou/Badger-s-Law-The-Golden-Spiral/main/golden_spiral_demo.png)

*Blue = λ 0 (circle) | Orange = λ 0.10 (spiral) — same start, one dial changed.*

---

## 2 · Hard-math snapshot

Spiral-Penalty Lagrangian (polar):

```
L = ½ m ( ṙ² + r² θ̇² ) − G M m / r + ½ λ m ( ṙ − k r θ̇ )²
```

Analytic stability ceiling (n bodies):

```
V(t) = Σ_{i<j} |r_i − r_j|  ≤  n(n−1) · a
```

---

## 3 · How we found it (plain English)

1. **Pen line** → zoom in, ink is a micro-helix.  
2. **Breath vortex** → rings expand as spirals.  
3. **Satellite ground-track** → perfect ellipse looks spiral in Earth’s frame.  

*Hunch*: “Straight” might be a coarse view of spirals → add λ knob.

---

## 4 · Run it yourself (60 s Colab)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Tomdubbayou/Badger-s-Law-The-Golden-Spiral/blob/main/one_click_demo.ipynb)

---

## 5 · Dive deeper

* **/docs/dossier.txt** — full derivations & logs  
* **/demos/phase_tension_widgets.ipynb** — n-body slider  
* **/demos/drift_scan.ipynb** — radius vs λ curve  

---

## 6 · Why care?

* Artists → organic scatter, smoother camera rails  
* Robotics → spiral sweeps save ≈ 15 % turning energy  
* Physics → one dial, zero broken laws — testable toy-gravity

---

MIT Licence — twist away
