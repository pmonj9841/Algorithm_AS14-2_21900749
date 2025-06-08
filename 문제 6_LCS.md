# 선택 알고리즘
Dynamic Programming

# 선택 이유 및 장단점 비교
해당 문제는 2차원 공간을 만들어 Dynamic programming을 사용하여 해결이 가능하다. 전체 문제는 2차원 공간의 요소 하나하나에 대한
문제로 쪼개질 수 있고(최적 부분 구조), 각 부분 문제의 해를 저장해가면서 다 구하면 전체 해를 구할 수 있다(중복 부분 문제).

# 구현 코드 및 실행 결과
![image](https://github.com/user-attachments/assets/bd3da763-4efa-49f3-87c7-90a545c1c575)
![image](https://github.com/user-attachments/assets/a083d62f-aaa8-452d-9755-8b1ea63e32f7)
![image](https://github.com/user-attachments/assets/171cf275-6cd3-456b-bed2-2940425fc63c)

# 시간/공간 복잡도
시간 복잡도  
O(m×n)  
m: DP테이블의 행 수  
n: DP테이블의 열 수  
DP 테이블의 각 칸을 계산해야 하므로.

공간 복잡도
O(m×n)  
m: DP테이블의 행 수  
n: DP테이블의 열 수  
DP 테이블의 각 칸의 해를 저장해야 하므로.

# AI 사용 구분
lcs()함수 작성을 위해 AI 참조. 주석 본인 작성.
