# JavaScript


### Javascript는 사용자와 상호작용하는 언어이다

- 웹브라우저는 한번 화면에 출력되면 자기 자신을 바꿀 수 없다.
- 하지만 버튼을 클릭하면 body태그에 style 속성이 추가되면서 디자인을 바꿔준다
- Javascript가 html을 제어하는 언어이다
(javascript는 html 위에서 시작)

### JavaScript 동적이다.
<script> // JavaScript를 쓸 것이다 선전포고
<br> document.write(1+1) -> 2가 나옴
<br></script>

### event: 웹브라우저에서 일어나는 일

### console: 파일을 만들지 않고도 javascript 코드를 즉석에서 실행할 수 있다

console에서 실행시키는 JS는 웹페이지를 대상으로 실행되게 된다.

### JavaScript DataType

- Boolean
- Null
- Undefined
- Number
- String
- Symbol

### Function

- 장점:
    - 함수의 코드 1개만 수정해도 모든 곳에 적용
    - 여러 줄의 코드 -> 함수호출 1코드(웹페이지 크기가 극단적으로 줄어듬)
    - 똑같은 로직을 사용한다는 점을 명확하게 보여줌
    - 함수 이름으로 코드의 정체를 분명하게 이해할 수 있음
- 구성요소
    - parameter(매개변수): function 함수이름(a, b) {} 
    - argument(인자): 함수이름(2, 3) 
    - return: 리턴 값으로 다양한 문맥에서 활용 가능

### Object(객체)
- 이름이 있는 정리정돈 상자(정보를 순서 없이 넣는 것)

- 용어정리
    - 메소드: 객체에 속해있는 함수
    - 객체에 소속된 변수(key): 프로퍼티(property)

- 객체 문법
    - 배열은 [](대괄호), 객체는 {}(중괄호)
    - 객체에 데이터 저장하는 법(like 딕셔너리): {"key" : "value",}
    - 객체를 호출할 때는 key로: for (var key in 객체) { document.write(key + " : " +객체[key]}
    - 객체 내부의 함수(메소드) 호출 시, 객체 이름이 아닌 this로 호출
 
