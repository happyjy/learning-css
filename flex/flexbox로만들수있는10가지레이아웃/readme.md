[flexbox로 만들 수 있는 10가지 레이아웃](https://d2.naver.com/helloworld/8540176)

# 부모 요소와 자식 요소에 정의하는 속성 구분

- flex container 속성: flex-direction, flex-wrap, justify-content, align-items, align-content
- flex item 속성: flex, flex-grow, flex-shrink, flex-basis, order

* flex: 1의 의미
  - flex-grow 속성과 flex-shrink 속성, flex-basis 속성을 축약해서 flex 속성으로 표현할 때 flex: 1 속성은 flex: 1 1 0 속성을 의미한다.
  - 즉, flex-grow 속성의 값이 '1'이고 flex-shrink 속성의 값이 '1'이기 때문에 flex container의 크기에 따라 flex item의 크기도 커지거나 작아진다는 의미다.
