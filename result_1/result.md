### *Table 1*. 
Analysis of Language Prior's Robustness. We evaluate the stability of our Cascade Language Guidance (CLG) module under four prompt variations: 1) Original: using standard class names; 2) Category order shuffled: to test permutation invariance of the text inputs; 3) Slight noise added: appending contextual phrases (e.g., "in an autonomous driving scene") to test phrasing stability; and 4) Synonym replacement: utilizing semantic equivalents (e.g., "bicycle" → "bike", "car" → "automobile") to verify conceptual understanding. The negligible performance drops (Δ<0.015 mIoU) demonstrate that our model fundamentally captures VLM semantic priors rather than overfitting to specific words or token orders.
| Variant | Score | Δ from Original |
|---|---:|---:|
| Original | 20.7212 | 0.0000 |
| Category order shuffled | 20.7065 | -0.0147 |
| Slight noise added | 20.7123 | -0.0089 |
| Synonym replacement | 20.7077 | -0.0135 |
