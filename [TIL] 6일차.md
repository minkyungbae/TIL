[TIL_6일차](https://bmk0703.tistory.com/17)
### <center> *TIL* </center>
[TIL] 내일배움캠프 본캠프 6일차_Python 라이브러리로 데이터 분석하기

---
### <center>**요약**
1. 과제 2_class 정의
```python
# 4트
class person:
    def __init__(self):
        self.name = input("이름을 입력해주세요 -> ")
        self.gender = input("성별을 입력해주세요 -> ")
        self.age = int(input("나이를 입력해주세요 -> "))
        
    def display(self):
        print("이름 : {}, 성별 : {}, 나이 : {}".format(self.name, self.gender, self.age))
        
# 객체 생성(=person_info)
person_info = person()
person_info.display()
```
2. 파이썬 라이브러리 강의 시청
3. 가상환경 활성화 하기
4. Data Frame 생성하기
```python
import pandas as pd
dataframe = pd.read_excel('crime.xlsx')
dataframe
```
5. 관서명의 빈칸에 '구 없음'으로 채우기
```python
dataframe['구 별'] = dataframe['관서명'].map(df).fillna('구 없음')

dataframe
```
---
