# Study-Babel

## Needs Plug-in
~~~javascript
/**
 * 바벨에서 트랜스파일링을 시도한 결과에 Array.from 생성(구버전의 브라우저에서 인식 불능)
 * */
str => [...str]
~~~

## Needs Polyfill
~~~javascript
Array.from()
~~~
