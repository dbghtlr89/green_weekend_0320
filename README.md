# 3/20 필기장

## GITHUB 기초개념

>### GITHUB 용어

>>stage(commit할 대상 ) -> commit(스냅,저장) -> push(깃허브서버로 업로드)

>><strong>pull</strong> : 깃허브서버에서 다운로드 (혐업목표)

>><strong>branch</strong> : 작업자들은 메인 프로젝트의 브랜치를 따서 자신만의 버전을 만드는 것을 말한다. 작업이 끝난 후 프로젝트의 메인 디렉토리인 master에 브랜치를 다시 merge(합치기)한다.

>><strong>merge</strong>  : 혐업된 가지들은 합치는 작업은 메인개발자가 진행
     
>><strong>pull request</strong> : 작업마무리된후 메인작업자에게 공지 (브랜치를 따서 혐업한 사람)   




## HTML

> 무료넷상코딩사이트 [codepen](https://codepen.io/)

> 무료넷상코딩사이트 [w3scools](https://www.w3schools.com/)

> 깃허브 문서작성 [마크다운 사용법](https://gist.github.com/ihoneymon/652be052a0727ad59601)

> 문서보관서비스 [github](github.com)

## WEB/IT 기초개념

>클라이언트-서버 모델

<img src="https://github.com/dbghtlr89/green_weekend_0320/blob/main/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C.png?raw=true" width="648"/>

클라이언트-서버 모델에서 클라이언트는 사용자가 사용하는 디바이스(pc,mobile)를 의미하고, 서버는 클라이언트가 접속해서 데이터나 파일을 요청했을때 응답하는 시스템

클라이언트와 서버 모델은 실제 연결을 아니지만 개념적으로 클라이언트 관점에서 1:1로 연결되었다고 생각할 수 있음

클라이언트 서버 모델에서 이루어지는 동작은 클라이언트의 요청(request)과 서버의 응답(response)의  1 사이클로 구성됨클라이언트 서버 모델에서 이루어지는 동작은 클라이언트의 요청(request)과 서버의 응답(response)의  1 사이클로 구성됨

클라이언트는 클라이언트 디바이스에서 실행되는 웹브라우저, 서버는 서버 디바이스에서 실행되는 서버 소프트웨어가 실제로 사용되는 것임

<img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/course/2614/4971.png" >




프런트앤드 업계인식
: 개발자들이 웹퍼블리셔 무시하는 경향이 있음 이유는 모름 전세계적으로 그런경향이 있음

: 퍼블리셔는 우리나라에만 있는 단어임

: 웹퍼블리셔랑 프런트앤드 개발이랑 사실 똑같은거임 굳이 나눌필요가 없음

: 웹퍼블리셔는 html,css 정도만 활용하나봄

: 언어를 하나만 깊이 파는거보다 여러개를 공부하는게 더 나을거같다고 하심

: 요새 파이썬이 뜨고있음 (단어가 쉽다고함)

: 프런트는 자바 백엔드는 자바,php,파이썬 주력언어가 될거임

: 일단 여러 언어를 아는게 중요하다고 함



## HTML

> [HTML Introduction](https://www.w3schools.com/html/html_intro.asp)

> [html Elements](https://www.w3schools.com/html/html_elements.asp)

> [HTML Attributes](https://www.w3schools.com/html/html_attributes.asp)

일반적으로 <p> 제목입니다 </p> 이런식으로 시작과 끝을 해줘야하는데

<a> </a> 하이퍼링크나 이미지삽입은 내용입력에서 끝나는게 아닌 자료를 어디서 갖고와야되는지 연결부분에 대한 설명이 필요하므로 가로로 닫지않는다.

ex)

<a href="www.naver.com"> 네이버주소 </a>

<img src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAxOTA0MTRfMTIg%2FMDAxNTU1MjEwMzQyODMz.Ag4EoVScWkPfatn8_TOENrjrcZBUikNoENSEJbjk1EMg.rmwPGgthV8JRvFuLAv_TUdlahUGDZpiadct4OtakY-Ag.JPEG.fif11035%2F1555160080380.jpg&type=sc960_832" width="100" height="100">


HTML 속성 (Attributes)
1) html element에 추가 정보를 제공
2) name = "value" 형태로 사용

> [HTML Paragraphs](https://www.w3schools.com/html/html_attributes.asp)

제목 태그 (Tag)
Heading -> h
h1~h6

> [HTML TAG](https://www.w3schools.com/html/html_headings.asp)

단락 태그
paragraph -> p           (문단?같은걸로 생각하면됨)


수평선
Horizontal Rules -> hr(Empty Elements)  (밑줄?같은걸로 나눠지는거라고 보면됨)


하이퍼링크
Anchor -> a
href : 링크로 연결된 목적지 주소

1)외부링크
-링크주소 입력시 http(https) 키워드 잊지말고 사용할 것

2)북마크
-목적지에 id attribute를 사용해서 이름을 정해줌
-href attribute에 #를 사용해서 목적지이름을 입력


[Html Tables](https://www.w3schools.com/html/html_tables.asp)

-[Html Generatoe](https://www.tablesgenerator.com/html_tables#)            (이사이트에서 데이터 입력해서 코드 복사해서 사용)

[Html list](https://www.w3schools.com/html/html_lists.asp)

1)순서없는 목록 (ul)
2)순서있는 목록 (ol)
3)설명 목록

ul,ol 목록에서 사용시 중첩(nested) 형태로 사용할때 포함관계를 주의                       (ul,ol 안에 li가 포함되는 형태로 되야함)
-포함하는 목록 항목에 작은
