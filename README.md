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

* 코딩을 할 때, 가독성을 위해 들여쓰기를 합니다. 하지만 파이썬은 문법적인 강제사항입니다.  

* 코드 블럭을 구성하기 위해 if, for, class, def 등등 을 작성하면서 나오는 : 다음 아랫줄은 들여쓰기를 해야합니다.  

* 들여쓰기의 방법은 한칸, 두칸, 4칸, 탭 등 여러가지 방식이 있습니다.  

* 중요한 것은 같은 블록 내에서는 들여쓰기 칸 수가 같아야 합니다. 공백과 탭을 섞어쓰면 안됩니다.  

```python
for i in range(10):
     print(i)
     print(i + 1)
```
