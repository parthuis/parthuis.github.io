---
layout: post
title:  "BIMSRG: A novel many-body expansion formalism"
---

To kick off this section of the website, here is a short summary on a new
 article on Bogoliubov In-Medium Similarity Remnormalization Group that just got
 accepted in the European Physics Journal A. For now, you can read the preprint
 on [arXiv](https://arxiv.org/abs/2102.10889).

In-Medium Similarity Renormalization Group has been a theory of choice for ab
 initio many-body practitioners, and with its Multi-Reference and Valence-Space
 counterparts have been instrumental in recent progress [1]. Though MR-IMSRG and
 VS-IMSRG are already able to tackle open-shell nuclei, they are pretty costly
 methods. Here we propose a single-reference, symmetry-breaking alternative,
 similar to the recently successful Bogoliubov MBPT [2].

Because BIMSRG inherently consists in a simple commutator, the structure of its
 contributions is pretty well constrained. This makes for an easy automated
 generation of diagrams and expressions from the get go. So with this new paper,
 we have updated the [Automated Diagram Generator ADG](https://github.com/adgproject/adg)
 to v3. It is now able to generate BIMSRG expressions at arbitrary orders and
 for traditional or exotic truncations, i.e. truncating all the operators at the
 same many-body level or not.

Edit on 10/01/22: The published article in now available on the
 [EPJA website](https://doi.org/10.1140/epja/s10050-021-00621-6).

[1] [H. Hergert, *A Guided Tour of ab initio Nuclear Many-Body Theory*, *Front. in Phys.* 8, 379 (2020)](https://doi.org/10.3389/fphy.2020.00379)

[2] [A. Tichai, P. Arthuis, T. Duguet, H. Hergert, V. Somà and R. Roth, *Bogoliubov Many-Body Perturbation Theory for Open-Shell Nuclei*, *Phys. Lett. B* 786, 195-200](https://doi.org/10.1016/j.physletb.2018.09.044)
