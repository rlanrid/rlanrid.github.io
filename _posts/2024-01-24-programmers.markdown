---
layout: post
title:  "x 사이의 개수"
date:   2024-01-24 17:00:00 +0530
categories: Javascript
--- 
<h2>문제</h2>   
문자열 `myString`이 주어집니다. `myString`을 문자 "x"를 기준으로 나눴을 때 나눠진 문자열 각각의 길이를 순서대로 저장한 배열을 return 하는 solution 함수를 완성해 주세요.
<br/>
<br/>

<h2>정답</h2>   

```js
function solution(myString) {
    var answer = [];
    
    myString.split("x").forEach((item) => {
        answer.push(item.length)
    })
    
    return answer;
}
```   

1. 문자열 `myString` 을 문자 "x"를 기준으로 `split` 메서드를 이용해 나눕니다.   

2. forEach문으로 배열 answer에 `push` 메서드를 이용해 저장합니다.   


![profile]({{site.url}}/assets/profile.png)
