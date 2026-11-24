# Uncountability of continuum, aftermath

[![DOI](https://zenodo.org/badge/1469542281.svg)](https://doi.org/10.5281/zenodo.24490642)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Preface

This article finalizes the series Uncountability of Continuum. Still it's character is scientific rather than engeneering, it remains investigational: rather than offering a finished, self-contained solution, it traces a path of inquiry and invites the reader to follow the same line of thought.

## Abstract

The paper is devoted to a retrospective investigation into the crisis in the foundations of mathematics associated with the interpretation of the concept of infinity. An analysis of classical proofs of the uncountability of the set of real numbers, carried out in previous works of the series, revealed their substantial dependence on initial ontological and methodological conceptions of the morphology of the infinite. Under the assumption of a universal total structure that enables the comparison of infinite objects, these proofs remain valid; under the assumption of a fundamental homogeneity of all infinite objects, they prove internally inconsistent due to a conflation of referent positions. A detailed examination of existing axiomatic set theories (ZFC, NBG, and their variants) uncovers fundamental problems: fallacies of hasty generalization (accident and false dichotomy) in proving reflexivity, the minimality of ω, and the equality ⋃ ω = ω; architectural defects associated with an ill-formed axiom of infinity (lack of stratification, ambiguity, and lack of purity and independence); the fallacy of reification; and, ultimately, the persistence of conditional consistency, whose nature remains unclear—either the explicit and implicit assumptions of the modern interpretation genuinely do not contradict one another, or censorship axioms isolate a consistent fragment of a contradictory theory. The modern interpretation effectively negates Cantor’s original theorem for ordered sets by extending internal (cardinal) induction to limit objects and leading to equalities such as ω = 2^ω, which conflicts with the axiom of continuity and blocks natural mechanisms for strengthening predicativity to resist semantic loops. The authors identify five key mathematical paradigms—formalist, intuitionist, logicist, constructivist, and structural—and analyze them across six criteria: truth, identity, expressibility of objects, logical closure, continuum, and metatheory. This analysis reveals significant differences in the assumptions defining the boundaries of applicability of each paradigm and explains why representatives of different schools often speak different languages even when discussing the same theorems, while at the same time showing that each of them is indispensable to mathematics.

The notions of referent positions, regions of regularity and singularity, and cardinal, ordinal, and indexal morphologies are introduced, serving as the basis for formulating a unified conceptual language for describing infinity that clarifies the ambiguity of traditional concepts (potential/actual infinity, dynamism/staticism, intensionality/extensionality). Through the lens of this conceptual apparatus, the paper traces the history of how the modern interpretation of set theory took shape—from Cantor’s original ontology, through simplified early-twentieth-century adaptations and the origins of ZFC/NBG, to von Neumann’s breakthrough contributions and the entrenchment of the dominant picture, accompanied by gradual dogmatization and institutional censorship of alternative approaches. A theoretical construction is proposed that unifies alternative conceptions of infinity with the modern interpretation into a consistent picture. Axioms of limitation and safe induction are introduced, along with a stratification of the membership relation and axioms of indexal and cardinal infinity, enabling proper switching of perspectives and restoring alignment with Cantor’s original ontology. The work demonstrates that many paradoxes of self-reference arise from conflating referent positions rather than from self-reference itself. In conclusion, key directions for further research are outlined: constructing conservative extensions (ZFCS, NBGS, ZFCL, NBGL) and synthesizing them with surreal numbers, Quine’s New Foundations, gross-set theory, and non-standard analysis; investigating the diversification of continuum annotation models and its consequences for measure theory; applying the apparatus of referent positions to semantic theorems (Gödel, Tarski, Kleene, Turing) and the problem of artificial intelligence; developing formal criteria for detecting object censorship in axiomatic systems; and integrating cognitive-mathematical and historical-philosophical methods to overcome institutional stagnation in the foundations of mathematics. The proposed unifying picture brings together a substantial number of disparate areas into a single consistent system and opens a path toward methodologically honest work with infinity.

## Repository Structure

```text
.
├── article_ru.tex      # Main LaTeX source file in Russian
├── article_ru.bib      # BibTeX bibliography
├── CITATION.cff        # Citation metadata for GitHub and Zenodo
├── LICENSE             # CC BY 4.0 license text
└── README.md           # Project overview and build instructions
```

## Compiling the Paper

To compile the PDF locally using `latexmk` (recommended, handles bibliography passes automatically):

```bash
latexmk -pdf article_ru.tex
```

Alternatively, run `pdflatex` and `bibtex` manually:

```bash
pdflatex article_ru.tex
bibtex article_ru
pdflatex article_ru.tex
pdflatex article_ru.tex
```

## How to Cite

If you reference this work, please cite it via Zenodo or use the following BibTeX entry:

```bibtex
@misc{korotkov2026continuumanother,
  author       = {Korotkov, Roman},
  title        = {Uncountability of continuum, aftermath},
  year         = {2026},
  publisher    = {Zenodo},
  version      = {v0.9.0},
  doi          = {10.5281/zenodo.24490642},
  url          = {https://doi.org/10.5281/zenodo.24490642}
}
```

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
