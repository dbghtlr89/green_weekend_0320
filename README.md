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

웹 문서에서 표시될수 있는 컨텐츠

1)텍스트
2)이미지
3)멀티미디어 (비디오,오디오)

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
-포함하는 목록 항목에 작은 목록전체가 포함됨


### 이미지 컨텐츠 요소

[HTML 이미지](https://www.w3schools.com/html/html_images.asp)

1) src attribute : 가져올 이미지 파일 위치 정보
2) alt(alternative) attribute : 대체 텍스트


### 멀티미디어 컨텐츠 요소

[HTML 비디오](https://www.w3schools.com/html/html5_video.asp)

attribute의 형태
1) name = "value"
2) name만 사용

video 태그의 attribute
1)controls
2)autoplays
3)muted
4)loop


[HTML YouTube 동영상](https://www.w3schools.com/html/html_youtube.asp)

youtube의 매개변수
1)controls => youtube_url/VIDEO_ID?contrls=1
2)autoplay => youtube_url/VIDEO_ID?autoplay=1
3)mute => youtube_url/VIDEO_ID?mute=1
4)loop => youtube_url/VIDEO_ID?loop=1

여러 매개변수 동시사용
youtube_url?contrls=1&autoplay=1&mute=1&loop=1 (& : ampersand)




### HTMLS contents models
: sectioning Contents
=> semantic Element

[CAN I use](https://caniuse.com/)

[웹 포토샾](https://www.photopea.com/)

[연습용 웹페이터 사이트](https://freebiesbug.com/)

###프론트 엔드 기술 (HTML, CSS, JS)체크

-프론트엔드 기술이 버전업 될떄마다 브라우저가 지원하는지 체크할 필요가 있음
-HTML5/5.1 , CSS3 , ES2015이후 버전드르이 기술은 항상 지원여부 체크가 필요함
-브라우저 지원여부
  -상위 호환성 : 새 버전 브라우저의 지원여부
  -하위 호환성 : 구 버전 브라우저의 지원여부
-일반적으로 브라우저 지원은 하위 호환성 체크가 필요함


[HTML Block and Inline Elements](https://www.w3schools.com/html/html_blocks.asp)

- Non-semestic slement(grouping 요소)
  -div(division)
  -span
  
### Block/Inline Element

-block : 새 줄(줄바꿈)에서 표시
-inline : 한 줄에 나란히 표시
-포함관계
  -Block : block,inline,contents(text) 모두 포함할수 있음
  -inline : inline,contents(text)만 포함 가능
  

### 폼 요소

-사용자 입력을 받을 수 있는 요소
[html form elements](https://www.w3schools.com/html/html_form_elements.asp)


> 텍스트 입력 폼 요소
```
<input type="text" /> : 한줄입력
<textarea></textarea> : 여러줄입력
<input typr="password"
```

> 파일 업로드 폼 요소
```
- <input type="file">
```
> 선택 폼 요소
```
<input type="radio">
<input type="checkbox">
항상 같이 label을 써줘야한다 (텍스트를 표시할 방법이 없음)
<select> 안에 <option> 넣어줌
 ex)
 <select title="과목선택목록">
            <option>HTML</option>
            <option>CSS</option>
            <option>JS</option>
 </select>
```

> 실행 폼 요소
```
-<input type="button" />
-<input type="reset" />
-<input type="submit" />
-<input type="button"></button>
-<input type="reset"></reset>
-<input type="submit"></submit>
```

### HTML Element에 이름 붙이기

> ID,CLASS를 사용
```
id="name"
ex)
<p id="paragraph1">단락</p>

class
ex)
<p class="paragraph2"></p>
```
> id와 class 의 사용처
- id는 하나의 HTML파일(문서)에서 중복 사용될 수 없음
- class는 하나의 HTML파일(문서)에서 중복 사용할 수 있음 (CSS styling, Javascript 기능을 동시 


> 표기법(여러단어가 사용될경우 단어를 구분)
-gnb-list-item : kebab case
-gnb_list_item : snake case
-gnbListItem : camel case
-GnbListItem : pascal case

-파일,폴더 이름 : snake case
-id,class : kebab case
-자바스크립트 변수,함수 : camel case


### 박스 가로 배치

> float

-left,right 속성값으로 가로배치
-부모요소를 기준으로 왼쪽 배치 , 오른쪽 배치
25

```
- <input type="file">
```
> 선택 폼 요소

```
<input type="radio">
<input type="checkbox">
항상 같이 label을 써줘야한다 (텍스트를 표시할 방법이 없음)
<select> 안에 <option> 넣어줌
 ex)
 <select title="과목선택목록">
            <option>HTML</option>
            <option>CSS</option>
            <option>JS</option>
 </select>
```
> 실행 폼 요소

```
-<input type="button" />
-<input type="reset" />
-<input type="submit" />
-<input type="button"></button>
-<input type="reset"></reset>
-<input type="submit"></submit>
```

### HTML Element에 이름 붙이기
> ID,CLASS를 사용

```

id="name"
ex)
<p id="paragraph1">단락</p>
class
ex)
<p class="paragraph2"></p>
```

264

> id와 class 의 사용처
- id는 하나의 HTML파일(문서)에서 중복 사용될 수 없음
- class는 하나의 HTML파일(문서)에서 중복 사용할 수 있음 (CSS styling, Javascript 기능을 동시 
> 표기법(여러단어가 사용될경우 단어를 구분)
-gnb-list-item : kebab case
-gnb_list_item : snake case
-gnbListItem : camel case
-GnbListItem : pascal case
-파일,폴더 이름 : snake case
-id,class : kebab case
-자바스크립트 변수,함수 : camel case
### 박스 가로 배치
> float
-left,right 속성값으로 가로배치
-부모요소를 기준으로 왼쪽 배치 , 오른쪽 배치
-right를 값을 사용하면 박스순서가 반대로 배치-right를 값을 사용하면 박스순서가 반대로 배치


### 반응형 웹

> OSMU ( One Source Multi Use) - One Source => HTML
> 적응형 
