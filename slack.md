#Third party apps
Developer Tools

https://kdkangoneday.slack.com/apps/category/At0EFRCDNY-developer-tools


Connect your development tools to Slack and raise visibility into builds, errors, or anything else that needs your attention.


1. GitHub 깃허브
Source control and code management.

2. IFTTT
Automated connections between web services.

    IFTTT 기본 개념 정리
    https://sonsofaureus.wordpress.com/2014/05/29/ifttt-%EA%B8%B0%EB%B3%B8-%EA%B0%9C%EB%85%90-%EC%A0%95%EB%A6%AC/
    https://sonsofaureus.files.wordpress.com/2014/05/ifttt-recipe_thumb.png?w=545&h=413
    Recipe = IFTTT 에서 Recipe 의 정의는 위의 그림에 나와있습니다.  Recipe 란 IFTTT 가 행할수 있는 하나의 완전한 지시입니다.  IFTTT 의 Recipe 는 모두 위의 형식을 갖춥니다 – 이런일이 일어나면 이렇게 해라.

    Trigger = 행위를 취하기 전에 충족이 필요한 조건입니다.  위의 문장에 THIS 라는 부분입니다.

    Action = Trigger 의 조건이 충족되면 시작되는 행동을 뜻합니다.  위의 문장에 THAT 부분이죠.  예를들어 “나한테 문자를 보내줘” 아니면 “Facebook 에 status 글을 올려” 이런것이죠.

    Channels = IFTTT 가 연동할수 있는 모든 앱들입니다.  에버노트, 페이스북, 이메일, Gmail, 원노트 등등 현제 107가지 앱과 서비스가 IFTTT 채널을 보유하고 있고 이들은 고유의 Trigger 와 Action 이 있습니다.

    Ingridients = Trigger 에서 빼올수 있는 data 를 뜻합니다.  예를들어 Email Channel 을 Trigger 로 썼을때 쓰일수 있는 ingredient 는 제목, 내용, 받은날짜, 전송자 주소 등이 있겠습니다.

    ON/OFF = Recipe 를 껐다 켜는데 사용됩니다.

    Polling Period = Trigger 조건이 충족되는지 알아보기를 얼마나 자주 할것인지를 나타내는 시간입니다.  기본적으로 15분 입니다



3. Zapier
Easy automation for busy people

    Zapier를 이용한 자동화 활용하기(트위터 팔로워 알림:푸쉬 대용)
    http://geserkhan.blogspot.kr/2013/08/zapier.html

4. Bitbucket
Free source code hosting for Git and Mercurial.
    계정정보찾을것.

5. Jenkins CI
An open source continuous integration server.
    현재 64번서버에 설치해보는것이 젤적당.

6. Jira Cloud
Easily connect Jira Cloud projects to your Slack channels
    클라우드요금... jira는 redmine같은 통합관리툴.

7. Hubot
GitHub's scriptable chat bot.
    Hubot 이란?
    Hubot is your company’s robot. 공식 홈페이지에 나와있는 소개입니다. 실제로 머릿말에서 말했듯이 Frientrip에서도 다양한 기능으로 업무에 이용하고 있습니다. IRC나 Slack등 채팅 App들에 연동이 가능하며 간단한 명령어를 통해 미리 짜둔 Script를 실행시켜 원하는 결과 값을 얻어낼 수 있습니다.
    slack통합링크
    https://qkraudghgh.github.io/hubot/2016/07/16/hubot-slack.html

    map me 신한은행 되는 자비스 만들어보자.


8. Zeplin
Collaboration & handoff for designers and developers


    뭐라는지 모르겠어. 나중에 읽어야지.부제 : 제플린이 없었으면 어떻게 일했을꼬?
    http://blog.minimap.net/index.php/2017/02/02/sketch-zeplin/


9. Visual Studio Team Services
Collaborate and manage software projects online.

    나중에 알아볼일이다.
    https://happybono.wordpress.com/2016/11/29/%ED%98%91%EC%97%85%EA%B3%BC-%EC%BD%94%EB%93%9C%EA%B4%80%EB%A6%AC-%EB%91%90-%EB%A7%88%EB%A6%AC-%ED%86%A0%EB%81%BC%EB%A5%BC-%EC%9E%A1%EB%8A%94-visual-studio-team-services/

10. CircleCI
Continuous Integration and Deployment.

    [Android] CircleCI로 Github CI 구성

    http://blog.themuser.xyz/circleci%EB%A1%9C-github-ci-%EA%B5%AC%EC%84%B1/
    그렇게 해서 접하게 된 것이 바로 CircleCI 인데, 장점은 다음과 같다.
    – 서비스형이기 때문에 별도 호스팅이 필요 없음
    – 빌드 환경을 구성하는 것이 쉽고 간편함

    CircleCI: 커스텀 도커 이미지로 어플리케이션 빌드 시간 단축하기
    https://engineering.huiseoul.com/circleci-%EC%BB%A4%EC%8A%A4%ED%85%80-%EB%8F%84%EC%BB%A4-%EC%9D%B4%EB%AF%B8%EC%A7%80%EB%A1%9C-%EB%B9%8C%EB%93%9C-%EC%8B%9C%EA%B0%84-%EB%8B%A8%EC%B6%95%ED%95%98%EA%B8%B0-5c3a889bd2f7


11. New Relic
Real-time application performance management.

    오픈소스 모니터링 시스템 Prometheus #1
    https://blog.outsider.ne.kr/1254

12. PagerDuty
PagerDuty is your fastest path to incident resolution

    Pagerduty를 활용하여, 장애발생시 SMS알림받기
    http://jmyung.tistory.com/81


13. Travis CI
Test and Deploy your code with confidence

    Travis CI
    Travis CI 로고이름을 보는 순간 눈치를 채겠지만 Travis CI는 오픈소스 커뮤니티를 위한 지속적인 통합(continuous integration) 서비스입니다. 2011년 초 Ruby 커뮤니티를 위해 시작되었지만 지금은 수많은 언어를 지원하는 형태로 발전하였으면 Travis CI자체도 Github에서 관리되고 있으며 당연히 오픈소스 입니다. Github로 오픈소스가 엄청나게 활발해 지고 오픈소스 프로젝트를 위한 다양한 환경과 문화가 구성되었지만 그 중에 빠져있는 것이 CI 서버였습니다.(제가 모르는 어떤 것들이 있는지 모르겠네요.) 그래서 오픈소스로 개발을 하려고 하더라도 지속적인 통합을 위해서는 자체 서버에 허드슨이나 젠킨스를 두어야 했습니다.(CI 서버를 둔다고 지속적인 통합은 아니겠으나 일반적인 오픈소스가 회사보다 이런 부분이 잘 되어 있으니 CI 서버만 빠져있었다고 할 수 있습니다.) Travis CI는 오픈소스의 이러한 인프라 공백을 메워주는 서비스라고 할 수 있습니다.

    Travis CI 기부페이지를 보면 현재 5천여개의 프로젝트의 40만 이상의 테스트를 수행하고 있음을 보여주고 있습니다. 좀 더 써보고 더 맘에들면 기부하고 스티커라도 받아야 겠습니다. ㅎㅎㅎ

    현재 Travis CI는 Clojure, Erlang, Groovy Haskell, Java, JavaScirpt, Node.js, Perl PHP, Rython, Ruby, Scala의 언어를 지원하고 있습니다. 올초만 해도 동적언어만 지원하고 있었지만 올 3월에 Java를 포함해서 Scala와 Groovy에 대한 지원을 추가했습니다. Travis CI는 아주 다양한 환경의 테스트를 수행할 수 있도록 지원하고 있습니다. 위의 다양한 언어들을 포함해서 상당히 많은 종류의 데이터베이스가 이미 설치되어 있으며(물론 오픈소스 기준입니다.) Travis CI에서 지원하지 않는 영역에 대한 자유도를 폭 넓게 제공하고 있어서 빌드 나 테스트 전후로 라이브러리나 네이티브 모듈을 설치해서 테스트하는 것이 가능합니다. Travis CI를 써보려고 내용을 정리하다보니 가이드의 내용이 많아서 원래는 프로젝트에 Travis CI 적용하는 것을 적으려다가 약간 범용적인 내용을 따로 정리합니다.

14. Sentry
Real-time error logging for your applications.

    Sentry 를 이용한 Node.js 에러 모니터링
    https://ansuchan.com/nodejs-error-monitoring-with-sentry/


15. Pingdom
Uptime and performance monitoring.

    웹사이트 출력 속도를 점수로 확인할 수 있는 사이트 / Pingdom Website Speed Test
    http://www.erzsamatory.net/118

Crashlytics
Mobile crash analysis and reporting.

Lucidchart
Quickly and easily collaborate on diagrams

Datadog
SaaS app monitoring all in one place.

Rollbar
Full-stack error monitoring for developers.

Codeship
Continuous Integration and Deployment SaaS.

Jirio - JIRA Slack Integration
Create and manage JIRA issues from Slack

Nagios
Server monitoring and alerting.

Moqups
Shape your ideas and collaborate on wireframes, diagrams and prototypes

GitLab
Add GitLab slash commands

Bugsnag
Focused and powerful error monitoring for web, mobile, and server apps.

Marvel
Design and Prototyping for Everyone

Subversion
The Subversion software source control package.

Obie
Access knowledge, wikis and documents quicker without leaving Slack.

Lita
A chat bot scriptable with Ruby

OpsGenie
OpsGenie forwards alerts from your IT monitoring tools to notify users via mobile apps,


-------------------------------------------
프로그래머의 선택 : 7가지 우수한 깃허브 통합 사례
아사나(Asana) 아사나는 이메일 사용 없이 팀워크를 촉진하기 위한 프로젝트 관리 도구다. 웹 앱과 모바일 앱(iOS 및 안드로이드 기기용) 형태로 제공된다. 차트비트(Chartbeat)의 엔지니어링 담당 부사장 네이던 포터는 회사 전체적인 작업 관리에 아사나를 사용한다고 밝혔다. 실시간 웹 분석을 제공하는 차트비트는 깃허브를 통해 코드베이스를 관리한다. 포터는 "2012년에 내가 아사나-깃허브 통합 코드를 썼다"고 말했다. 깃허브의 오픈소스 플러그인 시스템이 이러한 통합 작업에 도움이 됐다. 깃허브에서 코드 커밋이 이루어지면 아사나에서 작업 ID가 생성되고 커밋에 대한 링크가 자동으로 첨부된다.


서클CI(CircleCI) 서클CI는 웹 개발자를 위한 지속적인 통합 및 배포 도구다. 인터컴(Intercom) CTO 시아란 리는 깃허브-서클CI 연결을 통해 상당한 시간을 절약할 수 있음을 발견했다. 웹 기업을 대상으로 고객과의 대화를 위한 도구를 제공하는 인터컴은 깃허브에 코드를 보관하고 서클CI를 통해 이 코드에 대한 테스트를 실행한다. 리는 "매일 많은 시간을 절약해준다"며, 두 가지를 연결하는 작업도 거의 자동으로 된다고 덧붙였다. 리가 발견한 유일한 문제는 깃허브에서 서클CI와 동시에 코드 품질 분석 도구인 코드 클라이밋(Code Climate)을 사용하려는 경우에 발생했다. 인터컴은 둘 중 하나를 선택해야 했지만 리는 것허브가 이 문제를 수정하기 위해 작업 중일 것이라고 생각한다.


클라우드비스(CloudBees) 클라우드비스는 젠킨스(Jenkins) 지속 통합을 활용하여 고객이 더 빠르게, 점진적으로 소프트웨어를 완성할 수 있도록 돕는 자바 PaaS 공급업체다. 민간 고객에게 최대 부하 및 에너지 전송에 대한 정보를 제공하는 버리디티 에너지(Viridity Energy)의 엔지니어링 담당 부사장인 던컨 드보어는 품질 보증 테스트와 프로덕션 환경에서, 그리고 바이너리용 리포지토리 용도로 클라우드비스를 사용한다고 말했다. 모듈형 분산 애플리케이션을 구축하는 이 회사는 깃허브에서 소스 코드를 조정하고 문제를 추적하며, 아무 문제 없이 깃허브와 클라우드비스를 통합해 사용하고 있다. 버리디티의 클라우드 기반 패러다임은 내부 시스템을 대체한다. 드보어는 "클라우드로 전환한 것은 비즈니스 소프트웨어를 개발하는 데 집중하고 배포 측면에 대해서는 신경을 쓰지 않기 위해서였다"고 말했다.

코드 클라이밋(Code Climate) 코드 클라이밋은 루비 온 레일스와 자바스크립트 프로젝트에 대한 정적 분석을 제공한다. 깃 서버에 저장된 코드에 접근하는 호스팅 서비스다. 접근은 인터넷을 통해 이루어진다. 크라우드펀딩 웹 사이트인 킥스타터(Kickstarter)는 코드 클라이밋-깃허브 통합을 사용해 버그를 찾는다. 킥스타터의 운영 엔지니어인 아론 석스는 "깃허브에 코드를 푸시하면 웹 후크에서 코드 클라이밋에 변경 사항을 분석하라는 지시를 자동으로 보낸다"며, "코드 클라이밋 결과는 풀 요청에 연결된다. 또한 코드 클라이밋은 개발자에게 이메일 및 채팅룸을 통해 중요한 이벤트를 알린다"고 말했다. 킥스타터는 깃허브 풀 요청에 의견을 게시하기 위한 용도로도 코드 클라이밋 기능을 사용한다.

피보탈 트래커(Pivotal Tracker) 피보탈 트래커는 피보탈 랩(Pivotal Labs)의 애자일 프로젝트 관리 도구다. 의료 저널 큐어러스(Cureus)는 피보탈 트래커를 사용해서 깃허브 코드 리포지토리와 연계하여 작업을 관리한다. 큐어러스의 엔지니어링 담당 부사장 크리스 바레토는 "각 리포지토리 커밋에서 커밋을 작성한 개발자 쌍과 트래커 스토리 ID 및 상태를 포함한다"면서 "커밋이 깃허브의 마스터 브랜치로 올라가면 트래커에서 스토리가 새 상태로 업데이트되고 스토리 주석 내에 깃허브 커밋이 내장된다"고 말했다. 큐어러스는 피보탈 트래커-깃허브 통합의 결과에 대단히 만족하지만, 피보탈 트래커의 프로젝트당 알림 설정을 포함한 일부 기능은 개선의 여지가 있다고 밝혔다.


트래비스 CI(Travis CI) 호스팅 버전과 방화벽 내부 버전, 두 가지 모두로 제공되는 트래비스 CI는 지속 통합, 배포 및 테스팅을 위한 도구다. 온라인 소매업체 모드클로스(ModCloth)는 1년 전에 관리 오버헤드를 줄이기 위해 젠킨스 서버에서 트래비스 CI로 전환했고, 이후 깃허브 코드 리포지토리와 함께 트래비스 CI를 사용하고 있다. 모드클로스의 선임 소프트웨어 엔지니어인 댄 벅은 깃허브와 트래비스 CI가 깃허브 API를 통해 상호작용한다고 전했다. 벅은 깃허브에 대해 만족하지만 모드클로스의 경우 깃허브 플랫폼에서 사소한 문제가 있다며 "우리가 원하는 만큼 빠르게 기능을 제공하지 못한다"고 말했다.


텐엑서(TenXer) 텐엑서 업무생산성 분석 도구는 깃허브를 포함해서 팀이 이미 사용하는 서비스에서 데이터를 가져오는 방법으로 엔지니어에게 업무 방식에 대한 시야를 제공한다. 텐엑서의 마케팅 담당자 JP 파틸은 깃허브와의 통합은 표준 깃허브 API를 통하거나 깃허브 오스(OAuth)를 사용해 텐엑서에 가입하는 방법으로 이루어진다고 말했다. 파틸은 "깃허브 엔터프라이즈 사용자의 경우 고객은 텐엑서 에이전트를 방화벽 내에 설치해야 한다. 텐엑서 에이전트는 동일한 API를 통해 깃허브 엔터프라이즈와 통신하지만, 보안 포트를 통해 필요한 데이터를 텐엑서의 서버로 푸시할 수 있다"고 말했다. 깃허브 사용자가 텐엑서에 API를 통한 데이터 접근 권한을 부여하는 경우 텐엑서는 분석을 수행하기 위한 다양한 메트릭과 데이터 포인트를 추적할 수 있다.