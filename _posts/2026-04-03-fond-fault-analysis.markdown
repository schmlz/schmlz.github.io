---
title: Algorithms for Deciding the Safety of States in Fully Observable Non-deterministic Problems
layout: single
header:
  # image: /assets/images/cognere/cognere_summary.svg
  # teaser: /assets/images/cognere/cognere_summary.svg
# classes: wide
last_modified_at: 2026-06-25
excerpt_separator: <!--more-->
---

----

Suppose you have a learned policy for a Fully Observable Non-deterministic (FOND) problem. How can you be sure that it is safe? One approach is via fault analysis, which relies on algorithms that find whether individual states are safe or not. This work shows that the existing state-of-the-art algorithm for this has an exponential worst-case time complexity, and then we present a practical alternative.

<!--more-->

----

**ICAPS 2026 Short Paper** [[link]](https://ojs.aaai.org/index.php/ICAPS/article/view/42858)

This short paper was accepted at [ICAPS 2026](https://icaps26.icaps-conference.org/)!
{: style="color: #9097a3"}

----

**Technical Report** [[pdf]({{ site.url }}/downloads/fond-fault-analysis/fond_fault_analysis_icaps2026_extended_paper.pdf)] [[arxiv]](https://arxiv.org/abs/2603.15282)

Extended version of the paper that **subsumes the short conference version**. It has more details for the algorithms, proofs, and experimental results.
{: style="color: #9097a3"}

----

**Source Code, Benchmarks, and Data** [[zenodo]](https://zenodo.org/records/18926835) [[github]](https://github.com/ChaahatJain/ICAPS26-Deciding-State-Safety-in-FOND)

The code, benchmarks, and experimental results are all here.
{: style="color: #9097a3"}
