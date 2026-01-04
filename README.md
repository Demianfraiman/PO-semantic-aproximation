# Semantic Approximation Theory via Transformers  
### A Partial Order–Based Framework for Language and Meaning

This repository contains the paper:

> **Semantic Approximation Theory via Transformers:  
> A Partial Order-Based Framework**  
> Demián Fraiman (2026)

📄 **[paper.pdf](paper_po.pdf)**

---

## Overview

This work proposes a **mathematically grounded framework for semantic
representation in language models**, based on **partial orders and domain
theory**, rather than metric embedding spaces.

The central premise is that **meaning is inherently ordered**, not metric:
texts and concepts are related through refinement, generalization, and
deduction, which are more naturally modeled by partial orders than by distances
in vector spaces.

Within this framework, the paper establishes a **universal approximation
theorem for Transformer architectures**, showing that they can approximate any
well-behaved semantic interpretation that respects this ordered structure.

---

## Main Ideas

- **Texts as ordered objects**  
  Texts are modeled as a partially ordered set, where the order captures
  informational refinement (e.g. prefix or inclusion-based orders).

- **Concepts as ordered semantic entities**  
  Concepts are organized by semantic specificity, forming a partially ordered
  conceptual space.

- **Meaning as a monotone map**  
  Semantic interpretation is formalized as a monotone function, as adding more text increases specifity of the concept.


---

## Key Result (Informal)

> Any semantic function can be approximated arbitrarily well by a Transformer architecture.

This result is **structural and topological**, not statistical: it does not rely
on training dynamics or probabilistic assumptions.

---

## Why This Matters

- Challenges the dominance of **purely metric representations** in NLP.
- Provides a **formal semantics–first foundation** for language modeling.
- Bridges:
  - domain theory,
  - topology,
  - approximation theory,
  - and modern deep learning architectures.
- Offers a principled perspective on **reasoning, hierarchy, and semantic
  structure** in language models.

---

```bibtex
@article{fraiman2026semantic,
  title={Semantic Approximation Theory via Transformers: A Partial Order-Based Framework},
  author={Fraiman, Demian},
  year={2026}
}

