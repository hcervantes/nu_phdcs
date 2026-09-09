## ✍️ Paper Outline (SBIRS OPIR Use Case)

**Paper Focus:** How SBIRS OPIR collects, processes, transforms, and shares infrared data to detect missile plumes, classify them using ML, generate early track files, and cue radar systems for confirmation.

> **Why this use case:** It is a single end-to-end operational pipeline — collection → storage → manipulation → transformation → movement → ML classification → output (track files) → sharing (radar cueing). Every required assignment element maps to a real stage of the SBIRS/OPIR mission, which directly satisfies the "data manipulation in an operations environment" rubric criterion (3 pts).

**Format:** 6–8 pages, APA 7th, double-spaced, 12pt Times New Roman, 1-inch margins  
**Working Title:** *From Infrared Acquisition to Radar Cueing: The Role of Data in the SBIRS OPIR Missile Warning Pipeline*

---

### **Title Page**

- Title, your name, course (CSC-8102), instructor, due date (September 13, 2026)

---

### **Section 1: Introduction (\~0.75 page)**

- **Hook:** Strategic missile warning depends on turning raw infrared photons into actionable radar cues within seconds — a complete data lifecycle in miniature.
- **Context:** SBIRS (GEO + HEO satellites with OPIR scanners) and the Next-Gen OPIR successor detect the hot exhaust plume of a boosting missile against the Earth background and feed ground processing at the SBIRS Mission Control Station (Buckley Space Force Base).
- **Thesis/Roadmap:** This paper traces the role of data from acquisition to deletion through the SBIRS OPIR pipeline — collection by infrared sensors, storage and ground processing, transformation into track files, ML-based plume classification, and movement as cueing messages to radar systems for confirmation.

---

### **Section 2: Data, Information, and Metadata in the OPIR Context (\~1 page)**

- **Data:** Raw infrared sensor reads (pixel intensities, wavelengths, timestamps, sensor ID) — largely **unstructured** IR imagery/streams from scanning and staring sensors.
- **Information:** Processed outputs — confirmed missile launch events, plume trajectories, estimated launch point, predicted impact point — data placed into operational context.
- **Metadata:** Sensor ID, collection time, look angle, band (SWIR/MWIR), calibration state, confidence flags — descriptive/structural/administrative metadata that tags each IR frame.
- **Comparison table** (Data vs. Information vs. Metadata) using OPIR-specific examples.

---

### **Section 3: Purpose of Data Operations in the OPIR Pipeline (\~1 page)**

Frame each operation as a stage in the SBIRS pipeline:

- **Collection** — OPIR scanners/staring sensors continuously sweep and collect IR radiation (heat signatures) of missile plumes against the Earth background.
- **Storage** — Raw IR frames and derived events held in ground processing systems (FORGE C2 / Mission Control Station) for real-time and historical access.
- **Manipulation** — Background subtraction, clutter rejection, thresholding, and noise filtering to isolate the plume signal from terrain, clouds, and fires.
- **Movement** — Downlinked sensor data → ground station → processing center → broadcast to combatant commanders via JTAGS / Integrated Broadcast Service / Link 16.
- **Transformation** — IR frames converted into structured track records (azimuth, elevation, intensity, velocity estimates) suitable for ML inference and radar handoff.

---

### **Section 4: Stages of the Data Lifecycle — SBIRS OPIR (\~1.25 pages)**

Walk all seven stages through the OPIR example:

1. **Creation/Collection** — IR photons captured by GEO/HEO sensors during boost-phase missile flight.
2. **Storage** — Raw and processed data retained at the ground station; archived event logs for intelligence/battlespace characterization.
3. **Processing/Manipulation** — Signal processing to detect the plume; ML classification of event type.
4. **Use** — Track files feed missile warning, missile defense cueing, and technical intelligence.
5. **Sharing** — Warning, alerting, and cueing disseminated to combatant commanders and BMDS via JTAGS, IBS, Link 16.
6. **Archiving** — Event data retained for forensic analysis, model retraining, and intelligence history.
7. **Destruction** — Aged raw sensor streams purged per retention policy; only derived tracks/intelligence retained.

---

### **Section 5: Data Flow Diagram — SBIRS OPIR Cueing Pipeline (\~0.75 page + diagram)**

Create in **Lucidchart**. Show a single hypothetical use case: *detection of a theater ballistic missile launch*.

- **Input (External Entities):**
  - SBIRS GEO/HEO satellite OPIR sensors → raw IR radiation
  - Supporting context: Earth background, cloud/clutter data
- **Processing (Processes):**
  1. Sensor data downlink to ground station
  2. Background subtraction / clutter rejection (manipulation)
  3. Feature extraction (intensity, temporal profile, spectral signature)
  4. ML plume classification (missile type / false-alarm rejection)
  5. Track file generation (launch point, trajectory, predicted impact)
  6. Cueing message generation (targeting vector for radar)
- **Output (External Entities):**
  - Early warning reports to combatant commanders (JTAGS / Link 16)
  - Track files to battle management / fire control
  - **Radar cueing messages** → ground/sea radar systems for confirmation track
- **Data Stores:** Raw IR archive; processed track database; ML model repository
- **Label clearly** as *Figure 1* and reference it in the text.

> **Diagram tip:** Use a classic Gane-Sarson DFD — external entities (rectangles), processes (rounded rectangles), data stores (open rectangles), data flows (labeled arrows). Keep it on one page.

---

### **Section 6: Data in AI/ML — Plume Classification &amp; Track Generation (\~1 page)**

- **Data as model fuel:** ML classifiers are trained on labeled historical IR event data (true missile launches vs. false alarms like wildfires, aircraft afterburners, meteors).
- **Preprocessing applied to OPIR data:**
  - Cleaning: dropped/corrupted frames, sensor calibration drift.
  - Transformation: normalization of intensity, temporal resampling, spectral band alignment.
  - Feature engineering: plume temporal profile, intensity slope, spatial extent, multi-band ratios.
  - Train/test split: historical confirmed events vs. novel live events.
- **Model role:** Classify detected IR event as missile class vs. non-missile; reduce false-alarm rate; support confidence scoring on the track file.
- **Generalization:** Model must perform on novel threat classes (e.g., hypersonic glide vehicles) and different theaters — link this to "generalizable results" in the research summary.
- **Operational impact:** Faster, more accurate classification → earlier valid track file → quicker radar cue → more intercept timeline.

---

### **Section 7: Peer-Reviewed Research Summary (\~1.25 pages)**

Use the 2 required course articles, interpreted through the OPIR lens:

- **Azad et al. (2020)** — *Structured and Unstructured Data Managing Mechanisms in IoT*
  - **Objectives:** Compare SQL, NoSQL, and graph databases for managing IoT data.
  - **Data for insights:** Systematic review of scalability, query performance, and flexibility for mixed structured/unstructured data — directly analogous to SBIRS handling structured track files vs. unstructured raw IR streams.
  - **Generalizable results:** Findings on NoSQL suitability for high-volume unstructured sensor data generalize to OPIR ground processing architecture choices.
- **Thompson et al. (2021)** — *Farm Data Lifecycle*
  - **Objectives:** Analyze how farm data moves through collection → use → impact.
  - **Data for insights:** Survey and lifecycle analysis showing data value is realized only when each lifecycle stage is connected to decision-making — parallels the OPIR pipeline where value is realized only at the radar-cueing/output stage.
  - **Generalizable results:** The lifecycle framework generalizes to any sensor-to-decision pipeline, including missile warning.

> Add **2 additional peer-reviewed sources** on ML for IR/missile classification or sensor-cueing architectures to reach the 4-source minimum.

---

### **Section 8: Conclusion (\~0.5 page)**

- Restate the thesis: SBIRS OPIR is a complete data lifecycle — raw IR acquisition → processing → ML classification → track files → radar cueing.
- Emphasize that every required data operation (collection, storage, manipulation, movement, transformation) is present and mission-critical.
- Closing thought: as Next-Gen OPIR and proliferated architectures (e.g., HBTSS) expand the sensor layer, the data pipeline — not just the sensor — determines warning speed and accuracy.

---

### **References (APA 7th)**

- Azad, P., Navimipour, N. J., Rahmani, A. M., &amp; Sharifi, A. (2020). The role of structured and unstructured data managing mechanisms in the Internet of things. *Cluster Computing, 23*, 1185–1198. [https://doi.org/10.1007/s10586-019-02986-2](https://doi.org/10.1007/s10586-019-02986-2)
- Thompson, N. M., DeLay, N. D., &amp; Mintert, J. R. (2021). Understanding the farm data lifecycle: Collection, use, and impact of farm data on U.S. commercial corn and soybean farms. *Precision Agriculture, 22*(6), 1685–1710. [https://doi.org/10.1007/s11119-021-09807-w](https://doi.org/10.1007/s11119-021-09807-w)
- - 2 additional peer-reviewed sources (ML for IR/missile classification, sensor-cueing, or OPIR data processing).

---
