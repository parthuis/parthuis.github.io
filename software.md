---
title: Software
subtitle:
layout: "page"
icon: fa-laptop
order: 3
---

Over the past decades, *ab initio* many-body methods have known a tremendous
development, moving from the light sector of the nuclear chart up to the Tin
isotopic line. With progress being made in nuclear Hamiltonians as well as
numerical techniques, high-precision calculations using high-order formalisms
are now within reach.

But with the complexity coming from high-order methods comes an increased risk
of mistakes when derivations are made by hand, as well as an increased time
spent in the design phase of the formalism. As such, trying to automatise the
process as much as possible will help to both speed up the formal development
and make it safer.

This is what is being accomplished with the Automatic Diagram Generator
[ADG](https://github.com/adgproject/adg/), of which I am the main developer
and maintainer. ADG is developed in Python and relies on external libraries
[Numpy](https://numpy.org/), [Scipy](https://scipy.org/) and
[NetworkX](https://networkx.org/). It uses methods of graph theory to generate
the diagrams for a given formalism and extract the associated expression, thus
providing the user directly with the expressions to be implemented in
their numerical code. The code is open-source, available on
[GitHub](https://github.com/adgproject/adg/) and distributed via the
[Python Package Index](https://pypi.org/project/adg/). Code quality is ensured
via [Continuous Integration](https://travis-ci.com/github/adgproject/adg),
and the code documentation is available [online](https://adg.readthedocs.io/).

Up to now, ADG has known three major releases associated to three articles,
extending the set of supported formalisms to:
  - [Bogoliubov Many-Body Perturbation Theory (BMBPT), as well as support for two-body Hartree-Fock MBPT](https://doi.org/10.1016/j.cpc.2018.11.023)
  - [Projected BMBPT](https://doi.org/10.1016/j.cpc.2020.107677
  - [Bogoliubov In-Medium Similarity Renormalization Group (BIMSRG)](https://arxiv.org/abs/2102.10889)

The goal is for ADG to be extended to other formalisms in the years to come,
including support for Gorkov Self-Consistent Green's Function theory.
