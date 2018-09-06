#FDS Day-3


`웹접근성과 웹표준, HTML CSS JavaScript, FRONT-END`

##### 인터넷 역사

- INTERNET SEVICE

  - Telnet 
  - IRC
  - e-mail 
  - Archie
  - Usenet 
  - Gopher
  - FTP 
  - WWW

`인터넷의 아버지 Tim Berners-Lee`

##### WWW (World Wide Web)

###### 웹 개발자들은 두가지로 나누어 진다.

- BACK-END
  - Server
  - Databass
  - Application Layer

- FRONT-END
  - Client
  - Web Browser
  - Presentation Layer

##### FRONT-END의 기술

- HTML5
  - 건강한 신체, 뼈대

- CSS
  - 근사한 스타일링

- JavaScript
  - 스마트한 두뇌

##### 웹 표준, 웹 접근성

`W3C (World Wide Web Consortiums) 웹 표준을 만드는 기구`
`제프리 젤드만의 웹표준 가이드 _ 책 추천`
`뭔가 이용 할 수 없는 상황을 대비해서 우회 할 수 있는 서비스를 제공`

- 웹 접근성 (Web Accessibility)

- 장애에 대한 이해

  - 시각 장애 
    - 전맹, 저시력
  - 청각 장애
  - 지체 장애
    - 절단 및 지체기능 장애    
  - 뇌병변 장애

- 환경에 대한 이해

  - 다양한 Platform
  - Cross Browsing
  - SEO (Search Enging Optimization)
  - 저사양 또는 저속회선

  ---

  ##### HTML5

  `93년 최초버전 99년 HTML5가 나오기전 최신 표준 2007년 HTML5 등장` 현재는 5.2버전 까지 나왔다.

  `HTML5는 HTML + CSS + JAVASCRIPT 의 업그레이드 버전`

- XHTML은 XML을 바탕으로 명령어를 직접 만들 수 있다.

- HTML과 XML의 차이점 
  - 태그 
    - XHTML은 무조건 소문자
    - HTML5는 대문자, 소문자 모두 가능
  - 태그 닫힘
    - XHTML은 반드시 필요
    - HTML5은 선택사항
  - 홈 태그시 닫힘
    - XHTML 반드시 필요
    - HTML5 선택사항 

- XHTML
  - HTML5가 나오기전 가장 최신의 HTML 규격문서
  - XHTML 이전에 HTML은 굉장히 느슨한 언어 였지만 XHTML이 나온 이후 정교한 프로그래밍 언어와 같은 방식으로 작동

---

##### 블록(block) 요소와 인라인(inline) 요소)

- 블록 요소


인라인 모델의 대표적인 모델

A 태그 

---

##### HTML5 콘텐츠 모델

- 콘텐츠 모델 종류
  - Flow
  - Phrasing
  - Embedded
  - Heading
  - Sectioning
  - Metadata
  - Interactive

- 플로우 콘텐츠 (Flow Content)
  - 특성 
    - 대부분 Body 안에 요소들이 포함
    - 플로우 콘텐츠는 임베디드 콘텐츠를 포함

  - 플로우 콘텐츠 태그

    `a, abbr, address, map>area, article, aside, audio, b, bdo, blockquote, br, button, canvas, cite, code, command, datalist, del, details, dfn, div, dl, em, embed, fieldset, figure, footer, form, h1 ~ h6, header, hgroup, hr, i, iframe, img, input, ins, kbd, keygen, label, map, mark, math, menu, meter, nav, noscript, object, ol, output, p, pre, progress, q, ruby, samp, script, section, select, small, span, strong, style[scoped], sub, sup, svg, table, textarea, time, ul, var, video, wbr`

- 메타데이타 콘텐츠 (metadata content)
  - 특성
    - 콘텐츠의 모양, 동작을 설정하거나 다른 문서와의 관계를 나타낸다.

  - 메타데이타 콘텐츠 태그

    `base, command, link, meta, noscript, script, style, title`

- 섹셔닝 콘텐츠 (sectioning content)
  - 특성
    - 헤딩과 푸터의 범위를 결정하는 요소
    - 모든 섹셔닝 콘텐츠는 헤딩과 아웃라인을 가짐
  
  - 섹셔닝 콘텐츠 태그

    `article, aside, nav, section`

- 헤딩 콘텐츠 (heading content)
  - 특성
    - 섹션의 헤더를 의미
  
  - 헤딩 콘텐츠 태그

    `h1, h2, h3, h4, h5, h6, hgroup`
  
- 프레이징 콘텐츠 (phrasing content)
  - 특성
    - 문서와 텍스트를 의미
    - 프레이징 콘텐츠는 하위에 텍스트나 임베디드 콘텐츠를 포함

  - 프레이징 콘텐츠 태그

    `a, abbr, map>area, audio, b, bdo, br, button, canvas, cite, code, command, datalist, del, dfn, em, embed, i, iframe, img, input, ins, kbd, keygen, label, map, mark, math, meter, noscript, object, output, progress, q, ruby, samp, script, select, small, span, strong, sub, sup, svg, textarea, time, var, video, wbr`

- 임베디드 콘텐츠 (embedded content)
  - 특성 
    - 이미지, 비디오, 플래시 등 외부 콘텐츠를 문서내에 표현

  - 임베디드 콘텐츠 태그

    `audio, canvas, embed, iframe, img, math, object, svg, video`

- 인터랙티브 콘텐츠 (interactive content)
  - 특성
    - 사용자와 상호작용하는 요소
  
  - 인터렉티브 콘텐츠 태그
    
    `a, audio[controls], button, details, embed, iframe, img[usemap], input, keygen, label, menu, object[usemap], select, textarea, video[controls]`

- 트랜스패런트 콘텐츠 (transparent content)
  - 특성
    - 부모 요소의 콘텐츠에 따라 포함하는 콘텐츠의 분류가 바뀌는 요소

---


정역 리스트

div 태그

api

dtt 문서형 정의


utf-8 다국어 지원 인코딩

meta 태그 

ie=edge

title