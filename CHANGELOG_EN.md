# Changelog

All notable changes to the project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-03-29

### Added
- **Black Hole Simulation** (`gargantua.html`)
  - Schwarzschild metric implementation
  - Runge-Kutta 4th order geodesic integration
  - Adaptive ray tracing (350 steps per ray)
  - Gravitational lensing visualization
  - Accretion disk rendering with relativistic effects
  - Interactive camera controls (mouse drag, scroll zoom)
  - Real-time performance (~60 FPS)
  
- **Landing Page** (`main_page.html`)
  - NASA-style typography
  - 3D Earth background (Three.js)
  - Responsive glass-morphism UI
  - Statistics display (Mass, Ray Steps, ISCO Radius)
  
- **Saturn Visualization** (`saturn.html`)
  - Procedural Saturn rendering with rings
  - Canvas-based texture generation (no CORS issues)
  - Realistic axial tilt (26.7°)
  - Animated ring system

### Technical Features
- WebGL 2.0 rendering pipeline
- Three.js r128 library
- Custom shader programs for gravitational effects
- Adaptive step-size control for numerical integration
- Procedural texture generation (no external dependencies)
- Responsive design for all screen sizes
- NASA font integration

### Physics Implementation
- Schwarzschild metric: ds² = -(1-2M/r)dt² + (1-2M/r)⁻¹dr² + r²dΩ²
- Geodesic equations solved via RK4 method
- ISCO (Innermost Stable Circular Orbit) at 3.0 R_s
- Observer distance: 10.0 R_s
- Black hole mass: 4.3 × 10⁶ M☉ (Sagittarius A* parameters)

### Performance
- 350 adaptive ray steps
- 60 FPS target framerate
- Optimized WebGL rendering
- Efficient memory management

## [0.2.0] - 2026-03-28

### Added
- Saturn visualization prototype
- Procedural ring system generation
- Canvas-based texture creation

## [0.1.0] - 2026-03-27

### Added
- Initial project structure
- Basic Three.js setup
- Landing page design
- Black hole simulation concept

---

## Future Roadmap

### Planned Features
- [ ] Kerr metric support (rotating black holes)
- [ ] Realistic accretion disk physics (temperature gradients)
- [ ] Doppler beaming effects
- [ ] Gravitational redshift visualization
- [ ] Multiple black hole systems
- [ ] VR/AR support
- [ ] Export simulation frames as video
- [ ] Custom black hole parameters UI
- [ ] Educational mode with explanations
- [ ] Comparison with EHT observational data

### Improvements
- [ ] Higher precision numerical integration
- [ ] GPU-accelerated ray tracing
- [ ] Post-processing effects (bloom, tone mapping)
- [ ] Sound design (sonification of data)
- [ ] Multi-language support

---

## Contributors

- Lead Developer & Physics Implementation
- Three.js & WebGL Development
- UI/UX Design

## Acknowledgments

- Event Horizon Telescope Collaboration for M87* and Sgr A* images
- NASA for educational resources
- Three.js community