# Html5-Study

대학에서 수강중인 웹프로그래밍에 대해 정리한 것

## 1. 1주차
태그 - ```<html></html>``` 등등 (앞에는 여는 태그, 뒤에는 닫는 태그이고 닫을때 앞에다 / 를 붙인다.)<br/>
속성 - ```<font color="red">``` (이때 font는 태그, color는 속성이다.)<br/><br/>

```<head>``` 머릿말<br/>
```<title>``` 웹페이지의 제목<br/>
```<body>``` 웹페이지의 내용<br/>
```<b> or <strong>``` <b>굵게</b><br/>
```<br>, <br/>, <BR>, <BR/>``` 줄바꿈<br/>
```<font>``` 글자 변경<br/>
```<img src="URL">``` 이미지 삽입<br/>
```<a>``` 눌렀을때 이동, a 태그 사이에 글자 or 이미지를 넣어서 클릭할 개체를 넣어야 한다.<br/>

> ### Font의 속성
> 1. Color=""<br/>
>    글자의 색을 변경하는 속성.<br/>
>    Red, Blue 등 색의 이름을 사용하거나, #000000 같은 색상코드를 사용   
> 2. Size="N"<br/>
>    글자의 크기를 변경하는 속성.
> 3. Face=""<br/>
>    글자의 폰트를 변경하는 속성.

> ### Img의 속성
> 1. src="Link"<br/>
>    이미지의 소스를 넣는다. (링크)
> 2. width="N"<br/>
>    이미지의 가로 길이<br/>
>    뒤에다가 단위 설정가능 Ex) px
> 4. height="N"<br/>
>    이미지의 세로 길이<br/>
>    뒤에다가 단위 설정가능 Ex) px
> 5. title=""<br/>
>    이미지의 타이틀
> 6. alt=""<br/>
>    대체 텍스트트

> ### a의 속성
> 1. href="Link"<br/>
>    이동할 주소(링크)
> 2. target=""<br/>
>    blank - 새로운 빈 창으로 연다
<br/>
<hr/>

## 2. 2주차
밖에 있는 요소를 부모 요소, 안에 있는 요소를 자식 요소라 칭한다.<br/><br/>

```<h1~6>``` 제목 태그. 1이 제일 크다<br/>
```<!--텍스트-->``` 주석 태그<br/>
```<hr/>``` 구분선 그어준다.<br/>
```<p>``` 단락 태그<br/><br/>
```<i>``` <i>이탤릭채 글자 적용 태그 (italic)</i><br/>
```<small>``` 글자 작게 만드는 태그<br/>
```<sub>``` 아래 첨자 요소 태그<sub>ex</sub><br/>
```<sup>``` 윗 첨자 요소 태그<sup>ex</sup><br/>
```<ins>``` <ins>밑줄 태그</ins><br/>
```<del>``` 취소선 태그 <del>ex</del><br/>

### 목록
```<ol>``` 순서가 있는 목록 태그 (Order List)<br/>
```<ul>``` 순서가 없는 목록 태그 (Unorder List)<br/>
```<li>``` ol, ul 태그 안에 넣는 항목 태그<br/><br/>

### 테이블
```<table>``` 테이블 태그<br/>
```<tr>``` 테이블 행 태그 (row)<br/>
```<td>``` 테이블 행의 내용 태그 (data)<br/>
```<th>``` 테이블 머리글 태그 (head)<br/>

> ### table의 속성
> 1. border="N"<br/>
>    외곽쪽 테두리. 숫자, 단위는 px<br/>

> ### 테이블 행, 열의 속성
> 1. colspan="N"<br/>
>    열 병합
> 2. rowspan="N"<br/>
>    행 병합
<hr/>

## 3. 3주차
### 미디어 태그
```<audio>```사운드 태그<br/>
```<source>```audio나 video처럼 닫는 태그가 있고 src 소스 주소가 필요한 태그때 사용 가능<br/>
```<video>```영상 태그<br/>

> ### Audio의 속성
> 1. src="Link"<br/>
>    사운드의 주소
> 2. preload=""<br/>
>    asdf
> 3. autoplay<br/>
>    asdf
> 4. loop<br/>
>    asdf

> ### Source의 속성
> 1. src<br/>
>    asdf
> 2. type<br/>
>    asdf

### 입력양식 태그
```<form>```입력 양식의 시작 태그<br/>
```<input>```입력 방식을 설정하는 태그<br/>

> ### Input의 속성
> 1. text<br/>
>    텍스트로 입력받는다
> 2. submit<br/>
>    입력한 것을 제출하는 버튼 생성
> 3. password<br/>
>    비밀번호를 입력받는다 ex)●●●●●●
> 4. file<br/>
>    파일 제출
> 5. checkbox<br/>
>    체크박스 생성 네모난 형태 ex) □
> 6. radio<br/>
>    체크박스 생성 동그란 형태 ex) ○
> 7. hidden<br/>
>    보이지 않는 양식
> 8. button<br/>
>    버튼 양식
> 9. reset<br/>
>    입력한 것들을 초기화
> 10. image<br/>
>    이미지<br/>
>    src 이미지 경로 필요함
