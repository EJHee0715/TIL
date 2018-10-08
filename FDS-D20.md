* FDS Day-20

문제 잘 푸는법!

손으로 문제를 먼저 풀어보거나, 생각 해보기

문제 속에서 어떤걸 원하는지 알아보고 거기에 맞는 기술 쓰기

```js

function stdDev(arr) {
  // arr의 평균 구하기
  const sum = arr.reduce((acc, item) => acc + item, 0)
  const mean = sum / arr.length
  console.log(`mean: ${mean}`)
  // 각 요소에 대한 편차 구하기 (편차 = 값 - 평균)
  const ps = arr.map(item => item - mean)
  console.log(`ps: ${ps}`)
  // 각 요소에 대해 제곱하기
  const powers = ps.map(item => item ** 2)
  // 위 제곱한 배열의 평균 구하기
  const vv = powers.reduce((acc, item) => acc + item, 0) / powers.length
  // 루트 씌우기
  return Math.sqrt(vv)
}

stdDev([1,2,3,4,5])

```
```js
function max(arr) {
//reduce를 쓸 때
// '누적값의 역활'이 무엇인지를 잘 정하는 것이 중요하다.

// 누적값: 지금까지 봤던 숫자 중에 제일 큰 수

arr.reduce((acc, item) => {
  // 안에 들어있는 함수의 반환값이, 다음 단계의 누적값이 된다.
  if(acc > item) {
    return acc
  }else {
    return item
  }
}, 0)
}

max([1,2,3,4,5]);



```