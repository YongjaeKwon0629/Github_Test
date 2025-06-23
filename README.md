🐍 Python 이론 & 실전 정리 (Python Theory & Practice)

Python 기초부터 실전 활용까지 12가지 핵심 주제를 정리한 README입니다. GitHub에서 바로 복사해 붙여넣으면 목차와 내용이 연동되며 문서 형태로 사용 가능합니다.

📚 목차 (Table of Contents)

파이썬 개요와 특징

변수, 자료형, 연산자

조건문과 반복문

함수와 람다 함수

자료구조: 리스트, 튜플, 딕셔너리, 집합

객체지향 프로그래밍 (OOP)

예외 처리와 파일 입출력

모듈, 패키지, 가상환경

파이썬 알고리즘 기초

파이썬 데이터 분석 입문

파이썬 시각화 기초

파이썬과 인공지능 개요

1. 파이썬 개요와 특징

1.1 파이썬의 역사

1991년 Guido van Rossum이 개발

1.2 특징

인터프리터 언어, 크로스 플랫폼, 동적 타이핑, 가독성 강조

1.3 활용 분야

웹 개발, 데이터 분석, 인공지능, 자동화, IoT, 교육 등

2. 변수, 자료형, 연산자

2.1 변수 선언

x = 5
name = "Alice"

2.2 자료형

int, float, str, bool, NoneType 등

2.3 형 변환

int("10"), str(20), float("3.14")

2.4 연산자

산술, 비교, 논리, 복합 할당 연산자 등

3. 조건문과 반복문

3.1 조건문

if x > 0:
    ...
elif x == 0:
    ...
else:
    ...

3.2 반복문

for i in range(5):
    print(i)

while True:
    break

3.3 제어문

break, continue, pass

4. 함수와 람다 함수

4.1 함수 정의

def add(a, b):
    return a + b

4.2 기본 인자, 키워드 인자

4.3 가변 인자

4.4 람다 함수

square = lambda x: x ** 2

5. 자료구조: 리스트, 튜플, 딕셔너리, 집합

5.1 리스트

lst = [1, 2, 3]
lst.append(4)

5.2 튜플

tpl = (1, 2, 3)

5.3 딕셔너리

dct = {"name": "Tom", "age": 25}

5.4 집합

st = {1, 2, 3, 3}  # 중복 제거

5.5 컴프리헨션

[x * 2 for x in range(5)]

6. 객체지향 프로그래밍 (OOP)

6.1 클래스와 인스턴스

class Dog:
    def __init__(self, name):
        self.name = name

6.2 캡슐화

class Account:
    def __init__(self):
        self.__balance = 0

6.3 상속

class Animal:
    def speak(self):
        print("소리")
class Dog(Animal):
    def speak(self):
        print("멍멍")

6.4 다형성

for a in [Dog(), Animal()]:
    a.speak()

7. 예외 처리와 파일 입출력

7.1 예외 처리

try:
    1 / 0
except ZeroDivisionError:
    ...
finally:
    ...

7.2 사용자 정의 예외

class MyError(Exception):
    pass

7.3 파일 입출력

with open("file.txt") as f:
    content = f.read()

8. 모듈, 패키지, 가상환경

8.1 모듈 사용

import math
print(math.sqrt(4))

8.2 패키지 구성

디렉토리 + init.py

8.3 가상환경

python -m venv venv
source venv/bin/activate

9. 파이썬 알고리즘 기초

9.1 재귀 함수

def factorial(n):
    return 1 if n == 0 else n * factorial(n-1)

9.2 정렬

버블, 선택, 삽입, 병합, 퀵 정렬

9.3 탐색

선형 탐색, 이진 탐색

9.4 시간 복잡도

O(1), O(n), O(n log n) 등

10. 파이썬 데이터 분석 입문

10.1 pandas 사용

import pandas as pd
df = pd.read_csv("file.csv")

10.2 numpy 배열

import numpy as np
arr = np.array([1, 2, 3])

10.3 필터링과 그룹화

filtered = df[df["age"] > 30]

11. 파이썬 시각화 기초

11.1 matplotlib

import matplotlib.pyplot as plt
plt.plot([1, 2, 3], [4, 5, 6])
plt.show()

11.2 seaborn

import seaborn as sns
sns.histplot(df['column'])

11.3 plotly

import plotly.express as px
fig = px.scatter(df, x="a", y="b")
fig.show()

12. 파이썬과 인공지능 개요

12.1 머신러닝 vs 딥러닝

머신러닝: 통계 기반 모델 (ex. SVM, 의사결정나무)

딥러닝: 신경망 기반 모델 (CNN, RNN 등)

12.2 지도/비지도 학습

지도학습: label 포함 (분류, 회귀)

비지도학습: label 없음 (클러스터링 등)

12.3 분류/회귀/클러스터링

분류: 이메일 스팸 여부 판별

회귀: 주택 가격 예측

클러스터링: 고객 세분화

12.4 과적합 vs 일반화

from sklearn.linear_model import Ridge
model = Ridge(alpha=1.0)
