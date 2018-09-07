# FDS Day-4

`HTML` `CSS`

##### css

- CSS (Cascading Style Sheet)

  - CSS는 HTMl로 만들어진 문서 텍스트를 색상, 크기, 이미지 크기나 위치, 표의색상, 배치방법 등 웹 문서의 디자인 요소를 담당하는 언어

  - 문서의  디자인 및 배치의 역활을 하며, CSS에 기술방식에 따라 '외부 CSS', '내부 CSS' 로 나뉘어 진다.

---

##### 웹 카페 실습

- HTML

  - 기본 뼈대

    - container
      - 전체를 그룹핑 하는 역할
    - header
      - 상단 영역
    - visual
    - main
      - 메인 콘텐츠
    - slogan
    - footer



---

##### WAI-ARIA 접근성

  - WAI-ARIA (Web Accessibility Initiative - Web Accessible Rich Internet Applications)

    - WAI-ARIA 속성은 브라우저를 통해 운영체제의 접근성 API로 변환된 후 보조기기를 통해 상호작용 할 수 있도록 만들어졌다. 

    - WAI-ARIA 구성

      - Role
        - slider, menu bar, dialog와 같은 HTML4에서 사용하지 못하는 특정 컴포넌트의 역할을 정의

      - Property
        - 해당 컴포넌트의 특징이나 상황을 정의하며 속성명으로 접두사 “aria-“를 사용

      - State
        - 해당 컴포넌트의 상태 정보를 정의

  - 다양한 Role의 정의

    - Role 4가지 카테고리로 분류되며, W3C의 ARIA 관련 문서 중 Definitions of Roles를 보면 다양한 Role의 정의되어 있다.

      - Document Structure Role (문서구조 역할)
      
      - Abstract Role (추상 역할)

      - Landmark Role (랜드마크 역할)

      - Widget Role (위젯 역할)

`https://eatdesignlove.github.io/post/first-WAI-ARIA 출처 블로그에 상세한 설명`

---

css 레이아웃 정복

float position grid

box-sizing, border-box, content-box

병합현상 상황에 따른 margin과 padding

flex-box, fles, justify-content, align-item

order

float 부모영역 안에서 맨 왼쪽으로 움직인다.

clear  클리어 속성은 블록 속성만 된다.

clearfix

가상요소 선택자