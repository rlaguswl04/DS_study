### **문법**

- vector란?

C++ 표준라이브러리(**S**tandard **T**emplate **L**ibrary)에 있는 컨테이너로 사용자가 사용하기 편하게 정의된 class. vector를 생성하면 메모리 heap에 생성되며 동적할당됨.

- vector<자료형> 변수명: 백터 생성
- v.push_back(): 백터의 마지막 부분에 새로운 요소 추가

### **문제풀이**

- "같은 숫자가 연속하면 안된다 " 라는 것은 n번쨰 숫자와 n-1번쨰 숫자가 같으면 n번째 숫자는 answer 벡터에 넣지 않는다와 같음
- 배열 arr의 크기는 1,000,000 이하의 자연수이고 1보다 크므로 n-1을 사용하기 위해서 첫번째 값은 answer에 넣어줌
- 그 뒤로 n-1 번째와 n번째를 비교해가며 answer에 넣음
