# Mathematical Induction (수학적 귀납법)

## Climbing an Infinite Ladder (무한 사다리 타기)
Suppose we have an infinite ladder:
1. We can reach the first rung of the ladder.
2. If we can reach a particular rung of the ladder, then we can reach the next rung.
From (1), we can reach the first rung. 
Then by applying (2), we can reach the second rung.
Applying (2) again, the third rung. And so on.
We can apply (2) any number of times to reach any particular rung, no matter how high up.
This example motivates proof by mathematical induction.

우리가 무한한 사다리를 가지고 있다고 가정하자:
1. 우리는 사다리의 첫 번째 줄에 도달할 수 있다.
2. 사다리의 특정 부분에 도달할 수 있다면 다음 단계에 도달할 수 있습니다.
(1)부터, 우리는 첫 번째 라운드에 도달할 수 있다. 
그런 다음 (2)를 적용하면 2위까지 갈 수 있다.
다시 (2)를 적용하면, 세 번째 줄입니다. 등등.
우리는 아무리 높은 곳에 있더라도, 어떤 특정 순위에 도달하기 위해 (2)를 몇 번이라도 적용할 수 있다.
이 예는 수학적 귀납에 의해 증명에 동기를 부여한다.

## Principle of Mathematical Induction (수학적 귀납의 원리)
Principle of Mathematical Induction: To prove that P(n) is true for all positive integers n, we complete these steps:
• Basis Step: Show that P(1) is true.
• Inductive Step: Show that P(k) → P(k + 1) is true for all positive integers k.
To complete the inductive step, assuming the inductive hypothesis that P(k) holds for an arbitrary integer k, show that must P(k + 1) be true.
Climbing an Infinite Ladder Example:
• BASIS STEP: By (1), we can reach rung 1.
• INDUCTIVE STEP: Assume the inductive hypothesis that we can reach rung k. Then by (2), we can reach rung k + 1.
Hence, P(k) → P(k + 1) is true for all positive integers k. 
We can reach every rung on the ladder.

수학적 귀납의 원리: 모든 양의 정수 n에 대해 P(n)가 참임을 증명하기 위해, 우리는 다음 단계를 완료한다.
• 기본 단계: P(1)가 참임을 나타냅니다.
• 유도 단계: 모든 양의 정수 k에 대해 P(k) → P(k + 1)가 참임을 보여준다.
유도 단계를 완료하기 위해, P(k)가 임의의 정수 k에 대해 갖는 유도 가설을 가정하면, P(k + 1)가 참이어야 한다.
무한 사다리 타기 예:
• 기본 단계: (1)에 의해, 우리는 랭크 1에 도달할 수 있다.
• 귀납적 단계: 우리가 랭크에 도달할 수 있다는 귀납적 가설을 가정하자. 그러면 (2)에 의해, 우리는 랭크 + 1에 도달할 수 있다.
따라서, P(k) → P(k + 1)는 모든 양의 정수 k에 대해 참이다. 
우리는 사다리의 모든 계단까지 갈 수 있다.

## Important Points About Using Mathematical Induction (수학적 귀납법 사용에 대한 중요 사항)
Mathematical induction can be expressed as the rule of inference

(P(1) ∧ ∀k (P(k) → P(k + 1)) → ∀n P(n),

where the domain is the set of positive integers.
In a proof by mathematical induction, we don’t assume that P(k)
is true for all positive integers! We show that if we assume that
P(k) is true, then P(k + 1) must also be true.
Proofs by mathematical induction do not always start at the
integer 1. In such a case, the basis step begins at a starting point
b where b is an integer. We will see examples of this soon.

수학적 귀납은 추론의 법칙으로 표현될 수 있다.

(P(1) ∧ ∀k (P(k) → P(k + 1)) → ∀n P(n),

여기서 도메인은 양의 정수 집합이다.
수학적 귀납법에 의한 증명에서, 우리는 P(k)가 모든 양의 정수에 대해 참이라고 가정하지 않는다! 
우리는 P(k)가 참이라고 가정하면 P(k + 1)도 참이어야 한다는 것을 보여준다.
수학적 귀납법에 의한 증명은 항상 정수 1에서 시작하는 것은 아니다. 
이 경우, 기본 단계는 b가 정수인 시작점 b에서 시작한다. 우리는 곧 이것의 예시를 볼 것이다.
