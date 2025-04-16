# 🧼 Bias Evaluation of Toxicity Detection

**Fairness evaluation of a toxicity classifier across identity subgroups using open datasets**

---

## 📌 Overview
This project evaluated the fairness of a pre-trained toxicity detection system (Detoxify) by measuring its performance across identity subgroups using the Civil Comments dataset. We analyzed disparities in false positive rates, recall, and fairness metrics like Equal Opportunity and Demographic Parity.

## 🧠 Techniques & Tools
`Fairness Auditing` · `FPR/TPR Parity` · `Subgroup Analysis` · `Visualization` · `Pandas` · `Matplotlib` · `Jupyter`


## 📊 Key Results
- Overall AUC = 0.975, but subgroup AUCs dropped to 0.866 (Race), 0.914 (Religion)
- Found over-flagging of non-toxic comments referencing marginalized identities
- Proposed mitigations: group-specific thresholds, data augmentation

## 🔗 Links
- 🔍 [View Full Notebook (HTML)](rendered_html/bias_analysis.html)
- 🧾 [Final Report (PDF)](report.pdf)
- 🌐 [Portfolio](https://tanyanaheta.github.io)