# 240423 #
**HTML/CSS/JAVA Script** : 
- 증감 연산자 (변수의 값을 1씩 증가 시키거나 감소 시킴, 변수에만 적용 가능, ++(증가) --(감소))
  1. ++a 전위 증가 연산자: 변수를 불러오기 전에 1 증가 후 출력
  2. a++ 후위 증가 연산자: 변수를 먼저 출력 후 1 증가    
- 비교 연산자 (왼쪽의 피연산자 기준, 두 개 이상의 값 비교)
1. <, > 작다, 크다
2. <=, >= 작거나 같다(이하), 크거나 같다(이상)
3. == 같다
4. != 같지 않다
5. === 완전히 같다(데이터형까지 비교)
6. !== 왼전히 같지 않다   
- 데이터형비교연산자
- 논리 연산자: 두 개 이상의 조건 값 비교
1. &&(AND) - A조건 && B조건: A조건, B조건 모두 만족시킬 때 true 반환
2. ||(OR) - A조건 || B조건: A조건, B조건 중 하나만 만족시켜도 true 반환
3. !(NOT) - !A조건 : A 조건의 반대값 반환
     (toggle botton 만들 때 가장 많이 사용됨/ 하나의 버튼에 두 개의 기능을 넣고자 할 때)     
- 제어문 : if조건문, switch선택문, for반복문, while반복문
1. if 조건문: 주어진 조건에 따라 참과 거짓으로 구분. true일 때 실행
2. if-else조건문 / else-if조건문  
- 삼항 연산자 / (조건식) ? 참인 실행문 : 거짓인 실행문;
- // 숫자 데이터 타입으로 변환
1. num = Number(num); 숫자 타입 변환
2. num = parseInt(num); 정수 반환
3. num = +num; + 연산자를 붙이면 숫자 타입으로 변환
-  중첩if문
-  switch선택문: 특정 값과 비교하여 참인 경우 실행
   switch (비교값) {
  	case 비교할 값: (이 값과 비교하여 참인 경우 실행문 실행. 비교 시 엄격한 비교 ===);
  	실행문;
  	break; (비교 값이 참인 경우 다음으로 넘어가지 않고 구문을 벗어나게 하는 키워드)
 	default: (위의 비교값과 일치하는 값이 없는 경우 실행. else와 같은 역할을 하며 생략 가능);
  	실행문;
  	break; (제일 마지막이기 때문에 생략 가능)
   } 

# 240422 #
**JAVA Script** : 
- 자바 스크립트 내부 선언/ 외부 선언
- defer 속성
- 사용자 입출력, 알림 => alert(); confirm(); prompt();
- 변수 선언, 선언 후 대입, 변수 선언과 동시에 대입(var, let)
- const상수 : 변하지 않는 수, 상수의 경우 선언 후 대입 x, 호이스팅 불가능,재할당, 재선언 불가능
- 데이터 타입 (string, number, boolean, undefined, null, object, function, array, typeof)
- 산술 연산자 (= 대입 혹은 할당, + 더하기, - 빼기, * 곱하기, / 나누기, % 나머지값, **거듭제곱)
- 문자열 연산자 (더하기, 빼기, 곱하기, 나누기)
- 대입(할당) 연산자 (= 를 기준으로 우변의 숫자만큼 연산하여 좌변의 변수에 "새로운 값으로 갱신")
- 변수 초기화
1. let txt = ''; 문자열
2. let num = 0; 숫자
3. let boo = false; 불리언
4. let obj = null; 객체


# 240419 #
**HTML/CSS** : 
- https://bdmp-001.cafe24.com/bizdemo144534/ 웹,모바일 버전 작업
- 유튜브 비율 유지 방법 => width: 100%; aspect-ratio: 16 / 9;
- ::after 값 없애는 방법 => height: 0; / display: inline; / content: none;
- position: static; /* 이전 position:fixed;값 초기화 */
- gap: initial; (이전 gap 값 초기화)
- swiper js/ 플러그인 사용 및 적용 방법
- gridEx 예제 연습 / 반응형 (pc tablet moblie)

# 240418 #
**HTML/CSS** : 
- https://bdmp-001.cafe24.com/bizdemo144534/ 웹,모바일 버전 작업
- css var(변수)
- backdrop-filter: ; (요소 뒤 영역에 그래픽 효과 적용)

# 240417 #
**HTML/CSS** : 바이텍캠 웹사이트 모바일 버전 제작(평가용 웹사이트)

# 240416 #
**HTML/CSS** : 
- https://bdmp-001.cafe24.com/bizdemo144534/ 웹, 모바일 버전 작업
- js개인 공부
- swiper js 개인공부

# 240415 #
**HTML/CSS** : 
- grid-column: auto; (이전 값 초기화, auto 작성)
- mqEx1 ~4.html
- https://bdmp-001.cafe24.com/bizdemo144534/ 웹, 모바일 버전 작업

# 240412 #
**HTML/CSS** : 
- gridEx6 ~ 8.html
- 미디어 쿼리
- box-shadow: x축 y축 블러값 #컬러; (블러값 생략 가능)
- writing-mode: vertical-lr; (텍스트의 진행 방향의 가로, 세로 정렬. 상속)
- text-orientation: upright; (writing-mode 작성시 영어의 글자 방향)
- letter-spacing: 2px; (글자 자간 늘려줌)

# 240411 #
**HTML/CSS** : 
- display: grid;
- grid-template-rows: 높이(세로) 값;
- grid-template-columns: 너비(가로) 값;
- grid-template: minmax(최소값, 최대값)
- 문자 o(알파벳) 기준 5ch == ooooo, 2ch == oo
- gap: ; / row-gap : ; / column-gap: ;, repeat(반복횟수, 크기); 행과 열의 값 반복
- grid-auto-rows: 명시된 행 외의 줄 추가
- min-content / max-content
- grid line: 셀 제어
- 그리드 아이템 정렬: justify-content, align-content, justify-items, align-items
- 그리드 아이템 개별 정렬: justify-self, align-self, place-self, auto-fit / auto-fill

# 240410 #
**HTML/CSS** : 
- https://www.panstar.co.kr/ 사이트 구현
- kakaodevlopers / Web 플랫폼 등록
- 백그라운드 컬러와 이미지 중첩 방법
- 한 줄 말줄임/ 여러 줄 말줄임
- 기본 리스트 스타일 외 스타일 설정방법
- float: right;
- align-self: stretch;
- filter: grayscale(100%) contrast(20%); /* css filter, https://developer.mozilla.org/ko/docs/Web/CSS/filter */

# 240409 #
**HTML/CSS** : 
- https://www.panstar.co.kr/ 사이트 구현
- youtube 옵션 ~/embed/유튜브비디오아이디&amp;옵션1=값&반족=true&음소거=true&자동실행=true
- :not(:first-child)
- display: grid;
- place-items: center;

# 240408 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 왼료 보고서 작성 및 제출

**HTML/CSS** : https://www.panstar.co.kr/ 사이트 구현

# 240405 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 발표 대본 작성, PPT 수정 및 발표

# 240404 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 발표 대본 작성

**HTML/CSS** : animation
1. animation-name: ani2; /* 애니메이션 이름. 키프레임에 부여한 이름 */
2. animation-duration: 2s; /* 진행시간 */
3. animation-delay: 0.5s; /* 대기시간 */
4. animation-timing-function: linear; /* 움직임 스타일 */
5. animation-iteration-count: infinite; /* 반복횟수. 무한 */
6. animation-fill-mode: backwards; /* 끝난 후 위치. 기본값 끝난 후 출발점으로 돌아옴 */
7. animation-fill-mode: forwards; /* 끝난 후 도착점에 그대로 있음 */
8. animation-direction: normal; /* 방향. 기본값 */
9. animation-direction: reverse; /* 역방향 to, 100% -> from, 0% */
10. animation-direction: alternate-reverse; /* 역방향 진행 후 순방향 진행 3>2>1>2>3 */
11. animation-direction: alternate; /* 순방향 진행 후 역방향 진행 1>2>3>2>1 */
12. animation-play-state: paused; /* 일시멈춤 */
- text-shadow: px px #color;
- aniEx1, 2, 3

# 240403 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 발표 PPT 제작

**HTML/CSS** : 아이콘 연결 (css), linear-gradient(), animationBasic

# 240402 #
**팀 프로젝트/UI 디자인 (예약시스템)** : prototype 제작(https://www.figma.com/file/RnsWHPq2OkIhmeXloQhoYZ/%EB%84%A4%EC%9E%8E%ED%81%B4%EB%A1%9C%EB%B2%84_%ED%94%84%EB%A1%9C%ED%86%A0%ED%83%80%EC%9E%85?type=design&node-id=0-1&mode=design&t=ZkYNL9HdOcsMhhew-0
), 디자인 소스 정리

**HTML/CSS** : 
- position: static; /* 포지션 초기화 */
- transform: perspective() 원근감
- transEx 예제들 

# 240401 #
**팀 프로젝트/UI 디자인 (예약시스템)** : prototype 제작

**HTML/CSS** : 
- transition-property(움직임 속성)
- transition-duration(움직임 진행시간)
- transition-delay
- transition-timing-function(움직임 형태 제어)
- transform:scale(); (크기/ 배수의 값으로 단위값 없음)
- transform:rotate( 값 deg) (회전)
- transform:skew( 값 deg) (기울기)
- transform:traslate() (이동)
- transform-origin: 값; (기준축)/ 기본값 50%

# 240329 #
**팀 프로젝트/UI 디자인 (예약시스템)** : prototype 제작

**HTML/CSS** : navEx1/ navEx2 (예제 연습)

# 240328 #
**팀 프로젝트/UI 디자인 (예약시스템)** : prototype 제작

**HTML/CSS** : 
- object-fit (이미지나 비디오의 비율 조절)
- object-position
- aspect-ratio (가로 세로 비율 설정)

# 240327 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 
- 체크리스트 작성
- prototype 제작

**HTML/CSS** : 
- 스크롤바 제어 방법
- position: sticky;
- z-index: (숫자);

# 240326 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 
- 와이어프레임, 서브흐름/ 메인흐름/ 페이지 설명(간략하게)
- 홈(전시설명)/ 예약/ 안내사항/ 회원정보 ==figma 로 제작

**HTML/CSS** : 
- positionEX2/ positionEx3
- ::selection (문서를 드래그 했을 때)
- min == code 압축되었다는 뜻
- reset.css 수정 및 작성 ->boxsizing들어가 있음
- 웹 폰트 연결

# 240325 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 
- 와이어프레임
- 서브흐름/ 메인흐름/ 페이지 설명(간략하게)
- 홈(전시설명)/ 예약/ 안내사항/ 회원정보 ==figma 로 제작

**HTML/CSS** : 
- 반응형 웹 -layout.css
- 내가 작성한 common, header, footer (css 문서)
- position : 요소의 배치 (static;/ relative;/ absolute;/ fixed;)

# 240322 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 
- 페르소나 작성
- 간단한 사용자 시나리오 작성
- 정보구조도 IA (메뉴트리 작성)

**HTML/CSS** : 
- flexItemEx2
- mini reset css (css 초기화 코드)
- meta /favicon
- ttf to woff , woff2 (폰트 변환)
- 웹폰트를 사용하기 위한 사전 설정 방법
- layout.html / layout.css / fonts.css

# 240321 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 
- 경쟁사의 강점, 약점 참고 => 개선
- 사용자의 니즈 파악
- 페르소나 자료조사
- 일지 작성

**HTML/CSS** : 
- svg 파일 vscode로 열기
- (면색 변경 방법) : <svg fill="#색상코드">
- flex-item css 특성 종류(order, flex-grow, flex-shrink, flex-basis, flex ...)

# 240320 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 자료조사 및 정리, 발표 : 하은혜

**HTML/CSS** : 
- 수열선택자Ex
- a의 수열선택자 작성 방법
- background-image: url(외부 파일 링크 주소);
- background-repeat: repeat/ repeat-y/ repeat-x/ no-repeat;
- background-position: 0 0; / 기본값 x축 y축 (배경이미지 위치)
- background-attachment: scroll/ fixed;
- background-size
- background 축약형 작성 방법
- backgroundMulti (중첩은 쉼표로 구분. 먼저 작성된 값이 위에 보여짐)

# 240319 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 자료조사

**HTML/CSS** : 
- flexEx9, display:inline-flex
- display:flex
- 수열선택자 - 의사클래스

# 240318 #
**팀 프로젝트/UI 디자인 (예약시스템)** : 
- 주제 : 아트보다 갤러리 전시 예약
- 갤러리, 모바일 앱 : 뮤지엄라이너, 대림미술관, 아트가이드, 아트맵
- 아트보다 갤러리: https://artboda.co.kr/
- UI/UX 디자인 이론과 실습

**HTML/CSS** : flexEx 6 / 7 / 8

# 240315 #
**HTML/CSS 오전** : 
- flex-flow : <플렉스 방향> <플렉스 줄 배치>
- gap:0; (기본값 / 아이템과 아이템 사이의 여백)
- justify-content / (주축 기준 아이템 하나씩 정렬)
- align-items / (교차축 기준 아이템 하나씩 정렬)
- align-content / (교차축 기준, 여러 아이템을 하나의 덩어리로 보고 정렬)
- align-self / (교차축 기준 개별 배치, 자식인 플렉스 아이템에 적용)

**HTML/CSS 오후** : 
- css 함수 : calc(값 * 값) 반드시 연산자를 띄어써야 함
- margin: auto; (center center)
- margin-left: auto;/ margin-right: auto;/ margin-bottom: auto;/ margin-top: auto
- flexEx1 ~flexEx6

# 240314 #
**UI/UX 디자인 이론과 실습** : 
- UI의 종류
- UI의 평가 기준 (휴리스틱 평가)
- UX의 이해
- 모바일 환경/ 터치 제스처
- 모바일 앱의 종류

**HTML/CSS** : 
- * 전체 선택자
-  em 단위, rem 단위
-  viewport 단위(vw: viewport width/ vh: viewport height)
-  flex-direction 정렬, display: flex; (상속되지 않음)
-  flex-direction: row/colums/row-reverse/column-reverse;
-  flex-wrap: nowrap/wrap/wrap-reverse;

# 240313 #
**Figma** : 와이어프레임을 기준으로 모바일 사이트 리디자인, https://bitekchems.com/ (바이텍켐스), PC 버전으로 작업

**HTML/CSS** : 
- table 성격
- 요소 성격 변경 display(inline; inline-block; block; none;)
- visibility(visible; hidden;)
- opacity(숫자, 불투명도 조절)
- 세로 중앙 정렬 방법 (height=line-height)
- :before, ::before, :after, ::after
- accent-color

# 240312 #
**Figma** : 와이어프레임을 기준으로 모바일 사이트 리디자인, https://bitekchems.com/ (바이텍켐스)

**HTML/CSS** : 
- webFont 설정 방법 (html and css : fonts.google.com)
- CDN
- Font origin: Network resource, max-width/ min-width
- 마진상쇄 현상 해결 방법 : 부모 요소에 overflow: hidden;
- empty-cells (show;/ hide;)
- border-spacing
- border-collapse: separate;
- border-collapse: collapse;

# 240311 #
**Figma** : 와이어프레임을 기준으로 모바일 사이트 디자인, https://bitekchems.com/ (바이텍켐스)

**HTML/CSS** : 
- 요소의 실제 크기
- word-break: normal, break-all, keep-all; (줄바꿈)
- box-sizing(content-box /  border-box)
- 넘치는 컨텐츠 제어 overflow (inherit, visible, hidden, auto, scroll), overflow-x,y

# 240308 #
**Figma** : 
- mobile UI/UX design 방법 (ios, android)
- prototype : sticky/ fixed/ horizontal
- FloatingActionButtons
- Sections
- 마크업 분석

**HTML/CSS** : 
- border-radius
- margin+padding 복습
- list-style (-type/ -position)
- 요소의 실제 크기 계산 방법

# 240307 #
**Figma** : 
- 반응형 웹 모바일 버전 (와이어 프레임 제작)
- figma commuitiy (UI/UX kit)
- icon 내보내기 (export - svg 파일 : vactor)

**HTML/CSS** : 
- vertical-align
- 박스 모델 (padding, border, margin)
- 마진 상쇄 현상
- 블록요소의 중앙 정렬 : margin 으로 처리

# 240306 #
**Figma** : 
- Prototype tool
- Variant (properties)
- prototype - after delay
- 반응형 웹 모바일 버전

**HTML/CSS** : 
- a(의사 클래스 :/  의사 요소::)
- 특성(속성) 선택자 [type="value"]
- 복합 선택자/ 인접 형제 선택자 (+)/ 일반 형제 선택자 (~)
- 종속 선택자/ 하위 선택자
-  width, height 

# 240305 #
**Figma** : 
- LayoutGrid
- component
- AutoLayout
- mask

**HTML/CSS** : 
- font+text 관련 css style code
- css 상속 (inheritance) 개념
- 선택자 개념 (종속, 복합)

# 240304 #
**Figma** : 
- 전체 단축키 보는 법 ( Ctrl + Shift +/)
- LayoutGrid, Frame

**HTML/CSS** : 
- style 입히는 방법
- css 선언 방식 (외부/ 내부/ 직접 선언)
- @charset "utf-8";
- color 특성 (name, hex, rgb, rgba)
- css 우선 순위

# 240229 #
**Adobe Photoshop** : 웹사이트 캡쳐 후 캡쳐 본 똑같이 제작 후 평가방에 제출

**HTML** : 
- meta tag
- (og:title, og:description, og:image, og:url)

# 240228 #
**Adobe Photoshop** : 
- FilterGallery
- PatternImg 제작 방법
- gif/영상 제작 방법

**HTML** : 
- code 작성 방법 (input type, button, teatarea ...etc.)
- fiedset-legend
- label (label for="")
- disabled
- video/audio
- favicon

# 240227 #
**Adobe Photoshop** : 
- LayerStyle
- ClippingMask
- Pattern
- Stamp
- Filter
- 사람 보정

**HTML** : 
- code 작성 방법 (table/ tr/ th/ td)
- (colspan/ rowspan)
- (caption/ thead/ tbody/tfoot)
- form (input -type/ -name/ -id/ -maxlength/ -placeholder)

# 240226 #
**Adobe Photoshop** : 
- Blending 사용 방법
- 조정 Layer
- ClippingMask 

**HTML** : 
- code 작성 방법 (특정.위치.이동/id속성)
- img/figure/figcaption
- 인라인 요소의 특성

# 240223 #
**Adobe Photoshop** : 
- smartObject Layer/ 일반 Layer 변환
- Puppet Warp
- ContentAware/ ContentAware move tool/ ContentAware scale, Layer mask

**Git** : github에 업로드 후 pages 제작 방법

**HTML** : code 작성 방법 (상대 경로 복습 및 예제 작성)

# 240222 #
**Adobe Photoshop** : 환경설정, 누끼따기, 이미지/캔버스 사이즈 조절

**HTML** : code 작성 방법 (anchor, 절대 경로 값 입력 시 target="_blank"), 절대 경로/ 상대 경로

# 240221 #
**Adobe Illust** : effet 사용 방법 (3D 효과, Transform, Stylize ...etc)

**HTML** : code 작성 방법 (div, span, ol, ul, 중첩 메뉴)

# 240220 #
**Adobe Illust** : text 문서 작성 방법

**Git** : Github에 과제물 업데이트

**HTML** : code 작성 방법 (pre, br, title, em, blockquote, p, hr, strong)

# 240215 #
**Adobe Illust** : path tool 다루는 방법 

**Git** : 
- Branch 관련 명령어 및 Git 사용 방법
- Github 사용 방법

# 240214 #
**Adobe Illust** : 
- 어도비 일러스트 패스 툴 교육 및 비트맵 사진 embed 방법 배움

**Git** : 
- Git 설치 및 Git Bash 옵션 수정
- 주요 터미널 명렁어
