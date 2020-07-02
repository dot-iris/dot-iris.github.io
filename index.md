This is the homepage for the **DOT-Iris** project. We extend the
formal foundations of the Scala programming language, that is, the DOT calculus,
using step-indexed logical relations and the Iris framework.

# Publications
  - _Scala Step-by-Step: Soundness for DOT with Step-Indexed Logical Relations in Iris_.
    Paolo G. Giarrusso, Yann Régis-Gianas and Philipp Schuster. ICFP 2020.

    **Abstract**: The metatheory of Scala's core type system---the *Dependent Object Types
    (DOT)* calculus---is hard to extend, like the metatheory of other type systems
    combining subtyping and dependent types. Soundness of important Scala features
    therefore remains an open problem in theory and in practice. To address some
    of these problems, we use a _semantics-first_ approach to develop a logical
    relations model for a new version of DOT, called **guarded DOT (gDOT)**. Our
    logical relations model makes use of an abstract form of *step-indexing*, as
    supported by the Iris framework, to model various forms of recursion in gDOT.
    To demonstrate the expressiveness of gDOT, we show that it handles Scala
    examples that could not be handled by previous versions of DOT, and prove
    using our logical relations model that gDOT provides the desired data
    abstraction. The gDOT type system, its semantic model, its soundness proofs,
    and all examples in the paper have been mechanized in Coq.

    - [Preprint, Version 1](2020-dot-submission.pdf)
    - Revised version coming soon.

# News

- 2020-07-01: Website online
- 2014-06-24: AEC submission accepted.
- 2020-06-19: _Scala Step-by-Step: Soundness for DOT with Step-Indexed Logical
  Relations in Iris_ unconditionally accepted at ICFP 2020.

# Source Code

[Source code](https://github.com/Blaisorblade/dot-iris) --- [coqdoc](coqdoc/).

# Trivia

- Q: Why "Scala Step-by-Step"?
- A: Because Scala is named after the Italian word for "staircase". And because
  we use _step-indexing_.

# Contacts
For any question or suggestion, feel free to contact me, Paolo G. Giarrusso, at
p !dot! giarrusso (at) gmail !dot! com.

{::comment}
# Credits
This project benefited from code and ideas of many different people:

- Paolo G. Giarrusso

Further acknowledgments in each publication.
{:/comment}