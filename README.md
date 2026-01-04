# Semantic Approximation Theory via Transformers  
### A Partial Order–Based Framework for Language and Meaning

This repository contains the paper:

> **Semantic Approximation Theory via Transformers:  
> A Partial Order-Based Framework**  
> Demian Fraiman (2026)

📄 **[paper_ordenes.pdf](paper_ordenes.pdf)**

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
  Semantic interpretation is formalized as a Scott-continuous function from the
  space of texts to the space of concepts.

- **Algebraic domains and approximation**  
  Both text and concept spaces are completed into algebraic domains, enabling
  finite and computable approximations of meaning via compact elements.

- **Lawson topology for semantic convergence**  
  The Lawson topology is proposed as an adequate notion of convergence for
  semantic approximation, overcoming limitations of Scott topology.

- **Transformers as semantic approximators**  
  Finite step functions are shown to be dense in the space of semantic functions,
  and Transformer architectures are proven capable of implementing these
  approximations exactly.

---

## Key Result (Informal)

> Any semantic function that is monotone, continuous, and respects conceptual
> structure can be approximated arbitrarily well by a Transformer architecture.

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

## Repository Structure

