![Vercel](https://img.shields.io/badge/Vercel-deployed-00C853?style=flat-square&logo=vercel&logoColor=white)
![UCLA](https://img.shields.io/badge/UCLA-MGMT%20258-2774AE?style=flat-square)
![Midterm](https://img.shields.io/badge/Midterm-Feb%2010%2C%202026-FF6D00?style=flat-square)
![Mermaid](https://img.shields.io/badge/Mermaid-33%20diagrams-FF3670?style=flat-square&logo=mermaid&logoColor=white)

# The Science of Happiness - Visual Knowledge Atlas

A comprehensive visual study guide for **MGMT 258: The Science of Happiness** at UCLA Anderson School of Management. 33 interactive Mermaid diagrams distilling 5 weeks of research-backed insights into one navigable page.

**[View Live](https://happiness-midterm.vercel.app)**

---

## Course Map

```mermaid
block-beta
  columns 5

  W1["Week 1\nFoundations"]:1
  W2["Week 2\nEnemies & Antidotes"]:1
  W3["Week 3\nTime & Experience"]:1
  W4["Week 4\nSocial Connection"]:1
  W5["Week 5\nDaily Practices"]:1

  W1A["Subjective\nWell-Being"]:1
  W2A["Hedonic\nAdaptation"]:1
  W3A["Time vs\nMoney"]:1
  W4A["Harvard\nStudy"]:1
  W5A["Gratitude"]:1

  W1B["50-40-10\nModel"]:1
  W2B["Social\nComparison"]:1
  W3B["Time\nCrafting"]:1
  W4B["Weak\nTies"]:1
  W5B["Mindfulness"]:1

  W1C["Hedonic vs\nEudaimonic"]:1
  W2C["Impact\nBias"]:1
  W3C["Extraordinary\nvs Ordinary"]:1
  W4C["Active Constructive\nResponding"]:1
  W5C["Exercise\n& Sleep"]:1

  space:1
  W2D["6 Anti-Adaptation\nStrategies"]:1
  space:1
  space:1
  W5D["Flow\nState"]:1

  style W1 fill:#1976d2,color:#fff,stroke:#1565c0
  style W2 fill:#c62828,color:#fff,stroke:#b71c1c
  style W3 fill:#2e7d32,color:#fff,stroke:#1b5e20
  style W4 fill:#e65100,color:#fff,stroke:#bf360c
  style W5 fill:#4a148c,color:#fff,stroke:#311b92

  style W1A fill:#e3f2fd,color:#1a1a1a,stroke:#1976d2
  style W1B fill:#e3f2fd,color:#1a1a1a,stroke:#1976d2
  style W1C fill:#e3f2fd,color:#1a1a1a,stroke:#1976d2
  style W2A fill:#ffebee,color:#1a1a1a,stroke:#c62828
  style W2B fill:#ffebee,color:#1a1a1a,stroke:#c62828
  style W2C fill:#ffebee,color:#1a1a1a,stroke:#c62828
  style W2D fill:#ffebee,color:#1a1a1a,stroke:#c62828
  style W3A fill:#e8f5e9,color:#1a1a1a,stroke:#2e7d32
  style W3B fill:#e8f5e9,color:#1a1a1a,stroke:#2e7d32
  style W3C fill:#e8f5e9,color:#1a1a1a,stroke:#2e7d32
  style W4A fill:#fff3e0,color:#1a1a1a,stroke:#e65100
  style W4B fill:#fff3e0,color:#1a1a1a,stroke:#e65100
  style W4C fill:#fff3e0,color:#1a1a1a,stroke:#e65100
  style W5A fill:#f3e5f5,color:#1a1a1a,stroke:#4a148c
  style W5B fill:#f3e5f5,color:#1a1a1a,stroke:#4a148c
  style W5C fill:#f3e5f5,color:#1a1a1a,stroke:#4a148c
  style W5D fill:#f3e5f5,color:#1a1a1a,stroke:#4a148c
```

## Key Formula

```mermaid
flowchart LR
    LS["Life Satisfaction\n(cognitive)"] -->|"+"| SWB["Subjective Well-Being"]
    PA["Positive Affect\n(emotional)"] -->|"+"| SWB
    NA["Negative Affect\n(emotional)"] -->|"-"| SWB

    style SWB fill:#1565c0,color:#fff,stroke:#0d47a1
    style LS fill:#e3f2fd,color:#1a1a1a,stroke:#1976d2
    style PA fill:#c8e6c9,color:#1a1a1a,stroke:#2e7d32
    style NA fill:#ffcdd2,color:#1a1a1a,stroke:#c62828
```

## The Happiness Pie

```mermaid
pie title What Determines Happiness?
    "Genetic Set Point (50%)" : 50
    "Intentional Activity (40%)" : 40
    "Life Circumstances (10%)" : 10
```

## What's Inside

| Section | Topics | Diagrams |
|---------|--------|----------|
| 0. Master Overview | Full course concept map + timeline | 2 |
| 1. What is Happiness? | SWB, 50-40-10, Hedonic vs Eudaimonic | 4 |
| 2. Three Enemies | Hedonic Adaptation, Social Comparison, Impact Bias | 5 |
| 3. Anti-Adaptation Toolkit | 6 strategies, savoring with breaks | 2 |
| 4. Time & Happiness | Time vs Money, Time Crafting, free time curve | 4 |
| 5. Extraordinary vs Ordinary | Socioemotional Selectivity Theory | 1 |
| 6. Social Connection | Harvard Study, weak ties, reaching out | 3 |
| 7. Active Constructive Responding | ACR 2x2 grid, social media | 2 |
| 8. Gratitude | Journal, letter, workplace gratitude | 3 |
| 9. Mind & Body | Mindfulness, exercise, sleep, flow | 5 |
| 10. Exam Cheat Visual | Summary + exam strategy | 2 |

**Total: 33 Mermaid diagrams** across **11 sections**

## Built With

- [Mermaid.js v11](https://mermaid.js.org/) - 33 diagrams (mindmap, flowchart, pie, sequence, timeline, xychart, quadrant)
- Vanilla HTML/CSS/JS - zero dependencies, single file
- [Vercel](https://vercel.com) - deployment

---

*UCLA Anderson School of Management, Winter 2026*
