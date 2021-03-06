# [달팽이 리스트] <https://www.acmicpc.net/problem/17827>

## 문제
영진이는 달팽이를 좋아한다. 달팽이를 너무너무 좋아하기 때문에 특정한 모양의 단방향 연결리스트에 달팽이 리스트라는 이름을 붙여주었다.

일반적인 선형 단방향 연결리스트의 각 노드 번호를 연결된 순서대로 1, 2, ..., N이라 하자. 이때 N번 노드는 아무 노드도 가리키지 않는데, 여기서 N번 노드가 1번 노드를 제외한 임의의 노드를 가리켜 사이클을 이루게 되는 리스트를 달팽이 리스트라고 한다. 달팽이 리스트는 각 노드당 하나의 정수를 저장한다.

즉, 달팽이 리스트는 다음과 같이 생긴 연결리스트이다. 노드 안의 수는 저장된 값을 뜻한다.

"달팽아 달팽아 1번 노드부터 한 칸씩 총 K번 이동해 도착한 노드엔 어떤 값이 있을까?"

영진이는 어두운 방 안에서 달팽이 리스트 하나를 쓱쓱 그리더니, 같은 말을 K만 바꿔가며 계속 중얼거렸다.

영진이의 상태가 심상치 않아 보인다... 상황이 더 악화되기 전에 영진이의 모든 질문에 대답해주도록 하자.

## 입력
첫째 줄에 노드의 개수 N(2 ≤ N ≤ 200,000), 질문의 횟수 M(1 ≤ M ≤ 200,000), N번 노드가 가리키는 노드의 번호 V(2 ≤ V ≤ N)가 공백으로 구분되어 주어진다.

둘째 줄에 N개의 정수 C1, C2, …, CN이 공백으로 구분되어 주어진다. 이때 Ci는 i번 노드에 저장된 값을 뜻한다. (1 ≤ Ci ≤ 1,000,000)

셋째 줄부터 M개의 줄에 걸쳐 각 질문에 해당하는 K(1 ≤ K ≤ 109)가 주어진다.

## 출력
M개의 줄에 걸쳐 각 질문의 답을 출력한다.

## 예제입력1
```
10 10 3
13 2 5 11 7 8 2 4 9 10
1
2
3
8
9
10
11
16
17
49
```
## 예제출력1
```
2
5
11
9
10
5
11
9
10
10
```

```
