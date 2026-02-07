# SWORD
 SWORD: Systematic Wikidata-based Object-Relation Distortion for Evaluating Cross-Lingual Bias in LLM Factual Accuracy

 ## Abstract 
## Overview

**Figure 1. SWORD pipeline overview**

[📄 View Figure 1 (PDF)](01.results/00.main_figures/Fig1.Pipeline.pdf)

Modern LLMs demonstrate impressive performance on multilin-gual tasks, often approaching human-level accuracy across diverse languages. 
However, standard benchmarks primarily reward select-ing correct answers, which does not necessarily indicate genuine factual understanding. 
We introduce Systematic Wikidata-based Object-Relation Distortion (SWORD), a benchmark that evaluates whether models consistently detect factual errors across languages.
SWORD generates syntactically well-formed but factually incor-rect statements in eight linguistically diverse languages through controlled perturbations of Wikidata triples, ranging from ran-dom entity substitutions to semantically plausible property-based selections. 
Our evaluation reveals substantial cross-lingual incon-sistencies: models that correctly validate original facts often fail to consistently reject distorted versions across languages. 
Notably, some Western-developed models exhibit disproportionate perfor-mance degradation on Asian languages under distortion, despite comparable baseline accuracy. These inconsistencies remain in-visible in standard multilingual benchmarks that measure only performance on correct answers, demonstrating that multilingual factual reasoning cannot be adequately assessed through aggregate metrics alone.
