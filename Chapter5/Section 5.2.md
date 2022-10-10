# Strong Induction and Well-Ordering (강력한 유도 및 질서 정돈)

## Strong Induction

Strong Induction: To prove that P(n) is true for all positive integers n, where P(n) is a propositional function, complete two steps:
• Basis Step: Verify that the proposition P(1) is true.
• Inductive Step: Show the conditional statement

[P(1) ∧ P(2) ∧ P(k)] → P(k + 1)

holds for all positive integers k.

강력한 유도: 모든 양의 정수 n에 대해 P(n)가 참임을 증명하기 위해, P(n)는 명제 함수이다.
• 기본 단계: 명제 P(1)가 참인지 확인합니다.
• 유도 단계: 조건문을 표시합니다.

[P(1) ∧ P(2) ∧ P(k)] → P(k + 1)

모든 양의 정수 k에 대해 고정합니다.

Strong Induction is sometimes called the second principle of mathematical induction or complete induction.
강한 귀납은 때때로 수학적 귀납 또는 완전 귀납의 두 번째 원리로 불린다.

## Strong Induction and the Infinite Ladder (강력한 인덕션과 무한 사다리)
Strong Induction and the Infinite LadderStrong induction tells us that we can reach all rungs if:
1. We can reach the first rung of the ladder.
2. For every integer k, if we can reach the first k rungs, then we can reach the (k + 1)th rung.
To conclude that we can reach every rung by strong
induction:
• BASIS STEP: P(1) holds
• INDUCTIVE STEP: Assume P(1) ∧ P(2) ∧∙∙∙ ∧ P(k)
holds for an arbitrary integer k, and show that P(k + 1) must also hold.
We will have then shown by strong induction that for every positive integer n, P(n) holds, i.e., we can reach the nth rung of the ladder.

강유도 및 무한 사다리 강유도는 다음과 같은 경우 모든 랭크에 도달할 수 있음을 알려줍니다.
1. 우리는 사다리의 첫 번째 줄에 도달할 수 있다.
2. 모든 정수 k에 대해, 만약 우리가 첫 번째 칸에 도달할 수 있다면, 우리는 (k + 1) 칸에 도달할 수 있다.
우리가 강한 힘으로 모든 단계에 도달할 수 있다고 결론짓기 위해
유도:
• 기본 단계: P(1) 보류
• 유도 단계: Assume P(1) ∧ P(2) ∧∙∙∙ ∧ P(k)
는 임의의 정수 k에 대해 홀드하며, P(k + 1)도 홀드해야 함을 나타냅니다.
그런 다음 우리는 모든 양의 정수 n에 대해 P(n)가 유지한다는, 즉 사다리의 n번째 줄에 도달할 수 있다는 것을 강한 유도로 보여줄 것이다.

## Completion of the proof of the Fundamental Theorem of Arithmetic (산술의 기본정리 증명서 완성)
Example: Show that if n is an integer greater than 1, then n can be written as the product of primes.
Solution: Let P(n) be the proposition that n can be written as a product of primes.
• BASIS STEP: P(2) is true since 2 itself is prime.
• INDUCTIVE STEP: The inductive hypothesis is that P(j) is true for all integers j with 2 ≤ j ≤ k. To show that P(k + 1) must be true under this assumption, two cases need to be considered:
• If k + 1 is prime, then P(k + 1) is true.
• Otherwise, k + 1 is composite and can be written as the product of two positive integers a and b with 2 ≤ a ≤ b < k + 1. By the inductive hypothesis a and b can be written as the product of primes and therefore k + 1 can also be written as the product of those primes.

Hence, it has been shown that every integer greater than 1 can be written as the product of primes.

예: 만약 n이 1보다 큰 정수라면, n은 소수의 곱으로 쓸 수 있다는 것을 보여준다.
솔루션: P(n)를 소수의 곱으로 쓸 수 있는 명제라고 하자.
• 기본 단계: 2 자체가 소수이기 때문에 P(2)가 참이다.
• 유도 단계: 유도 가설은 P(j)가 2 ≤ j ≤ k인 모든 정수 j에 대해 참이라는 것이다. 이 가정 하에서 P(k + 1)가 참이어야 한다는 것을 보여주기 위해, 두 가지 경우를 고려할 필요가 있다.
• 만약 k + 1이 소수라면, P(k + 1)는 참이다.
• 그렇지 않으면, k + 1은 복합적이며, 2 ≤ a ≤ b < k + 1인 두 양의 정수 a와 b의 곱으로 쓸 수 있다.

따라서 1보다 큰 모든 정수는 소수의 곱으로 쓸 수 있는 것으로 나타났다.

## Proof using Strong Induction (강력한 유도를 사용한 증명)

Example: Prove that every amount of postage of 12 cents or more can be formed using just 4-cent and 5-cent stamps.
Solution: Let P(n) be the proposition that postage of n cents can be formed using 4-cent and 5-cent stamps.
• BASIS STEP: P(12), P(13), P(14), and P(15) hold.
• P(12) uses three 4-cent stamps.
• P(13) uses two 4-cent stamps and one 5-cent stamp.
• P(14) uses one 4-cent stamp and two 5-cent stamps.
• P(15) uses three 5-cent stamps.

예: 12센트 이상의 모든 우표가 4센트와 5센트짜리 우표만으로 형성될 수 있다는 것을 증명하세요.
솔루션: P(n)가 4센트 및 5센트 우표를 사용하여 n센트의 우표를 형성할 수 있다는 제안을 하자.
• 기본 단계: P(12), P(13), P(14) 및 P(15) 고정.
• P(12)는 4센트짜리 우표 3장을 사용한다.
• P(13)는 4센트짜리 우표 두 개와 5센트짜리 우표 한 개를 사용한다.
• P(14)는 4센트짜리 우표 한 개와 5센트짜리 우표 두 개를 사용한다.
• P(15)는 5센트짜리 우표 3장을 사용한다.

The inductive hypothesis states that P(j) holds for 12 ≤ j ≤ k, where k ≥ 15. Assuming the inductive hypothesis, it can be shown that P(k + 1) holds. 
=> P 1 ∧ P 2 ∧ ⋯ ∧ P k → P k + 1
• Using the inductive hypothesis, P(k − 3) holds since k − 3 ≥ 12. To form postage of k + 1 cents, add a 4-cent stamp to the postage for k − 3 cents.
Hence, P(n) holds for all n ≥ 12.

귀납 가설은 P(j)가 12 ≤ j ≤ k이며, 여기서 k ≤ 15이다. 귀납 가설을 가정하면, P(k + 1)가 성립함을 알 수 있다. => P 1 p P 2 ∧ P k → P k + 1
• 귀납 가설을 사용하여 P(k - 3)는 k - 3 ≤ 12 이후를 유지합니다. k + 1센트의 우표를 형성하려면 k - 3센트의 우표에 4센트짜리 우표를 추가합니다.
따라서, P(n)는 모든 n ≥ 12를 유지한다.

## Proof of Same Example using Mathematical Induction (수학적 귀납법을 사용한 동일한 예제의 증명)
Example: Prove that every amount of postage of 12 cents or more can be formed using just 4-cent and 5-cent stamps.
Solution: Let P(n) be the proposition that postage of n cents can be formed using 4-cent and 5-cent stamps.
• BASIS STEP: Postage of 12 cents can be formed using three 4-cent stamps.
• INDUCTIVE STEP: The inductive hypothesis P(k) for any positive integer k is that postage of k cents can be formed using 4-cent and 5-cent stamps. To show P(k + 1) where k ≥ 12 , we consider two cases:
• If at least one 4-cent stamp has been used, then a 4-cent stamp can be replaced with a 5-cent stamp to yield a total of k + 1 cents.
• Otherwise, no 4-cent stamp have been used and at least three 5-cent stamps were used. Three 5-cent stamps can be replaced by four 4-cent stamps to yield a total of k + 1 cents.
Hence, P(n) holds for all n ≥ 12.

예: 12센트 이상의 모든 우표가 4센트와 5센트짜리 우표만으로 형성될 수 있다는 것을 증명하세요.
솔루션: P(n)가 4센트 및 5센트 우표를 사용하여 n센트의 우표를 형성할 수 있다는 제안을 하자.
• 기본 단계: 4센트짜리 우표 3장을 사용하여 12센트의 우표를 만들 수 있습니다.
• 유도 단계: 임의의 양의 정수 k에 대한 유도 가설 P(k)는 k센트의 우표가 4센트와 5센트의 우표를 사용하여 형성될 수 있다는 것이다. 여기서 P(k + 1)를 보여주기 위해 k ≤ 12인 경우, 우리는 두 가지 경우를 고려한다.
• 적어도 하나의 4센트짜리 우표를 사용한 경우, 4센트짜리 우표를 5센트짜리 우표로 대체하여 총 k + 1센트를 산출할 수 있습니다.
• 그렇지 않으면, 4센트짜리 우표는 사용되지 않았고 적어도 3개의 5센트짜리 우표가 사용되었습니다. 5센트짜리 우표 3장은 4센트짜리 우표 4장으로 대체되어 총 k+1센트를 산출할 수 있다.
따라서, P(n)는 모든 n ≥ 12를 유지한다.
