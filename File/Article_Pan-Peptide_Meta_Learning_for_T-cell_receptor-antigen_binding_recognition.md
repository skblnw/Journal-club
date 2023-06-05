Pan-Peptide Meta Learning for T-cell receptor-antigen binding recognition

---
[TOC]

---
## Summary
The article discusses a new computational framework called Pan-Peptide Meta Learning (PanPep) designed to improve the understanding and prediction of interactions between T-cell receptors (TCRs) and antigens. Accurate prediction of TCR-antigen pairing is a significant challenge in immunology and has substantial implications for vaccine development, diagnostics, and immunotherapies. Existing tools often fail to recognize antigens that have never been presented to the immune system or for which only a few TCR binding repertoires are known. Such binding specificity for neoantigens or exogenous peptides is crucial for immunological studies and immunotherapy.

PanPep is a universal framework that integrates concepts from meta-learning and the neural Turing machine (NTM) to recognize any type of peptide-TCR binding. Meta-learning allows the system to adapt quickly from a few samples in different tasks, while NTM uses external memory to prevent forgetting during the learning process. PanPep can be generalized to any new peptide-specific tasks in a pan-peptide manner and is effective in various settings, including those with a large number of known binding TCRs, with few known binding TCRs, or with peptides not present in the training data. This ability makes PanPep particularly useful for recognizing TCRs that bind to unseen peptides.

Comprehensive testing of PanPep showed that it significantly outperforms existing methods for TCR recognition across all settings. Notably, PanPep accurately identifies TCRs binding to exogenous or new peptides to the immune system, a task at which other existing tools failed. PanPep has demonstrated its utility in several clinical applications and offers interpretability, revealing the nature of peptide-TCR interactions in 3D crystal structures.

PanPep also showed significant improvement in the recognition of TCRs binding to unseen peptides compared to existing tools. This improvement was observed across all three settings: majority, few-shot, and zero-shot learning.
