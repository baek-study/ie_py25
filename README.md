# 파이썬 프로그래밍 입문 - 수 10:00 

수강자가 핵심 내용을 쉽게 알고, 실행 시켜 보는 페이지 입니다. <br> 



| 주차 | 수업내용 | 과제 |
| --- | --- | --- |
| 제1주 | 교과목 소개, 파이썬 개발환경 설정 |   | 
| 제2주 | 자료형1 - 변수와 자료형 |   | 
| 제3주 | 자료형2 - 수식과 연산자 |   | 
| 제4주 | 자료형3 - 문자열 | 1차 과제 마감    | 
| 제5주 | 자료형4 - 리스트 |  | 
| 제6주 | 제어문1 - 조건문(if) |  | 
| 제7주 | 제어문2 - 다중 조건문 |2차 과제 마감 | 
| 제8주 | <p>$\bf{\large{\color{#6580DD}중간시험\ (이론시험)\}}$</p> |  | 
| 제9주 | 제어문3 - 반복문(for)  |  | 
| 제10주 | 제어문4 - 반복문(while), 보조제어문  |  | 
| 제11주 | 함수1 - 함수 정의와 함수 호출 |3차 과제 마감  | 
| 제12주 | 함수2 - 함수 변수와 표준 모듈  |  | 
| 제13주 | 중급1 - 딕셔너리  | | 
| 제14주 | 중급2 - 파일 입출력과 예외처리 |4차 과제 마감  | 
| 제15주 | <p>$\bf{\large{\color{#6580DD}기말시험\ (이론시험)\}}$</p> | | 
<hr size = "10px", width ="500px">

<br>

## [2주차 강의&nbsp;-&nbsp;변수와 표준입력함수]()

### [변수 개념]()
<ul>
  <li>변수 : 데이터를 저장하는 공간 </li>
  <li>이름 규칙 : 알파벳(a~z, A~Z), 숫자(0~9), 밑줄(_)로 구성 </li>
  <li> 시작시 숫자 안됨, 이름내 공백 안됨, 예약어 안됨 </li>
</ul>

### [파이썬에서 변수]()
<ul>
  <li>변수이름 = 값 &ensp; </li>
  <li> 왼쪽은 항상 변수이름 </li>

  <li> x=1; y=3.14; z='hi'; b=True; </li>
</ul>

### [자료형(Data Type)](https://github.com/baek-study/python_mon/blob/main/source/week2_mju_mon.ipynb)
<ul>
  <li> 정수/int : print(123); print(123_456);</li>
  <li>  실수/float : print(3.14);print(3.14e12); </li>
  <li>  문자열/str: print("hello");print('100'+'200');</li>
  <li>  논리/bool: print(True); print(False);</li>
  <li>  자료형 확인 type() : type(1234) </li>
  <li>  정수로 변환int() : int("100")   </li>
</ul>

### [표준 입력함수 input()]()
<ul>
   <li>키보드를 통해 입력한 값을 하나의 '문자열' 형태로 반환</li>
    <li> msg = input('[안내메시지] 나이는?')&ensp;#문자열로 반환</li>
    <li> age = int(msg)&ensp;#정수변환</li>
    <li> fage = float(msg)&ensp;#실수변환</li>
</ul>

### [표준출력함수 print()]()
<ul>
    <li> 문자열 : print('hello') </li>
    <li> 다양한자료형 : print(1004);print(3.14);</li>
    <li> 여러개 값: print(2, '+', 3)</li>
    <li> 출력제어문자: print('탭키\t줄바꿈\n')</li>
  </li>
</ul>

<br>

<br>

## [1주차]()
<ul>
  <li>
    파이썬 소개 - 인터프리터(Interpreter) 언어, 객체지향 언어     
  </li>
  <li>
    파이썬 통합 개발 환경 - IDLE, Colab, Jupyter Notebook 등    
  </li>
</ul>
