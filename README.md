# Javascript-study
- 드림코딩 엘리님의 자바스크립트 강의 듣고 정리하고 반복하기 !!

- 2021-09-11 : 자바스크립트 2. 콘솔에 출력, script async 와 defer의 차이점<br>
<a href="https://www.youtube.com/watch?v=tJieVCgGzhs&list=PLv2d7VI9OotTVOL4QmPfvJWPJvkmv6h-2&index=2">자바스크립트 2. 콘솔에 출력, script async 와 defer의 차이점</a>

- async : Type boolean , default value = true
- parsing -> <script async> [fetching js ... Command(down)] -> parsing -> success download js ->  parsing stop [executing js ] -> parsing
- defer : <script defer> -> [fetching js ... Command(down)] -> all parsing -> executing js
- fetching js : js 파일을 가져오다 
- executing js : js 파일을 실행하다
  
- 'use strict'
자바스크립트 엔진이 조금 더 효율적으로 더 빠르고 분석하고 실행하는데 있어서 조금 더 나은 성능 개선을 기대볼 수 있음!<br>
