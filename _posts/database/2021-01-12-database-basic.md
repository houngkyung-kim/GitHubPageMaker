---
layout: post
current: post
cover: False
# cover:  assets/built/images/python-logo.png
navigation: True
title: Database - Mongoose 기본
date: 2021-01-14 -07:00:00
tags: [database]
class: post-template
subclass: "post tag-database"
author: houngkyung-kim
---

몽구스 Mongoose   
===
<br>
Mongoose는 node.js 환경에서 Schema를 활용해 쉽고 간편하게 몽고DB 데이터를 객체로 모델링하는 솔루션입니다. 원래 몽고DB는 noSQL이기 때문에 데이터의 유효성 검사나 캐스팅 및 비즈니스 로직을 작성하는 것이 어려웠습니다. 하지만 Schema를 활용하기 때문에 몽구스는 몽고DB를 더욱 편리하게 쓸 수 있게 하는 도와줍니다.
<br>

### 스키마 Schema

스키마는
   
### 메소드

- 조회: find, findOne, findById
- 삭제 및 수정: findOneAndRemove, findOneAndUpdate, findByIdAndRemove, findByIdAndUpdate

### populate

ObjectId를 객체로 바꿔주는 기능

### Promise

- async / await
- save

### 쿼리 빌더

- where
- equals, ne
- exists
- gt, lt, gte, lte
- in, nin, all
- and, or, nor
- size, mode, slice
- within, box, circle, geometry, near, intersects, maxDistance
- distinct
- regex
- select
- skip, limit
- sort
- find, findOne, findOneAndRemove, findOneAndUpdate

---

### 참고

[Mongoose 공식 웹사이트](https://mongoosejs.com/)
