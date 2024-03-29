# 🏆 C-YES! - 실시간 CS 퀴즈 서비스

![Imgur](./exec/images/title.gif)

# 📌목차

-   [프로젝트 진행 기간](#-프로젝트-진행-기간)
-   [개요](#-개요)
-   [프로젝트 구조](#-프로젝트-구조)
-   [주요 기술](#-주요-기술)
-   [기능 및 서비스 화면](#-기능-및-서비스-화면)
-   [프로젝트 파일 구조](#-프로젝트-파일-구조)
-   [팀원](#-팀원)
-   [프로젝트 산출물](#-프로젝트-산출물)


<br>

# 🎞 프로젝트 진행 기간

#### - 2023.10.09(화) ~ 2023.11.17(금) (39일간 진행)

#### - SSAFY 9기 2학기 자율프로젝트

<br>


# ✨ 개요

#### - CS학습의 중요성은 알고있지만 알고리즘/개발 공부하기에 바쁜 일정, 광범위하고 어려운 학습 방법은 항상 취준생들의 숙제로 남아있다.

#### - 따라서 언제 어디서나 친구와 함께하는 C-YES를 통해 문제를 해결하고자한다.

<br>

# 📋 프로젝트 구조
![architecture](https://github.com/Seolang/C-YES/assets/26866109/57a5f946-a414-469b-8020-3e03ef2ebb17)

<br>

# 🛠 주요 기술

**Backend**
<br>

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/springsecurity-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/junit5-25A162?style=for-the-badge&logo=junit5&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">

-   Java : Oracle OpenJDK 11
-   SpringBoot 2.7.17
-   Spring Data Jpa
-   queryDSL 5.0.0
-   Junit 4.13.1
-   Gradle 7.6.1
-   MySQL 서버 : latest
-   MongoDB 4.4.25
-   Redis 7.2.3

<br>

**FrontEnd**
<br>

<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">&nbsp;<img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/styled components-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">&nbsp;

-   React 18.2.0
-   Node.js 16.16.0
-   TypeScript 5.0.4
-   Redux 8.0.5
-   Redux-toolkit 1.9.4
-   Redux-persist 6.0.0
-   Styled-component 5.3.9
-   Axios 1.3.5

<br>

**CI/CD**
<br>

<img src="https://img.shields.io/badge/aws ec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/openssl-721412?style=for-the-badge&logo=openssl&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">&nbsp;

-   AWS EC2
-   Ubuntu 20.04 LTS
-   Jenkins 2.414.3
-   Docker Engine 24.0.5
-   Nginx 1.18.0
-   SSL
-   Grafana latest
-   Prometheus 2.44.0
-   netdata

<br>

**협업 툴**
<br>

<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jirasoftware&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/mattermost-0058CC?style=for-the-badge&logo=mattermost&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/figma-EA4335?style=for-the-badge&logo=figma&logoColor=white">&nbsp;

-   형상 관리 : Git
-   이슈 관리 : Jira
-   커뮤니케이션 : Mattermost, Notion
-   디자인 : Figma

<br>

# 💻 기능 및 서비스 화면

### 0️⃣ 실시간 퀴즈 서비스

#### - 공지된 시간전까지만 실시간 퀴즈에 참여할 수 있다.

#### - 실시간 퀴즈가 시작되면 출제된 퀴즈를 풀 수 있다.

#### - 문제마다 20초씩 주어지며, 각각의 문제가 끝날때마다 정답을 맞춘 인원과 전체 인원이 나온다.

#### - 모든 문제가 끝나고 나면 3등까지 순위표가 나타나고 퀴즈는 끝이 난다.

<p align="center">
<img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/7c32d726-d4db-4310-b0ff-ffb7414ee569" width="32%">
<img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/e1888a95-94f9-4a26-8d57-28c22ec6ace0" width="32%">
<img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/2188de1e-940c-47ee-b208-fa0ff71650a2" width="32%">
</p>

<br>

### 1️⃣ 문제은행 서비스

#### - 스스로 문제들을 학습할 수 있는 페이지이다.

#### - 문제 유형은 카드학습, 객관식, O/X로 구성되어있다.

#### - 문제 카테고리는 데이터베이스, 자료구조, 디자인 패턴, 컴퓨터구조, 알고리즘, 네트워크 운영체제가 있다.

<p align="center">
<img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/b072f507-5bb7-4900-9878-25c95f735cf6" width="32%">
<img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/ea99d35f-84bd-473c-bf25-eb73f1d853cb" width="32%">
<img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/567c18b0-be06-4a05-8fcc-96f21218771e" width="32%">
</p>

<br>

### 2️⃣ 그룹퀴즈 서비스

#### - 실시간 퀴즈 방식과 비슷하지만 원하는 사람들만 모아서 그룹퀴즈를 진행할 수 있다.

#### - 또한, 퀴즈방을 자유롭게 열어서 검색을 통해 퀴즈방에 입장할 수 있다.

<p align="center">
<img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/98fcc12a-cdf1-4950-8d7b-cf21ab317bd3" width="32%">
<img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/232b27e9-a87e-4a91-9ba3-04e5b05f0c11" width="32%">
<img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/876ea994-3790-459f-8034-3884991647e5" width="32%">
</p>

<br>

# 👩‍💻 팀원

|                                                                     우승빈                                                                      |                                                                     배수빈                                                                      |                                                                     우수인                                                                      |                                                                     유혜빈                                                                      |                                                                     유태영                                                                      |                                                                     조준희                                                                      |
| :---------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/969f0a0f-1724-4c82-ae8e-2f968a53bdb0" width="120" height="160"> | <img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/2433a282-13cd-482f-95b6-cba931708bf1" width="120" height="160"> | <img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/4faaddeb-e8fc-4b5f-80da-89308050bb15" width="120" height="160"> | <img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/03eeff3b-4775-400d-a76f-3a48ca7737c4" width="120" height="160"> | <img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/8ab648dd-ce59-47bb-aa24-9d419ea5f687" width="120" height="160"> | <img src="https://github.com/Seolang/C-Yes_CS_practice_platform/assets/26866109/36129bce-e5c9-4de4-8bfb-244cbb1943be" width="120" height="160"> |
|                                                                Leader & Backend                                                                 |                                                                    Frontend                                                                     |                                                                    Frontend                                                                     |                                                                      Infra                                                                      |                                                                     Backend                                                                     |                                                                     Backend                                                                     |

<br>


# 📋 프로젝트 산출물

-   [API 명세서](https://opalescent-appliance-551.notion.site/API-c9cdccd9338e409698efd89e495d1052?pvs=4)
-   [ERD](https://www.erdcloud.com/d/aReBoHxvGA84SdeaT)
-   [와이어프레임](https://www.figma.com/file/EHttBkzorg0ZYZp0YbVavo/%EA%B2%BD%EC%B6%95%EB%B9%84-c-yes?type=design&node-id=303-2&mode=design)
-   [시스템 아키텍처](https://www.canva.com/design/DAF0VGnfH20/yiLXKm1KIPTV1KpNKnaTkw/edit)

<br>


