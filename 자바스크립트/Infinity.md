## 1️⃣ Infinity / -Infinity
- Infinity: 자바스크립트에서 무한대(∞) 를 의미하는 전역 상수
- -Infinity: 음의 무한대
- 어떤 수와 비교하더라도
  1. Infinity는 항상 가장 큼
  2. -Infinity는 항상 가장 작음

### 🔹 기본 문법
```javascript
Infinity
-Infinity
```

### 🔹 사용 예시
```javascript
console.log(Infinity);      // Infinity
console.log(-Infinity);     // -Infinity

console.log(10 < Infinity);   // true
console.log(-10 > -Infinity); // true
```

### 🔹 Infinity가 나오는 경우
```javascript
console.log(1 / 0);   // Infinity
console.log(-1 / 0);  // -Infinity
```
