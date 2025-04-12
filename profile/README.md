# 📈 AI 기반 암호화폐 뉴스 & 시세 분석 서비스

초보 투자자도 시장 흐름을 쉽게 이해할 수 있도록 암호화폐 관련 뉴스와 시세 정보를 제공하고 AI모델을 이용해 뉴스를 감성 분석하여 전망을 제시하는 서비스입니다.

## 개발 기간
2025.01.31~2025.04.03

## 프로젝트 소개
본 프로젝트는 암호화폐 시세, 뉴스, 전망을 실시간으로 제공하는 사용자 친화적인 웹사이트를 구축하는 것을 목표로 합니다. 복잡한 암호화폐 시장 정보를 직관적이고 쉽게 이해할 수 있도록 설계하였으며, AI 기반 뉴스 감성 분석을 활용하여 시장 분위기 및 개별 암호화폐의 상태를 예측하고, 사용자에게 명확한 인사이트를 제공합니다.
이를 통해 투자자들이 보다 빠르고 정확한 정보를 기반으로 더 나은 결정을 내릴 수 있도록 지원하며, 실시간 데이터 및 감성 분석을 바탕으로 코인의 성장 가능성을 직관적으로 파악할 수 있도록 합니다.

## 지원 기능
<img width="520" src="https://github.com/user-attachments/assets/811e5dbb-9625-4c9c-bf23-c1ccd2bbc40d" />

## 📁 프로젝트 구성 리포지토리

- Frontend
    - [front-repo](https://github.com/profect-Oops/front-repo)  : 사용자 인터페이스 구현

- Backend
    - [back-repo](https://github.com/profect-Oops/back-repo)  : Spring Boot 기반 API 서버, DB 연동 및 비즈니스 로직

- AI / 데이터 파이프라인
    - [AI-repo](https://github.com/profect-Oops/AI-repo)  : AI 모델 기반 뉴스 감성 분석 및 데이터 수집 자동화

- Cloud / 인프라
    - [Cloud-repo](https://github.com/profect-Oops/Cloud-repo)  : Terraform, Jenkins, ArgoCD 기반 클라우드 인프라 구성

    - [oops-k8s-manifests](https://github.com/profect-Oops/oops-k8s-manifests)  : Kubernetes 매니페스트 및 Helm / ArgoCD 배포 관리



## 📚 기술 스택
| **Category**      | **Technologies** |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Frontend**       | <img src="https://img.shields.io/badge/JavaScript(ES6)-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> |
| **Backend**        | <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/REST API-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/WebSocket-000000?style=for-the-badge&logo=websocket&logoColor=white"> <img src="https://img.shields.io/badge/OAuth2.0-2FADFF?style=for-the-badge&logo=oauth&logoColor=white"> |
| **Database**       | <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"> |
| **Infrastructure** | <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"> <img src="https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white"> <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white"> <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"> |
| **CI/CD**          | <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"> <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white"> |
| **Monitoring**     | <img src="https://img.shields.io/badge/CloudWatch-232F3E?style=for-the-badge&logo=amazoncloudwatch&logoColor=white"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"> <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"> <img src="https://img.shields.io/badge/Loki-0E6E9C?style=for-the-badge&logo=loki&logoColor=white"> |
| **Data Pipeline**  | <img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white"> <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white"> <img src="https://img.shields.io/badge/Crontab-Linux_Scheduler-004050?style=for-the-badge&logo=linux&logoColor=white" /> |
| **AI**             | <img src="https://img.shields.io/badge/GPT API-412991?style=for-the-badge&logo=openai&logoColor=white"> <img src="https://img.shields.io/badge/SVM-Support_Vector_Machine-blue?style=for-the-badge" /> |



## 👥 팀 소개(PROFECT-1Team)

### Oops! : 객체지향 프로그래밍을 실천하는 개발자들 

팀원 한 명 한 명이 객체(Object)이며, 이 객체들이 모여 하나의 시스템을 만들어갑니다.
우리는 때때로 실수(Oops)를 할 수도 있지만, 객체지향적 사고(OOP)를 통해 문제를 해결하고 성장해 나갑니다. 각자의 개성과 역량을 존중하며, 하나의 목표를 향해 나아가는 우리 팀은 다양한 객체들이 유기적으로 연결되어 조화를 이루는 하나의 시스템입니다.

우리는 협력과 도전을 통해 더욱 빛나는 성과를 만들어가고자 합니다


### 팀원 역할 및 소개 :

- **고혜민**  
  프로젝트 총괄 / Cloud / Infra / FE 개발

- **이소민**  
  Cloud / Infra / FE 개발

- **이명진**  
  BE / FE 개발 / Cloud / Infra

- **소진영**  
  인공지능 개발자 / 데이터 엔지니어

- **백선영**  
  인공지능 개발자 / 데이터 엔지니어


| ![@apaals2](https://github.com/apaals2.png) | ![@MJLee39](https://github.com/MJLee39.png) | ![@baikAnalyst](https://github.com/baikAnalyst.png) | ![@logxingit](https://github.com/logxingit.png) | ![@sojy001-git](https://github.com/sojy001-git.png) | ![@kkmdevel](https://github.com/kkmdevel.png) |
|--------------------------------------------|---------------------------------------------|--------------------------------------------------|-----------------------------------------------|---------------------------------------------------|--------------------------------------------|
| **고혜민**<br>[@apaals2](https://github.com/orgs/profect-Oops/people/apaals2) | **이명진**<br>[@MJLee39](https://github.com/orgs/profect-Oops/people/MJLee39) | **백선영**<br>[@baikAnalyst](https://github.com/orgs/profect-Oops/people/baikAnalyst) | **이소민**<br>[@logxingit](https://github.com/orgs/profect-Oops/people/logxingit) | **소진영**<br>[@sojy001-git](https://github.com/orgs/profect-Oops/people/sojy001-git) | **김경민**<br>[@kkmdevel](https://github.com/orgs/profect-Oops/people/kkmdevel) |



