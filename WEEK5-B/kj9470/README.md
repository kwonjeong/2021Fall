### MST
> Minimum Spanning Tree

그래프 내의 모든 정점을 표현하는 트리
- Spanning tree는 그래프의 최소 연결 부분 그래프
- 최소 연결 : 간선의 수가 가장 적다
- n개의 정점을 가지는 그래프의 최소 간선의 수는 (n-1)이고, (n-1)개의 간선으로 연결되어 있으면 필연적으로 트리 형태가 되고 이것이 바로 Spanning tree가 된다
- Spanning tree는 모든 정점들이 연결되어 있어야 하고 사이클을 포함해서는 안된다
***
### DFS
> Depth First Search

루트 노드에서 시작해서 다음 분기로 넘어가기 전에 해당 분기를 완벽하게 탐색하는 방법
- 모든 노드를 방문하고자 할 때 이 방법 선택
- 어떤 노드를 방문했는지 여부를 반드시 검사해야 함

구현 방법
- 순환 호출 이용
- 명시적인 스택 사용
### BFS
> Breadth First Search

루트 노드에서 시작해서 인접한 노드를 먼저 탐색하는 방법
- 두 노드 사이의 최단 경로 혹은 임의의 경로를 찾을 때 사용
- DFS보다 복잡
- 재귀적으로 동작하지 않는다
- 방문한 노드를 차례로 저장할 수 있는 큐를 이용

구현
- 자료구조 큐(Queue)를 이용