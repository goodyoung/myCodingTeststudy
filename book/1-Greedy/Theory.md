# Greedy Alogirthm
---
> Greedy 알고리즘은 단순하지만 강력한 문제 해결 방법이다. 단순 무식하게 탐욕적으로 문제를 푸는 알고리즘이다.
그리디 알고리즘을 이용하면 ***매 순간 가장 좋아 보이는 것을 선택***하며, 현재의 선택이 나중에 미칠 영향에 대해서는 고려하지 않는다.

- 모든 문제를 암기로 대처하기 어렵다는 점을 이해해야 한다.
- 특정한 문제를 만났을 때 단순히 현재 상황에서 가장 좋아 보이는 것만을 선택해도 문제를 풀 수 있는지를 파악할 수 있어야 한다.
- 그리디 알고리즘 문제 해결 방법
  - 선택 절차: 현재 상태에서의 최적의 해답을 선택한다.
  - 적절성 검사: 선택된 해가 문제의 조건을 만족하는지 검사한다.
  - 해답 검사: 원래의 문제가 해결되었는지 검사하고 해결되지 않았다면 위의 과정 반복.

### 거스름돈 예시
- ***가장 큰 화폐 단위부터*** 돈을 거슬러주는 것이다.
- 이게 가능하게 된 이유는 동전 중에서 큰 단위가 항상 작은 단위의 배수이므로 다른 해가 나올 수 없기 때문이다. 만약 배수 관계가 아니라면 그리디 알고리즘이 문제를 적용하여 풀 수 없다.
- 따라서 문제풀이의 최적의 해답을 정하고(**선택 절차**) 적절한지 검토할 수 있어야(**적절성 검사**) 답을 도출 할 수 있게 된다.


그리디 알고리즘이랑 정렬이랑 같이 나오는 경우가 많다.