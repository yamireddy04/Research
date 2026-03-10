# Research

This repository contains my research work, including preprints and supporting materials.

## Preprints

### 1. A System-Level Framework for Sentiment-Aware Reflective Writing Systems: Modeling Temporal Emotional Patterns with Interpretability and Ethical Safety

**Status:** Preprint
**Repository:** TechRxiv
**DOI:** DOI: 10.36227/techrxiv.177274130.07417144/v1

**Abstract: **
Sentiment analysis has become a cornerstone of affective computing applications, enabling systems to detect emotional valence in usergenerated text. However, when deployed in reflective writing and coaching contexts, sentiment-based systems face a fundamental limitation: sentiment polarity does not reliably indicate user intent, therapeutic need, or appropriate system response. This paper formally analyzes the gap between sentiment detection and intent interpretation in emotion-aware interactive systems. We define sentiment as a function S : X → Y s mapping text to polarity labels, and intent as a context-dependent function I : X × C × G × H → A incorporating conversational context, user goals, and interaction history. Through system-level observations from early-stage prototype deployment, we demonstrate that S(x) alone is statistically insufficient for determining appropriate system actions. We present a multi-layer intent modeling framework that augments sentiment detection with pragmatic reasoning, temporal pattern recognition, and goal-aware interpretation. Our central contribution is a utility-theoretic framing of emotional response selection that explicitly models asymmetric costs (false intervention vs. missed support), derives optimal decision thresholds, and incorporates ethical constraints through action-space restriction.

**Links**

* TechRxiv: https://www.techrxiv.org/users/1032506/articles/1392661-a-system-level-framework-for-sentiment-aware-reflective-writing-systems-modeling-temporal-emotional-patterns-with-interpretability-and-ethical-safety
* Google Scholar: https://scholar.google.com/citations?view_op=view_citation&hl=en&user=zYTRPeIAAAAJ&authuser=1&citation_for_view=zYTRPeIAAAAJ:eO3_k5sD8BwC
* ORCID: https://orcid.org/my-orcid?orcid=0009-0004-9662-0219

---

### 2. Beyond Surface Affect: Why Sentiment Detection Alone is Insufficient for Intent Interpretation in Human-AI Communication

**Status:** Preprint
**Repository:** TechRxiv
**DOI:** 10.36227/techrxiv.177274129.99249714/v1

**Abstract: **
Sentiment detection-the automated classification of affective polarity in natural language text-has achieved strong empirical performance across standard benchmarks and is widely deployed in conversational AI systems. However, in interactive Human-AI communication contexts such as interview coaching assistants, reflective writing platforms, and mental health dialogue agents, sentiment polarity alone is demonstrably insufficient for interpreting user intent. This paper formalizes the distinction between sentiment detection and intent interpretation using mathematical notation. We define a sentiment classifier S(x) operating over surface text and contrast it with a contextualized intent function I(x, C, G, H), where C denotes dialogue context, G encodes user goals, and H represents interaction history. We prove formally that S(x) does not imply I(x, C, G, H) in the general case, and identify four canonical failure modes of sentiment-only systems. We present system-level case observations from MindNook, a sentiment-aware reflective diary platform, to ground these theoretical distinctions empirically. We propose a Multi-Layer Intent Modeling (MLIM) framework integrating affective, pragmatic, goal-theoretic, and contextual components, and conclude with an open research agenda addressing context management, multi-modal grounding, and privacy-preserving personalization.

**Links**

* TechRxiv: https://www.techrxiv.org/users/1032506/articles/1392660-beyond-surface-affect-why-sentiment-detection-alone-is-insufficient-for-intent-interpretation-in-human-ai-communication?commit=2b8a4238952ef4fb099d4a804df9d99aab24c199
* Google Scholar: https://scholar.google.com/citations?view_op=view_citation&hl=en&user=zYTRPeIAAAAJ&authuser=1&citation_for_view=zYTRPeIAAAAJ:DkZNVXde3BIC
* ORCID: https://orcid.org/my-orcid?orcid=0009-0004-9662-0219
