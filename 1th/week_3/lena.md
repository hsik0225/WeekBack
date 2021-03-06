# 기간
2021.01.18 ~ 2021.01.24



이번주 목표는 지난주 리뷰어인 푸글의 피드백 (최소한의 목표 + 체크리스트 + 체크리스트 단위를 아주 작게 나눠서 틈틈이 진도를 체크) &  SMART 기법을 적용해서 작성해봤습니다.

<img src="https://i.imgur.com/gtmXfHy.png" style="zoom:33%;" />

## 목표

### 포토 태그

| 마감 요일 | 달성 여부 ✅/❎ | 체크 리스트 | 링크 |
| --------- | --------- | ----------- | ----------- |
| 1월 19일 화요일 | ✅ | 노트 수정/삭제 기능 구현 & PR | [PR](https://github.com/SimLeeTag/photo-tag-iOS/pull/54) |
| 1월 19일 화요일 | 🔼 | 태그 추천 기능 구현 & PR  | [PR](https://github.com/SimLeeTag/photo-tag-iOS/pull/55) |
| 1월 20일 수요일 | ✅ | 포토 노트 리스트 UI 구현 & PR        |[PR](https://github.com/SimLeeTag/photo-tag-iOS/pull/51)        |
| 1월 20일 수요일 | ✅ | 포토 노트 리스트 기능 구현 & PR        |[PR](https://github.com/SimLeeTag/photo-tag-iOS/pull/51)        |
| 1월 21일 목요일 | . | 검색 UI 구현 & PR        |.        |
| 1월 21일 목요일 | . | 검색 기능 구현 & PR        |.        |

### 취준

| 마감 요일 | 달성 여부 ✅/❎ | 체크 리스트 |
| --------- | --------- | ----------- |
| 1월 22일 금요일 | . |   노션에 이력서 1차 작성    |
| 1월 22일 토요일 | . | 1명에게 피드백 받기   |



## 회고

취준 목록은 PR 디스크립션에는 없앴는데 md 파일에는 없애는 걸 깜빡했네요 ㅠㅠ

결국 역류성 식도염을 얻었습니다. 😢
패턴을 회복하고 건강 회복에 중점을 둬야할 것 같아요.
항상 제가 할 수 있는 맥시멈의 시간을 고려해서 목표 설정하고 있는 것 같아요.
그래서 휴식이나 운동 같이 일상과 공부의 균형을 맞추지 못하고 있는 것 같습니다.
이번주는 지난주에 비해 개발을 많이 못했네요 ㅠㅠ
<img src="https://user-images.githubusercontent.com/52783516/105634392-17faf380-5ea1-11eb-94cd-4231af30afef.png" alt="image" width="50%;" />



## TIL

### 01.26.Tue TIL

유튜브를 보고 SwiftUI로 Bar Graph를 만들어봤습니다. -> [Github](https://github.com/dev-Lena/SwiftUI/tree/main/ChartPractice)

<img src="https://github.com/dev-Lena/SwiftUI/raw/main/ChartPractice/Media/swiftui_chart_light_mode.gif" alt="img" width="20%">



### 01.28.Thu TIL

SwiftUI에서 사용되는 프로퍼티 래퍼(Property Wrapper)에 대해 알아봤습니다. (@State의 역할 등)

1. [A guide to SwiftUI’s state management system](https://www.swiftbysundell.com/articles/swiftui-state-management-guide/)
2. [What does the SwiftUI `@State` keyword do?](https://stackoverflow.com/questions/56438730/what-does-the-swiftui-state-keyword-do)
3. [Understanding of Property Wrappers in SwiftUI](https://medium.com/mindful-engineering/understanding-of-property-wrappers-in-swiftui-3789a72515c0)



### 01.29.Fri TIL

[WWDC 2018 iOS Memory Deep Dive](https://developer.apple.com/videos/play/wwdc2018/416/) 눕시청했습니다. 눕시청했는데 내용이 좋아서 나중에 다시 보며 정리할 예정입니다!



### 01.30.Sat TIL

터치 이벤트가 발생했을 때 이벤트를 처리할 UIView 객체를 찾아가는 과정에 대해 공부했습니다.
hit-testing에 대한 블로그 글을 쓰면서 알아보던 중 읽은 글에서 이벤트를 처리할 UIView 객체를 찾는 프로세스에서 reverse pre-order depth-first traversal algorithm 을 쓴다고 하는데 흥미로웠습니다. 제가 잠깐 찾아보고 이해한 바로는 깊이 우선 탐색 알고리즘의 변형? 응용? 버전인것 같은데요.

<img src="https://miro.medium.com/max/1680/0*miG6xdyYzdvrB67S.gif" alt="Breadth-first vs Depth-first Tree Traversal in Javascript | by Kenny Hom |  Medium" style="zoom:80%;" />
<br>여기서 왼쪽 DFS가 깊이 우선 탐색 알고리즘인데
<img src="http://d33wubrfki0l68.cloudfront.net/60d215400d2340e2334016ea6914aef24cfe6939/d4938/images/hit-test-depth-first-traversal.png" alt="계층 깊이 우선 순회보기" style="zoom:40%;" />

이벤트를 처리할 UIView 객체를 찾아가는 과정이 이렇거든요.

오 뭔가 흥미로웠습니다. 재밌네요 👻

1. [hitTest:withEvent:](https://developer.apple.com/documentation/uikit/uiview/1622469-hittest?language=objc)
2. [hitTest(_:with:)](https://developer.apple.com/documentation/uikit/uiview/1622469-hittest)
3. [Hit-Testing in iOS](http://smnh.me/hit-testing-in-ios/)