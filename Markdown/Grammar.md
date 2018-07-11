## 1. 헤더
# h1   
~~~
# h1 ,    h1  
          = (갯수 무관)
~~~
## h2  
~~~
## h2 ,   h2  
          - (갯수 무관)
~~~
### h3  
~~~
### h3
~~~
#### h4  
~~~
#### h4
~~~
##### h5  
~~~
##### h5
~~~
###### h6  
~~~
###### h6
~~~

## 2. 띄어쓰기

Word1    Word2  
Word1
Word2  

```
Word1(Space)(1번 이상)    Word2

Word1(Enter)(1번)
Word2
```

## 3. 개행 (줄넘기기)

Line 1  
Line 2
```
Line 1(Space)(Space)(2번 이상)(Enter)  
Line 2
```

## 4. 문단 나누기

Paragraph 1



Paragraph 2
```
Paragraph 1(Enter)
(Enter)(2번 이상)
Paragraph 2
```

## 5. 강조

*Italic* _Italic_  
**Bold** __Bold__  
***Italic Bold***  
++Underline++  
~~Cancleline~~  
```
*Italic* _Italic_  
**Bold** __Bold__  
***Italic Bold***  
++Underline++  
~~Cancleline~~  
```

## 6. 리스트
#### 숫자 목록

8. 8
2. 9
6. 10
---
1. 1
6. 2
3. 3

```
(숫자.)
8. 8
2. 9
6. 10
---
1. 1
6. 2
3. 3
```

#### 기호 목록
  + List 1
  - List 1
    * List 2
    + List 2
      - List 3
    - List 2
    
  ```
  +, -, * (순서 상관 없이)
  
  + List 1
  - List 1
  (tab)  * List 2
  (tab)  + List 2
  (tab)(tab)    - List 3
  (tab)  - List 2
  ```

#### 혼합 목록

- Unordered
  1. 1
  + Unordered
    1. 1 
    3. 2
    * Unordered
      1. 1
- Unordered
  1. 1
  2. 2
      
```
- Unordered
  1. 1
  + Unordered
    1. 1 
    3. 2
    * Unordered
      1. 1
- Unordered
  1. 1
  2. 2
```

## 7. 인용(Blockquotes)

>Quoting Text 1

>>_Quoting Text 2_

>>>>Quting Text 4
~~~
>Quoting Text 1

>>_Quoting Text 2_

>>>>Quting Text 4
~~~

## 8. 구분선
---
***
___
-  -  -  -  - 
```
-, _, * (3개 이상)
---
***
___
-  -  -  -  - (중간 공백 가능)
```

## 9. 링크

https://github.com/lilykju/TIL  
<https://github.com/lilykju/TIL>  

[Link](https://github.com/lilykju/TIL)

[1]:https://github.com/lilykju/TIL "TIL"
[2]:https://github.com/lilykju
[Link1][1], [Link2][2] 

```
https://github.com/lilykju/TIL
<https://github.com/lilykju/TIL>

[Link](https://github.com/lilykju/TIL)

[1]:https://github.com/lilykju/TIL "TIL"
[2]:https://github.com/lilykju
[Link1][1], [Link2][2]

```

## 10. 코드

`**Quoting code**`

                    **Quoting code**

```
`**Quoting code**`

(tab)(tab)(2번 이상)**Quoting code**
```

## 11. 코드 블럭

```
Quoting Block
[Link](https://github.com/lilykju/TIL)
```
~~~
Quoting Block
#h1
~~~
``````
`````
```(3개 이상)(위 아래 갯수 동일)
Quoting Block
[Link](https://github.com/lilykju/TIL)
```
~~~
Quoting Block
#h1
~~~
`````
``````
