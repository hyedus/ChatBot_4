# 뉴스 읽어주는 뉴스 챗봇
-------
## 실행방법
  - 텔레그램 챗봇 실행 /start
  - Chat_Bot.ipynb 실행
  - Chat_Bot.ipynb의 ver_2 셀 실행
------------
## 챗봇 순서
  - 실행
  - 메인 서비스 선택 (1. 오늘의 핫이슈 2. 오늘의 인기검색어 3. 뉴스 조회)
  - 1. 오늘의 이슈 -> Top5 숫자선택 -> 해당 기사 헤드라인 출력
  - 2. 오늘의 인기검색어 -> Top5 숫자선택 -> 해당 기사 요약 출력
  - 3. 뉴스조회 -> 검색한 기사 요약 출력
  - 뉴스조회 검색어 입력
  
------------------
## 본인의 챗봇에 적용할 경우
  - 텔레그램봇 토큰번호
  - 텔레그램 chat_id (https://api.telegram.org/bot + 토큰번호/getUpdates) 
  - 네이버 Developer ClientID, ClientSecret 
  - BigKinds API 키값  
  

-------------------
## 오류발생
- Pyaudio 오류발생: 아나콘다 Prompt -> conda install pyaudio 설치


-------------------
## 추가할 사항
- 해당 키워드에 해당하는 뉴스의 본문을 요약 해서 읽어주기 (Textrank를 활용한 요약)
  
