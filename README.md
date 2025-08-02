# cardiac-digital-twin-COMSOL
COMSOL-based FEM simulation of cardiac adaptation across gravity (0G–1G) using FSI, strain metrics &amp; automated Python analysis.
![Preload Decline](./preload_decline_microgravity.png)
## 📉 Panel A: Preload Decline Under Simulated Spaceflight Conditions

**Figure Title:** Preload (%) vs. Time Under Microgravity (0G) and Martian Gravity (0.38G)

![Preload Decline](./2cb2e05f-4c1b-47bc-8b58-15d10845a186.png)

### 📊 Interpretation

This graph demonstrates the progressive decline in preload (expressed as percentage reduction from baseline) during 15 months of simulated exposure to spaceflight gravitational conditions.

- **Orange Line (0G)**: Shows rapid initial preload decline, stabilizing near ~40% by month 12. This aligns with known fluid redistribution and cardiovascular deconditioning during extended microgravity.
- **Blue Line (0.38G)**: Indicates more gradual reduction, plateauing around ~25%. Suggests Martian gravity provides partial physiological mitigation of cardiac unloading.
- These results were generated using time-resolved COMSOL simulations and validated against bedrest analog and ISS fluid shift data.

**Relevance**: Preload decline is a critical determinant of diastolic dysfunction and ventricular atrophy in long-duration missions. This plot supports development of targeted pre-habilitation strategies and countermeasure testing.

---

## 📉 Panel B: Baroreflex Gain Resetting Over Time

[Baroreflex Gain](./baroreflex graph.png)

**Figure Description:**
This figure shows a time-resolved curve of **baroreflex gain adaptation** during prolonged spaceflight. The simulation models autonomic regulation in microgravity, featuring:

- **Resetting Phase (~3 months):** Reflects an early shift in baroreflex set point.
- **Delay Phase (~9 months):** A latency window before further desensitization sets in.
- **Overall Gain Loss:** Indicates progressive decline in autonomic responsiveness.

**Relevance:**
- Based on empirical findings from Norsk et al. (2021), ISS astronaut studies.
- Supports incorporation of **autonomic dynamics into cardiac digital twin behavior**.
- Critical for long-duration mission risk modeling and algorithm tuning.

