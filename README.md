# 자바 스크립트 알고리즘

### 팁

- ...arr : arr의 배열을 전개한다(ex: [1,2,3] => 1,2,3)
- arr.reduce((a,b) => a+b,0) : arr 배열의 총 합 반환
- arr.splice(i,1) : arr배열에서 i번째 요소를 1개 삭제
- str.replace(/A/g,"#") : str문자열에서 A를 모두 #으로 바꿔서 반환
- str.split("ex") : str문자열에서 "ex"를 기준으로 배열로 분리시켜서 반환 (마지막에 "" 추가됨)
- str.toUpperCase() : str문자를 대문자로 변경
- str.charCodeAt() : str의 아스키 코드 반환

### Math [링크](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Math)

- Math.ceil(n) : n의 소수점 자리를 올림 수 반환
- Math.abs(n) : n의 절댓값 반환
- Math.round(n) : n을 반올림 수 반환
- Math.sqrt(n) : n의 제곱근 반환
- Math.min(...arr) : arr의 최솟값 반환

### 시스템 최댓값 최솟값

- Number.MAX_SAFE_INTEGER : 시스템 최댓값
- Number.MIN_SAFE_INTEGER : 시스템 최솟값
