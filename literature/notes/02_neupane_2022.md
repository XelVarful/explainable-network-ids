# 02 — Neupane et al. (2022)

**Title:** Explainable Intrusion Detection Systems (X-IDS): A Survey of Current Methods, Challenges, and Opportunities  
**Publication:** IEEE Access, 2022  
**Article type:** Survey  
**DOI:** https://doi.org/10.1109/ACCESS.2022.3216617  
**Open full text:** https://arxiv.org/pdf/2207.06236

## Research objective

The authors examine how intrusion detection systems can explain their
predictions to the people who investigate security alerts.

## Main findings

The survey compares models whose decision rules can be inspected directly
with models that require a separate explanation method. The authors
propose an architecture that includes a human analyst and identify three
research needs: define what explainability means for an IDS, tailor
explanations to the intended user, and evaluate their quality.

One example in the survey illustrates two distinct criteria. Fidelity
asks whether the explanation reflects the model's behavior.
Understandability asks whether a person can follow that explanation.

## Relevance to our study

For RQ3, we will examine a correctly detected attack and a false alarm.
For each network flow, we will report the true label, the predicted label,
and the features that pushed the SHAP explanation toward an attack.
This lets us ask whether the model relied on the same traffic pattern
when it was right and when it was wrong.

## Limits of comparison

This survey informs our explanation design. To compare the detection
performance of our four models on a shared dataset, we will use
experimental studies and our own measurements.

## Evidence

- Abstract: research objective, analyst involvement, and research recommendations.
- Full text, PDF page 12, "Hybrid Approaches": example discussing fidelity
  and understandability.
``` :chatgpt-content-reference{index="1"}


**2. В `literature/review.md`** у статьи `02` замени `Identified` на `[Reviewed](notes/02_neupane_2022.md)` после сверки заметки с источником.

**3. Сохрани изменения и отправь их в текущую ветку:**

```bash
git add literature/notes/02_neupane_2022.md literature/review.md
git commit -m "docs: review Neupane et al. on explainable IDS"
git push