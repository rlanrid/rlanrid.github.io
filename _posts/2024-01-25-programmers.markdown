---
layout: post
title:  "n의 배수"
date:   2024-01-25 17:00:00 +0530
categories: Javascript
--- 
<h2>문제</h2>   
정수 num과 n이 매개 변수로 주어질 때, num이 n의 배수이면 1을 return n의 배수가 아니라면 0을 return하도록 solution 함수를 완성해주세요.
<br/>
<br/>

<h2>정답</h2>   

```js
function solution(num, n) {
    var answer = 0;
    
    if(num%n === 0){
        return answer = 1;
    } else {
        return answer = 0;
    }
    
    return answer;
}
```   

1. 매개변수 num을 n으로 나누었을때의 나머지값이 0이라면 num은 n의 배수입니다. 

2. if문을 이용해 n의 배수면 1을, n의 배수가 아니라면 0을 answer에 대입 후 반환합니다.


![profile]({{site.url}}/assets/profile.png)
