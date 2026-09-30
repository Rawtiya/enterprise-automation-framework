# Automation Scoring Model

## Purpose

The Automation Scoring Model provides a consistent method for comparing automation opportunities across the enterprise.

The model evaluates two dimensions:

1. Business Value
2. Automation Feasibility

The resulting scores support portfolio prioritization.

---

# 1. Business Value Score

Score each dimension from 1 to 5.

| Dimension | Weight |
|---|---:|
| Cost / FTE Impact | 20% |
| Capacity Release | 15% |
| Cycle-Time Improvement | 15% |
| Quality Improvement | 15% |
| Customer Experience | 10% |
| Risk Reduction | 15% |
| Compliance Impact | 10% |

### Formula

Business Value Score =

`Σ (Dimension Score × Weight)`

Maximum score = 5.0

---

# 2. Automation Feasibility Score

Score each dimension from 1 to 5.

| Dimension | Weight |
|---|---:|
| Process Stability | 15% |
| Rule-Based Work | 15% |
| Data Quality | 15% |
| Transaction Volume | 10% |
| System Accessibility | 15% |
| Exception Predictability | 10% |
| Process Standardization | 10% |
| Technology Readiness | 10% |

### Formula

Automation Feasibility Score =

`Σ (Dimension Score × Weight)`

Maximum score = 5.0

---

# 3. Overall Opportunity Score

The overall score combines Business Value and Automation Feasibility.

| Dimension | Weight |
|---|---:|
| Business Value | 60% |
| Automation Feasibility | 40% |

### Formula

`Overall Score = (Business Value × 0.60) + (Feasibility × 0.40)`

Maximum score = 5.0

---

# 4. Portfolio Classification

| Overall Score | Portfolio Category |
|---:|---|
| 4.0 – 5.0 | Strategic Opportunity |
| 3.5 – 3.99 | High Priority |
| 3.0 – 3.49 | Evaluate |
| 2.0 – 2.99 | Low Priority |
| < 2.0 | Do Not Prioritize |

These categories are decision-support indicators and should be considered alongside risk, investment, dependencies, and strategic alignment.

---

# 5. Example

### Process

Invoice Reconciliation

### Business Value

| Dimension | Score |
|---|---:|
| Cost / FTE Impact | 5 |
| Capacity Release | 5 |
| Cycle-Time Improvement | 4 |
| Quality Improvement | 4 |
| Customer Experience | 3 |
| Risk Reduction | 4 |
| Compliance Impact | 3 |

Weighted Business Value:

**4.15 / 5**

### Automation Feasibility

| Dimension | Score |
|---|---:|
| Process Stability | 4 |
| Rule-Based Work | 5 |
| Data Quality | 4 |
| Transaction Volume | 5 |
| System Accessibility | 4 |
| Exception Predictability | 4 |
| Process Standardization | 4 |
| Technology Readiness | 5 |

Weighted Feasibility:

**4.35 / 5**

### Overall Score

`(4.15 × 0.60) + (4.35 × 0.40)`

**Overall Score = 4.23 / 5**

Portfolio classification:

**Strategic Opportunity**

---

# 6. Decision Gate

A high score does not automatically mean "automate."

The opportunity should also pass these gates:

- Process redesign completed
- Business owner identified
- Data/privacy requirements assessed
- Security requirements assessed
- Compliance requirements assessed
- Technology architecture reviewed
- Business case approved
- Benefits baseline established

The principle remains:

> **Score the opportunity. Then apply management judgment.**

---

# 7. Recommended Technology

The score determines priority.

The process characteristics determine the technology.

Examples:

| Process Characteristic | Potential Technology |
|---|---|
| Rule-based repetitive work | RPA |
| Cross-system orchestration | API / Workflow |
| Document-heavy work | IDP |
| Prediction / classification | ML |
| Unstructured language | GenAI |
| Complex human workflow | BPM |
| Process bottleneck discovery | Process Mining |

Technology selection should be based on the problem rather than a predetermined automation tool.
