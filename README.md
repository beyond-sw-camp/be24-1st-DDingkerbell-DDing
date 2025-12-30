<p align="center">
<img width="500" alt="ChatGPT_Image_2025_12_30_11_24_18" src="https://github.com/user-attachments/assets/6857892f-f320-48f8-8ee4-4be17a77fc10" />

# 

# 👨‍💻👩‍💻**Team introduction**

- 👨‍💻 권민석 — Backend
- 👨‍💻 김사라 — Backend
- 👨‍💻 김미정 — Backend
- 👨‍💻 노승찬 — Backend
- 👨‍💻 이한별 — Backend

## 📍 위치 기반 공동구매 매칭 플랫폼

> 지역 기반 공동구매 매칭 플랫폼을 통한
1인 가구 생활비 절감과 동네 커뮤니티 활성화
> 

혼자서 감당하기 힘든 소비와 활동을

동네 사람들과 함께 **‘사고 · 쓰고 · 모이는’**

생활 밀착형 지역 플랫폼

## 📍 프로젝트 소개

본 프로젝트는 **GPS 기반 지역 인증**을 활용한

**동네 중심 공동구매 매칭 플랫폼**이다.

대용량 소비, 혼자 하기 어려운 활동,

단절된 이웃 관계라는 문제를 해결하기 위해

공동구매를 매개로 **사람과 생활을 연결하는 구조**를 제안한다.

## 📍 기술스택
### DATABASE
 ![mariadb](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white) ![mysql](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white) 

 ### TRAFFIC MANAGEMENT
![grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white) 
![haproxy](https://camo.githubusercontent.com/6bcf8603439a2934f709666a80c2ffdac14d64552d02e5fa1219a2a6f38428ad/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f484150726f78792d3145393046463f7374796c653d666f722d7468652d6261646765266c6f676f3d686170726f7879266c6f676f436f6c6f723d7768697465) ![JMeter](https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white)

### 협업
 ![github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) ![NOTION](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)



## 📍 프로젝트 기획안

 [Google Docs 기획안](https://docs.google.com/document/d/1VzyXLjJqwQZyX-jUeKYUx8Nn9bLWR6anQaBtFDBwXP8/edit?tab=t.0)



## 📍 요구사항 정의서

[요구사항 정의서](https://docs.google.com/spreadsheets/d/1vy4meR1GHU6tSzcL6rbRh7OsKovU3FEhKYtpDsHK8-s/edit?usp=sharing)



## 📍 ERD
<details>
<summary>ERD 펼쳐보기</summary>

<p align="center">
  <img src="https://github.com/user-attachments/assets/427dc229-dfde-4ff1-a329-088245cdd44d" width="510">
</p>

</details>

## 📍 시스템 아키텍처
<details>
<summary>시스템 아키텍쳐 펼쳐보기</summary>

 <p align="center">
<img width="550" alt="3D58072F-61AD-47EA-8278-B7B328D72380" src="https://github.com/user-attachments/assets/d8a05e1a-f8f9-4b19-8d67-a88a90b9189c" />

본 구조에서는 HAProxy를 DB 접근의 단일 진입점으로 두어 쓰기 트래픽은 Master DB로 직접 전달하고, 읽기 트래픽은 Slave DB 풀로 분산 처리하였다. 이를 통해 조회 부하를 분산시키고 Master DB를 보호함으로써 성능 저하 및 병목 현상을 방지하도록 설계하였다.
</details>




































