---
layout: publication
title: Semantic Grading of Written Answers in Low-Resource Language Bangla Using a Fine-Tuned Lightweight Language Model
status: preprint
description: >
  <ul>
    <li>Fine-tuned a lightweight language model to grade responses (Bangla and English) from the question, reference answer, and student answer, returning a numeric score and concise contexual feedback.</li>
    <li>Constructed a synthetic bilingual dataset for controlled training and evaluation, yielding stronger human-score agreement than several proprietary baselines.</li>
  </ul>
image: /assets/img/publications/cognifyq_method_horizontal_2.png
venue: <strong>ACL System Demonstration 2026</strong> <i>(Preprint)</i>
authors: <strong>Meherun Farzana*</strong>, Aniket Joarder*, Mahmudul Hasan, Md. Mosaddek Khan
paper_link: https://arxiv.org/abs/2606.11931
website_link: https://cognifyq.com/
date: 2026-02-28
---

<!-- **Venue:** Under Review at **ACL System Demonstration 2026** \\
**Authors:** **Meherun Farzana**, Aniket Joarder, Mahmudul Hasan, Md. Mosaddek Khan\\
**Links:** [Paper]({{ '/assets/papers/cognifyq.pdf' | relative_url }}), [Website](https://cognifyq.com/) -->

Bangla is among the world’s most widely spoken languages, yet it remains underserved in educational NLP research. In many remote and rural regions, access to qualified subject teachers is limited, and written answers are consequently graded largely by hand, restricting timely and consistent feedback. Automatic assessment is challenging because semantically correct responses can vary substantially in surface form. We present a bilingual (Bangla-English) evaluation system designed for low-resource educational settings that prioritizes semantic correctness over lexical overlap. Our approach fine-tunes a lightweight language model to grade each response using the question, reference answer, and student answer, producing a numeric score and concise, context-grounded feedback suitable for classroom deployment. We also construct a synthetic bilingual dataset to enable controlled training and evaluation. Across proprietary and open-source LLMs evaluated under a unified protocol, our QLoRA-tuned Qwen3-8B confirms consistent improvement by producing the most leakage-resistant feedback (RoRa = 0.819) in synthetic evaluation and the strongest agreement with human scores (ρ = 0.936, MAE = 0.725) in a dedicated human study.

