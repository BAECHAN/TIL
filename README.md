# TIL
## 2021-07-15
1. javascript 다시 공부중 2일차 (ES6 포함)<br>
2. SQL ( MSSQL 제외 ) - LAG() 함수와 LEAD() 함수 정리
3. foreach & for in & for of & reduce
4. 
    for (let i = 0; i < arr.length; i++) {

    대신에 아래처럼 쓰자! 루프가 반복될때마다 arr.length에 접근하므로 , for문 밖에서 태우고 변수에 담아줍시다

    let l = arr.length;
    for (let i = 0; i < l; i++) {
-----------------------------------------------------------------------------------------
## 2021-07-14
1.  TODO : 프로젝트 코드 리팩토링하기.
2.  html에서 onmouseover 도 많이 쓰일 것 같은데 알아두자.
3.  javascript 다시 공부중 1일차 (ES6 포함)<br>
    
-----------------------------------------------------------------------------------------
## 2021-07-13
1.  데이터 확인
2.  게시물 댓글 수정 작업 완료 - 14:20<br>

    수정 취소 버튼 만들어서 취소할 경우 이벤트 처리 - 14:36<br>

    댓글 수정 시 수정된 날짜 포맷 후 표시 - 14:49<br>

    게시물 댓글 삭제 처리 - 15:43<br>

    게시물 삭제 처리 : 댓글이 있다면 삭제 x, 댓글이 없다면 삭제 o  - 16:16<br>

    scroll to the top 개량 - 17:45<br>

    <p>
    scroll to the top 버튼 적용 후 scroll이 최상단에 있을경우 보이지 않게 하고,<br>
    스크롤을 어느 정도 내리면 fadein 처리, 반대로 다시 어느 정도 올리면 fadeout 처리 하였음<br>
    또한 기존 버튼의 opacity를 가져와서 1이였다면 fadeout처리, 0이였다면 fadein처리 하도록 자연스럽게 해둠<br>
    </p>
-----------------------------------------------------------------------------------------
## 2021-07-12 
1.  git vscode 연동

2.  무엇을 : 프로젝트 투입 전 게시판 작성

    어떻게 : 개인프로젝트

    왜 : 성격상 개발 진행 하면서 고민해야 될 부분들을 미리 대비해두기 위함,
        생각해볼 시간이 많이 있을 때 미리 작업해보고 부딪힐 난관들을 먼저 해결해보려함

3.  진행상황 : 게시물 댓글 추가 완료, scroll to the top 추가, 게시물 댓글 레이아웃

4.  TODO : 게시물 댓글 수정

