# TIL

---

TODO: 지도 관련 사이트 만들어보기, java memory 관련, storybook

저녁있는엑셀

---

---

## 2022-08-29
lego-app 배너 닫기 처리 

배너닫기할 때 rotate 90도 넘어주면서 active하도록

닫을 땐 그냥 닫기랑 "하루 동안 열지 않기" 체크 후 닫기

---

## 2021-11-09

1. 탭을 2개 띄운 상태로 하나의 탭을 로그아웃 했을 때(세션 해제) 반대쪽의 다른 탭에서 ajax 요청을 보내는 경우
   서버에서 세션체크 후 로그인 페이지로 이동
   ( interceptor에서 처리하려고 했는데 (ajax 경로도 interceptor로 들어오고 있었기 때문에) 해당 interceptor에서 화면을 다시 그려주기에
   동기 요청의 경우 정상작동되지만 ajax의 경우 return시 화면을 다시 그려주는게 아니기 때문에 interceptor에서 화면을 다시 그려주질 못함)

2. amchart export 사용

---

## 2021-10-06

1. js, css, jsp, html, img관련 파일 등 정적인 요소들을 반영해주고 나서 캐시를 지워주거나 다른 브라우저(기존의 캐시가 없는) 로 확인을 해주어야한다. <br>
   -> 브라우저 캐시 동작은 URL을 기준으로 기존에 동일한 URL에 요청한 적이 있었는지를 판단하여
   렌더링 되기 때문에 같은 이름의 파일인 경우 반영을 하더라도
   캐시 때문에 인식하지 못하는 상황에서 모든 사용자들에게 캐시를 제거해달라고 요청할 수 없으므로
   <strong>정적인 리소스 파일들을 호출할 때 쿼리스트링 방식으로 리소스 파일들을 호출하면 파일을 다르게 인식하여 기존의 캐시를 활용하지 않고 새로 요청하여 화면을 보여준다.</strong>

![111](https://user-images.githubusercontent.com/54573684/136133296-38e645e7-e911-4e0c-9e69-e6dd2873ff31.PNG)

---

## 2021-08-23

1. 데이터 작업 정리,문서화 (개인)
2. SQL 공부

---

## 2021-08-12

## listagg

## 2021-08-11

7월28일을 기점으로 휴가와 회사 프로젝트 개발 진행하였음 한동안 못 쓸거 같으니 여유로워지면 다시 오겠음

---

## 2021-07-28

1. svg 공부
2. css important 는 같은 속성을 여러 번 정의하여도 속성값 바뀌지 않게할 때<br>
   <strong>!important</strong>를 추가해줌.
3. transition은 svg circle 태그의 stroke-dashoffset에도 적용할 수 있음
4. vanilla js로 stroke-dashoffset값 변경해줄때 <strong>camelcase</strong>로 작성하는것 잊지말 것!!
5. svg_circle.html 파일 참고

---

## 2021-07-27

## 내용 지움

## 2021-07-26

내용 지움

---

## 2021-07-23

1. 스크롤 업 이벤트 발생 시 header 내려오도록 처리
   -> window.onmousewheel 이벤트 참고
   이벤트 객체를 파라미터로 넘겨 준 후 event.wheelDelta 값이 양수인지 음수인지 판단하여 처리하면 됨
2. 전자정부프레임워크 전반적인 구조와 사용법 확인
3. js class 핸들링 하는거 연습(jquery에 너무 길들어져 있지 않았나 반성)
   classList와 className 정리 완료

---

## 2021-07-22

1. css flex 연습

---

## 2021-07-21

1. FAQ 화면 작업 연습
2. excel loader 정리 -> 예전에 해두었던 소스가 안되서 확인해보니
   <script type="text/javascript"src="http://malsup.github.com/jquery.form.js"></script>
   위의 src가 404에러가 뜸 (아마 사이트가 없어진게 아닌가 싶은데)
   -> 그래서 수정하여 다시 올려둠 (ajaxSubmit -> ajax)

---

## 2021-07-20

1. javascript 다시 공부중 4일차 (ES6 포함)<br>
2. 화면설계서

---

## 2021-07-19

1. API로 프론트엔드 서버와 백엔드 서버 나눠서 통신하는 구조 공부
2. 화면설계서

---

## 2021-07-16

1. javascript 다시 공부중 3일차 (ES6 포함)<br>
2. youtube-background 플러그인으로 배경에 유튜브 영상 넣기 & video 태그로 배경에 영상 넣기
3. 현재 무음 자동 재생 ( muted autoplay ) 으로만 자동 재생이 가능
   유음 자동 재생이 막힌 이유는 공부 한글 파일에 작성해둠 ( 키워드 : 유음 자동 재생)
4. spread와 rest 정리

---

## 2021-07-15

1. javascript 다시 공부중 2일차 (ES6 포함)<br>
2. SQL ( MSSQL 제외 ) - LAG() 함수와 LEAD() 함수 정리
3. foreach & for in & for of & reduce
4. for (let i = 0; i < arr.length; i++) {

   대신에 아래처럼 쓰자! 루프가 반복될때마다 arr.length에 접근하므로 , for문 밖에서 태우고 변수에 담아줍시다

   let l = arr.length;
   for (let i = 0; i < l; i++) {

---

## 2021-07-14

1.  TODO : 프로젝트 코드 리팩토링하기.
2.  html에서 onmouseover 도 많이 쓰일 것 같은데 알아두자.
3.  javascript 다시 공부중 1일차 (ES6 포함)<br>

---

## 2021-07-13

1.  데이터 확인
2.  게시물 댓글 수정 작업 완료 - 14:20<br>

    수정 취소 버튼 만들어서 취소할 경우 이벤트 처리 - 14:36<br>

    댓글 수정 시 수정된 날짜 포맷 후 표시 - 14:49<br>

    게시물 댓글 삭제 처리 - 15:43<br>

    게시물 삭제 처리 : 댓글이 있다면 삭제 x, 댓글이 없다면 삭제 o - 16:16<br>

    scroll to the top 개량 - 17:45<br>

    <p>
    scroll to the top 버튼 적용 후 scroll이 최상단에 있을경우 보이지 않게 하고,<br>
    스크롤을 어느 정도 내리면 fadein 처리, 반대로 다시 어느 정도 올리면 fadeout 처리 하였음<br>
    또한 기존 버튼의 opacity를 가져와서 1이였다면 fadeout처리, 0이였다면 fadein처리 하도록 자연스럽게 해둠<br>
    </p>

---

## 2021-07-12

1.  git vscode 연동

2.  무엇을 : 프로젝트 투입 전 게시판 작성

    어떻게 : 개인프로젝트

    왜 : 성격상 개발 진행 하면서 고민해야 될 부분들을 미리 대비해두기 위함,
    생각해볼 시간이 많이 있을 때 미리 작업해보고 부딪힐 난관들을 먼저 해결해보려함

3.  진행상황 : 게시물 댓글 추가 완료, scroll to the top 추가, 게시물 댓글 레이아웃

4.  TODO : 게시물 댓글 수정

---

## start

<h2>git push 명령어</h2>
1. git add .
2. git commit -m "message"
3. git push

<hr>
<h2>git md파일 image 추가</h2>
1. Issues 탭 클릭
2. Write
3. "Attach files by dragging & dropping, selecting or pasting them." 클릭
4. 파일 선택
5. Write Editor 영역에 변환
