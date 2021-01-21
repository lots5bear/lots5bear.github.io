---
title:  "[Study]유튜브 생활코딩 - WEB1 > HTML & Internet"
excerpt: "혼자 공부한 생활코딩(유튜브) 👉 WEB1 > HTML & Internet"

categories:
  - Study
tags:
  - study_혼공
  - 생활코딩
# last_modified_at: 2019-04-13T08:06:00-05:00

# 마지막으로 수정된 시간은 {{ page.last_modified_at }}이다.
toc : true
toc_sticky: true
toc_label: "생활코딩 - HTML & Internet"
---

## 1. HTML(HyperText Markup Language) : 웹페이지를 만드는 언어
## 2. 에디터 설치 등 실습 환경 준비
    - 코드를 작성하기 위한 에디터가 필요함 👉 Atom을 에디터로 하여 수업 진행
    - 현 시점에서 가장 인기있는 에디터를 찾으려면? 👉 구글에서 **best HTML Editor yyyy**(연도) 로 검색!
## 3. 태그(Tags)

    ```html
    <strong>굵은 글씨</strong>
    <u>밑줄</u>
    ```

    ```html
    <h1>가장 큰 제목</h1>
    <h2>두번째로 큰 제목</h2>
    <h3>세번째로 큰 제목</h3>
    <h4>네번째로 큰 제목</h4>
    <h5>다섯번째로 큰 제목</h5>

    <br>다음줄로 - Enter를 친 효과
    <p>단락 나누기</p>
    ```

    ```html
    이미지 삽입
    <img scr="이미지주소" width=300>
    ```

    ```html
    부모자식과 목록
    <parent>
    	<child></child>
    </parent>

    ex) <html>
    			<head></head>
    			<body></body>
    		</html>

    		<ul> 👉 Unordered list. 넘버링 되지 않은 리스트 작성
    			<li></li>
    			<li></li>
    			<li></li>
    		</ul>

    		<ol> 👉 Ordered list. 넘버링 리스트 작성
    			<li></li>
    			<li></li>
    			<li></li>
    		</ol>

    		<head>
    			<body></body>
    		</head>

    		<table> 👉 표 작성
    			<tr> 👉 1행
    				<td>head</td> 👉 1행 1열
    				<td>98.1%</td> 👉 1행 2열
    			</tr>
    			<tr> 👉 2행
    				<td>body</td> 👉 2행 1열
    				<td>97.9%</td> 👉 2행 2열
    			</tr>
    			<tr> 👉 3행
    				<td>html</td> 👉 3행 1열
    				<td>97.9%</td> 👉 3행 2열
    			</tr>
    		</table>
    ```

    ```html
    <!doctype html>
    👉 이 페이지는 html이다,란 의미. <html>보다 더 위, 맨 윗줄에 쓰이는 설명
    ```

    ```html
    본문을 설명하는 태그들 - <head> 아래에 속하는 태그들

    <title></title> 👉 웹페이지의 창 이름에 뜨는 제목
    <meta charset="utf-8"> 👉 이 웹페이지를 utf-8 방식으로 읽도록 하는 명령
    ```

    ```html
    링크를 표시하는 태그

    <a href="링크주소" target="_blank" title=""></a>

    **a** 👉 anchor(닻)
    **h** 👉 html
    **ref** 👉 reference(참고)
    **target="_blank"** 👉 새 탭에서 열리도록!
    **title** 👉 링크 위에 마우스 올리면 말풍선에 표시될 이름
    ```

## 4. 웹 호스팅 : github page (무료)
    - repository(저장소)에 작성한 html 파일들을 업로드
    👉 Settings > GitHub Pages > Source에서 Branch를 main으로 선택한 후 Save 클릭
    👉 웹사이트 주소가 뜨고, 해당 주소를 입력하면 업로드한 html파일에 누구든 언제든 접속 가능!

