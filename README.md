# day02
JavaScript 수업 내용 정리

## 03. 요소가져오기(접근하기)

### 1. 데이터를 출력하는 기본 구문
    1) window.alert('알림창에 출력할 문구');
    2) window.console.log('콘솔창에 출력할 문구');
    3) document.write('화면에 출력할 문구');
    4) 선택한요소.innerHTML/innerText = '해당 요소에 출력할 문구';

### 2. 데이터를 입력받는 기본 구문(변수에 대입 가능)
    1) 변수 = window.confirm("질문내용");
    2) 변수 = window.prompt("질문내용");
    3) 변수 = 선택한요소.속성;(id, className, innerHTML, innerText, ...);
    4) 변수 = 선택한input요소.value;
