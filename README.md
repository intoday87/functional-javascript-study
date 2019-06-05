# functional-javascript-study

## first class function
- first class
  값으로 사용이 가능한
  - 변수에 저장이 가능하다
  - 매개 변수로 넘길 수 있다
  - 함수에서 리턴할 수 있다
- 더 나아가 first class function란?
  - 런타임에 아무때나 선언할 수 있다
    `var f = active ? function fn() { return 1; } : void 0;`
  - 익명으로 선언할 수 있다
    `(() => { console.log('logging...') })();`
  - 익명으로 선언한 함수를 매개변수로(값으로 취급이 가능하단) 넘길 수 있다
    `f((v) => v + 1);`
