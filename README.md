# Aadhaar Early-Childhood Enrolment Analysis (Age 0–5)

## Overview

This project analyses **early-childhood (0–5 years) Aadhaar enrolment** using UIDAI open datasets.
The goal is to identify **where enrolment gaps exist**, **how they vary across geography**, and **where interventions would have the highest national impact**.

The analysis progresses deliberately from
**problem identification → comparison → prioritisation → policy simulation**.

---

## Dataset

* **Source:** UIDAI Open Data
* **Level:** State and District
* **Age Focus:** 0–5 years
* **Tools:** Python, Pandas, Matplotlib, Jupyter Notebook

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Venugopal9578/aadhaar-early-childhood-enrolment-analysis.git
```

Open the Jupyter Notebook:

```bash
jupyter notebook
```

---

## Visualisations & Insights

---

### 1️⃣ States with Lowest Aadhaar Enrolment (Age 0–5)

**🎯 Intention**

To identify which states are performing worst in early-childhood Aadhaar enrolment.

**📊 What this visual shows**

States ranked by lowest percentage of 0–5 enrolment, without any national comparison.

**🧠 What it is saying**

Several states show very low early-childhood enrolment, indicating potential inclusion gaps at the state level.

**🔑 Why this matters**

Acts as the initial problem discovery step, highlighting where enrolment challenges are concentrated.

![States with Lowest Aadhaar Enrolment (Age 0–5)](screenshots/states_lowest_0_5.png)


---

### 2️⃣ States with Lowest Aadhaar Enrolment (Age 0–5) vs National Average

**🎯 Intention**

To understand how far low-performing states deviate from the national benchmark.

**📊 What this visual shows**

* Lowest-performing states
* National average reference line
* Same scale for direct comparison

**🧠 What it is saying**

Several states fall significantly below the national average, confirming these are meaningful gaps rather than minor deviations.

**🔑 Why this matters**

Introduces national context, helping distinguish truly critical states from marginal underperformers.

![States with Lowest Aadhaar Enrolment vs National Average](screenshots/states_vs_national_avg.png)


---

### 3️⃣ Meghalaya Districts with Lowest Aadhaar Enrolment (Age 0–5)

**🎯 Intention**
To check whether a low-performing state underperforms uniformly or due to specific districts.

**📊 What this visual shows**
District-wise 0–5 enrolment percentages within Meghalaya.

**🧠 What it is saying**
A small number of districts drive the state’s overall low performance.

**🔑 Why this matters**
Suggests district-level interventions would be more effective than broad state-wide actions.

![Meghalaya Districts with Lowest Aadhaar Enrolment](screenshots/meghalaya_districts.png)


---

### 4️⃣ National Contrast: Best vs Worst States in Early Childhood Aadhaar Enrolment

**🎯 Intention**
To expose the true scale of inequality by comparing the best and worst performing states together.

**📊 What this visual shows**

* Top 5 states
* Bottom 5 states
* National average reference line

**🧠 What it is saying**
The gap between best and worst states exceeds **80 percentage points**, revealing structural disparities in early-childhood enrolment.

**🔑 Why this matters**
Demonstrates that the issue is not small optimisation, but deep national inequality.

![National Contrast Best vs Worst States](screenshots/best_vs_worst_states.png)


---

### 5️⃣ Regional Patterns in Early Childhood Aadhaar Enrolment

**🎯 Intention**
To determine whether enrolment gaps are random or regionally structured.

**📊 What this visual shows**
Average 0–5 enrolment across regions compared to the national average.

**🧠 What it is saying**
The North-East region consistently underperforms, while most other regions exceed the national benchmark.

**🔑 Why this matters**
Confirms the challenge is systemic and regional, requiring region-specific strategies.

![Regional Patterns in Early Childhood Aadhaar Enrolment](screenshots/regional_patterns.png)


---

### 6️⃣ States Requiring Highest Priority Intervention for Aadhaar Enrolment (Age 0–5)

**🎯 Intention**
To identify where intervention would have the highest national impact, not just where enrolment is lowest.

**📊 What this visual shows**
States ranked using a custom **Intervention Priority Index (IPI)** based on:

* Severity (gap from national average)
* Scale (enrolment volume)

**🧠 What it is saying**

* Bihar emerges as the highest-impact intervention state due to population scale
* Meghalaya ranks high due to extreme severity

**🔑 Why this matters**
Shifts the narrative from *“who is worst”* to *“where action matters most”*.

![States Requiring Highest Priority Intervention](screenshots/intervention_priority.png)


---

### 7️⃣ Severity vs Scale Quadrant for Early Childhood Aadhaar Enrolment

**🎯 Intention**
To classify states into clear decision zones for intervention planning.

**📊 What this visual shows**

* X-axis: Severity of enrolment gap
* Y-axis: Population scale
* Bubble size: Intervention Priority Index

**🧠 What it is saying**

* High severity + high scale → national priority
* High severity + low scale → targeted regional action

**🔑 Why this matters**
Enables policy decisions at a glance, aligned with real-world resource allocation.

![Severity vs Scale Quadrant](screenshots/severity_vs_scale_quadrant.png)


---

### 8️⃣ State-wise Contribution to India’s Total Aadhaar Enrolment Gap (Age 0–5)

**🎯 Intention**
To quantify which states contribute most to India’s total enrolment deficit.

**📊 What this visual shows**
Percentage contribution of each state to the national 0–5 enrolment gap.

**🧠 What it is saying**

* Bihar contributes ~65% of the national gap
* Meghalaya contributes ~24%, despite smaller population

**🔑 Why this matters**
Shows that addressing just two states can reduce nearly 90% of the national gap.

![State-wise Contribution to National Enrolment Gap](screenshots/contribution_to_gap.png)


---

### 9️⃣ Policy Impact Simulation: Bihar +5% Improvement

**🎯 Intention**
To simulate realistic policy action and observe its national effect.

**📊 What this visual shows**

* Current national average
* After a simulated +5% improvement in Bihar

**🧠 What it is saying**
A modest improvement in a single high-impact state produces a measurable national shift.

**🔑 Why this matters**
Transforms analysis into actionable policy foresight and validates prioritisation decisions.

![Policy Impact Simulation Bihar +5%](screenshots/policy_simulation_bihar.png)


---

## Overall Conclusion

This project moves from **problem discovery to decision intelligence**, combining:

* State and regional comparison
* District-level diagnosis
* Custom prioritisation metrics
* Impact simulation

The result is a **clear, evidence-driven roadmap** for improving early-childhood Aadhaar enrolment in India through **focused, high-impact interventions**.
