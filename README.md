# ⚡ CAFFEINE STRATEGIST

> **"Focus is a resource. Sleep is a strategy. Don't leave either to chance."**

**Caffeine Strategist** is a data-driven bio-hacking tool designed for students, developers, and night-owls. It utilizes a **Pharmacokinetic (PK) Model** to simulate blood caffeine concentration, helping you hit "Golden Focus Zones" for exams (like ECON 458 or CS 577) while ensuring your $t_{1/2}$ (half-life) clears before your head hits the pillow.

---

## 🚀 Key Protocols

### 1. **Pharmacokinetic Simulation**

Visualizes your caffeine concentration curve using first-order elimination kinetics.

* **Formula:** 
$$C(t) = C_{peak} \cdot e^{-kt}$$


* **Elimination Constant:** 
$$k = \frac{\ln(2)}{t_{1/2}}$$



### 2. **Bio-Personalization Engine** (NEW in v2.0)

The system dynamically adjusts your metabolic half-life based on:

* **Genetic Profiles:** CYP1A2 enzyme speed (Fast vs. Slow metabolizers).
* **Biochemical Interference:** Adjusts for **medications** (e.g., birth control, which can double half-life) and **tobacco use** (which accelerates clearance).
* **Habitual Tolerance:** Adjusts focus thresholds based on your daily mg baseline.

### 3. **Reverse Strategy Optimizer**

Input your "Target Focus Time" and "Hard Sleep Deadline." The algorithm back-calculates the exact intake window and suggests the optimal drink type (Monster, Espresso, Tea) to fit the constraint.

### 4. **Strategic Exports**

* **Strategy Cards:** Download a high-res cyberpunk dashboard of your curve via `html2canvas`.
* **CSV Logs:** Export your intake history for long-term trend analysis in Python/Excel.

---

## 🛠️ Tech Stack

* **Logic:** JavaScript (Pharmacokinetic Modeling & Heuristic Optimization).
* **Visuals:** [ECharts](https://echarts.apache.org/) (Coordinate System & MarkAreas).
* **Aesthetic:** Cyberpunk CRT-style CSS with Scanline overlays.
* **Deployment:** Optimized for GitHub Pages with an auto-generating QR sync.

---

## 🧬 How the "Bio-Logic" Works

Your protocol isn't just a generic timer. It calculates a **Custom Half-Life ($t_{1/2}$)**:

* **Baseline:** $5.0$ hours.
* **Fast Metabolizer:** $-1.2$ hours.
* **Medication/Slow:** $+1.5$ hours.
* **Empty Stomach:** Shits peak offset from $45$ mins to $25$ mins.

---

## 🧪 Use Cases

* **The Final Exam Sprint:** Mapping out a 48-hour study session for **CS 577** without the 3 AM jitters.
* **Hackathon Endurance:** Stacking Red Bulls with precise decay tracking.
* **Circadian Alignment:** Ensuring your "Tired but Wired" phase doesn't overlap with your actual sleep window.

---

## 🛡️ Disclaimer

*For educational use only. I am a Computer Science/Economics student, not a doctor. Caffeine is a powerful stimulant; use the data, but listen to your heart (literally).*
