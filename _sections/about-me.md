---
title: About me
icon: fa-user
order: 2
---

<img src="assets/images/Arthuis_home_landscape.jpg" alt="Picture of Pierre Arthuis" class="portrait">

After studying both versatile engineering at École Centrale de Nantes (France)
and physics at Technische Universität Darmstadt (Germany), I prepared my PhD
within the Nuclear Physics Department of CEA Paris-Saclay, the French
Alternative Energies and Atomic Energy Commission, working with Thomas Duguet
and Jean-Paul Ébran. Right after obtaining my degree from Université
Paris-Saclay in September 2018, I moved to University of Surrey (United Kingdom)
to work within the Nuclear Theory Group with Carlo Barbieri. From September
2020, to 2024 I was a member of the STRONGINT group of Achim Schwenk at the TU
Darmstadt. I recently joined the Laboratoire des Deux Infinis Irène Joliot-Curie
(IJCLab) from CNRS in Orsay, France, as a Marie Skłodowska-Curie Fellow,
and have been made staff researcher (Chargé de recherche) there in 2025.

My research focuses on developing ab initio many-body methods to study the
structure of finite nuclei, both from a formal and a computational point of
view. My previous works include the development and first application of
[Bogoliubov Many-Body Perturbation Theory](https://tel.archives-ouvertes.fr/tel-01992165),
a low-cost correlated method relying on the concept of symmetry breaking.
After that, I worked on the extension towards heavier nuclei of
Self-Consistent Green's Functions calculations, resulting in the first
*ab initio* [study](https://doi.org/10.1103/PhysRevLett.125.182501) of charge
radii and densities and neutron skins above the Sn isotopic line. Other efforts
towards calculations of heavy nuclei include reducing the memory requirements
for storing matrix elements at the[two-body](https://doi.org/10.1016/j.physletb.2021.136623)
and [three-body level](https://arxiv.org/abs/2307.15572)
and thus possibly [accelerating calculations](https://doi.org/10.1103/PhysRevC.106.024320).
I also worked on extending the handling of [three-body forces](https://doi.org/10.1103/PhysRevC.107.044303)
to tackle infinite matter with non-local interactions.

My [latest work](https://arxiv.org/abs/2401.06675) has been focused on developping new low-resolution
interactions to predict bulk properties of nuclei. Such interactions based on chiral effective
field theory present good convergence properties with respect to system size and many-body
method expansion, which allows for accurate calculations at moderate cost.
Our novel interactions proved able to reproduce ground-state energy and charge radius for systems
ranging from Oxygen-16 to Lead-208. Additionally, we investigated neutron skins of neutron-rich
nuclei, a quantity that links nuclear physics with astrophysics. Our results show an
interesting sensitivity of this quantity to the nuclear interaction in very neutron-rich
systems that will gradually become accessible in rare isotope beam facilities like FRIB, RIBF or FAIR.

In particular, one of my interests is the automatisation of the development
process of many-body methods. When designing and implementing a new formalism,
or pushing it towards higher precision, a lot of time is spent on long,
error-prone hand-made derivations and operations. This can be reduced by using
the appropriate tools to let the computer take care of it.
As part of this effort, I am the maintainer and main developer of
[ADG](https://github.com/adgproject/adg/), an open-source Python package
generating diagrams and expressions for several many-body methods. This work
additionally led to progress in our understanding of [many-body diagrammatics](https://doi.org/10.1016/j.cpc.2018.11.023)
as well as automated-tools-supported introduction of [new formalisms](https://doi.org/10.1140/epja/s10050-021-00621-6).
