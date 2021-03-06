# 목표 작성
Issue #20

## 목표1
### 프로그래머스 2주차 과제
- [x] 2주차 과제 제출
- [x] 1주차 과제 리뷰 확인 후 정리

## 목표2
### 관련 강의 듣기
**부스트코스 - 웹 백엔드**
> [강의 링크](https://www.boostcourse.org/web326/joinLectures/28762)
- [x] 5. 웹 앱 개발 예약 서비스 - 3) Spring Security

## 목표3
### Photo Tag 리팩토링
- [x] 예외처리
    - 다른 유저 데이터 접근
    - 사진 없는 노트
    - 더미 데이터, 초기 데이터
- [x] 로그 시트 정리 및 수정
- [x] BE README 업데이트 (소개, 로그 시트 링크, wiki 기술 문서)
- [x] 팀 README 업데이트 (소개, 기술 스택, CI/CD, 로그 시트 링크)

# 회고
## 목표1, 2: 프로그래머스 2주 차 과제
![image](https://user-images.githubusercontent.com/58318786/105633872-7b375680-5e9e-11eb-8e23-14eddf316ccc.png)

![image](https://user-images.githubusercontent.com/58318786/105633731-a8373980-5e9d-11eb-8093-d6748bc10fe0.png)
* 다행히 이번 주에는 과제를 스터디 시작 전(당일이긴 하지만)에 제출할 수 있었다. 스터디 리더 분들이 실시간으로 리뷰를 달아주셔서 바로 궁금했던 점을 해결할 수 있었다. 이번 주 과제는 몇 가지 쉬운 내용 - 코드 리팩토링과 정규식을 활용한 Validation 작업, 헬스 체크 api 구현과 아주 어려웠던 Spring Security 관련 과제가 있었다.
* Spring Security 관련한 내용이 기존에 수강하던 부스트 코스 무료 강의에 있어서 참고하려고 했는데 어떤 강의는 자료가 잘못 업로드 되어있는가 하면, 이번 과제랑은 관련이 없는 내용을 주로 다루고 있어서 다소 도움이 되지 못했다. 다행히 과제를 위해서 힌트 코드를 리더 분들이 많이 제공해주셔서 그걸 토대로 흐름 정도를 이해하려고 했고 과제를 제출할 수 있었다. 그러나 여전히 이해가 어려운 상태라 솔라가 추천한 백기선님의 인프런 강의를 해당 스터디가 끝난 이후에 수강할 계획이다.

## 목표3: Photo Tag 리팩토링
![Screenshot from 2021-01-24 23-51-17](https://user-images.githubusercontent.com/58318786/105633993-18928a80-5e9f-11eb-9d25-b21c83e417b9.png)

* 적어놓지 않으면 영영 리팩토링을 하지 않을 것 같아 이번 목표에 넣었는데 도움이 많이 됐다. 일주일의 시간을 효율적으로 사용하지 못한 편이라 마감날 급하게 리팩토링을 시작했지만 덕분에 예외처리를 꼼꼼히 할 수 있었다. 
* 프로그래머스 과제를 하면서 Validation 검증하는 부분에 있어서 몇 가지 새로 고려하게 된 점들이 있는데,
    * 비즈니스 로직에 대한 검증은 Controller, Service 어느 단에서 이뤄져야 하는지
    * Request의 유효성에 대한 검증은 Controller에서만 있어도 되는지
    * 데이터가 호출되는 모든 곳에서 검증이 이뤄져야 하는지
등이 있었다.
* 우선 내가 논리적이라고 생각하는 내용을 바탕으로 예외처리를 해놨는데 스터디를 끝나고 새롭게 알게 된 점들이 있다면 반영해서 코드리뷰를 받을 예정이다.

* 개인적으로 이번 주 시간을 비효율적으로 사용할 것이라고 예상하고 있어서 어느 정도 목표를 조정했는데 그 덕을 좀 본 것 같다.
* 타임트래커 다이어리를 작성하면서 매일 피드백을 하다보니 내 자신에 대한 컨디션을 파악하기 수월했다고 생각한다.