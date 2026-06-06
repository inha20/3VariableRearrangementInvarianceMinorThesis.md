# originals/ — 원본 파일 보존 디렉터리
## 3VariableRearrangementInvarianceMinorThesis

**생성일:** 2026-06-05 (Phase 2 실행)  
**목적:** 향후 그림 파일이 생성·표준화되면, 원본 버전을 이 폴더에 보존합니다.  
**규칙:** 이 폴더의 파일은 **절대 수정·삭제 금지**. 읽기 전용으로 취급.

---

## 현재 상태

Paper 3은 아직 `figures/` 폴더에 실제 이미지 파일이 없습니다.  
25개의 계획 그림 전부 미생성 상태입니다 (`figures/figure_inventory.md` 참조).

향후 연구자가 그림을 직접 생성하면:
1. 원본 파일을 이 `figures/originals/` 폴더에 저장
2. 표준 파일명으로 복사본을 `figures/` 폴더에 배치

---

## 생성 예정 그림 목록 (25개)

연구자가 직접 생성해야 할 그림들입니다.

### 🔴 필수 (10개) — 먼저 생성

| 파일명 | 내용 |
|---|---|
| `figure01_standard_4variable_kmap.png` | 표준 4변수 카르노맵 (Gray Code 배열) |
| `figure02_variable_arrangement_examples.png` | 대표 배열 예시 AB/CD, AC/BD, AD/BC |
| `figure03_variable_rearrangement_concept.png` | 변수 재배열 개념도 (화살표 연결) |
| `figure04_xor_checkerboard_standard.png` | 기본 배열 XOR 체커보드 패턴 |
| `figure05_xor_checkerboard_rearranged.png` | 재배열 후 XOR 패턴 변화 |
| `figure06_xor_pattern_comparison.png` | 재배열 전후 XOR 비교 (나란히) |
| `figure16_representative_arrangements.png` | 24개 배열 → 대표 3종 분류 결과 |
| `figure18_xor_pattern_transformation.png` | 동일 XOR 함수 — 배열 1→2→3 비교 |
| `figure19_changed_properties.png` | 재배열에 의해 변화하는 요소 |
| `figure20_preserved_structure.png` | 재배열 이후에도 유지되는 구조 |

### 🟡 핵심 (10개) — 다음 생성

figure07, 08, 09, 10, 11, 17, 21, 22, 23, 24

### 🟢 보조 (5개) — 마지막 생성

figure12, 13, 14, 15, 25

---

## 그림 생성 원칙 (ImageStandardizationGuide 적용)

**이 연구 프로그램의 그림은 연구자가 직접 생성해야 합니다.**

허용 도구: PowerPoint, Keynote, Draw.io, 손 그림 스캔, Inkscape, GIMP  
금지: AI 이미지 생성 도구, AI가 작성한 코드 기반 자동 생성

시각 기준점: Paper 2의 `images/01.png`~`images/13.png`와 동일한 스타일

세부 명세: `../figure_inventory.md` 및 `../pictures.txt` 참조

---

*참조: ../figure_inventory.md, ../pictures.txt*  
*이미지 생성 규칙: Research-Portfolio-main/ProjectManagement/ImageStandardizationGuide.md*
