Code Logic
가위, 바위, 보 버튼 클릭
→ start 함수 : user, computer pick 정해짐
→ play 함수 : 가위바위보 결과, message, recordMsg정해짐
→ addResult, showReslt함수로 이동

addResult 함수 : gameRecord배열에 id와 message속성을 가지는 요소 추가
→ updateRecord : gameRecord 내에 있는 요소를 돌며 리스트 영역에 message와 삭제 버튼 출력

showResult 함수 : user, computer, resultMsg에 저장된 내용을 출력
→ updateScore : userScore, computerScore 출력

deleteAllResult 함수 : 전체 삭제 버튼 클릭 시 gameRecord 배열 초기화, userScore, computerScrore 0으로 초기화

deleteResult 함수 : 삭제 버튼 클릭 시 gameRecord 내의 삭제된 인덱스를 찾아 삭제하고 updateRecord해줌 + 삭제된 인덱스의 message 속성을 바탕으로 userScore와 computerScore 업데이트해줌
