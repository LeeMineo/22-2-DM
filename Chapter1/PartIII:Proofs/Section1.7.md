# Introduction to Proofs 증명 소개

## Definitions 정의들 <br>

A theorem is a statement that can be shown to be true using: <br>
정리는 다음과 같이 참임을 나타낼 수 있는 문장이다. <br>

• definitions 정의들 <br>
• other theorems 다른 정리 <br>
• axioms (statements which are given as true) 공리(참으로 주어진 문) <br>
• rules of inference 추론 규칙 <br>
 
A lemma is a ‘helping theorem’ or a result which is needed to prove a theorem. <br>
레마는 정리를 증명하기 위해 필요한 '도움 정리' 또는 결과이다. <br>

A corollary is a result which follows directly from a theorem.<br>
귀결은 정리에서 직접 나오는 결과이다.<br>

Less important theorems are sometimes called propositions. 덜 중요한 정리는 때때로 명제라고 불린다.<br>
A conjecture is a statement that is being proposed to be true. 추측은 사실로 제안되고 있는 진술이다.<br>

 Once a proof of a conjecture is found, it becomes a theorem. It may turn out to be false.<br>
 일단 추측의 증거가 발견되면, 그것은 정리가 된다. 그것은 거짓으로 판명될지도 모른다.<br>
 
 ## Forms of Theorems 정리의 형태<br>
 
Many theorems assert that a property holds for all elements in a domain, such as the integers, the real numbers, or some of the discrete structures that we will study in this class.<br>
많은 정리는 정수, 실수, 또는 우리가 이 클래스에서 연구할 이산 구조 중 일부와 같은 도메인 내의 모든 요소에 대한 속성을 가지고 있다고 주장한다.<br>

Often the universal quantifier (needed for a precise statement of a theorem) is omitted by standard mathematical convention.<br>
종종 (정리의 정확한 진술에 필요한) 보편적 정량자는 표준 수학 규칙에 의해 생략된다.<br>

For example, the statement: 예를 들어 다음과 같습니다.<br>
“If x > y, where x and y are positive real numbers, then x2 > y2 ” <br>
"만약 x > y, 여기서 x와 y는 양의 실수라면, x2 > y2"<br>

really means<br>
“For all positive real numbers x and y, if x > y, then x2 > y2.” <br>
"모든 양의 실수 x와 y에 대하여, 만약 x > y라면, x2 > y2이다.<br>

## Proving Theorems 증명 정리<br>
Many theorems have the form: 많은 정리는 다음과 같은 형태를 갖는다.<br>

where c is an arbitrary element of the domain, 여기서 c는 도메인의 임의의 요소이다.<br>
<img width="199" alt="스크린샷 2022-09-19 오전 10 15 44" src="https://user-images.githubusercontent.com/103713510/190936570-15f0a8d6-7b54-480d-beef-5fb2e783f078.png"><br>
<br>

By universal generalization the truth of the original formula follows.<br>
보편적인 일반화에 의해 원래의 공식의 진실은 다음과 같다.<br>
<img width="151" alt="스크린샷 2022-09-19 오전 10 15 48" src="https://user-images.githubusercontent.com/103713510/190936571-2c0e2362-d0d6-41be-a3bc-e78fed699ed4.png"><br>


So, we must prove something of the form: p → q<br>
그래서, 우리는 어떤 형태로든 증명해야 한다: p → q<br>

## Proving Conditional Statements: p → q 조건문 증명: p → q<br>

Trivial Proof: If we know q is true, then p → q is true as well. 사소한 증명: q가 참이라는 것을 알면 p → q도 참이다.<br>
“If it is raining then 1=1.” "비가 온다면 1=1입니다."<br>

Vacuous Proof: If we know p is false then p → q is true as well. 진공 증명: 만약 우리가 p가 거짓이라는 것을 안다면, p → q도 참이다.<br>
“If I am both rich and poor then 2 + 2 = 5.” "만약 내가 부자이고 가난하다면 2 + 2 = 5이다."<br>

[ Even though these examples seem silly, both trivial and vacuous proofs are often used in mathematical induction, as we will see in Chapter 5) ]<br>
[이러한 예들이 어리석게 보일지라도, 우리가 5장에서 보게 될 것처럼, 사소한 증명과 공허한 증명 모두 종종 수학적 귀납에 사용된다]<br>

## Proving Conditional Statements: p → q 2 조건문 증명: p → q 2<br>
Direct Proof: Assume that p is true. Use rules of inference, axioms, and logical equivalences to show that q must also be true.<br>
직접 증명: p가 참이라고 가정하자. 추론, 공리 및 논리적 동등성의 규칙을 사용하여 q도 참이어야 한다는 것을 보여준다.\<br>

Example: Give a direct proof of the theorem “If n is an odd integer, then n2(n제곱) is odd.”<br>
예: "n이 홀수 정수라면, n2는 홀수"라는 정리의 직접적인 증거를 제시하라.<br>

Solution: Assume that n is odd. Then n = 2k + 1 for an integer k. 솔루션: n이 홀수라고 가정하자. 그렇다면 n = 2k + 1은 정수 k이다.<br>
Squaring both sides of the equation, we get: 방정식의 양쪽을 제곱하면 다음과 같은 결과를 얻을 수 있다.<br>
<img width="664" alt="스크린샷 2022-09-19 오전 10 25 16" src="https://user-images.githubusercontent.com/103713510/190937114-69151773-396e-436d-86cb-fc7bb01ea4eb.png"><br>


We have proved that if n is an odd integer, then n2 is an odd integer. 우리는 n이 홀수 정수라면 n2가 홀수 정수라는 것을 증명했다.<br>
(marks the end of the proof. Sometimes QED is used instead.) (증거의 끝을 표시합니다. QED가 대신 사용되는 경우도 있습니다.)<br>

## Proving Conditional Statements: p → q 3 조건문 증명: p → q 3<br>
Proof by Contraposition: Assume ¬q and show ¬p is true also. 대비에 의한 증명: <br>
This is sometimes called an indirect proof method. If we give a direct proof of ¬q → ¬p then we have a proof of p → q.<br>
이것은 간접 증명법이라고 불리기도 한다. 만약 우리가 ¬q → ¬p에 대한 직접적인 증거를 제공한다면, 우리는 p → q에 대한 증거를 갖게 된다.<br>

Why does this work? 왜 이렇게 되는 거죠?<br>

Example: Prove that if n is an integer and 3n + 2 is odd, then n is odd. 예: n이 정수이고 3n + 2가 홀수이면 n이 홀수임을 증명한다.<br>

Solution: Assume n is even. So, n = 2k for some integer k. 솔루션: n이 짝수라고 가정하자. 따라서, n은 정수 k에 대해 2k이다.<br>
3n + 2 = 3(2k) + 2 =6k +2 = 2(3k + 1) = 2j for j = 3k +1<br>

Therefore 3n + 2 is even. Since we have shown ¬q → ¬p , p → q must hold as well. If n is an integer and 3n + 2 is odd (not even) , then n is odd (not even).<br>
따라서 3n + 2는 짝수이다. ¬q → ¬p를 보여줬기 때문에 p → q도 유지되어야 합니다. n이 정수이고 3n + 2가 홀수(짝수 아님)이면 n은 홀수(짝수 아님)입니다.<br>

## Proving Conditional Statements: p → q 4 조건문 증명: p → q 4<br>
Proof by Contradiction: (AKA reductio ad absurdum). 모순에 의한 증명: (일명 AKA 축소 광고 부조리)<br>

To prove p, assume ¬p and derive a contradiction such as r ∧ ¬r. (an indirect form of proof). p를 증명하기 위해, ¬p를 가정하고 r ∧ ¬r(간접적인 형태의 증명)과 같은 모순을 도출한다. <br>
Since we have shown that ¬p →F is true , it follows that the contrapositive T→p also holds. ¬p →F가 참이라는 것을 보여주었으므로, 역양성 T→p도 성립한다.<br>

Example: Prove that if you pick 22 days from the calendar, at least 4 must fall on the same day of the week.<br>
예: 달력에서 22일을 선택하면 적어도 4일은 같은 요일에 해당해야 합니다.<br>

Solution: Assume that no more than 3 of the 22 days fall on the same day of the week. Because there are 7 days of the week, we could only have picked 21 days. This contradicts the assumption that we have picked 22 days.<br>
솔루션: 22일 중 3일을 넘지 않는 날이 주의 같은 날이라고 가정하자. 일주일 중 7일이니까 21일만 뽑을 수 있었을 텐데. 이것은 우리가 22일을 선택했다는 가정과 모순된다.<br>

## Theorems that are Biconditional Statements 이항 조건문인 정리<br>

To prove a theorem that is a biconditional statement, that is, a statement of the form p ↔ q, we show that p → q and q →p are both true.<br>
이항 조건문인 정리, 즉 p ↔ q 형식의 문임을 증명하기 위해, 우리는 p → q와 q → p가 모두 참임을 보여준다.<br>

Example: Prove the theorem: “If n is an integer, then n is odd if and only if n제곱 is odd.” 예: "n이 정수라면 n2가 홀수일 때만 n이 홀수이다."라는 정리를 증명하라.<br>
Solution: We have already shown (previous slides) that both p →q and q →p. Therefore we can conclude p ↔ q.<br>
솔루션: 우리는 이미 (이전 슬라이드) p → q와 q → p 둘 다 보여주었습니다. 따라서 우리는 p ↔ q라는 결론을 내릴 수 있다.<br>

Sometimes iff is used as an abbreviation for “if and only if,” as in 때때로 iff는 다음과 같이 "if and only if"의 약어로 사용된다.<br>

“If n is an integer, then n is odd iff n 2 is odd.” "n이 정수라면, n2가 홀수라면 n은 홀수이다."<br>
