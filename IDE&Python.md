---
marp: true
---

# 2023 메이크@정보보안 멘토링

## IDE & Python

---

<style scoped>
section {
  font-size: 1.7rem;
}
</style>

# IDE란?

IDE(Integrated Development Environment)란 개발을 위한 통합 개발 환경을 뜻합니다.
IDE는 코드 작성, 디버깅, 테스트 등의 개발 과정에서 필요한 모든 기능을 제공하여 개발 생산성을 높입니다.

---

<style scoped>
section {
  font-size: 1.38rem;
}
</style>

### 1. Visual Studio Code

경량형 오픈소스 코드 편집기, 다양한 언어 지원, 디버깅, Git 통합 등 기능 제공

### 2. IntelliJ IDEA

자바 기반 통합 개발 환경, 다양한 언어 지원, 코드 스니펫, 디버깅, 테스트 등 기능 제공

### 3. XCode

애플의 iOS, macOS 등 애플 플랫폼 개발을 위한 IDE, Swift, Objective-C 등 다양한 언어 지원, 시뮬레이터 등 제공

### 4. Android Studio

구글의 안드로이드 앱 개발을 위한 IDE, Java, Kotlin 등 다양한 언어 지원, 시뮬레이터 등 제공

### 5. Vim

터미널 기반 텍스트 에디터, 유닉스 계열 운영체제에서 많이 사용, 확장성 높은 설정, 명령어 기반 사용 등 특징 있음.

---

# Python

Python은 쉽고 간결한 문법으로 인기 있는 프로그래밍 언어입니다.

---

## 변수

Python에서 변수를 정의할 때는 변수 이름과 값을 할당 연산자 `=`를 사용합니다.

```python
x = 10
y = "Hello, World!"
```

---

## 조건문

Python에서 조건문은 `if`, `elif`, `else` 키워드를 사용합니다.

```python
x = 10

if x > 0:
    print("x는 양수입니다!")
elif x < 0:
    print("x는 음수입니다!")
else:
    print("x는 0입니다!")
```

---

## 반복문

Python에서 반복문은 `for`와 `while` 두 가지 방법으로 구현할 수 있습니다.

```python
for i in range(5):
    print(i)
```

```python
while True:
    print("while loop!")
```

---

## 함수

Python에서 함수는 `def` 키워드를 사용하여 정의합니다.

```python
def add(x, y):
    return x + y

result = add(3, 5)
print(result)
```

위 코드에서는 add() 함수를 정의하고, add(3, 5)를 호출하여 함수를 실행한 후 결과값을 출력합니다.

---

## 리스트

Python에서 리스트는 여러 값을 하나의 변수에 저장할 수 있는 데이터 타입입니다.

```python
fruits = ["apple", "banana", "cherry"]
print(fruits)
```

위 코드에서는 fruits 변수에 세 개의 과일 이름이 포함된 리스트를 할당하고, print() 함수를 사용하여 리스트를 출력합니다. 출력된 결과는 `["apple", "banana", "cherry"]`와 같습니다.

---

# 파이썬 문제풀이

---

## 백준(Baekjoon Online Judge)

국내 최대 규모의 알고리즘 문제 사이트. 파이썬 뿐만 아니라 다양한 언어를 지원하며, 실력에 따라 난이도를 선택할 수 있다.

## 프로그래머스(Programmers)

코딩 테스트 연습을 위한 사이트. 기업 코딩 테스트 문제를 비롯해 다양한 난이도와 주제의 문제를 제공하며, 파이썬 외에도 다양한 언어를 지원한다.

---

# 프로그래머스 가입하기
