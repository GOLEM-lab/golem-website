---
date: "2025-11"
description: Breaking the dream of using LLM for extracting derived features from text.
subtitle: Arianna Graciotti, Franziska Pannach, Valentina Presutti, and Federico Pianzola
title: "Llamas Don’t Understand Fiction: Application and Evaluation of Large Language Models for Knowledge Extraction from Short Stories in English"
image: golem_death.png
title-block-style: none
toc: false
categories: 
  - LLMs
  - NLP
  - features extraction
---

<button type="button" class="btn btn-outline-success" target="_blank"><a href="https://doi.org/10.63744/iCGYNUN0uUAe">Download</a></button>



## Abstract 
Extracting event knowledge from unstructured text is a well-known challenge in Natural
Language Processing (NLP) and is particularly difficult when dealing with fiction. Subtext,
rather than explicit information, and figurative style in fictional narratives, complicate event
extraction. Recent advances in Large Language Models (LLMs) have improved performance
across various NLP tasks. However, their effectiveness in extracting events from fiction
remains underexplored. In this article, we evaluate the performance of open-weights LLMs to
extract character death events from fictional narratives in English. These events are defined as
triples consisting of Victim, Perpetrator, and Mode of Demise. We cast Knowledge Extraction
(KE) as a zero-shot task and evaluate our approach on a manually annotated benchmark
of fanfiction stories. Our results show that LLMs struggle with KE from fiction, with a
maximum F1-score of 0.45 across the elements constituting the triples and, at most, 25%
of death events correctly extracted. A detailed error analysis reveals that most errors stem
from missed death events and from direct presentation modes, such as direct speech, which
significantly impair extraction performance. Moreover, KE accuracy declines as the story
length increases, while LLMs’ background knowledge leakage contributes to false positives.
These findings provide domain-specific insights into the challenges of KE in fiction.

In *Computational Humanities Research 2025*, ed. by Taylor Arnold, Margherita Fantoli, and Ruben Ros. Vol. 3. Anthology of Computers and the Humanities. 2025, 4–32.