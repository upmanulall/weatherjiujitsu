# Weather Jiu-Jitsu: Climate Adaptation for the 21st Century

[![Research Status](https://img.shields.io/badge/Status-Active%20Research-brightgreen)](https://github.com/qhuang62/weatherjiujitsu)
[![Publication](https://img.shields.io/badge/Paper-Under%20Review-yellow)](./publication/wjj-perspective.pdf)
[![GitHub Pages](https://img.shields.io/badge/Docs-GitHub%20Pages-blue)](https://qhuang62.github.io/weatherjiujitsu)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

**Weather Jiu-Jitsu** is a novel research framework that explores how to *gently redirect or deflect* extreme weather — such as hurricanes and atmospheric rivers — through scientifically informed, low-energy interventions in the atmosphere.

<p align="center">
  <img src="./media/wjj-funny.png" width="300"/>
</p>

> "Like martial arts for the atmosphere — using the system's own chaotic energy against itself."

This project is led by [Prof. Upmanu Lall](https://en.wikipedia.org/wiki/Upmanu_Lall) in collaboration with researchers at [Columbia Water Center](https://water.columbia.edu/) and [ASU Water Institute](https://globalfutures.asu.edu/water-institute/).  

## 🚀 Quick Start

- **📖 [Read the Full Documentation](https://github.com/upmanulall/weatherjiujitsu/blob/main/docs/README.md)** - Complete research overview
- **🔬 [Browse Research Papers](./publication/)** - Perspective paper and technical publications  
- **📊 [View Project Timeline](./TIMELINE.md)** - Research roadmap and milestones
- **🤝 [Contribute to Research](./CONTRIBUTING.md)** - Join our collaborative effort

---

## Featured Work
### 📄 Preprint Papers

- 🔬 **[Weather Jiu-Jitsu: Climate Adaptation for the 21st Century](https://arxiv.org/abs/2508.09376)**  
  This perspective proposes a new paradigm for climate adaptation. As extreme climate events intensify, traditional infrastructure and mitigation strategies are proving inadequate. We introduce Weather Jiu-Jitsu—a novel approach that exploits the chaotic dynamics of weather systems to subtly redirect or weaken destructive events using precisely timed, low-energy interventions.
<p align="center">
  <img src="./media/AR_Steering_Visuals.png" width="500"/>
</p>
  This vision blends adaptive chaos control theory with advances in observation, forecasting, and intervention technologies, laying the groundwork for a nature-assisted global infrastructure to confront 21st-century climate risks.

- 🌪️ **[Adaptive Chaos Control of Weather Extremes: Demonstrating “Weather Jiu-Jitsu” in Idealized Models](./publication/control-paper.pdf)**  
  We develop and test an optimal control framework for mitigating extreme weather in simplified atmospheric systems. Using Lorenz 63 and Lorenz 84 models, we show that small perturbations, guided by local Lyapunov exponents and ensemble forecasts, can keep weather trajectories within safe boundaries while minimizing energy use.

  Control strategies are robust to noise and uncertainty, demonstrating the feasibility of real-time adaptive interventions in chaotic systems. These results provide a foundation for scaling Weather Jiu-Jitsu to more realistic atmospheric models.

  <p align="center">
    <a href="https:///moyan-liu.github.io/weatherjiujitsu/media/nhmm_3d_l84.html">
      <strong>🗺️ View Interactive 3D Map for L84 control </strong>
    </a>
    <br>
    <em>Explore our results in an interactive 3D visualization</em>
  </p>

---

## Ongoing Work

- 🔬 **Foundation-Model Testbed for Controlled Perturbations in Tropical Cyclones & Hard Freezes (with Sensitivity Analysis)**  
  We’re building a lightweight testbed to probe how small, targeted nudges affect extreme-weather evolution in foundation models. The pipeline runs offline rollouts, injects constrained perturbations (pressure/temperature/moisture/flow proxies), and measures downstream changes in track, intensity, and impact proxies for (a) tropical cyclones and (b) hard freeze outbreaks. A systematic sensitivity sweep ranks variables, times, and locations by control leverage and robustness.  
  - **Goal:** Identify “high-leverage, low-energy” perturbation windows.  
  - **Methods:** Encoder feature hooks, ensemble rollouts, causal/attribution metrics, ablation & Sobol sensitivity.  
  - **Outputs:** Playbooks of effective nudge patterns + reproducible notebooks and evaluation dashboards.  

- 🔬 **Latent-State & Instability Triggers for Adaptive Chaos Control in Seasonal Lorenz-84**  
  We extend our Weather Jiu-Jitsu framework to a seasonally forced Lorenz 84, using latent-state regimes and local instability cues to trigger minimal-energy control. Hidden-state models define “danger zones,” while local Lyapunov exponent diagnostics flag imminent transitions. When triggered, an optimizer applies bounded nudges that keep eddy energy within safe envelopes across varying seasonal forcing. The result may serve as a starting point for future foundation model pertubation.
  - **Goal:** Prevent entry into dangerous regimes and damp incipient eddies with minimal intervention.  
  - **Methods:** Regime discovery, constrained optimization, season-by-season benchmarking.  
  - **Outputs:** Benchmarks of trigger efficacy, control-energy budgets, and guidance for mapping to real-model encoders.  

---

## 📊 Conference Posters & Abstracts

- 📍 **[AGU 2024 Poster – Investigating Adaptive Chaos Control for Mitigating Weather Extremes](./publication/AGU-poster-2024.pdf)**
  This poster introduces the concept of adaptive chaos control as a potential method for weather modification.

  It explores how small, targeted perturbations—guided by Lyapunov exponents—can influence mid-latitude atmospheric circulation to reduce flood and drought risks. The work proposes a shift from traditional infrastructure toward dynamic interventions.

---

- 📍 **[AGU 2025 Abstracts](./publication/AGU-poster-2025)**  
  Abstracts submitted to AGU 2025 explore Weather Jiu-Jitsu strategies across foundational theory, idealized and DL-based modeling, tropical cyclone and AR control, and seasonal regime dynamics.
  
  PDFs and final posters will be added as acceptance progresses.

    1. **[Weather Jiu Jitsu: A 21st century paradigm to leverage nature's power to mitigate some Compound, Concurrent, and Cascading Weather Hazards in a Changing Climate](./publication/AGU-poster-2025/1.pdf)**
  
  This talk outlines the potential for using small, strategically timed interventions to steer the atmosphere away from persistent weather regimes that produce compound extremes—floods, droughts, heatwaves, and more—drawing on idealized models and deep learning emulators to propose a new global-scale mitigation strategy.

    2. **[Steering Tropical Cyclones with Small Perturbations of the Jet Stream in Experiments with Deep Learning Foundation Models](./publication/AGU-poster-2025/2.pdf)**
  
  Explores the feasibility of shifting tropical cyclone tracks away from vulnerable regions by subtly influencing upstream steering winds using the Aurora deep learning model.

    3. **[Toward Controlling Atmospheric Rivers with Deep Learning Foundation Models and Adaptive Perturbation](./publication/AGU-poster-2025/3.pdf)**

  Applies the Weather Jiu-Jitsu framework to Atmospheric Rivers, using Aurora to identify sensitive spatiotemporal zones where small interventions may redirect AR trajectories pre-landfall.

    4. **[Toward Adaptive Control of Extreme Weather Regimes Using the Seasonally Forced Lorenz-84 Model](./publication/AGU-poster-2025/4.pdf)**
  
  Extends previous idealized control work to a seasonally forced L84 system, showing that weather regime frequency and intensity can be adaptively modulated using targeted, time-sensitive nudges.

    5. **[Adaptive Chaos Control with Deep Learning of Atmospheric Dynamics to leverage the power of the atmospheric circulation with nudges to move or defuse storms and avert catastrophic flooding](./publication/AGU-poster-2025/5.pdf)**
  
  Presents Weather Jiu-Jitsu as an alternative to traditional flood infrastructure, exploring how small, well-timed perturbations to atmospheric circulation—supported by idealized models and deep learning emulators—could reduce the intensity or reroute flood-producing storms to mitigate impacts.

---

## 🌟 Join the Movement

Weather Jiu-Jitsu represents a fundamental shift in how humanity approaches extreme weather. By contributing to this research, you're helping develop capabilities that could save thousands of lives and prevent billions in damages.

**Every contribution matters** - whether you're a world-class atmospheric scientist or an undergraduate student, your unique perspective and skills can advance our understanding and capabilities.

---

## 📚 How to Cite

We invite collaboration to develop Weather Jiu Jitsu as a community research platform.

Please cite Weather Jiu-Jitsu if you use or build upon this work:

```bibtex
@article{lall2025weatherjiujitsu,
  author = {Lall, Upmanu and Liu, Moyan and Qin, Huang},
  title = {Weather Jiu-Jitsu: Climate Adaptation for the 21st Century},
  year = {2025},
  note = {Preprint available at GitHub}
}
