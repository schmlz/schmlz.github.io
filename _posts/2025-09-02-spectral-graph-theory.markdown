---
title: Finding Plans and Heuristics with Spectral Graph Theory
layout: single
header:
  # image: /assets/images/cognere/cognere_summary.svg
  # teaser: /assets/images/cognere/cognere_summary.svg
# classes: wide
last_modified_at: 2025-12-06
excerpt_separator: <!--more-->
---

----

Spectral graph theory considers the matrices associated with graphs and studies these matrices' eigenvalues and eigenvectors. Spectral graph theory has applications in many fields of computer sciences, but has had surprisingly little impact in planning. A paper by Steinerberger (2021) shows how a particular eigenvector can be used to construct a descending heuristic - following this greedily is guaranteed to lead to the goal. We give an alternative proof of this fact by showing that the eigenvector describes a network flow, and we establish further connections to planning by showing that the eigenvector describes a consistent, goal-aware heuristic. We also give some examples to illustrate the behaviour of Steinerberger's algorithm, and answer one of his open questions.

<!--more-->

----

**HSDIP 2025 Paper**  [[v2 pdf]({{ site.url }}/downloads/spectral-graph-theory/spectral_graph_theory_hsdip_paper_v2.pdf)] [[v1 pdf]({{ site.url }}/downloads/spectral-graph-theory/spectral_graph_theory_hsdip_paper_v1.pdf)]

This paper was accepted at the [HSDIP 2025](https://icaps25.icaps-conference.org/program/workshops/hsdip/) workshop!
{: style="color: #9097a3"}

**Corrigendum:** the heuristic error on path graphs (fig. 5) is wrong in v1 and has been fixed in v2. Due to numeric issues, we were not selecting the smallest eigenvector but a close-to-smallest one, which does not describe a descending heuristic. The correct error curve is less complex (it's no longer sinusoidal), but it remains unclear how to predict. Thanks /P@trik Haslum for spotting the bug!
{: style="color: #9097a3"}

----

**Talk** [[HSDIP slides]({{ site.url }}/downloads/spectral-graph-theory/spectral_graph_theory_hsdip_talk.pdf)] [[AmsterCAPS slides]({{ site.url }}/downloads/spectral-graph-theory/spectral_graph_theory_amstercaps_talk.pdf)]

I gave this talk at [AmsterCAPS 2025](https://galvusdamor.github.io/ourAMSTERcaps25/) and [HSDIP 2025](https://icaps25.icaps-conference.org/program/workshops/hsdip/). The HSDIP version is newer and has more details.
{: style="color: #9097a3"}

----

**Code** [[github]](https://github.com/schmlz/spectral-plans-and-heuristics/tree/main)

Some python code for generating all the pictures from the paper and slides.
{: style="color: #9097a3"}
