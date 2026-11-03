# fabric-lab

Hands-on labs I build while preparing the Microsoft Fabric certifications **DP-600** (Fabric Analytics Engineer) and **DP-700** (Fabric Data Engineer). Each lab is small, runs on a Fabric trial capacity and uses public or synthetic data only.

> 🇪🇸 Laboratorios prácticos que hago mientras preparo las certificaciones DP-600 y DP-700 de Microsoft Fabric. Cada laboratorio es pequeño, funciona con una capacidad de prueba de Fabric y usa solo datos públicos o sintéticos.

## Why

I work as a data analyst running a company BI platform on Microsoft Fabric and Power BI. These labs cover the parts of Fabric I use less in my day-to-day work, and they are the material behind the posts I share on LinkedIn while I study.

## Roadmap

| Certification | Exam (target) | Status |
| --- | --- | --- |
| [DP-600 · Fabric Analytics Engineer](dp-600/) | January 2027 | 🟡 In progress |
| [DP-700 · Fabric Data Engineer](dp-700/) | May 2027 | ⚪ Not started |

## Structure

```
fabric-lab/
├── dp-600/        Analytics engineering: lakehouse, warehouse, semantic models, deployment
│   └── NN-topic/  one folder per lab
└── dp-700/        Data engineering: PySpark, Delta Lake, pipelines, real-time, monitoring
    └── NN-topic/
```

Every lab folder has a short `README.md` with:

1. **Goal**: what the lab practises and which exam skill it maps to.
2. **Steps**: how to reproduce it in a Fabric workspace.
3. **Files**: notebooks (`.ipynb`), SQL scripts, pipeline definitions or Power BI projects (`.pbip`).
4. **What I learned**: the gotchas, including the ones that cost me time.

## Conventions

- Public or synthetic data only. Nothing from any employer.
- Notebooks are committed with their outputs cleared.
- Power BI work is saved as Power BI projects (`.pbip`), so changes show up in diffs.
- The exam skills follow the official study guides: [DP-600](https://learn.microsoft.com/credentials/certifications/resources/study-guides/dp-600) · [DP-700](https://learn.microsoft.com/credentials/certifications/resources/study-guides/dp-700).

## Author

**Adrián Reviriego** · Data Analyst & Engineer · Pamplona, Spain
