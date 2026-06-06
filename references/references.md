# 참고문헌 (References)

본 소논문에서 인용하거나 배경으로 참조한 문헌 목록입니다.

---

## 1. 카르노맵 원전 및 불 함수 최소화

**[1]** Karnaugh, M. (1953).  
"The map method for synthesis of combinational logic circuits."  
*Transactions of the American Institute of Electrical Engineers, Part I: Communication and Electronics*, 72(5), 593–599.

> 카르노맵을 처음 제안한 원전 논문.

---

**[2]** Veitch, E. W. (1952).  
"A chart method for simplifying truth functions."  
*Proceedings of the 1952 ACM National Meeting (Pittsburgh)*, pp. 127–133.

> 카르노맵에 선행하는 Veitch 도표(Veitch chart)를 제안한 논문.

---

**[3]** McCluskey, E. J., Jr. (1956).  
"Minimization of Boolean functions."  
*Bell System Technical Journal*, 35(5), 1417–1444.

> 불 함수 최소화의 체계적 알고리즘(Quine–McCluskey 방법)을 정립한 논문.

---

**[4]** Quine, W. V. (1952).  
"The problem of simplifying truth functions."  
*The American Mathematical Monthly*, 59(8), 521–531.

> McCluskey 이전 Quine이 제안한 최소화 방법의 수학적 기반.

---

**[5]** Quine, W. V. (1955).  
"A way to simplify truth functions."  
*The American Mathematical Monthly*, 62(9), 627–631.

> [4]의 후속 논문. 방법론 정리 및 확장.

---

## 2. Gray Code

**[6]** Gray, F. (1953).  
"Pulse code communication."  
*U.S. Patent 2,632,058*, March 17, 1953.

> Gray Code의 원특허. 카르노맵의 행·열 배열 원리(인접 셀 간 1비트 차이)의 기반.

---

## 3. 디지털 논리 설계 교재

**[7]** Mano, M. M., & Ciletti, M. D.  
*Digital Design: With an Introduction to the Verilog HDL, VHDL, and SystemVerilog* (6th ed.).  
Pearson Education.

> 카르노맵, 불 함수, 논리 최소화를 다루는 표준 교재. 본 논문의 기본 개념 정의 참조.

---

**[8]** Roth, C. H., Jr., & Kinney, L. L.  
*Fundamentals of Logic Design* (7th ed.).  
Cengage Learning.

> 논리 설계 입문서. 카르노맵 기초 개념 및 Gray Code 배열 참조.

---

## 4. 완전대칭함수 (Symmetric Boolean Functions)

**[9]** Shannon, C. E. (1938).  
"A symbolic analysis of relay and switching circuits."  
*Transactions of the American Institute of Electrical Engineers*, 57(12), 713–723.

> 불 대수를 전기 회로 설계에 적용한 기초 논문. 대칭함수 개념의 출발점.

---

**[10]** Davio, M., Deschamps, J.-P., & Thayse, A. (1978).  
*Discrete and Switching Functions.*  
McGraw-Hill.

> 대칭 불 함수의 수학적 구조를 체계적으로 다룬 참고서.

---

## 5. 불변성 및 군론 (향후 연구 배경)

*본 논문에서는 이 방향을 직접 다루지 않으나, 향후 연구(FUTURE_IDEAS.md 참조)를 위한 기반 문헌.*

**[11]** Dummit, D. S., & Foote, R. M.  
*Abstract Algebra* (3rd ed.).  
Wiley.

> 치환군(symmetric group) S₄ 분석의 수학적 기반. 향후 변수 배열 동치류 연구에 필요.

---

**[12]** Weyl, H. (1952).  
*Symmetry.*  
Princeton University Press.

> 수학과 물리학에서의 불변성(invariance) 개념을 직관적으로 설명한 고전.

---

## 비고

- 각 인용 번호([1]–[12])는 논문 본문에 `[1]`, `[7]` 형식으로 표기할 것을 권장합니다.
- [10], [11], [12]는 본 논문 본문에서 직접 인용하지 않았으며, 향후 연구 맥락에서 참조용입니다.
- 출판 연도 및 판(edition)은 이용 가능한 최신판 기준으로 업데이트하여 사용하십시오.
