# Github_Test
# Test
## **호**
### *날*
#### '두'
##### ~~짱~~
![젖닌두](https://github.com/user-attachments/assets/7d45c35d-a9f5-4fd6-8a49-228d35a641b5)
``` bash
asiudhiwushdjfi
olsaijfoijoij
aosiuhdoiashd
```
```
pip install matplotlib
sudo apt update
sudo apt upgrade
```
# 🐍 Python 이론 학습 정리

> Python 기초부터 고급 이론까지 이 README에서 이론 내용을 정리합니다.

---

## 📖 목차

1. [1. 파이썬이란?](#1-파이썬이란)
2. [2. 변수와 자료형](#2-변수와-자료형)
3. [3. 연산자](#3-연산자)
4. [4. 조건문](#4-조건문)
5. [5. 반복문](#5-반복문)
6. [6. 함수](#6-함수)
7. [7. 자료구조 (리스트, 튜플, 딕셔너리, 집합)](#7-자료구조-리스트-튜플-딕셔너리-집합)
8. [8. 클래스와 객체지향](#8-클래스와-객체지향)
9. [9. 예외 처리](#9-예외-처리)
10. [10. 모듈과 패키지](#10-모듈과-패키지)
11. [11. 파일 입출력](#11-파일-입출력)
12. [12. 파이썬 주요 표준 라이브러리](#12-파이썬-주요-표준-라이브러리)

---

## 1. 파이썬이란?

- 파이썬은 1991년 귀도 반 로섬이 개발한 고급 프로그래밍 언어입니다.
- 간결하고 가독성이 좋아 초보자에게 적합합니다.
- 인터프리터 언어이며 다양한 분야(웹, 데이터, AI 등)에서 사용됩니다.

---

## 2. 변수와 자료형

- 변수는 데이터를 저장하는 공간이며, 동적 타이핑을 지원합니다.
- 주요 자료형: `int`, `float`, `str`, `bool`, `None`

```python
x = 10        # int
name = "Tom"  # str
3. 연산자
산술 연산자: +, -, *, /, //, %, **

비교 연산자: ==, !=, >, <, >=, <=

논리 연산자: and, or, not

4. 조건문
if, elif, else를 사용하여 조건에 따라 분기합니다.

python
복사
편집
if x > 0:
    print("양수")
elif x == 0:
    print("0")
else:
    print("음수")
5. 반복문
for와 while로 반복 수행

python
복사
편집
for i in range(5):
    print(i)
6. 함수
def 키워드를 사용하여 함수 정의

python
복사
편집
def greet(name):
    return f"Hello, {name}"
7. 자료구조 (리스트, 튜플, 딕셔너리, 집합)
리스트: 변경 가능, 순서 O

튜플: 변경 불가, 순서 O

딕셔너리: 키-값 쌍

집합: 중복 X, 순서 X

python
복사
편집
lst = [1, 2, 3]
tpl = (1, 2)
dct = {"name": "Tom"}
st = {1, 2, 2, 3}
8. 클래스와 객체지향
파이썬은 객체지향 언어

클래스와 인스턴스를 통해 재사용성과 구조화 강화

python
복사
편집
class Person:
    def __init__(self, name):
        self.name = name
9. 예외 처리
try, except, finally 사용

python
복사
편집
try:
    1 / 0
except ZeroDivisionError:
    print("0으로 나눌 수 없음")
10. 모듈과 패키지
모듈: .py 파일 하나

패키지: 모듈들의 폴더 구조 (__init__.py 포함)

11. 파일 입출력
python
복사
편집
with open("file.txt", "r") as f:
    data = f.read()
12. 파이썬 주요 표준 라이브러리
os: 파일 시스템

sys: 파이썬 시스템 설정

datetime: 날짜/시간

math: 수학 함수

random: 난수 생성
