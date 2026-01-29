# WaveLab | Interactive Virtual Wave Laboratory

WaveLab is a professional-grade, interactive educational platform designed for the exploration of unguided transmission media, specifically focusing on **Microwaves** and **Infrared** signals. It provides a visual and mathematical bridge between theoretical engineering concepts and real-world physical interactions.

## 🚀 Key Features

- **Universal Spectrum Lab**: A unified signal generation engine allowing users to sweep frequencies from 1 GHz (Microwaves) up to 400 THz (Infrared).
- **Real-time Dual Engines**:
  - **Terrestrial/Satellite Simulation**: Visualize wave propagation and line-of-sight characteristics.
  - **Microscopic Interaction Model**: Physical visualization of dipole resonance and electron motion in antennas.
- **Spectrum HUD**: Live telemetry data including Frequency ($f$), Wavelength ($\lambda$), and Photon Energy ($E$).
- **Comprehensive Theory**: Detailed engineering specifications for terrestrial and satellite microwave systems.
- **Interactive Assessment**: A full-featured quiz system to validate understanding of electromagnetic wave theory.

## 🛠️ Technology Stack

- **Structure**: Semantic HTML5
- **Design**: Vanilla CSS3 (Custom Variables, CRT effects, Glassmorphism)
- **Logic**: Pure JavaScript (ES6+)
- **Graphics**: HTML5 Canvas API for high-frequency signal rendering

## 📂 Project Structure

```text
├── css/
│   └── style.css            # Core design system and animations
├── js/
│   ├── spectrum-lab.js      # Unified simulation logic
│   ├── microwave-sim.js     # Specific microwave dynamics
│   ├── infrared-sim.js      # Specific infrared dynamics
│   └── quiz.js              # Assessment engine
├── index.html               # Gateway to the Lab
├── theory.html              # Engineering knowledge base
├── experiments.html         # Interactive DIY Lab
├── applications.html        # Real-world use cases
└── quiz.html                # Assessment interface
```

## 🚥 Getting Started

1. Clone or download the repository.
2. Open `index.html` in any modern web browser (no build steps required).
3. Navigate to the **Engineering Lab** to start generating signals.

## 🧪 Simulation Physics

The lab uses accurate physical relations for its visualizations:
- **Wavelength**: $\lambda = c / f$
- **Energy**: $E = h \cdot f$
- **Dipole Length**: $L = \lambda / 2$

---
Created with ♥ for DIY Learners | © 2026 WaveLab Aerospace
