#FDS Day-3


`웹접근성과 웹표준` `HTML CSS JavaScript` `FRONT-END` `시멘틱` `CSS`

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
  - 블록 요소는 일반적으로 새 줄로 시작하거나 끝 나는 요소.

  - 블록 요소 태그
    
    ` h1, p, ul, table `

- 인라인 요소
  - 인라인 요소는 줄 바꿈 없이 표시 하는 요소

  - 인라인 요소 태그

    ` b, td, a, img `

- div 태그
  - div 요소는 다른 요소를 그룹화 해서 담는 그릇으로 사용하며, 블록 요소로 표현 된다.
  - div 요소는 특별한 의미는 없으며, 어떤 속성도 요구되지 않지 만, style 과 class 가 흔히 사 용된다. 이는 블록 수준 요소이므로 브라우저는 그 이전과 그 이후에 줄 바꿈을 표시된다

      `<div><h2>테스트</h2><p>div 테스트</p></div>`

- span 태그
  - span 태그는 텍스트를 담는 그릇으로 표현 하며, 인라인 요소이다.
  - span 태그는 div와 달리 어떠한 자동 포맷팅을 가지고 있지 않다.

    `<h1>My <span style="color:red">Important</span> Heading</h1>`

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

##### HTML5에 새롭게 추가된 태그

- header : 헤더를 의미

- nav : 내비게이션을 의미

- aside : 사이드에 위치하는 공간을 의미

- section : 본문의 여러 내용(article)을 포함하는 공간을 의미

- article : 분문의 주내용이 들어가는 공간을 의미

- footer : 푸터를 의미

---

`API란? 응용 프로그램에서 사용할 수 있도록, 운용체제나 프로그래밍 언어가 제공하는 기능(파일 제어, 창 제어 화상 처리, 문자 제어 등등)을 제어 할 수 있게 만든 인터페이스 `

##### 시멘틱 (Semantic)

- 시맨틱 태그란 브라우저, 검색엔진, 사용자 모두에게 콘텐츠의 명확한 의미를 전달 하는 역활

- 시멘틱 마크업 (의미에 맞는 마크업)

  - 시멘틱 마크업이란 논리적인 구조를 묘사 하는 것으로, 컴퓨터 프로그램이 HTML 문서를 제대로 읽어내게 하려면 의미에 맞게 끔 설계를 하는 것 이며, 누가봐도 그 의미를 알 수 있게끔 설계 하는게 시멘틱 마크업이라 한다.

  - 시멘티 마크업 장점 

    - 접근성이 좋아진다.
    
    - SEO (Search Engine Optimization)

    - 코드 가독성이 올라간다.

`SEO (Search Engine Optimization) -  검색엔진최적화의 약자로써 특정한 키워드를 검색 했을 때 자신이 발행한 포스트, 또는 블로그가 상위에 노출 되게 한다. `

---

dtt 문서형 정의

utf-8 다국어 지원 인코딩

meta 태그 

ie=edge

title

a태그

콘텐츠 중심 마크업

구조설계 

HTML 에서 네이밍 하는 작업 id 방식, class 방식 id는 유니크해야 된다 웹에서 한번만 사용 가능한게 id 여러번 사용 가능한게 class 

파스칼 케이스 카멜 케이스 

css

