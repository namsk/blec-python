# Quiz 03

### Q1

* 파일명은 quiz03_1.py로 저장합니다.
* 키보드로 정수를 입력 받습니다.
* 만일 입력받은 값이 정수 형태가 아니면 "정수가 아닙니다"를 출력하고 다시 입력을 받습니다.
* 만일 입력받은 값이 정수라면 1부터 해당 입력값까지의 정수 중에서 3의 배수만 합산하여 출력합니다.

```
(결과)

수를 입력하세요:abc
정수가 아닙니다. 다시 입력하세요
수를 입력하세요:100
1부터 100까지 3의 배수의 합 = 1683
```

### Q2

* 파일명은 quiz03_2.py로 합니다.
* 다음과 같이 리스트가 선언되어 있다고 가정합니다.

```
lst = [1, 3.14, 'python', 7, 89.1, 3]
```

* 해당 리스트에서 정수형, 실수형 데이터만 추출하여 lst_cleaned 라는 이름의 리스트에 담아 봅시다.

### Q3

* 파일명은 quiz03_3.py로 합니다.
* 메서드를 하나 만들고, 임의의 개수의 인수를 받아서 해당 인수의 합, 최대값, 최소값, 평균값을 한꺼번에 반환하는 함수를 만들어 봅시다.

```
(함수 사용 예)
total, maxval, minval, avg = summary(80, 75, 90, 95, 85)
print(total, maxval, minval, avg)

(결과)
425 95 75 85.0
```

### Q4

* 파일명은 quiz03_4.py로 합니다.
* 다음과 같이 문자열이 설정되어 있습니다.
```
s = """We encourage everyone to contribute to Python. 
If you still have questions after reviewing the material
in this guide, then the Python Mentors 
group is available to help guide new contributors through the process."""
```

* 문자열에서 ',', '.', '\n'을 제거하고 모두 대문자로 변경합니다.
* 변경된 소스를 기반으로 단어의 빈도수를 체크해 봅시다.

```
(실행 결과 예시)
WE: 1
ENCOURAGE: 1
EVERYONE: 1
TO: 3
CONTRIBUTE: 1
PYTHON: 2
IF: 1
...
```