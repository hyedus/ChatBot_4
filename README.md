# 뉴스 읽어주는 뉴스 챗봇
-------
## 실행방법
  - 텔레그램 챗봇 실행 /start
  - Chat_Bot.ipynb 실행
  - 개인의 키값 입력
------------
## 챗봇 순서
  - 실행
  - 메인 서비스 선택 (1. 오늘의 핫이슈 2. 오늘의 인기검색어 3. 뉴스 조회)
  ![image](https://user-images.githubusercontent.com/55487601/93583683-257a0b80-f9df-11ea-9ecd-b674f6bbd8c0.png)

  - 1. 오늘의 이슈 -> Top5 숫자선택 -> 해당 기사 헤드라인 출력
  ![image](https://user-images.githubusercontent.com/55487601/93583698-3034a080-f9df-11ea-9f0b-84cedcf2dd3b.png)

  - 2. 오늘의 인기검색어 -> Top5 숫자선택 -> 해당 기사 요약 출력
  ![image](https://user-images.githubusercontent.com/55487601/93583720-3b87cc00-f9df-11ea-9c32-981af0be889d.png)

  - 3. 뉴스조회 -> 검색한 기사 요약 출력
  ![image](https://user-images.githubusercontent.com/55487601/93583750-47738e00-f9df-11ea-8649-f3ece45f04a5.png)

  - 4. 종료
  ![image](https://user-images.githubusercontent.com/55487601/93583802-58bc9a80-f9df-11ea-974e-fde6ac6b6b35.png)

* 모든 선택 옵션에서 잘못된 번호를 입력받을 경우 경고 메세지와 함께 다시 입력받음
![image](https://user-images.githubusercontent.com/55487601/93583875-7853c300-f9df-11ea-8a04-dc2886947f78.png)

------------------
## 본인의 챗봇에 적용할 경우
  - 텔레그램봇 토큰번호
  - 텔레그램 chat_id (https://api.telegram.org/bot + 토큰번호/getUpdates) 
  - 네이버 Developer ClientID, ClientSecret 
  - BigKinds API 키값  
  

-------------------
## 오류가 발생할 경우 해결방법
- Pyaudio 오류발생: 아나콘다 Prompt -> conda install pyaudio 설치


-------------------
## 향후 추가할 사항
- 해당 키워드에 해당하는 뉴스의 본문을 요약 해서 읽어주기 (Textrank를 활용한 요약)
  
