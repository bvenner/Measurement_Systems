---
title: "Notes on Statistical Analysis of Compositional Data"
author: "Brad Venner"
date: "03/24/2026"
output: html_document
---

This is a classic paper by J. Aitchison that introduced the entire subfield of compositional data analysis. I've seen this paper cited by authors when they point to a theoretical justification.

My intuition is that there is an important link between Lawvere's general metrology and the specific mapping between the multivariate normal and the simplex space. 

I vaguely remember a paper connecting the simplex as one end of an adjunction that gave rise to the probability monad. 

Another possible connection would be between mereology and "material composition". The Internet Encyclopedia of Philosophy entry on (material composition)[https://iep.utm.edu/mat-comp/] states that "material composition falls under the wider purview of *mereology*. So this investigation might touch upon Heyting mereology, a paper that I still need to read.

Convex spaces are defined as a set that contains "kinds" and the unit interval such that the space X contains all convex sums of any two points in the set. This idea that "kinds" are atomic seems to violate a more general mereology. It's also interesting how none of these definitions include the concept of a "total" or a "normalizing constant", as this plays an important role in Lawvere's work, with the terminal object playing the role of total. Is this an artifact of considering convex spaces as essentially finite? The move to more general probability monads gives "formal generalized convex combinations". Note that allowing for unnormalized coefficients gives a (conical space)[https://ncatlab.org/nlab/show/conical+space].     

Jacobs has a paper titled *Convexity, duality and effects* [@jacobs:2010:convexity] that relates convex sets and effect algebras. The nlab entry on (convex spaces)[https://ncatlab.org/nlab/show/convex+space]

Fritz has a paper titled *Convex Spaces I: Definition and Examples* [@fritz:2015:convex]

## Structual mereology

Thomas Mormann has a paper titled *Structural Mereology: A Formal Elucidation and Some Metaphysical Applications* that is available for free on the internet. Mormann wrote a series of mereological papers in the 2010's. I have downloaded their paper *Heyting Mereology as a Framework for Spatial Reasoning* from 2013, but got bogged down with some heavy notation early on. This paper is more philosphical, based more on natural language, and easier for me to understand. 

The main mathematical vehicle for this paper is the notion of a "structural set". A regular set is considered as a "homogenous set", while the chosen notion of "structure" allows for various forms of "inhomogeneity". The stucture on a set is a reflexive, transitive and anti-symmetric relation. These are the conditions for a poset. A "Kripke frame" combines an accessibility relation with a partial order. Since Kripke frames are used to model intuitionistic logic, it is no surprise that Heyting algebras appear in both fields.

So is structural mereology simply intuitionistic logic? Mormann develops some examples, such as Cartesian rectangles, that are intermediate between a Boolean and a Heyting algebra.

Mereology is an essential component of metrology in analytical chemistry and "analytical" subdisciplines . 