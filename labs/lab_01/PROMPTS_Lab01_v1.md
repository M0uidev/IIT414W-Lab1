# Lab 1 · AI and contribution record

Members: Matías Mouat and María Jose Lopez

AI used / not used:  AI was used. We used Claude mainly to clarify parts of the lab instructions, support the local environment setup, and help review the wording of some interpretations. We only kept suggestions that matched the notebook outputs and our own analysis, and adjusted the wording when necessary. Relevant exchanges included environment setup, clarification of EDA results, and review of the calibration/final interpretation.

Own decision: We decided to keep the complete results population, including retirements and other non-finishers, instead of evaluating only drivers who finished the race.
Verification, observed result and limitation (notebook reference allowed): In the training data, evaluating all 1,200 rows gave the qualifying rule 0.742 accuracy and 0.742 balanced accuracy. Restricting the evaluation to the 1,024 finishers increased those metrics to 0.770 and 0.775 because 74 non-finishers who had qualified in the top ten were removed; those cases are genuine false positives at the stated prediction moment. This verified that filtering by race completion would make the rule look artificially better. A limitation is that `status` comes from the retrospective post-race source, so it is used only for auditing and not as a predictor or operational filter.

| Member | Contribution and evidence reference |
|---|---|
| Matías Mouat | Contributed to the implementation and development of the notebook, including data preparation, exploratory analyses, baseline evaluation, and review of the methodology. Evidence: `Lab01_EDA_Baselines_Student_v1.ipynb`, Sections 1–5. |
| María Jose López | Contributed to reproducing and verifying the notebook execution, reviewing the EDA and baseline results, completing the calibration/freeze/final interpretation, and documenting reproducibility and AI use. Evidence: `Lab01_EDA_Baselines_Student_v1.ipynb`, Sections 5–7, `RUNBOOK_Lab01_v1.md`, and `PROMPTS_Lab01_v1.md`. |
