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


<!-- There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

There should be whitespace between paragraphs.

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](another-page).

* toc
{:toc .large-only}

## Header 2

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

### Header 3

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists

Name
: Godzilla

Born
: 1952

Birthplace
: Japan

Color
: Green

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this. Or is it?
```

```
The final element.
``` -->
