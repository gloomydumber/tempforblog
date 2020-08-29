---
layout: post
title: "JavaScript"
date: 2020-08-20 10:00:00
categories: WEB-FRONTEND
permalink: /archivers/Javascript
nocomments: false
use_math: true
---

# JavaScript

JavaScript에 관해 공부하며 간단 메모한 글

## What is JavaScript?

[JavaScript 언어 동작 방식 1 (클릭 시 새 탭 열기)](https://doitnow-man.tistory.com/128){: target="\_blank"}

[JavaScript 언어 동작 방식 2 (클릭 시 새 탭 열기)](https://engineering.huiseoul.com/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EB%8A%94-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%9E%91%EB%8F%99%ED%95%98%EB%8A%94%EA%B0%80-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EB%A3%A8%ED%94%84%EC%99%80-%EB%B9%84%EB%8F%99%EA%B8%B0-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%EC%9D%98-%EB%B6%80%EC%83%81-async-await%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EC%BD%94%EB%94%A9-%ED%8C%81-%EB%8B%A4%EC%84%AF-%EA%B0%80%EC%A7%80-df65ffb4e7e){: target="\_blank"}

[JavaScript 코드 최적화 하기 (클릭 시 새 탭 열기)](https://mollangk.tistory.com/14){: target="\_blank"}

[JavaScript 비동기 처리 로직 (클릭 시 새 탭 열기)](https://medium.com/@nsh235482/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%97%90%EC%84%9C%EC%9D%98-%EB%B9%84%EB%8F%99%EA%B8%B0-%EC%B2%98%EB%A6%AC-%EB%A1%9C%EC%A7%81-93a09e96dc36){: target="\_blank"}

<!-- javascript구조에 관한 사진 -->

## AJAX

<!-- ![url](/assets/posts/2020-05-24-nodejs/url.png) -->

[XMLHttpRequest에 관하여 - zerocho (클릭 시 새 탭 열기)](https://www.zerocho.com/category/HTML&DOM/post/594bc4e9991b0e0018fff5ed){: target="\_blank"}

[ajax 데이터 로딩 중 로딩 표시(클릭 시 새 탭 열기)](https://skylhs3.tistory.com/4){: target="\_blank"}

[ajax 속성 등(클릭 시 새 탭 열기)](https://tutorialpost.apptilus.com/code/posts/jquery/jq-ajax/){: target="\_blank"}

[ajax CORS 문제에 관하여(클릭 시 새 탭 열기)](https://infotake.tistory.com/88){: target="\_blank"}

[ajax CORS 문제 nodeJS로 해결 (클릭 시 새 탭 열기)](https://kosaf04pyh.tistory.com/25){: target="\_blank"}

[하나은행 환율 API 간헐적 CORS/CORB (클릭 시 새 탭 열기)](https://blog.edit.kr/entry/PHP-%ED%95%98%EB%82%98-%EC%9D%80%ED%96%89-%ED%99%98%EC%9C%A8-API%EB%A5%BC-%ED%86%B5%ED%95%9C-JSON){: target="\_blank"}

[간헐적 CORS 사례 (클릭 시 새 탭 열기)](https://devtalk.kakao.com/t/cors/104823/5){: target="\_blank"}

HTTP Request 할 시, setRequestHeader를 통해, Header설정 하는 방법 등

script generated HTML code 를 parsing 하는 방법 (only JS?)

http -> https 요청 (가능) / https -> http 요청 (불가) ->> hosting받아서 http로 만듦...

[/wapi/v3/assetDetail.html API (클릭 시 새 탭 열기)](https://github.com/binance-exchange/binance-official-api-docs/blob/master/wapi-api.md){: target="\_blank"}

## setTimeOut

[for문 안 에서의 setTimeOut (클릭 시 새 탭 열기)](http://yoonbumtae.com/?p=643){: target="\_blank"}

## jQuery

[jQuery에서 append() 사용 시 주의 할 점 (클릭 시 새 탭 열기)](https://jonnung.tistory.com/16){: target="\_blank"}

## etc

### effect

[특정 수치 이상일 경우 배경색 변경(table cell의 경우) (클릭 시 새 탭 열기)](https://www.codeproject.com/Questions/1202518/Blink-td-cells-background-in-the-row-if-value-is-g){: target="\_blank"}

[notification 효과 주는 JS (클릭 시 새 탭 열기)](https://alertifyjs.com/notifier/message.html){: target="\_blank"}

### 숫자 처리

개발중, toFixed를 7주고 함수 만들어서 그 함수에 전달 후, 10000이상이면 tofixed2 등 처리 할 생각이었으나, \*1 하는 방법 사용

소수인 number 변수에 \* 1 을 하면 끝 0을 제외한 유효숫자 까지만 표기 됨

(ex : var a = 0.5600 인경우 console.log(a\*1) 은 0.56으로 표기 됨)

### forced reflow while executing JavaSCript took Xms

빈번한 DOM 구조 변경으로 인한 에러

[관련링크 (클릭 시 새 탭 열기)](https://www.facebook.com/groups/codingeverybody/permalink/2210757938964730/){: target="\_blank"}

tippy.js 적용시 발생.. 빈번한 DOM 구조 변경인듯

### XMLHttpRequest 등으로 외부 요청 시 cache되어 데이터가 update되지 않는 문제

https://stackoverflow.com/questions/6090990/how-can-i-avoid-cached-data-when-downloading-via-xmlhttprequest

time을 이용

https://stackoverflow.com/questions/168963/stop-jquery-load-response-from-being-cached/168977#168977

ajax 에서 no cache option

## 문법 간단 메모

### array

array에서 indexof 사용 시, 원하는 값 편리하게 찾을 수 있음

```js
var name = "foo, need mod";
var letter = `Dear ${name}

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. ${name} Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. ${
  1 + 1
} Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa egoing qui officia deserunt mollit anim id est laborum. ${name}`;

console.log(letter);
```

### table

[table 정렬하기 1 (클릭 시 새 탭 열기)](https://tonks.tistory.com/79){: target="\_blank"}

[table Header 클릭 시 정렬되는 예제 코드 (클릭 시 새 탭 열기)](https://m.blog.naver.com/PostView.nhn?blogId=websearch&logNo=220897790755&proxyReferer=https:%2F%2Fwww.google.com%2F){: target="\_blank"}

[table안에 이미지 딱 맞춰 넣기 (클릭 시 새 탭 열기)](https://namubada.net/203){: target="\_blank"}

### MutationObserver

[Mutation Observer 에 관하여 1 (클릭 시 새 탭 열기)](https://www.zerocho.com/category/HTML&DOM/post/5be24eacdb0c31001c4c5040){: target="\_blank"}

[Mutation Observer 에 관하여 2 (클릭 시 새 탭 열기)](https://uxgjs.tistory.com/170){: target="\_blank"}

[Mutation Observer Stackoverflow my question (클릭 시 새 탭 열기)](https://stackoverflow.com/questions/63483340/detect-change-of-textcontentvalue-of-html-table-cell-and-apply-animation-on-ch){: target="\_blank"}

(Mutation oberver에서 config를 subtree: true로 설정하라 함)

### localStorage

[클라이언트에 정보, 데이터 저장 (클릭 시 새 탭 열기)](http://bitly.kr/w362h3jwQ1Z){: target="\_blank"}

[localStroage에 배열형식 value 저장](https://amajoy.tistory.com/entry/localStorage-%EB%B0%B0%EC%97%B4%ED%98%95%EC%8B%9D-%EC%A0%80%EC%9E%A5%ED%95%98%EA%B8%B0){: target="\_blank"}

### input

[input에서 enter키 누를 시 이벤트 발생 (클릭 시 새 탭 열기)](https://hsol.tistory.com/550){: target="\_blank"}