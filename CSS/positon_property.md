## Static  
  - position 속성의 defalt 값.  
  - 위치 지정이 불가능.
  - 자동 배치.
  
## Fixed  
  - 화면에서 항상 지정한 위치에 존재.  
  - 스크롤과 무관.  
  - 지정 위치 : 브라우저 (0, 0, 0, 0) + offset(top, right, bottom, left)
  
## Relative
  - static 위치 + offset(top, right, bottom, left)
  
## Absolute
  - 상위 요소 위치 + offset(top, right, bottom, left)
  - 상위 요소가 relative 이면 relative 좌측 상단을 기준.
  - 상위 요소가 없는 경우 body 기준.
  
