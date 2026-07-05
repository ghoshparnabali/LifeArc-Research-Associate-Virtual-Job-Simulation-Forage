# LifeArc Research Associate Virtual Job Simulation (Forage)
This repository documents the completion of the [LifeArc Research Associate Virtual Job Simulation Experience](https://www.theforage.com/simulations/life-arc/life-sciences-biology-research-5t8f) on Forage. The simulation involved four tasks centred on optimising a fibroblast-to-sensory-neuron differentiation protocol for use in chronic pain drug screening.

---

## Tasks

**Task 1 — Experiment Design (Excel):** Designed a factorial optimisation experiment varying NGN2 lentivirus dose (MOI: 1, 2, 5, 10) and NT3 supplement concentration (0, 5, 25, 50 ng/mL) across a 24-well plate, including empty vector and no-treatment controls, MOI-to-volume conversions, and quadruplicate replication of the predicted optimal condition.

**Task 2 — Data Analysis (R):** Visualised and statistically analysed high-content imaging data reporting the fraction of MAP2-expressing cells across all treatment combinations (3 replicates each). 5 MOI NGN2 combined with NT3 supplementation produced the highest neuronal yield (mean ~12% MAP2+), identifying it as the optimal condition.

**Task 3 — Scientific Communication (Email):** Integrated follow-up data from a colleague (TRKA immunostaining and Ca²⁺ functional imaging) with Task 2 findings to assess nociceptor-specific output. Concluded that while NT3 increases overall neuronal yield, it reduces the proportion of functionally responsive nociceptors — recommending 5 MOI NGN2 without NT3 for screening applications.

**Task 4 — Presentation (PowerPoint):** Delivered a ~10-minute recorded work-in-progress presentation summarising the optimisation experiment design, imaging results, follow-up analysis, and provisional conclusions with next steps.

---

## Repository Structure

```
LifeArc-Research-Associate-Virtual-Job-Simulation-Forage/
├── LifeArc_Job_Simulation/
│   ├── task_1/
│   │   ├── data_experimental_protocol.pdf
│   │   └── result_experiment_design.xlsx
│   ├── task_2/
│   │   ├── data_input.txt
│   │   ├── data_task_outline.Rmd
│   │   └── result_data_analysis.html
│   ├── task_3/
│   │   ├── data_email_from_Ela.pdf
│   │   └── result_email_to_Ela.pdf
│   └── task_4/
│       └── result_presentation.mp4
└── README.md
```

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Experiment design and sample matrix |
| R / RMarkdown | Statistical analysis and visualisation |
| Microsoft Word | Scientific email writing |
| Microsoft PowerPoint | Scientific presentation |
