# WebappLearningNote2017
2017년 2학기 웹어플리케이션 대비 공부한 것들

============================================================================
html

타 웹 브라우저 호환
http://www.g-it.kr/bbs/board.php?bo_table=prog_html&wr_id=771

ie 조건부 주석 쓰는법
http://webdir.tistory.com/451

html base 태그를 써야하는가 
https://stackoverflow.com/questions/1889076/is-it-recommended-to-use-the-base-html-tag

html fieldset tag를 써야하는가
https://stackoverflow.com/questions/9741328/why-do-we-need-a-fieldset-tag

input type = button 대신에 <button>를 사용해라
https://stackoverflow.com/questions/7117639/input-type-submit-vs-button-tag-are-they-interchangeable

=============================================================================
css
css best practice
https://1stwebdesigner.com/css-best-practices/

child element는 parent elelment한테 background-color를 상속받지 않는다
https://stackoverflow.com/questions/10561347/css-child-element-losing-parent-background-color-when-floated-or-aligned

position:relative 가 position:absolute위에 있을 경우와 없을 경우(원래 무조건 있어야 함)
https://stackoverflow.com/questions/44846934/what-difference-does-defining-position-relative-make-over-when-position-prop
dropdown 사용시 position: absolute 위에 position:relative 사용시 overflow:hidden이 되어있으면 relative를 사용하지 않는것이 좋다
https://stackoverflow.com/questions/43010321/why-is-dropdown-menu-disappear-when-position-of-its-ancestor-is-set-to-relative
canvas 사용 
https://stackoverflow.com/questions/1332501/how-can-i-use-the-html5-canvas-element-in-ie

css 순서
https://stackoverflow.com/questions/1291309/css-issue-ahover-not-working-with-ie-css-ninja-needed
box-shadow ordering
https://stackoverflow.com/questions/15962630/box-shadow-order-of-parameters
removing white space under img tag
https://stackoverflow.com/questions/10844205/html-5-strange-img-always-adds-3px-margin-at-bottom
iframe height 100%하면 overflow

z-index 안먹힐 때
position static에서 relative, absolute로 변경

inline block 정렬 -> vertical align : middle 이 제일잘됨
https://codepen.io/edge0703/pen/iHJuA

image change animation
http://css3.bradshawenterprises.com/cfimg/
css animation
https://css-tricks.com/using-requestanimationframe/
===============================================================================
javascript

setattribute에 관한 고찰
https://stackoverflow.com/questions/3919291/when-to-use-setattribute-vs-attribute-in-javascript

javascript 처음 onclick시 css 적용 안되는 현상 해결법
https://stackoverflow.com/questions/14192772/onclick-action-doesnt-work-at-once-but-only-for-the-first-load-live-example-in

form submit 방지 : onsubmit return
https://stackoverflow.com/questions/3350247/how-to-prevent-form-from-being-submitted
height 100% 안됨
http://jos39.tistory.com/170

가로 스크롤바 생김 : width100%상태에서 padding넣어주면안됨
https://stackoverflow.com/questions/5495079/what-causes-a-horizontal-scrollbar-in-css
element노드를 첫번째 자식으로 집어넣기

https://stackoverflow.com/questions/2007357/how-to-set-dom-element-as-the-first-child
iteration에서 항상 에러가 해당 라인에서 발생하지는 않음 

insertAfter 노드
https://stackoverflow.com/questions/4793604/how-to-do-insert-after-in-javascript-without-using-a-library
div의 폭 구하기
https://stackoverflow.com/questions/4787527/how-to-find-the-width-of-a-div-using-raw-javascript

위지윅 에디터 가능
https://www.youtube.com/watch?v=7ymnoz8bBqQ&t=4s

element classname 찾기, 수정
https://stackoverflow.com/questions/195951/change-an-elements-class-with-javascript
https://stackoverflow.com/questions/9959781/remove-classname-from-element-with-javascript

button 눌렀을 떄 파란색 테두리 지우기
https://stackoverflow.com/questions/20340138/remove-blue-border-from-css-custom-styled-button-in-chrome
https://stackoverflow.com/questions/6520192/get-text-node-of-an-element
해당 메모장 코드에 있는 속성 확인하기
https://stackoverflow.com/questions/8142006/updating-the-state-of-a-button-in-a-text-editor

자바스크립트 ctrl 이벤트
https://stackoverflow.com/questions/4604057/jquery-keypress-ctrlc-or-some-combo-like-that
textarea 비어있는지 확인
https://stackoverflow.com/questions/2476382/how-to-check-if-a-textarea-is-empty-in-javascript-or-jquery/2476389

자바스크립트 oop
https://okky.kr/article/409329
ex) 내가
prototype에 대하여
https://stackoverflow.com/questions/9772307/declaring-javascript-object-method-in-constructor-function-vs-in-prototype
=> 의미
https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Functions/%EC%95%A0%EB%A1%9C%EC%9A%B0_%ED%8E%91%EC%85%98
foreach undefined
https://stackoverflow.com/questions/19445599/accessing-this-in-a-foreach-loop-results-in-undefined

자바스크립트 클래스 생성(모든 브라우저 호환)
https://stackoverflow.com/questions/3641229/class-variable-in-javascript
event listener in this
https://stackoverflow.com/questions/1338599/the-value-of-this-within-the-handler-using-addeventlistener

foreach문에서 break 안될떄 return사용

button에 글씨 넣기
http://permadi.com/tutorial/jsInnerHTMLDOM/
https://stackoverflow.com/questions/8028980/change-text-of-first-child

fontcolor, fontsize 얻는법
https://stackoverflow.com/questions/8770008/contenteditable-get-current-font-color-size

string에서 ""지우기
https://stackoverflow.com/questions/19156148/i-want-to-remove-double-quotes-from-a-string

overflow xy 동시에 쓰지말것

inline block 정렬
https://codepen.io/herrfischer/pen/pbkyoJ
커서 맨 끝에 던져놓기
https://stackoverflow.com/questions/4233265/contenteditable-set-caret-at-the-end-of-the-text-cross-browser

오픈소스
jsslider // https://www.jssor.com

==============================================================================
디렉토리, 파일접근 불가능 php접근 가능
https://stackoverflow.com/questions/2679524/block-direct-access-to-a-file-over-http-but-allow-php-script-access
htaccess 안됨
https://stackoverflow.com/questions/12202387/htaccess-not-working-apache
htaccess 오류
https://stackoverflow.com/questions/11682561/fuelcmscodeigniter-htaccess-order-takes-one-argument-allow-deny-deny-all

서버오류 로그확인
https://stackoverflow.com/questions/6438475/the-server-encountered-an-internal-error-or-misconfiguration-and-was-unable-to-c

app yaml 쓰는법
https://stackoverflow.com/questions/4324843/how-should-i-write-my-google-app-engine-app-yaml-file

p를 넣는방안

자바 객체지향 코딩
https://okky.kr/article/409329
===========================================================================
php
모든 페이지에 session start
email validation : 	
password validation ^(?=.*[0-9])(?=.*[a-z])(?=.*[A-Z])(?=.*[@#$%^&+=])(?=\S+$).{8,}$
ip validation : (25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)(\.(25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)){3}
세션 유효 체크법

php redirect
https://stackoverflow.com/questions/768431/how-to-make-a-redirect-in-php

비즈니스 로직은 무엇인가
https://stackoverflow.com/questions/4526160/where-is-business-logic-situated-in-mvc-pattern
https://www.tutorialspoint.com/codeigniter/codeigniter_mvc_framework.htm

MVC 패턴에 대한 생각 : 특정한 php 페이지(Controller, 다리 역활)에서 상황에 따라 연산(Model)을 수행하고 페이지(View)를 로드한다.
장점 : 확장성
https://www.quora.com/Why-is-MVC-better  
difference between self and this
===========================================================================
codeigniter 관련
https://stackoverflow.com/questions/6630770/where-do-i-put-image-files-css-js-etc-in-codeigniter
404 override
https://thephpcode.com/blog/view/how-to-create-custom-404-page-with-codeigniter.html
============================================================================
phpstorm 설정
sdk directory : C:\Program Files (x86)\Google\Cloud SDK\google-cloud-sdk\platform\google_appengine
python : C:\Python27\python.exe
============================================================================
google cloud command
gcloud auth login hycubewinter@gmail.com
업로드 안될 시 체크사항 :	
 https://stackoverflow.com/questions/32107712/google-app-engine-app-deployment
 https://stackoverflow.com/questions/10407955/google-app-engine-this-application-does-not-exist
 
=========================================================================
프론트앤드 면접 :
https://okky.kr/article/401634
=======================================================================




