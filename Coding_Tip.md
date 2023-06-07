### 코딩 팁
코딩문제를 풀면서 배운 내용들을 끄적이는 공간

## 우선순위 큐 (힙) 사용법
힙 선언은 일반적인 배열과 동일하다
힙은 배열의 원소를 자동으로 오름차순 정렬한다
힙의 원소들에 -1을 곱하여 내림차순 힙처럼 동작할 수 있다
```
import heapq
heap = [] 
```

힙에 원소를 삽입하는 방법
```
heapq.heappush(heap, 5)
heapq.heappush(heap, 1)
heapq.heappush(heap, 3)
print(heap) # [1,3,5]
```

힙의 원소를 빼내는 방법
```
P0 = heapq.heappop(heap)
print(P0) # P0 == 1
```

## sys를 활용한 입력
sys를 활용하면 input을 활용할 때보다 더 빠르게 입력받을 수 있다
```
import sys
n = int(sys.stdin.readline())
```