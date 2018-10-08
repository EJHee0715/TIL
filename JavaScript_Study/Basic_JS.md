# 2018-10-08 월요일

`JavaScript Basic` `Variable` `Value` `Identifier`

자바스크립트는 느슨한 타입 체크 언어이다. 엄격한 타입 체크 언어인 C언어는 변수를 선언할 때 변수에 저장할 데이터에 종류에 따라 예약어를 이용해서 변수 데이터의 타입을 지정 해야 한다.

##### 변수 (Variable)

변수는 ES2015 이전에는 Var를 사용했지만 ES20215가 도입된 이후에는 Const, Let을 사용한다.

 - 변수(Variable)는 값(Value)을 지정하고 그 값을 참조 하기 위해 사용한다.
 - 변수(Variable)은 한번 쓰리고 버리는 값이 아닌 유지(캐싱)해서 사용할 값을 담아 사용한다.
 - 변수를 선언 할 때는 어떤식으로 사용하는지에 대한 의도를 나타내는 이름으로 작성하는게 코드 가독성에 좋다.

###### Const

  - Const는 기본적으로 "값을 재대입 할 수 없는" 변수이며, 변수의 값을 고정으로 저장 할 때에는 COnst를 사용한다.

###### Let

  - Let은 "값을 재대입 할 수 있는" 변수이며, 이미 값이 들어가 있는 변수에 재대입을 할 수 있다.

###### Const 와 Let

  - Const, Let 둘 중에 하나를 선택할 때 무엇을 선택할지 모르겠다면, 그 변수에 값이 재대입이 필요 한지 아닌지를 생각하면 되며, 좋은 습관은 주로 Const를 사용하는게 더 좋다.

  - Let 같은 경우는 정말 재대입이 필요로 할 때만 사용하는게 좋다.

---

##### 식별자(Identifier) 

  - 식별자는 Const, Let을 선언 후 앞에 붙이는 이름을 식별자라고 한다.
  - 프로그래밍 언어에서 식별자는 어떤 개체를 유일하게 식별학기 위해서 사용한다.

  - 식별자 규칙 

    - 숫자, 알파벳, 달러 문자($), 언더스코프 (_)가 포함될 수 있다.
    - 단 숫자는 먼저 시작할 수 없다.
    - 예약어는 숫자가 될 수 없다. (Var, Const, Let)
    - 한글도 식별자에 포함은 되지만, 가급적 사용하지 않는게 좋다.

  ```js
    const foo; // O
    const _bar123; // O
    const $; // O - jQuery가 이 식별자를 사용합니다.
    const 7seven; // X
    const const; // X - 예약어는 식별자가 될 수 없습니다.

  ```

###### Camel Case 

  - 식별자에 이름을 지을 땐 관례가 있다. 이 관례를 Camel Casse 라고 한다.

  - 식별자에 들어가는 각 단어의 첫글자를 대문자로 써주는 방식

  `EX) const fastCampus // Camel Case`

###### Snake Cases

  - Snake Case는 Camel Case와 달리 모든 글씨를 소문자로 써도 되지만 중간에 _ 언더바를 넣는다.

  `EX) const fast_campus // Snake Case`

---

##### 값 (Value)


