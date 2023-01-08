# 자바 스크립트 알고리즘

### 팁

- parseInt(f) : f를 Int로 형변환
- isNaN(n) : n 문자가 숫자인지 판별
- new Set() : set 자료구조 초기화
- new Map() : map 자료구조 초기화

- ...arr : arr의 배열을 전개한다(ex: [1,2,3] => 1,2,3)
- arr.reduce((a,b) => a+b,0) : arr 배열의 총 합 반환
- arr.splice(i,1) : arr배열에서 i번째 요소를 1개 삭제
- arr.reverse() : 배열의 순서를 뒤집어서 반환
- arr.join('') : 배열의 문자 요소들 사이에 ""를 조인 시켜서 반환
- arr.sort() : 배열을 정렬
- arr.sort((a,b) => b - a) : 배열을 내림차순으로 정렬
- arr.slice(a,b) : 배열의 a번부터 b-1번까지 반환
- arr.forEach(x => {}) : 배열의 요소를 하나하나를 x로 치환하여 반복문 실행

- map.set(k,i) : map 자료구조에 { k : i } 저장 or 추가 or 변경
- map.get(k) : map 자료구조에서 k의 value 반환
- map.has(k) : map 자료구조에서 k, key값이 있는지 확인

- str.replace(/A/g,"#") : str문자열에서 A를 모두 #으로 바꿔서 반환
- str.split("ex") : str문자열에서 "ex"를 기준으로 배열로 분리시켜서 반환 (마지막에 "" 추가됨)
- str.toUpperCase() : str문자를 대문자로 변경
- str.toLowerCase() : str문자를 소문자로 변경
- str.charCodeAt() : str의 아스키 코드 반환
- String.fromCharCode(char) : 아스키 코드인 char를 문자로 반환
- str.substring(n,m) : 문자열 n번부터 m-1번까지의 문자열로 반환
- str.substr(n,2) : 문자열 n번부터 n번 다음 2번째까지의 문자열로 반환
- str.indexOf(s) : str에서 s의 첫번째 인덱스 값 반환 없으면 -1 반환
- str.replace(/[^a-z]/g,'') : 알파벳 소문자가 아닌 문자는 다 ""로 치환
- str.replace(/[^a-z]/g,'') : 알파벳이 아닌 문자는 다 ""로 치환

- Array.from({length:n},()=>1) : 1이 n 길이만큼 들어가 있는 리스트 반환
- Array.from({length: 5}, (undefined, i) => i) === [0,1,2,3,4]
- Array.from(set) : set을 배열로 반환

### Math [링크](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Math)

- Math.ceil(n) : n의 소수점 자리를 올림 수 반환
- Math.abs(n) : n의 절댓값 반환
- Math.round(n) : n을 반올림 수 반환
- Math.sqrt(n) : n의 제곱근 반환
- Math.min(...arr) : arr의 최솟값 반환

### 시스템 최댓값 최솟값

- Number.MAX_SAFE_INTEGER : 시스템 최댓값
- Number.MIN_SAFE_INTEGER : 시스템 최솟값
