---
layout: post
current: post
cover:  False
# cover:  assets/built/images/python-logo.png
navigation: True
title: JavaScript (1) - Strings 
date: 2021-01-17 03:33:00
tags: [web]
class: post-template
subclass: 'post tag-web'
author: houngkyung-kim
---
# 자바스크립트 String

오늘은 자바스크립트에서 String에 대해 살펴봅시다.
자바스크립트에서 string은 따옴표나 쌍따옴표를 통해 표현합니다.

~~~javascript
"이것은 스트링입니다";
'이것도 스트링이죠';
~~~

두 가지 경우 정확히 동일한 표현입니다. 하지만 한 가지 주의해야할 것은 ' 로 시작했으면 ' 러, "로 시작했으면 "로 끝나야 합니다. 

~~~javascript
'이건 잘못된 표현입니다.";
~~~

다음으로 스트링에서 쓸 수 있는 기본적인 method을 살펴봅시다.

* .length 
이 method는 스트링의 길이를 반환합니다.

~~~javascript
"apple".length;
// 5
~~~

* .include(searchString)

이 method는 String에 특정 String이 포함되어 있는지 확인합니다.

~~~javascript
"apple".include("ppl"); // true
"apple".include("ppa"); // false
~~~

* .toUpperCase()

이 method는 영문 소문자 String을 대문자로 변환합니다.

~~~javascript
"Banana".toUpperCase; // "BANANA"
~~~

* .toLowerCase()

이 method는 영문 대문자 String을 소문자로 변환합니다.

~~~javascript
"Pineapple".toLowerCase(); // "pineapple"
~~~

##### 참고
일반적으로 method는 함수이기 때문에 선언 시 괄호 ()가 뒤에 붙는다. 다만 length의 경우는 괄호가 없는데 내재적으로 이미 포함된 것이다.


##### 기타

string.startWith(searchString)
string.endsWith(searchString)
string.trim()
