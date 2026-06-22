---
title: "Metrology, Mereology, Topology"
author: "Brad Venner"
date: "03/26/2026"
output: html_document
---

## Introduction

Mari's book does not really address "bulk analysis," perhaps because of it's focus on relationships to an individually-focused understanding of educational assessment. I complained about this focus in another notes entry and that it neglects the hierarchical Bayesian modeling that's increasingly common in the educational space. It does discuss the difference between the "effective property" and the "property of interest", but it doesn't really consider this from a mereological point of view. 

My recent reading on mereology has convinced me that this should have been a primary focus of my work at NEIC. The "part-whole" relationship is crucial to understanding sampling, particularly of bulk materials but also potentially on other "spaces" such as networks. Indeed, there are papers on mereological approaches to higher-order structure (see below). 

## Lawvere on topology and mereology

I do not know if Lawvere ever explicitly wrote on all three concepts of metrology, mereology and topology in the same paper. I've written elsewhere about the potential for applying Lawvere in metrology - his analysis of the duality of space and quantity and the relationship between instrinsic and extrinsic quantity seem very important. Since the relationship between category theory and continuum physics was an important subject for Lawvere, this is no surprise. Lawvere explicitly included mereological concerns into his development of topos theory. According to nLab, 

> With the inception of topos theory, William Lawvere has conceived of logic from the perspective of mereology by making the role of the subobject classifier manifest.

> More specifically, he has pointed out in the 1980s the relevance of co-Heyting and bi-Heyting structures to mereology in this context and proposed to view logical theories from the point of view of a ‘mereodynamics’.

The two papers cited in the nLab article are:

1. (Introduction)[https://lawverearchives.com/wp-content/uploads/2024/12/1982-introduction-to-categories-in-continuum-physics.pdf] , pp.1-16 in Lawvere, Schanuel (eds.), Categories in Continuum Physics , Springer LNM 1174 1986.

2. (Intrinsic Co-Heyting Boundaries and the Leibniz Rule in Certain Toposes)[https://lawverearchives.com/wp-content/uploads/2024/12/1991-intrinsic-co-heyting-boundaries-and-the-leibniz-rule-in-certain-toposes.pdf] , pp.279-281 in Carboni, Pedicchio, Rosolini (eds.) , Category Theory Como Conference, Springer LNM 1488 (1991).

Neither of these papers are in my "metrology" stack.

The first paper is 17 pages long and serves as an overview of the contents of a multi-authored volume. He motivates the importance of the cartesian closed property in the analysis of space

The second paper is a scant three pages long. 

## Diakoptics, Tektology, Mereology

Another potential application of structural (pluralistic) mereology is to develop the asymmetry between composition and decomposition. Authors like Rosen, Ellerman and Bogdanov have emphasized this asymmetry, but this hasn't been discussed in the (admittedly limited) mereological literature that I've seen. A Google search for \("systems theory" mereology\) gave me the term (diakoptics)[https://en.wikipedia.org/wiki/Diakoptics], which is a neologism for the "method of tearing" (Greek dia–through + kopto–cut, tear). The term "diakoptics" was introduced by (Gabriel Kron)[https://en.wikipedia.org/wiki/Gabriel_Kron]. Diakoptics was given a formal basis in algebraic topology in the 1950's and thus must have some deep connections to category theory and possibly homotopy type theory. A brief walk through references doesn't give a clear "categorification" of this idea, but something may have been developed in the categorical systems literature. 

Diakoptics plays a major role in Willem's *The Behavioral Approach to Open and Interconnected Systems*, which uses the three phases of tearing, zooming and linking as defining the behavioral approach. Given the emphasis on relations in the paper, this could also be called the "relational approach".

Bogdanov used the term "disintegration" for "decomposition" or "tearing" and emphasized the underlying physical process, if secondary literature is to believed. Bogdanov believed that all systems were subject to the competing processes of organization and disorganization and that a system must maintain a balance between these forces. The "method of tearing" is more epistemological - decomposition is performed on the model of the system and is non-destructive.    

## Sampling and mereology

## Structural mereology

Thomas Mormann has a paper titled *Structural Mereology: A Formal Elucidation and Some Metaphysical Applications* that is available for free on the internet. Mormann wrote a series of mereological papers in the 2010's. I have downloaded their paper *Heyting Mereology as a Framework for Spatial Reasoning* from 2013, but got bogged down with some heavy notation early on. This paper is more philosophical, based more on natural language, and easier for me to understand. 

The main mathematical vehicle for this paper is the notion of a "structural set". A regular set is considered as a "homogenous set", while the chosen notion of "structure" allows for various forms of "inhomogeneity". The structure on a set is a reflexive, transitive and anti-symmetric relation. These are the conditions for a poset. A "Kripke frame" combines an accessibility relation with a partial order. Since Kripke frames are used to model intuitionistic logic, it is no surprise that Heyting algebras appear in both fields.

So is structural mereology simply intuitionistic logic? Mormann develops some examples, such as Cartesian rectangles, that are intermediate between a Boolean and a Heyting algebra.

Mereology is an essential component of metrology in analytical chemistry and "analytical" subdisciplines. Is there is a form of "compositional trinitarianism" where philosophy, mathematics and science meet in a way that is analogous to "computational trinitarianism" and it's more specialized division of proof theory, category theory and type theory? Unfortunately, it looks like "compositional trinitarianism" has already been taken by Christianity, although there could be interesting analogies with the more religious ideas.

The less flamboyant term for "computational trinitarianism" is the "Curry-Howard-Lambek correspondence". When I searched for this term on Google, one of results on the first page was the paper (*Curry-Howard-Lambek Correspondence for Intuitionistic Belief*)[https://arxiv.org/pdf/2006.02417] [@brogi:2020:curry] by Cosimo Brogi. This paper develops a natural deduction calculus for an intuitionistic belief logic with a belief modality. The goal of this paper is to model formally the cognitive model underlying intuitionism. This suggests an interesting project in formalizing this natural deduction model in Hazel. This project would help me familiarize myself with the Hazel language/environment but could also be a step towards a formal measurement systems theory. Another link to recent interests is the emphasis that this model of belief places on the notion of verification. This could be important in understanding "gradual verification" by 

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

