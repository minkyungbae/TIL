[TIL_5일차](https://bmk0703.tistory.com/15)
### <center> *TIL* </center>
[TIL] 내일배움캠프 본캠프 5일차_프로그래머스 3문제 풀이와 과제 진행

---
### <center>**요약**
1. 프로그래머스 3문제 풀이
    1.각도 합치기
    2. 피타고라스
    3. 두 수의 차
2. 딕셔너리 발표 진행(14:00~17:20)
3. 개인과제_첫 번째 문제 풀기
    1.import random
---
```python
import random

input_random_numbers = random.randint(1, 10)
print(input_random_numbers)

while True:
    start_sentence = int(input("숫자를 입력해주세요: "))
    if input_random_numbers == start_sentence:
        print("정답입니다!")
        break
    elif start_sentence < input_random_numbers:
        print("보다 큽니다, 다시 입력해주세요!")
    elif start_sentence > input_random_numbers:
        print("보다 작습니다, 다시 입력해주세요!")
    else:
        print("땡! 다시 입력해주세요")
```
---
