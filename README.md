# ❄️ 손쉬운 시각화 조건 검색 서비스 ❄️

## 🏡 서비스 개요 ##
주식 초보, 일반 투자자들이 눈송이 모양의 그래프를 통해서 손쉽게 자신의 투자 기준에 맞는 종목을 찾을 수 있는 서비스

<img width="854" alt="스크린샷 2025-03-17 오전 11 09 19" src="https://github.com/user-attachments/assets/f36ccef4-b73e-472b-9498-778749f7edcd" />

배포 URL : https://snowper.shop/

<br>

## 📌 주요 기능

- **Snowflake 그래프 사용자 맞춤 필터 설정**
    
    : 시가총액, 매출액 , 영업이익, 당기순이익 등 여러 요소들 중 사용자가 원하는 요소를 골라 검색할 수 있습니다.
    
- **개별 종목 - 경쟁사 그래프 조회**
    
    : 같은 섹터에 포함된 경쟁사들의 시가총액, PER, 부채비율, 배당수익률, 외국인 보유률을 snowflake 그래프로 확인 할 수 있습니다.
    
- **나의 포트폴리오 | 공유 포트폴리오**
    
    : 포트폴리오에 포함된 종목에 대한 **평균 시가총액, 평균 PER, 평균 부채비율, 평균 배당**을 보여줍니다. **다른 사람들이 공유한 포트폴리오** 또는 **전문가 포트폴리오**를 확인하고, 전략을 참고하여 더 나은 투자 결정을 내릴 수 있습니다.
    
- **커뮤니티 댓글**
    
    : **종목** 및 **공유 포트폴리오**에 대해 **투자자 간 의견을 교환**하거나 **지표/전략을 공유**할 수 있는 **환경을 제공**합니다.
    
- **텔레그램 알림 설정**
    
    : 나의 포트폴리오별 알림 설정을 통해서 매일 8시마다 포트폴리오에 포함된 종목들의 **현재가**와 **등락률**을 **텔레그램 봇**을 통해 받을 수 있습니다.

<br>

## 📌 아이디어 도출
- **기존 주식 조건 검색의 문제점**
  - **접근성 : 초보 투자자가 접근하기 어려움**
  - **속도: 여러 조건과 무거운 기능으로 종목 검색 속도가 느림**
  - **기술적 분석 위주: 초보, 일반 투자자들이 주로 사용하는 펀드멘탈 분석 조건보다 
기술적 분석 조건이 과하게 많고 중점이 됨**

## ❄️ Snowper의 솔루션
**초보, 일반 투자자가 손쉽게 자신의 투자 기준에 맞는 종목을 찾을 수 있는 서비스를 만들자**

- **시각적 직관성**: 눈송이(Snowflake) 그래프를 통해 종목 정보를 한눈에 파악
  - 복잡한 숫자 데이터를 시각화하여 초보 투자자도 쉽게 이해 가능
  - 여러 지표를 동시에 비교할 수 있는 직관적인 그래프 제공
  
- **사용자 중심 검색**: 초보 투자자가 접근하기 쉬운 검색 시스템 구현
  - 시가총액, 매출액, 영업이익 등 기본적인 펀드멘탈 지표 중심 검색
  - 필요한 조건만 선택하여 간편하게 검색 가능한 인터페이스



## 팀원 구성

<div align="center">

| **김도은(BE)** | **박준승(BE)** | **이수용(BE)** | **이유진(FE)** | **장한영(BE)** |
| :------: |  :------: | :------: | :------: | :------: |
| [<img src="https://avatars.githubusercontent.com/u/143738200?v=4" height=150 width=150> <br/> @doeuni](https://github.com/doeuni) | [<img src="https://avatars.githubusercontent.com/u/125808024?v=4" height=150 width=150> <br/> @Pasak22](https://github.com/Pasak22) | [<img src="https://avatars.githubusercontent.com/u/69045133?v=4" height=150 width=150> <br/> @leesuyong4029](https://github.com/leesuyong4029) | [<img src="https://avatars.githubusercontent.com/u/98758209?v=4" height=150 width=150> <br/> @ZZZINU](https://github.com/ZZZINU) | [<img src="https://avatars.githubusercontent.com/u/28581494?v=4" height=150 width=150> <br/> @qpwisu](https://github.com/qpwisu) |

</div>
<br> <br>

## 🛠️ 개발스택
### Front-End
<div>
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> 
  <img src="https://img.shields.io/badge/typescript-007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=ffd35b" />
  <img src="https://img.shields.io/badge/React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white" />
  <img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" />
  &nbsp
  <br>
</div>

### Back-End
<div>
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white">
  
  <img src="https://img.shields.io/badge/Spring Data JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/MyBatis-000000?style=for-the-badge&logo=mybatis&logoColor=white">
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON Web Tokens&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Spring Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/Spring Cloud Gateway-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/Netflix Eureka-E50914?style=for-the-badge&logo=netflix&logoColor=white">
  <img src="https://img.shields.io/badge/Spring Cloud OpenFeign-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/Spring Batch-6DB33F?style=for-the-badge&logo=spring&logoColor=white">

</div>

### Devops
<div>

  <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"> 
  <img src="https://img.shields.io/badge/AWS RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white"> 
  <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"> 
  <img src="https://img.shields.io/badge/AWS CloudFront-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Route 53-8C4FFF?style=for-the-badge&logo=amazonroute53&logoColor=white"> 
  <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white"> 
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"> 
  <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"> 
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
</div>

### DB
<div>
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/mongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white">
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white"> 
</div>

## 🔧 ERD ##
<img src = "https://github.com/user-attachments/assets/12a0b9d6-4607-4c7c-aa0b-7901ed6837f1">

## 🧑‍💻 아키텍처 ##
<img src = "https://github.com/user-attachments/assets/0b865cca-ed9f-445f-a097-65fc8b76fea8">



