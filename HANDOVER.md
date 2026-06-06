# HANDOVER — 3VariableRearrangementInvarianceMinorThesis

*For future contributors, researchers, or AI models continuing this project.*

---

## Project Summary

**Repository:** `3VariableRearrangementInvarianceMinorThesis`  
**Working Title:** Variable-Rearrangement-Based Interpretation of Karnaugh Map Patterns  
**Language:** Korean (한국어) with key terms in English  
**Status:** Main thesis drafted; figures and references pending

This is the **third** in a series of minor theses exploring visual patterns and structural properties in Karnaugh maps. It investigates what happens to visual patterns when variable arrangements are changed, and identifies which structural properties survive those transformations.

---

## Research Context

### How This Project Emerged

**1st thesis — 1KarnaughMapVisualPatternAnalysisMinorThesis**  
Initiated the visual approach to Karnaugh maps: instead of treating K-maps only as logic minimization tools, this project identified that certain Boolean functions produce distinctive visual patterns (checkerboard, corner, ring, block, diagonal).

**2nd thesis — 2SymmetricBooleanFunctionVisualPatternAnalysisMinorThesis**  
Focused specifically on symmetric Boolean functions (Exactly-k, XOR, XNOR, etc.) and analyzed their characteristic visual patterns and structural properties in detail.

**3rd thesis — This repository**  
Builds on both prior works: takes the established visual patterns and asks what happens when the variable arrangement is changed. The central observation is that some patterns are *transformed* but not *destroyed* — certain structural properties persist.

### Evolution of the Research Program

```
Visual Pattern Discovery (Thesis 1)
            ↓
Pattern Classification in Symmetric Functions (Thesis 2)
            ↓
Structural Invariance Under Variable Rearrangement (Thesis 3)  ← HERE
            ↓
  [Planned: Human / AI Structural Recognition (Thesis 4+)]
```

---

## Core Research Question

> **Which structural properties of Karnaugh map patterns remain invariant under variable rearrangement?**

Supporting questions:
- How do visual patterns change under variable rearrangement?
- Which properties change and which remain unchanged?
- Can variable rearrangement serve as a tool for discovering hidden patterns?

---

## Motivation

Variable rearrangement is interesting because:

1. The **logical function is unchanged** — only the visual representation changes
2. Some patterns look completely different under different arrangements
3. Yet **certain structural properties persist** despite the visual transformation
4. This suggests that visual patterns carry deeper structural information than surface appearance implies
5. Variable rearrangement can act as a "lens" for revealing hidden structure in a function

The total number of variable arrangements for a 4-variable K-map is **4! = 24**.  
This thesis examines what is invariant across all 24 arrangements.

---

## Current Thesis Direction

### Main Focus
- Variable rearrangement as an operation on K-map visual representation
- Pattern transformation behavior under rearrangement (5 pattern types analyzed)
- Structural invariance — what is preserved across all arrangements

### Intentionally Out of Scope → FUTURE_IDEAS.md
- Human cognition and visual perception
- AI intuition and pattern recognition
- Educational applications of K-maps

These are noted as valid future research directions but are kept separate from the main thesis body.

---

## Current Thesis Structure

Main paper location: `paper/VariableRearrangementInvarianceMinorThesis.md`

### Chapter Outline (Markdown heading structure)

**서론 (Introduction)**
- 연구 배경 — Traditional K-map research context; visual pattern approach motivation
- 연구 문제 — The invariance question
- 연구 목적 — Goals of the study
- 연구 기여 — Four stated contributions

**이론적 배경 (Theoretical Background)**
- 카르노맵 — Definition, 16-cell structure, adjacency
- 변수 배열과 Gray Code — Why Gray Code; how arrangement affects layout
- 변수 재배열 — Definition; 24 possible arrangements; examples (AB/CD, AC/BD, AD/BC)
- 구조적 불변성 — Concept of invariance; expected invariant vs. variable elements

**연구 방법 (Research Method)**
- 연구 절차 — 7-step procedure (selection → arrangement → K-map → observation → analysis → extraction → interpretation)
- 변수 배열 생성 방법 — 4! = 24 arrangements; example table
- 분석 대상 함수 — Checkerboard, symmetric, block, diagonal pattern functions
- 패턴 관찰 방법 — Whole-pattern vs. cell-by-cell approach; 6 observation dimensions
- 비교 기준 — Comparison table (cell count, pattern shape, symmetry, connectivity, position, direction)

**변수 재배열에 따른 패턴 변화 분석 (Pattern Change Analysis)**
- 체커보드 패턴 — XOR/XNOR; direction changes but repetition structure persists
- 대각선 패턴 — May transform into block or repetition structure under rearrangement
- 모서리 패턴 — Corner positions may shift; logical structure retained
- 고리 패턴 — Ring shape may deform; Hamming weight layer structure preserved
- 블록 패턴 — Position changes; block size and logical relationship preserved
- 소결 — Position/orientation changes; some structure persists

**구조적 불변성 분석 (Structural Invariance Analysis)**
- 변화하는 요소 — Position, orientation, symmetry axis
- 유지되는 요소 — Function itself, 1-cell count, pattern causal origin
- 구조적 불변성의 분류 — Four categories: Logical, Quantitative, Relational, Structural
- 구조적 불변성 해석 — K-map as structure representation, not just calculation tool

**해석 프레임워크 제안 (Proposed Interpretation Framework)**
- 패턴 중심 해석 — Visual form as entry point for function analysis
- 구조 중심 해석 — Internal relationships over surface appearance
- 변수 재배열 기반 해석 — Rearrangement as a structure exploration tool
- 제안 프레임워크 — 5-step framework: Observe → Rearrange → Compare → Extract → Interpret

**결론 (Conclusion)**
- 연구 요약
- 연구 기여 (4 contributions)
- 연구의 한계 — Limited to 4-variable K-maps; observational hypotheses; no formal proofs yet
- 향후 연구 — S₄ group analysis, rotation/reflection invariance, equivalence classes

---

## Key Hypotheses

These are **hypotheses based on observation, not confirmed conclusions**:

1. **Pattern Transformation Hypothesis:** Variable rearrangement transforms visual patterns but does not destroy them — the underlying structure persists in some form.

2. **Structural Invariance Hypothesis:** Certain properties (number of 1-cells, causal relationships, repetition structures) remain invariant under variable rearrangement.

3. **Hidden Structure Hypothesis:** Variable rearrangement can reveal structural properties that are not visible in any single arrangement, making it a useful structural exploration tool.

4. **Representation vs. Structure Hypothesis:** Visual appearance (position, orientation, symmetry axis) is arrangement-dependent; structural relationships (logic connections, Hamming weight distribution, pattern generation cause) are arrangement-independent.

---

## Future Research Connections

Identified directions for continuation (details in `FUTURE_IDEAS.md`):

| Topic | Connection |
|---|---|
| Symmetric Group S₄ | Mathematical formalization of the 24 variable permutations |
| Rotation/Reflection Invariance | Extending invariance beyond variable rearrangement |
| Equivalence Classes of Arrangements | Classifying 24 arrangements into canonical groups |
| Formal Invariance Definition | Mathematical proof-level formalization |
| Human Structural Recognition | How humans perceive K-map structure |
| Human-AI Collaboration | Joint structural pattern discovery |

---

## Repository Organization

| File / Folder | Purpose |
|---|---|
| `README.md` | Public-facing project overview for GitHub |
| `HANDOVER.md` | This file — continuation guide |
| `FUTURE_IDEAS.md` | Out-of-scope ideas preserved for future work |
| `paper/` | Main thesis document |
| `figures/` | Figures (25 figures planned; see `pictures.txt` for full list) |
| `references/` | Citations and references |
| `notes/` | Working notes, drafts, scratch analysis |
| `pictures.txt` | Detailed figure list with filenames, descriptions, placement notes |
| `a.md` | Original project specification (keep as reference) |
| `b.md` | Paper writing instructions (Korean format requirements) |
| `c.md` | Additional content design instructions |

---

## Continuation Instructions

### For a future AI model or researcher picking this up:

1. **Read first:** This file (`HANDOVER.md`), `a.md`, and `paper/VariableRearrangementInvarianceMinorThesis.md`
2. **Check outstanding items:** `c.md` describes additional result sections and figure/table lists to be added
3. **Figure work:** `pictures.txt` has the full figure list (25 figures); figures need to be generated and placed in `figures/`
4. **Scope discipline:** Do not expand the main body into cognitive science, AI perception, or educational topics — those go in `FUTURE_IDEAS.md`
5. **Change log:** If direction or structure changes, record it: note the previous approach, new approach, and reason (do not delete prior ideas)

### Priority remaining tasks:

- [ ] Generate figures described in `pictures.txt` and place in `figures/`
- [ ] Format and add references to `references/`
- [ ] Expand `FUTURE_IDEAS.md` with ideas from `c.md`
- [ ] Review `c.md` for additional result sections and table lists to incorporate
- [ ] Final consistency review of paper
- [ ] GitHub upload

---

*Maintained across Antigravity IDE sessions — Thesis 3 of the Karnaugh Map Visual Pattern Research Program.*

---

## Architecture B 통합 메모 (추가일: 2026-06-05)

**공식 아키텍처:** Architecture B (경험적 토대 모델) — 2026-06-05 채택

### Architecture B 내 이 저장소의 역할

```
Paper 1: KMap Structure Invariance       (경험적 사례 1 — 시각적 패턴 발견)
Paper 2: Symmetric Boolean Functions     (경험적 사례 2 — 구조적 규칙성)
Paper 3: Variable Rearrangement         ← 이 저장소 (경험적 사례 3 — 변환 하의 구조 보존)
         ↓
Paper 4: Structure Recognition Theory   (이론적 허브 — 위 세 논문을 통합)
```

### SRT 가설과의 연결 매핑

| Paper 3의 핵심 관찰 | SRT 가설 |
|---|---|
| 변수 재배열 시 시각 패턴이 극적으로 변함 | H2 (표현 변환이 구조를 드러냄) |
| "무엇이 보존되는가?" 가 핵심 질문으로 부상 | H4 (불변성이 유의미함의 기준), H6 (설명적 잠재력 탐지) |
| 변수 재배열이 숨겨진 구조를 드러내는 도구 | H2, H3 (주의 필터: 불변 구조가 주의를 끌어당김) |
| 논리적 동등함에도 불구한 시각적 변화 | H5 (설명이 존재할 것이라는 기대) |

### 현재 미완료 항목 (Summer 2026 우선 처리)

- [ ] `figures/` 디렉터리에 25개 그림 생성 및 배치 (pictures.txt 참조)
- [ ] `references/` 참고문헌 형식화
- [ ] `FUTURE_IDEAS.md` — c.md의 아이디어로 확장
- [ ] GitHub Pages 설정 (Research-Portfolio GitHub Pages 네트워크에 통합)
- [ ] 최종 일관성 검토

### 프로그램 핵심 문서 바로가기
- [MasterHandoverDocument](../Research-Portfolio-main/ProjectManagement/MasterHandoverDocument.md)
- [ResearchProgramArchitecture](../Research-Portfolio-main/ProjectManagement/ResearchProgramArchitecture.md)
- [Structure Recognition Theory v0.1](../4StructureRecognitionTheory-main/theory/StructureRecognitionTheory_v0.1.md)
- [Paper 4 HANDOVER](../4StructureRecognitionTheory-main/HANDOVER.md)

*아키텍처 교차 참조 최종 갱신: 2026-06-05*
