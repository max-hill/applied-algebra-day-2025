---
layout: latex
title: Titles and Abstracts
permalink: /titles-and-abstracts/
---

# Bella Finkel

**Title:** Scattering Hypertrees

**Abstract:** Hypertrees are combinatorial structures that serve as data for reduced MHV on-shell diagrams in N=4 super Yang Mills theory and hypergraphs that parametrize exceptional divisors on the Grothendieck-Knudsen moduli space of stable rational curves. The former description inspires the association of the maximum likelihood degree of a scattering potential on $$\mathcal{M}_{0,n}$$ to hypertrees in particular and to $n$-vertex graphs in general. We will discuss a new construction for an infinite family of hypertrees with compelling geometric and physical interpretations of the maximum likelihood degree.
   
Based on ongoing work with Barbara Betti, Viktoriia Borovik, Bernd Sturmfels and Bailee Zacovic.

# Danai Deligeorgaki

**Title:** How to DAG Your Model: Where Algebra Meets Causality in the Margins

**Abstract:**: A DAG model (or Bayesian network) is a graphical model representing causal or dependency relationships between variables via a directed acyclic graph. In this talk, we focus on estimating the structure of a DAG model from observational data. Conditional independence statements among variables impose structural constraints on the DAG. In joint work with Alex Markham, Pratik Misra, and Liam Solus, we study classes of DAGs that share the same unconditional independence structure and characterize how these DAGs relate and transform within and across such classes. By constructing a Gröbner basis for a related toric ideal, we define a set of moves that connect different equivalence classes of DAGs. These tools lead to GrUES (Gröbner-based Unconditional Equivalence Search), an MCMC algorithm for estimating the marginal independence structure of a causal system. Empirically, GrUES outperforms standard independence tests, yielding more accurate BIC-optimal or MAP estimates along with posterior information.

# Max Hill

**Title:** Semialgebraic Hypothesis Testing with Incomplete U-Statistics: A Case Study with Biologically-Motivated Models

**Abstract:** Recently, Sturma, Drton, and Leung (2024) introduced a general stochastic test for semialgebraic statistical models---that is, models defined by polynomial equality and inequality constraints. One remarkable feature of their method is that it remains valid even near pathological points such as singularities and model boundaries, as such points pose challenges for traditional testing methodologies. In this talk, I'll discuss recent work implementing this method and applying it to a number of biologically-motivated models from phylogenetics. While we found the method capable of matching performance of traditional deterministic tests, a number of surprising methodological challenges arose along the way.

This talk is based on joint work with Dave Barnhill, Marina Garrote-López, Elizabeth Gross, Bryson Kagy, John Rhodes, and Joy Zhang.


# Claudia Solis-Lemus

**Title:** Ultrafast learning of 4-node hybridization cycles using phylogenetic invariants

**Abstract:** The abundance of gene flow in the Tree of Life challenges the notion that evolution can be represented with a fully bifurcating process which cannot capture important biological realities like hybridization, introgression, or horizontal gene transfer. Coalescent-based network methods are increasingly popular, yet not scalable for big data, because they need to perform a heuristic search in the space of networks as well as numerical optimization that can be NP-hard. Here, we introduce a novel method to reconstruct phylogenetic networks based on algebraic invariants. While there is a long tradition of using algebraic invariants in phylogenetics, our work is the first to define phylogenetic invariants on concordance factors (frequencies of four-taxon splits in the input gene trees) to identify level-1 phylogenetic networks under the multispecies coalescent model. Our novel hybrid detection methodology is optimization-free as it only requires the evaluation of polynomial equations, and as such, it bypasses the traversal of network space, yielding a computational speed at least 10 times faster than the fastest-to-date network methods. We illustrate our method’s performance on simulated and real data from the genus Canis. We present an open-source publicly available Julia package PhyloDiamond.jl with broad applicability within the evolutionary community.
