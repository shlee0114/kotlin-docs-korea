# kotlin-docs-korea
2022-04-25 시작 매주 최소 한 페이징 이상 업로드\
하는 이유와 목적 : 개인적인 공부, 개인적인 공부이기에 kotlin과 서버를 제외한 다른 부분은 번역하지 않음
# Get started with Kotlin

코틀린은 최신 언어이지만 개발자들을 행복하는 것에 초점을 맞춘 이미 성숙한 프로그래밍 언어다\
코틀린은 간결하고 안전하고, 자비나 다른 언어들과 상호 운용이 가능하며, 생산적인 프로그래밍을 위해 멀티 플랫폼에서 코드를 제사용 가능하도록 많은 방법을 제공하고 있다.

그러니 강력한 어플리케이션을 구축하고 싶으면 kotlin을 시작하라!

## 코틀린의 기초 배우기
- 만약 하나 이상의 프로그래밍 언어에 익숙하다면 - [코틀린 학습 교재]()
- 만약 코틀린이 너의 첫번째 프로그래밍 언어라면 - [Atomic Kotlin book⏎](https://www.atomickotlin.com/atomickotlin/) 혹은 JetBrains Academy의 무료강좌인 [Kotlin Basics track⏎](https://hyperskill.org/tracks/18?_gl=1%2ayttt5a%2a_ga%2aMjExMjE2NzMwNC4xNjUwNzk3NTE1%2a_ga_J6T75801PF%2aMTY1MDc5NzUxNC4xLjEuMTY1MDc5OTc1MC4w&_ga=2.213090909.858156114.1650797516-2112167304.1650797515)을 수강하라

# 코틀린과 함께히 강력한 어플리케이션 개발
1. 백엔드 어플리케이션
   - 코틀린 서버 사이드 개발의 첫 발을 때기 위한 방법
     1. [install Intellij IDEA latest version](https://www.jetbrains.com/idea/download/?_gl=1*se7678*_ga*MjExMjE2NzMwNC4xNjUwNzk3NTE1*_ga_J6T75801PF*MTY1MDc5NzUxNC4xLjEuMTY1MDc5OTkyMC4w&_ga=2.44756461.858156114.1650797516-2112167304.1650797515#section=mac)
     2. 첫번째 백엔드 어플리케이션 생성
        1. scratch나 [Intellij IDEA 프로젝트 생성자로 기본 JVM 어플리캐이션 생성하기]()를 통해 시작해라
        2. 만약 더 확실한 예를 원한다면 아래의 프레임워크 중 하나를 선택하고 프로젝트를 생성해라
           1. Spring
              - 전세계적으로 수백만의 개발자들이 사용하는 생태계가 확립된 성숙한 프레임워크 제품군
              - [Spring Boot로 RESTful한 웹 서비스 개발]()
              - [Build web applications with Spring Boot with Kotlin⏎](https://spring.io/guides/tutorials/spring-boot-kotlin/)
              - [Use Spring Boot with Kotlin and RSocket⏎](https://spring.io/guides/tutorials/spring-webflux-kotlin-rsocket/)
           2. Ktor
              - 자유로운 설계를 위한 경량화된 프레임워크
              - [Create HTTP API with Ktor⏎](https://ktor.io/docs/creating-http-apis.html?_gl=1*19jj4e6*_ga*MjExMjE2NzMwNC4xNjUwNzk3NTE1*_ga_J6T75801PF*MTY1MDgzMTIzNC4yLjEuMTY1MDgzMjYwNi4w&_ga=2.213699165.858156114.1650797516-2112167304.1650797515)
              - [Create WebSocket chat with Ktor⏎](https://ktor.io/docs/creating-web-socket-chat.html?_ga=2.221045073.858156114.1650797516-2112167304.1650797515&_gl=1*128m5f3*_ga*MjExMjE2NzMwNC4xNjUwNzk3NTE1*_ga_J6T75801PF*MTY1MDgzMTIzNC4yLjEuMTY1MDgzMjc3NS4w)
              - [Create interactive website with Ktor⏎](https://ktor.io/docs/creating-interactive-website.html?_gl=1*gx7mhn*_ga*MjExMjE2NzMwNC4xNjUwNzk3NTE1*_ga_J6T75801PF*MTY1MDgzMTIzNC4yLjEuMTY1MDgzMjg5Mi4w&_ga=2.247710158.858156114.1650797516-2112167304.1650797515)
              - [Publish server-side Kotlin applications: Ktor on Heroku⏎](https://ktor.io/docs/heroku.html?_gl=1*s7j8pa*_ga*MjExMjE2NzMwNC4xNjUwNzk3NTE1*_ga_J6T75801PF*MTY1MDgzMTIzNC4yLjEuMTY1MDgzMjgzOS4w&_ga=2.247710158.858156114.1650797516-2112167304.1650797515)
     3. 어플리캐이션에 Kotlin과 third-party 라이브러리 사용하기. 알고 싶다면 [프로젝트에 라이브라리와 의존성을 추가하기]()
        - [Kotlin standard library⏎](https://kotlinlang.org/api/latest/jvm/stdlib/)는 [collections]()과 [coroutines]()와 같이 유용한 것들을 제공해준다
        - 다음을 살펴 보시오 [third-party frameworks, libs and tools for Kotlin⏎](https://blog.jetbrains.com/kotlin/2020/11/server-side-development-with-kotlin-frameworks-and-libraries/?_gl=1*msgbbl*_ga*MjExMjE2NzMwNC4xNjUwNzk3NTE1*_ga_J6T75801PF*MTY1MDgzMTIzNC4yLjEuMTY1MDgzMzI2Ni4w&_ga=2.150775551.858156114.1650797516-2112167304.1650797515)
     4. 서버 사이드 코틀린에 대해 배우기
        - [유닛 테스트 작성법]()
        - [어플리캐이션에서 Java와 Kotlin코드를 섞는 법]()
     5. Kotlin 서버 사이드 커뮤니티에 참여해라
        - Slack : [get an invite⏎](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up?_gl=1*obld1x*_ga*MjExMjE2NzMwNC4xNjUwNzk3NTE1*_ga_J6T75801PF*MTY1MDgzMTIzNC4yLjEuMTY1MDgzMzM3Ni4w&_ga=2.45974253.858156114.1650797516-2112167304.1650797515)그리고 해당 체널에 들어와라 [#getting-started⏎](https://kotlinlang.slack.com/archives/C0B8MA7FA), [#server⏎](https://kotlinlang.slack.com/archives/C0B8RC352), [#spring⏎](https://kotlinlang.slack.com/archives/C0B8ZTWE4), 혹은 [#ktor⏎](https://kotlinlang.slack.com/archives/C0A974TJ9)
        - StackOverflow : [Kotlin⏎](https://stackoverflow.com/questions/tagged/kotlin), [spring-kotlin⏎](https://stackoverflow.com/questions/tagged/spring-kotlin)혹은 [Ktor⏎](https://stackoverflow.com/questions/tagged/ktor)태그들을 구독해라
     6. Kotlin을 주시해라
        - [Twitter⏎](https://twitter.com/kotlin), [Reddit⏎](), 그리고 [Youtube⏎](), 그리고 중요한 업데이트를 놓치지 말아라
    만약 어떤 난간이나 문제를 맞닥트리면 [issue tracker⏎](https://youtrack.jetbrains.com/issues/KT?_gl=1*1b3c9tj*_ga*MjExMjE2NzMwNC4xNjUwNzk3NTE1*_ga_J6T75801PF*MTY1MDgzMTIzNC4yLjEuMTY1MDgzNDMzMS4w&_ga=2.141208187.858156114.1650797516-2112167304.1650797515)로 신고를 부탁한다.
## 놓친 부분이 있나요?
이페이지에서 없거나 헷갈리는 부분이 있다면 [문제점을 공유해주세요⏎](https://surveys.hotjar.com/d82e82b0-00d9-44a7-b793-0611bf6189df)

오역과 이상한 말이 많을 수 있으니 번역관련 부분은 PR로 부탁드려요 저도 영어는 공부 중입니다
