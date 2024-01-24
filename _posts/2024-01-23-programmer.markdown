---
layout: post
title:  "첫 번째로 나오는 음수"
date:   2024-01-23 17:20:00 +0530
categories: Javascript
--- 
<h2>문제</h2>   
정수 리스트 num_list가 주어질 때, 첫 번째로 나오는 음수의 인덱스를 return하도록 solution 함수를 완성해주세요. 음수가 없다면 -1을 return합니다.
<br/>
<br/>

<h2>정답</h2>   

```js
function solution(num_list) {
    let answer = -1;
    
    num_list.forEach((item, index) => {
      if(item<0 && answer === -1){
          return answer = index;
      }
    })
    
    return answer;
}
```   

1. `answer`를 루프 외부에서 초기화하고 -1로 설정합니다.   

2. 배열을 순회하면서 처음으로 나타나는 음수의 인덱스만 할당합니다.   

3. 이미 음수의 인덱스가 할당되었다면 추가적인 할당을 하지 않도록 조건을 추가합니다.   

![profile]({{site.url}}/assets/profile.png)
