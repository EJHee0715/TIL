# FDS Day-16

`JavaScript` `Data Type` `원시타입(Primitive Data Type)` `기초`

#### Data Type

데이터 타입은 프로그래밍 언어에서 사용 할 수 있는 값의 종류를 말한다.

자바스크립트는 모든 값의 데이터 타입이 있으며, ECMAScript 표준은 7개의 데이터를 제공한다.

`자바스크립트에서 제공하는 데이터 타입은 크게 원시타입(Primitive Data Type), 객체 타입 (Object Type)으로 구분 할 수 있다.`

---

##### 원시타입 (Primitive Data Type)

원시 타입의 종류

  - number
  - string
  - boolean
  - null
  - nudefiend
  - symbol (ES6에서 추가 됨)

` 원시 타입은 변경이 불가능한 값 (immutable value)이며 pass-by-value(값에 의한 전달) 이다. 또한 이들 값은 메모리의 스택 영역(Stack Segment)에 고정된 메모리 영역을 점유하고 저장된다.`

---

##### number

C언어는 다양한 숫자 자료형이 있지만 자바스크립트는 하나의 숫자 자료형만 있다.

추가적으로 세가지 의미있는 기호적인 값들도 표현 할 수 있다. Infinity, -Infinity, NaN (Not a Number)

```js
var x = 10;    // 정수
var y = 10.12; // 실수
var z = -20;   // 음의 정수

var foo = 42 / -0;
console.log(foo);        // -Infinity
console.log(typeof foo); // number

var bar = 1 * 'string';
console.log(bar);        // NaN
console.log(typeof bar); // number
```

---

##### Boolean

Boolean 타입은 논리적 참, 거짓을 나타내는 true, false 뿐이다.

```js
var foo = true;
var bar = false;

// typeof를 통해 foo 와 bar의 타입을 나타내는 문자열

console.log(typeof foo); // true
console.log(typeof bar); // false
```

비어있는 문자열과 null, undefiend, 숫자 0은 false로 나타난다.

---