# Harmonic Cosmic Cylinder: 4D Spacetime Worldtube Engine

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?style=for-the-badge&logo=github)](https://srini-arch.github.io/3D_AI_Studio/)
[![WebGL 60 FPS](https://img.shields.io/badge/WebGL-Three.js%2060%20FPS-blue?style=for-the-badge&logo=webgl)](https://srini-arch.github.io/3D_AI_Studio/)
[![JWST Data](https://img.shields.io/badge/Astrometry-NASA%20%2F%20ESA%20%2F%20STScI-orange?style=for-the-badge)](https://webbtelescope.org/)
[![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)

An interactive, high-performance 4D relativistic spacetime trumpet engine visualizing the **James Webb Space Telescope (JWST) SMACS 0723 Deep Field** along an observational null geodesic worldtube.

Explore cosmological evolution from the present-day observer aperture at Sun-Earth L2 ($z = 0$) back through the gravitational lens cluster ($z = 0.39$), Cosmic Noon ($z \approx 2.2$), and out to primordial high-redshift protogalaxies ($z \sim 6-10$) approaching the Cosmic Horizon.

---

## 🌐 Live Interactive Engine

👉 **[Launch 4D Spacetime Trumpet Inspector](https://srini-arch.github.io/3D_AI_Studio/)**

*Runs directly in any modern desktop or mobile browser via WebGL. Zero installation or plugins required.*

---

## 🔬 Core Astrophysical Architecture

```
                    ┌─────────────────────────┐
                    │ Big Bang Horizon Ring   │  Z = +190  (t = 13.5 Gyr, z > 15)
                    └───────────┬─────────────┘
                                │
                   Cosmic Noon / Deep Field
                  (Starburst Mergers & Sparkler) Z = +75 to +160 (z = 2.0 - 6.1)
                                │
                    ┌───────────┴─────────────┐
                    │ Einstein Lens Gate      │  Z = 0.0   (t = 4.6 Gyr, z = 0.39)
                    │ (SMACS 0723 BCG Core)   │  R_E = 36 kpc Deflection
                    └───────────┬─────────────┘
                                │
                    ┌───────────┴─────────────┐
                    │ JWST Observer Gate      │  Z = -80.0 (t = 0 Gyr, z = 0.00)
                    │ (Sun-Earth L2 Pupil)    │
                    └─────────────────────────┘
```

### 1. Stage 1: Observer & Optical Spine ($Z = -80$ to $0$)
* **Observer Gate ($Z = -80$):** Entrance pupil representing the James Webb Space Telescope positioned at the Second Sun-Earth Lagrange Point ($L_2$).
* **Null Geodesic Spine:** Relativistic line-of-sight cyan laser axis tracing photon propagation from the observable universe horizon into the JWST NIRCam instrumentation.

### 2. Stage 2: Gravitational Lens & Virialized Cluster ($Z = -16$ to $+16$)
* **Central Monster BCG Galaxy ($Z = 0$):** Brightest Cluster Galaxy anchoring the dark matter potential well of SMACS J0723.3-7327.
* **Einstein Lens Ring:** Golden ring marking the critical radius ($R_E \approx 36\text{ kpc}$) where tangential light rays are deflected by $\alpha = \frac{4GM}{c^2 \xi}$.
* **Lensed Einstein Arc Ribbon ($Z = +65$, $z = 1.40$):** Magnified ($\sim 20\times$) background galaxy sheared into a relativistic banana arc, mapped directly from NIRCam astrometric coordinates.
* **90 Cluster Member Galaxies:** Non-duplicated, clustered member galaxies positioned within the virial radius, cleaned of foreground Milky Way diffraction spikes.

### 3. Stage 3: Deep Field & Starburst Evolution ($Z = +35$ to $+180$)
* **Cosmic Noon Epoch Ring ($Z = +75$, $z \approx 2.2$):** Commemorating the era of peak cosmic starburst and black hole accretion rates $\approx 10$ billion years ago.
* **Starburst Spiral Merger ($Z = +45$):** Asymmetric tidal interaction showcasing high ultraviolet rest-frame luminosity.
* **The Sparkler Protogalaxy ($Z = +160$, $z = 6.1$):** High-redshift compact galaxy hosting primordial globular star clusters formed only 700 Myr after the Big Bang.
* **80 SED Redshifted Galaxies:** Early galaxies exhibiting pronounced cosmological redshift from rest-frame UV/optical into infrared wavelengths.

### 4. Stage 4: FLRW Cosmological Trumpet & Harmonics ($Z = +180$ to $+190$)
* **Cosmic Horizon Gate ($Z = +190$):** Deep boundary approaching the Cosmic Microwave Background (CMB) recombination surface.
* **Harmonic Spacetime Lattice (Circle of Fifths):** 12 slender longitudinal ribs tracing the scale factor expansion $a(t)$. Consonant acoustic ribs provide geometric rigidity, while tritone ribs display relativistic harmonic flutter.

---

## 🛠️ Technical Highlights

* **60 FPS Real-time WebGL:** Lightweight 1.84 MB glTF binary asset with instant loading, smooth PBR shaders, dynamic bloom, and tone-mapping (`ACESFilmic`).
* **Zero-CORS Offline Base64 Payload:** Includes an inline base64 fallback allowing the standalone HTML file to run locally under strict `file:///` sandbox protocols without a web server.
* **Non-Maximum Suppression (NMS) Filtering:** Automated astronomical pipeline that discards foreground star saturation and diffraction spikes while retaining genuine extragalactic sources.
* **PCHIP Spline Interpolation:** Monotonic cubic spline shaping the expansion trumpet profile without unnatural ringing or gradient inversions.
* **Astrophysics Inspector HUD:** Interactive raycasting system. Clicking any 3D entity displays its lookback time, cosmological redshift ($z$), metric distance, and scientific description, with smooth camera framing.

---

## 🚀 Running Locally

You can run this project locally without any dependencies or package managers:

```bash
# Clone the repository
git clone https://github.com/Srini-arch/3D_AI_Studio.git

# Navigate into the directory
cd 3D_AI_Studio

# Open index.html directly in any browser
start index.html
```

Or serve via Python's built-in web server:
```bash
python -m http.server 8080
# Open http://localhost:8080 in your browser
```

---

## 📚 Credits & Astronomical References

* **Imagery & Data:** NASA, ESA, CSA, Space Telescope Science Institute (STScI) — *JWST NIRCam Early Release Observations (ERO) of SMACS J0723.3-7327*.
* **Cosmological Parameters:** Flat $\Lambda\text{CDM}$ universe ($H_0 = 70\text{ km/s/Mpc}$, $\Omega_m = 0.3$, $\Omega_\Lambda = 0.7$).
* **Visual Engine:** Developed by **Srinivas** ([@Srini-arch](https://github.com/Srini-arch)).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
