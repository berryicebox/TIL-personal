## 1️⃣ Number.prototype.toString()
- 숫자를 문자열로 변환하는 메서드
- toString()은 숫자를 문자열로 변환하며 인자로 진법(radix) 을 전달할 수 있다.

### 🔹 기본 문법
```
number.toString(radix)
```
- radix : 변환할 진법 (2 ~ 36)

### 🔹 사용 예시
```
const num = 10;

console.log(num.toString(2));   // "1010"
console.log(num.toString(10));  // "10"
console.log(num.toString(16));  // "a"
```

### 🔹 특징
- 반환값은 문자열(String) 이다
- 음수도 변환 가능
```
(-5).toString(2); // "-101"
```
