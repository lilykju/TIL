## transition

```
  p {
    transition : transition-property transition-duration (transition-timing-function) (transition-delay);
  }
  
  p:state {
    property : value;
  }
```

  - state가 바뀔 때 delay시간 후에 특정 property가 duration동안 timing-function 속도로 변화한다.
  <br>  
  
## transition-timing-function

  - linear : 시작부터 종료까지 동일한 속도.
  - ease : 극초반지점은 느리고, 시작지점은 빠르고, 종료지점은 느린 속도.
  - ease-in : 시작지점이 느린 속도
  - ease-out : 종료지점이 느린 속도. 
  - ease-in-out : 시작과 종료지점이 느린 속도.
    
