---
title: "Metrology, Mereology, Topology"
author: "Brad Venner"
date: "03/26/2026"
output: html_document
---

Mari's book does not really address "bulk analysis," perhaps because of it's focus on relationships to an individually-focused understanding of educational assessment. I complained about this focus in another notes entry and that it neglects the hierarchical Bayesian modeling that's increasingly common in the educational space. It does discuss the difference between the "effective property" and the "property of interest", but it doesn't really consider this from a mereological point of view. 

My recent reading on mereology has convinced me that this should have been a primary focus of my work at NEIC. The "part-whole" relationship is crucial to understanding sampling, particularly of bulk materials but also potentially on other "spaces" such as networks. Indeed, there are papers on mereological approaches to higher-order structure (see below). 

Another potential application of structural mereology is to document the asymmetry between composition and decomposition. Authors like Rosen, Ellerman and Bogdanov have emphasized this asymmetry, but this hasn't been discussed in the (admittedly limited) mereological literature that I've seen. A Google search for \("systems theory" mereology\) gave me the term "diakoptics," which is used as a term for the "method of tearing", which was used in Willem's *The Behavioral Approach to Open and Interconnected Systems*, which uses the three phases of tearing, zooming and linking as defining the behavioral approach. Given the emphasis on relations in the paper, this could also be called the "relational approach".



## Sampling and mereology

## Structural mereology

Thomas Mormann has a paper titled *Structural Mereology: A Formal Elucidation and Some Metaphysical Applications* that is available for free on the internet. Mormann wrote a series of mereological papers in the 2010's. I have downloaded their paper *Heyting Mereology as a Framework for Spatial Reasoning* from 2013, but got bogged down with some heavy notation early on. This paper is more philosophical, based more on natural language, and easier for me to understand. 

The main mathematical vehicle for this paper is the notion of a "structural set". A regular set is considered as a "homogenous set", while the chosen notion of "structure" allows for various forms of "inhomogeneity". The structure on a set is a reflexive, transitive and anti-symmetric relation. These are the conditions for a poset. A "Kripke frame" combines an accessibility relation with a partial order. Since Kripke frames are used to model intuitionistic logic, it is no surprise that Heyting algebras appear in both fields.

So is structural mereology simply intuitionistic logic? Mormann develops some examples, such as Cartesian rectangles, that are intermediate between a Boolean and a Heyting algebra.

Mereology is an essential component of metrology in analytical chemistry and "analytical" subdisciplines. Is there is a form of "compositional trinitarianism" where philosophy, mathematics and science meet in a way that is analogous to "computational trinitarianism" and it's more specialized division of proof theory, category theory and type theory? Unfortunately, it looks like "compositional trinitarianism" has already been taken by Christianity, although there could be interesting analogies with the more religious ideas.

The less flamboyant term for "computational trinitarianism" is the Curry-Howard-Lambek correspondence. When I searched for this term on Google, one of results on the first page was the paper (*Curry-Howard-Lambek Correspondence for Intuitionistic Belief*)[https://arxiv.org/pdf/2006.02417] [@brogi:2020:curry] by Cosimo Brogi. This paper develops a natural deduction calculus for an intuitionistic belief logic with a belief modality. The goal of this paper is to model formally the cognitive model underlying intuitionism. This suggests an interesting project in formalizing this natural deduction model in Hazel. This project would help me familiarize myself with the Hazel language/environment but could also be a step towards a formal measurement systems theory. Another link to recent interests is the emphasis that this model of belief places on the notion of verification. This could be important in understanding "gradual verification" by 

Also, this paper could relate to a more recent Mormann paper titled (*Completeness and Doxastic Plurality for Topological Operators of Knowledge and Belief*)[https://philpapers.org/archive/MORCAD-7.pdf] [@mormann:2023:completeness]. This paper focuses on the interaction of two modal operators that describe knowledge and belief and their interaction. 


##  Higher-order structural mereology

Mormann develops a general approach to "structural mereology". Does this approach also work for higher-order structure? Understanding this potential link would require a better sense of topos theory. A topos can model higher-order logic. A topos can be decomposed into sub-topos and the resulting lattice forms a complete Heyting algebra.

Jansma's paper (*A Mereological Approach to Higher-Order Structure in Complex Systems: from Macro to Micro with Möbius*)[https://arxiv.org/pdf/2404.14423] [@jansma:2025:mereological] takes a more practical and less category-theoretic approach. It looks at the general concept of *Möbius inversions* and develops examples of the approach in several disciplines, including information theory, biology, and chemistry.

## Sheaf semantics for mereology

Two potentially related traditions here. Goguen and Malcom developed sheaf semantics for distributed concurrent systems. This work explicitly built upon Goguen's work on categorical systems theory. This doesn't explicitly mention mereology but does consider the "transition from local to global properties" 

The other approach is "behavioral mereology" by Spivak and others.

## Types as theories

This doesn't really belong in this section, but I wanted to write it down. Goguen wrote a paper in 1991 titled *Types as Theories* that was published in the book titled *Topology and category theory in computer science*. This seems to be an early precursor to the notion of "types as specifications". 

There is an online development of (Specifications and Testing)[https://course.ccs.neu.edu/cs2800f25/lectures/3.2/] that is done in Ocaml that distinguishes between "types as specifications" and "properties as specifications".  

> the art of choosing a specification, and encoding it into a programming language, is necessary for both property-based testing and (proof-based) verification (and is quite useful even if you aren't testing).

