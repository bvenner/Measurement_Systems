---
title: "Notes on Treatment of Uncorrected Measurement Bias"
author: "Brad Venner"
date: "7/30/2025"
output: html_document
---

> For appreciably different test objects or matrices within the scope of a procedure, however, we may expect a different bias for each different type of test object; each class may have a different expectation.

This sentence introduces the notion of *class* within the scope of a method/procedure. It also softens the random/systematic distinction. Bias can vary over test objects but has an expected value based on the class of the test object.

The document endorses the use of an assymetric interval calculated in a similar manner to how I have calulcate assymetric intervals as providing the smallest uncetainty interval. 

For symmetric intervals, the document proposes two different approaches. The first approach when the bias is larger than the other uncertainty, they use a method by Synek that adds the bias term to the mean square of the uncertainty from precision and the uncertainty in the bias correction, but the bias term is weighted by a term "E" between zero and two. When the bias is less than the other uncertainty terms, they recommend calculating the root mean square and adding this in quadrature to the precision component, which is the same approach proposed by Nordtest.

I need to write down how to calculate an assymetric uncertainty with a relative bias. Perhaps do a simulation study similar to the papers in this approach.