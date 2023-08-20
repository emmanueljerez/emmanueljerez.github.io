---
title: "Model Categories"
date: 2023-08-18
tags:
  - Abstract Homotopy Theory
image: "/posts/model-categories/images/cd.svg"
katex: true
---
  In this blog entry I'll write as an exercise the five axioms that determines a model category, with its respective diagrams.


  A **model category** is a category $M$ together with three classes of morphisms $\mathcal{W}, \mathcal{C}, \mathcal{F}$ called *weak equivalences*, *cofibrations*, and *fibrations*, respectively. We will use the following notation for weak equivalences, cofibrations and fibrations respectively
  
![Arrows](/posts/model-categories/images/arrosMC.svg)

  That satisfies the following properties:

  M1. $\mathcal{M}$ is a category with all small limits and colimits.
  
  M2. **2-out-of-3**. If we have a diagram in $\mathcal{M}$ as follows:

![2 out of 3](/posts/model-categories/images/2o3.svg)

  Then, if two of the above maps are weak equivalences, then so is the third.

  M3. **Retract**. Consider the following diagram:

  ![Retract](/posts/model-categories/images/retract.svg)

  Then, if $g$ is a weak equivalence, cofibration, or fibration, the so is $f$.

  M4. **Lifting**. Given the following diagram:

  ![Lift](/posts/model-categories/images/lift.svg)

  If $i$ or $p$ are weak equivalences, then such $h$ there exists.

  M5. **Factorization**. For any map $X \to Y$, there exists two functorial factorizations

  ![Factorizations](/posts/model-categories/images/factor.svg).