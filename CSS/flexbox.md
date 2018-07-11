## 사용
```
   flex_box {
      display : flex;
      flex-direction : column;
      flex-wrap : wrap;
      justify-content : space-between;
      align-content : space-around;
   }
   
   first_flex_item {
      align-slef:flex-end;
   }
```
  - 박스의 배치를 자유롭게 조작.
  - 부모 요소(flexable box)에 flex 적용시키면 자식 요소(flex item)는 자동으로 display : inline-block 설정됨.
  <br>  

## flex-direction
  - 주축 방향 정의.
  - row : 수평. defalt.
  - row-reverse : 수평. 역방향.
  - column : 수직.
  - column-reverse : 수직. 역방향.
<br>  

## flex-wrap
  - nowrap : 박스를 한 줄로 배치. defalt.
  - wrap : 박스 여러 줄로 배치. 폭 유지하고 박스를 다음 줄로 넘김.
  - wrap-reverse : wrap 상태. 역방향으로 배치.
<br>  

## justify-content
  - 주축 방향 배치 정의.
  - flex-start : 박스 주축의 시작점 배치. 공백 없음. defalt.
  - flex-end : 박스 주축의 끝점 배치. 공백 없음.
  - center : 박스 주축의 중앙 배치. 공백 없음.
  - space-between : 박스 주축의 양 끝 공백 없음. 자식 박스들 사이 간격 일정.
  - space-around : 박스 주축의 양 끝과 자식 박스들 사이 간격 모두 일정.
  <br>  

## align-items
  - 교차축 방향 배치 정의.
  - strech : 박스 교차축 길이 만큼 자식 박스를 확장 배치. defalt.
  - flex-start : 박스 교차축 시작점 배치.
  - flex-end : 박스 교차축 끝점 배치.
  - center : 박스 교차축의 중앙 배치.
 <br>  
 
## align-self
  - 자식 박스(flex item)를 교차축 방향으로 개별적 배치.
  <br>  

## align-content
  - 교차축 방향으로 박스가 여러 줄일 때 배치 정의.
  - stretch : defalt.
  - flex-start, flex-end, center, space-between, space-around : justify-content 속성값과 동일.
  
