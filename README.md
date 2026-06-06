# 3VariableRearrangementInvarianceMinorThesis

## Variable-Rearrangement-Based Interpretation of Karnaugh Map Patterns

*카르노맵 패턴의 변수 재배열 기반 해석: 구조적 불변성 연구*

---

## Abstract

This minor thesis investigates the visual pattern transformations that occur in Karnaugh maps when variable arrangements are rearranged, and identifies the structural properties preserved through those transformations. The central concept — **structural invariance** (구조적 불변성) — refers to properties that remain unchanged regardless of how variables are permuted across the map axes. Through systematic analysis using permutation theory (S₄ group), the thesis demonstrates that while the visual layout of K-map patterns changes substantially under variable rearrangement, the underlying logical function, Hamming weight, causal origin of patterns, and fundamental structural relationships between cells are preserved. Variable rearrangement is proposed as a tool for revealing hidden structural properties in Boolean functions. This work constitutes the third empirical case study in the Structure Recognition Research Program, extending the series from visual pattern discovery (Paper 1) and symmetric function structure (Paper 2) to structural invariance under transformation.

---

## Project Overview

This repository contains a minor thesis investigating the visual pattern changes that occur when variable arrangements in Karnaugh maps are rearranged, and identifying the structural properties (**structural invariance**) that are preserved through those transformations.

This work is the **third** in a series of minor theses on visual patterns and structure in Karnaugh maps:

| #     | Repository                                                | Focus                                                  |
| ----- | --------------------------------------------------------- | ------------------------------------------------------ |
| 1     | [1KMapStructureInvariance](https://github.com/inha20/1KMapStructureInvariance) | Visual pattern discovery and classification            |
| 2     | [2SymmetricBooleanFunctionMinorThesis](https://github.com/inha20/2SymmetricBooleanFunctionMinorThesis) | Pattern analysis of symmetric Boolean functions        |
| **3** | **3VariableRearrangementInvarianceMinorThesis**           | **Structural invariance under variable rearrangement** |

---

## Keywords

variable rearrangement, structural invariance, Karnaugh map, Boolean function, visual pattern, symmetry, equivalence class, S₄ group, permutation, pattern transformation, structure recognition

---

## Research Motivation

Traditional Karnaugh map research focuses primarily on logic minimization. However, Karnaugh maps also serve as visual representations of Boolean function structure.

Certain Boolean functions form distinctive visual patterns — checkerboards, corners, rings, blocks, and diagonals — that may reflect the internal structure of the function. When variables are rearranged, these patterns change, but **not all structural properties change with them**.

This raises the question: *what is preserved?*

---

## Core Research Questions

1. How do visual patterns change when variable arrangements in a Karnaugh map are rearranged?
2. Which properties change, and which remain invariant?
3. What constitutes **structural invariance** (구조적 불변성) in this context?
4. Can variable rearrangement serve as a tool for discovering hidden structural patterns?

---

## Repository Structure

```
3VariableRearrangementInvarianceMinorThesis-main/
├── README.md                                          ← This file
├── HANDOVER.md                                        ← Continuation guide for future contributors
├── FUTURE_IDEAS.md                                    ← Out-of-scope ideas for future research
├── paper/
│   └── VariableRearrangementInvarianceMinorThesis.md  ← Main thesis (Korean)
├── figures/                                           ← Figures and diagrams
├── references/                                        ← References and citations
└── notes/                                             ← Working notes and scratch analysis
```

---

## Key Findings (Summary)

Under variable rearrangement:

**What changes:**

- Position of patterns on the K-map grid
- Orientation and direction of patterns
- The apparent axis of symmetry
- Overall visual layout

**What is preserved:**

- The logical function itself
- The number of 1-cells (Hamming weight)
- The causal origin of the pattern (e.g., XOR relationship → checkerboard structure)
- Fundamental structural relationships between cells

---

## Expected Contributions

- Extends Karnaugh maps from logic minimization tools to **visual structure analysis instruments**
- Provides systematic analysis of pattern transformations under variable rearrangement
- Proposes **structural invariance** as an analytical framework for Karnaugh map patterns
- Suggests variable rearrangement as a method for discovering hidden structural properties
- Bridges the gap between the first two theses (visual pattern discovery → symmetric function analysis → structural invariance)

---

## Future Research Directions

The following are identified as promising future directions (see `FUTURE_IDEAS.md` for details):

- Mathematical modeling using symmetric groups (S₄ permutations)
- Rotation and reflection invariance analysis
- Equivalence classes of variable arrangements
- Formal definition and proof of structural invariance
- Human structural recognition in Karnaugh map patterns
- Human-AI collaboration in structural pattern discovery

---

## Research Program Context

```
1KMapStructureInvariance
            ↓
2SymmetricBooleanFunctionMinorThesis
            ↓
3VariableRearrangementInvariance  ← (This repository)
            ↓
  [Future: Human Structural Recognition]
```

---

## Language

The main thesis is written in **Korean** (한국어) with key technical terms in English.  
README and HANDOVER are written in English for broader accessibility.

---

## Status

- [x] Main thesis drafted
- [x] Figure list prepared (`pictures.txt`)
- [ ] Figures generated and placed in `figures/`
- [ ] References formatted and placed in `references/`
- [ ] Final review

---

## Research Program Links

This repository is part of the **Structure Recognition Research Program**.

| Repository | Role |
|---|---|
| [Research-Portfolio](https://github.com/inha20/Research-Portfolio) | Program Hub |
| [1KMapStructureInvariance](https://github.com/inha20/1KMapStructureInvariance) | Empirical Case Study 1 |
| [2SymmetricBooleanFunctionMinorThesis](https://github.com/inha20/2SymmetricBooleanFunctionMinorThesis) | Empirical Case Study 2 |
| [3VariableRearrangementInvarianceMinorThesis](https://github.com/inha20/3VariableRearrangementInvarianceMinorThesis) | Empirical Case Study 3 ← You are here |
| [4StructureRecognitionTheory](https://github.com/inha20/4StructureRecognitionTheory) | Theoretical Hub |

**Master Handover Document:** [MasterHandoverDocument.md](https://github.com/inha20/Research-Portfolio/blob/main/ProjectManagement/MasterHandoverDocument.md)

---

## Author

Choi Jonghun  
Inha University

---

*This repository is part of an ongoing research program on visual pattern analysis in Karnaugh maps.*