# day02
JavaScript 수업 내용 정리

## 03. 요소가져오기(접근하기)

### HTML 요소에 접근하기(해당 요소객체 가져오기)
        1) 아이디로 접근하기
        2) 태그명으로 접근하기
        3) name속성으로 접근하기
        4) 클래스명을으로 접근하기
***

## 04. 변수와자료형

### 변수와 자료형

#### * var, let, const의 차이점

        1) 변수 선언 방법 : 중복선언과 재할당
        2) scope(사용가능 범위)

#### * 변수 선언 위치에 따른 전역변수/ 지역변수

#### 자료형

##### 자바스크립트의 자료형

        * string(문자열)
        * number(숫자)
        * boolean(논리값)
        * object(객체)
        * function(함수)
        * undefined(초기화가 아직 진행되지 않은 변수)
        
## 05. 문자열과 숫자
### 문자열과 숫자
#### * 문자열 관련 메소드
        1) 문자열의 길이 : length
        2) 대문자/소문자 : toUpperCase()/toLowerCase()
        3) 문자열에서 특정 인덱스에 위치하는 유니코드 단일문자 반환 : charAt()
        4) indexof()와 lastIndexof()
        5) substring()
        6) split()

#### * 숫자 관련 메소드
1. Math 내장 객체(Math.메소드명())   <br>
        1) 절대값 : Math.abs()      <br>
        2) 랜덤값 : Math.random()   <br>
        3) 반올림 : Math.round()    <br>
        4) 버림 : Math.ceil()       <br>
        5) 올림 : Math.floor()      <br>
        6) 제곱급 : Math.sqrt()     <br>

2. 다른 자료형끼리의 산술연산               <br>
        1) 덧셈 연산                       <br>
        2) 덧셈을 제외한 나머지 산술연산     <br>
        3) 강제형변환(문자열 => 숫자)       <br>
        ① Number(문자열)                   <br>
        ② parseInt(문자열)                 <br>
        ③ parseFloat(문자열)               <br>
