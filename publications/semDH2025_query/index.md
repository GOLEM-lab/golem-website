---
date: "2025-06"
description: Multilingual natural language to SPARQL with LLMs.
subtitle: Jose Maldonado-RodrÃŋguez, Arianna Graciotti, Valentina Presutti, and Federico Pianzola
title: "Natural Language Querying for Humanities Knowledge Graphs: A Case Study on the GOLEM Knowledge Graph"
image: golem_query.png
title-block-style: none
toc: false
categories: 
  - LLMs
  - NLP
  - semantic web
---

<button type="button" class="btn btn-outline-success" target="_blank"><a href="https://ceur-ws.org/Vol-4009/paper_12.pdf">Download</a></button>



## Abstract 
Large-scale Knowledge Graphs (KGs) are increasingly relevant for humanities research, yet querying them via
SPARQL poses challenges for non-technical users. While Text-to-SPARQL studies predominantly target popular
KGs such as Wikidata or DBpedia, domain-specific KGs remain underexplored. This paper introduces a bilingual
(English-Spanish) dataset designed for evaluating automatic text-to-SPARQL translation on GOLEM, a humanities
KG containing metadata and extracted features from fanfiction stories hosted on Archive of Our Own (AO3). The
dataset includes 477 manually crafted natural language questions paired with gold SPARQL queries, augmented
to 1,895 questions through automatic paraphrasing. We benchmark several Large Language Models (LLMs) with
prompt-based approaches, particularly examining in-context learning methods that select prompt examples
based on semantic similarity, which yield the best results. Error analysis highlights entity linking as essential for
improving query generation. This work provides practical insights and opens pathways for future research on
natural language interfaces for querying domain-specific KGs in Digital Humanities. The dataset and output of
our experiments are available at: [https://github.com/GOLEM-lab/GOLEM_Text-to-SPARQL](https://github.com/GOLEM-lab/GOLEM_Text-to-SPARQL).

In *SemDH 2025: Second International Workshop of Semantic Digital Humanities. Co-located with ESWC 2025, June 02, 2025, Portoroz, Slovenia.*