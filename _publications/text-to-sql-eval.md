---
layout: publication
title: "Q-SEM: Fine-Grained Question-Grounded Semantic Evaluation for Text-to-SQL"
status: preprint
description: >
  <ul>
    <li>Proposed Q-SEM, a fine-grained question-grounded semantic evaluation framework for Text-to-SQL that judges whether generated SQL preserves the intent of the natural-language question.</li>
    <li>Combined gold-SQL-agnostic and gold-SQL-contrastive semantic views to evaluate SQL correctness beyond exact match and execution-result matching.</li>
  </ul>
image: /assets/img/publications/qsem_archi.jpg
venue: <strong>EMNLP Main Track 2026</strong> <i>(under review)</i>
authors: Md. Mahmudul Hasan*, <strong>Meherun Farzana*</strong>, Mehrajul Abadin Miraj, Aniket Joarder, Mahmudul Hasan, Abir Chakraborty Partha, Md. Ahasanul Alam, Md. Tanvir Alam, Redwan Ahmed Rizvee, Md. Fahim Arefin, Md Mahmudur Rahman, Md. Mosaddek Khan
# paper_link: /assets/papers/qsem.pdf
# website_link: https://bi.cognistorm.ai/login 
date: 2026-05-25
---

<!-- **Venue:** Under Review at **ACL System Demonstration 2026** \\
**Authors:** **Meherun Farzana**, Aniket Joarder, Mahmudul Hasan, Md. Mosaddek Khan\\
**Links:** [Paper]({{ '/assets/papers/cognifyq.pdf' | relative_url }}), [Website](https://cognifyq.com/) -->

Text-to-SQL evaluation remains largely reference-centered. Execution Accuracy (EX), the dominant metric, evaluates a predicted SQL query by comparing its execution result against that of a single reference SQL. However, EX frequently fails when a prediction follows the same intended logic as the reference but differs in underspecified output behavior, when the question or schema admits multiple plausible interpretations, or when the reference SQL itself is noisy or incorrect. We therefore propose Q-SEM, a fine-grained, Question-grounded Semantic Evaluation Metric that evaluates whether a predicted SQL query preserves the intent of the natural-language question. Q-SEM combines two gold-SQL-agnostic views that assess whether the prediction covers and correctly composes the question’s semantic requirements with two gold-SQL-contrastive views that determine whether semantic differences constitute actual semantic errors with respect to the question intent. A final adjudicator resolves disagreements among the four views and produces the final acceptability decision. On the expert-labeled ROSE-VEC-BIRD benchmark, Q-SEM achieves 85.61% Cohen’s κ, obtaining the strongest agreement with human judgments and consistently outperforming deterministic metrics (EX reaches only 43.56%) and LLM-based methods across every evaluated LLM.

