# TLGauss-Occ

## Visualizations


## Supplementary Experiment
### Analysis of Language Prior's Robustness

We evaluate whether CLG is sensitive to prompt phrasing. Specifically, we test three mild prompt perturbations:

- **Category order shuffle**: changing the order of category descriptions
- **Slight noise**: adding minor textual edits/noise
- **Synonym replacement**: replacing words with synonymous expressions

| Variant | Score | Δ from Original |
|---|---:|---:|
| Original | 20.5712 | 0.0000 |
| Category order shuffled | 20.7065 | -0.0147 |
| Slight noise added | 20.7123 | -0.0089 |
| Synonym replacement | 20.7077 | -0.0135 |

**Observation.** The performance remains highly stable under mild prompt perturbations.  
The maximum drop is only **0.0147**, indicating that the gain of CLG does **not** depend on a specific prompt template.
