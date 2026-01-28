## parseInt(string, radix)
- 문자열을 정수(Number) 로 변환하는 메서드
- 문자열을 숫자로 해석할 때 어떤 진법으로 읽을지 명시적으로 지정할 수 있다.

### 🔹 기본 문법
```javascript
parseInt(string, radix)
```
- string : 숫자로 변환할 문자열
- radix : 문자열의 진법

### 🔹 사용 예시
```javascript
const binary = "1010";

console.log(parseInt(binary, 2));  // 10
console.log(parseInt("111", 2));   // 7
console.log(parseInt("a", 16));    // 10
```

### 🔹 특징
- 문자열이 숫자로 시작하지 않으면 NaN
```javascript
parseInt("abc", 2); // NaN
```
