---
layout: post
title:  "각도기"
date:   2024-01-22 17:21:00 +0530
categories: Javascript
--- 
<h2>문제</h2>   
각에서 0도 초과 90도 미만은 예각, 90도는 직각, 90도 초과 180도 미만은 둔각 180도는 평각으로 분류합니다. 각 `angle`이 매개변수로 주어질 때 예각일 때 1, 직각일 때 2, 둔각일 때 3, 평각일 때 4를 return하도록 solution 함수를 완성해주세요.
<br/>
<br/>

<h2>정답</h2>   

```js
function solution(angle) {
    if(angle > 0 && angle <= 180){
        if(angle > 0 && angle < 90){
            return answer=1;
        } else if (angle === 90){
            return answer=2;
        } else if (angle > 90 && angle < 180){
            return answer=3;
        } else if (angle === 180){
            return answer=4;   
        }   
    }
}
```   

1. 주어진 각도에 대한 분류 결과를 반환하는 함수를 정의합니다. 함수는 `angle` 매개변수를 받습니다.   

2. if문과 else if문을 활용해 각각의 조건을 설정합니다.   

3. 각 조건에 따라 반환되는 return값이 실행됩니다.

![profile]({{site.url}}/assets/profile.png)
