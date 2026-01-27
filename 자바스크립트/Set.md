## 1️⃣ Set (집합)
- **중복되지 않는 유일한 값**들의 모음을 관리하는 자료구조
- 배열보다 값의 존재 여부를 확인하는 속도가 매우 빠르다.

### 🔹 기본 문법
```JavaScript
const mySet = new Set();
mySet.add(value);
```

### 🔹 사용 예시
```JavaScript
const s = new Set();
s.add(10);
s.add(10); // 이미 10이 있어 추가되지 않음
s.add(20);

console.log(s); // Set { 10, 20 }
```

## 2️⃣ Set.prototype.has()
- Set 객체 안에 특정 값이 존재하는지 확인하여 **불리언(true/false)을 반환**한다.

### 🔹 기본 문법
```JavaScript
set.has(value)
```

### 🔹 사용 예시
```JavaScript
const resultContainer = new Set([10, 20, 30]);

console.log(resultContainer.has(20)); // true
console.log(resultContainer.has(99)); // false
```
