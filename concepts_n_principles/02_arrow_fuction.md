# Arrow function
## 함수 표현식보다 단순하고 간결한 문법으로 함수를 만들 수 있는 방법, (함수 선언문이 아닌 함수 표현식을 간단하게 하는거임!)
``` javascript
let sum = (a, b) => { 
  let result = a + b;
  return result; 
};

let sum = function (a, b) {
    let result = a + b;
  return result; 
}
```