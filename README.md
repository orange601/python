## 파이썬준비하기

### 1. 사용

#### 1.1 다운로드
* https://www.python.org/downloads/windows/  
* “Windows x86-64 executable installer(Windows x86-64 실행 가능 설치 패키지 프로그램) 다운로드

#### 1.2 설치
* Add Python 3.9 to Path 체크 후 Install Now  
> Path를 자동으로 설정

* 윈도우 재부팅 후 Path 설정됨

* 설치 확인
> CMD - python입력

### 2. 기본문법  

#### 2.1 들여쓰기  

* 문법적인 강제사항

* 코드 블럭을 구성하기 위해 if, for, class, def 등등 을 작성하면서 나오는 : 다음 아랫줄은 들여쓰기를 해야한다.

* 블록 내에서는 들여쓰기 칸 수가 같아야 한다. 공백과 탭을 섞어쓰면 안된다.

```python
for i in range(10):
     print(i)
     print(i + 1)
```

#### 2.2 주석

```python
#이건주석입니다.
if i > 0:
     print("OK")
```

#### 2.3 세미콜론

* 필수사항X

* 여러구문을 같은 줄에 쓸때 사용하기도 한다.

```python
print('Hello'); print('world')
```

#### 2.4 import

* 라이브러리 전체 import

```python
import math
math.sqrt(81) #제곱근
```

* 라이브러리 함수만 import

```python
from sqrt import math
sqrt(81)
```

* 함수 별칭 사용이 가능하다

```python
from sqrt import math as dou
dou(81)
```

#### 2.5 데이터타입

##### 2.5.1 스칼라 데이터 타입

* int 
```python
>>> int(3.5)
3
>>> int(-3.5)
-3
>>> int(True)
1
>>> int(False)
0
>>> int("500")
500
>>> int("1000",3)
27
```
