# 이유찬 (Yuchan Lee)

[![GitHub](https://img.shields.io/badge/-lasuillard-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lasuillard)
[![이메일](https://img.shields.io/badge/-lasuillard@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:lasuillard@gmail.com)
[![블로그](https://img.shields.io/badge/-lasuillard.me-FF5722?style=flat-square&logo=blogger&logoColor=white)](https://lasuillard.me)

Python과 AWS 기반의 백엔드 시스템 개발을 전문으로 하는 개발자입니다. 확장 가능한 백엔드 시스템과 클라우드 인프라 구축에 열정을 가지고 있으며, 개발 워크플로우 및 CI/CD 파이프라인 자동화를 통해 개발 효율성을 높이는 것을 중요하게 생각합니다. 현재는 Infrastructure as Code와 DevOps 모범 사례를 꾸준히 학습하며 더 나은 개발 문화를 만들어가고자 노력하고 있습니다.

## 🛠️ 기술

### 프로그래밍 언어
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white)

### 프레임워크 및 라이브러리
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=Django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/-Django_REST_Framework-A30000?style=flat-square&logo=Django&logoColor=white)
![Django Ninja](https://img.shields.io/badge/-Django_Ninja-092E20?style=flat-square&logo=Django&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=Celery&logoColor=white)
![Selenium](https://img.shields.io/badge/-Selenium-43B02A?style=flat-square&logo=Selenium&logoColor=white)
![Twisted](https://img.shields.io/badge/-Twisted-000000?style=flat-square&logo=Python&logoColor=white)

### 클라우드 및 인프라
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/-AWS_Lambda-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS ECS](https://img.shields.io/badge/-AWS_ECS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS Elastic Beanstalk](https://img.shields.io/badge/-AWS_Elastic_Beanstalk-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS RDS](https://img.shields.io/badge/-AWS_RDS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS Redshift](https://img.shields.io/badge/-AWS_Redshift-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS DMS](https://img.shields.io/badge/-AWS_DMS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/-Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Pulumi](https://img.shields.io/badge/-Pulumi-8A3391?style=flat-square&logo=pulumi&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Windows Server](https://img.shields.io/badge/-Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)

### 데이터베이스
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=Redis&logoColor=white)
![ClickHouse](https://img.shields.io/badge/-ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)

### 개발 도구
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

## 💼 경력

### 얼리페이 (EarlyPay) - 백엔드 엔지니어
**2023년 12월 - 2025년 6월**

선정산 서비스가 안정적으로 운영될 수 있도록 다양한 백엔드 시스템을 개발하고 유지보수하였습니다. 정산 및 크롤러 서비스 개발부터 인프라 구축 및 관리까지 폭넓은 업무를 담당하였습니다.

#### 📝 주요 담당 업무

- **선정산 서비스 개발 및 유지보수**
  - Django로 작성된 선정산 서비스의 유지보수 및 신규 기능 개발을 담당
  - Celery 구성 전반을 관리하여 워커 및 큐 구성을 최적화하고 동적 라우팅, 작업 처리 속도 제어 등을 활용해 작업 병목을 해소하고 전반적인 정산 업무 속도를 향상
  - 의존성 관리 및 배포 프로세스를 개선하고 서비스 가용성을 높이기 위해 Elastic Beanstalk 환경에서 AWS ECS로 이전
  - 복잡한 구성의 레거시 VPC를 새 VPC로 마이그레이션하여 유지보수성을 향상
  - AWS RDS의 표준 지원이 종료된 PostgreSQL 12에서 PostgreSQL 15로 블루-그린 배포 전략을 사용한 무중단 업그레이드

- **크롤러 개발 및 유지보수**
  - 웹 데이터 수집을 위한 FastAPI 기반 크롤러의 구성 및 유지보수, 봇 탐지 우회 및 신규 기능 개발
  - 단일 서버에서 운영되던 크롤러를 AWS Lambda로 이전 후, 봇 탐지 우회를 위한 시스템 리소스 수준 증가로 AWS ECS 환경으로 재이전
  - 오토 스케일링을 통해 크롤러의 확장성 및 가용성을 향상시키고 비용을 효율적으로 관리
  - 일부 VAN사 사이트의 IP 차단 문제 해결을 위한 IP 로테이션 기능 도입으로 크롤러 안정성 향상
  - 사이트 보안 프로그램(보안 키패드) 때문에 자동화하지 못했던 일부 VAN사 크롤러를 Windows Server 및 OpenCV를 활용하여 개발
  - 반자동으로 처리하던 매출 수집 작업을 완전 자동화하여 정산 업무의 효율성 향상

- **인프라 구축 및 관리**
  - Pulumi를 활용한 AWS 인프라 구성의 코드 관리로 인프라 버전 관리 및 재현성을 향상시키고 인프라 변경 사항 추적 가능
  - 개발자가 직접 일부 인프라를 관리할 수 있도록 GitHub Actions을 활용한 셀프 서비스 워크플로 구축
  - 개발 데이터베이스를 운영 데이터베이스 스냅샷으로부터 재구성할 수 있도록 하며 데이터 마스킹 등의 필수 후처리 지원
  - TIPS 프로젝트의 일환으로 AWS Redshift를 활용한 데이터 웨어하우스 구축
  - AWS Database Migration Service (DMS)를 활용하여 연관 데이터베이스로부터 데이터를 실시간으로 Redshift로 복제
  - 대규모 데이터 분석 및 보고서 생성을 위한 기반 마련 및 Grafana를 활용한 BI 대시보드 구축
  - 불필요하거나 과다한 리소스를 식별하고 제거하여 인프라 비용을 최적화하고 운영 비용 절감

- **그 외**
  - Python 코드 품질 향상을 위해 Ruff, MyPy 등의 도구를 사용한 코드 검사 및 자동화 테스트 도입으로 코드 일관성 유지 및 버그 사전 방지
  - GitHub Actions를 활용한 코드 검사 및 테스트 자동화로 개발 과정에서 자주 발생하는 실수(예: Django Migrations) 사전 방지
  - 개발 문화 형성을 위한 테크 세션 주도로 개발팀의 기술 역량 향상 및 팀원들과의 지식 공유 촉진
  - 팀 내에서 최신 기술 동향과 모범 사례를 공유하고 개발 프로세스 개선을 위한 아이디어 논의

#### 🛠️ 사용 기술
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/-AWS_Lambda-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS ECS](https://img.shields.io/badge/-AWS_ECS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS RDS](https://img.shields.io/badge/-AWS_RDS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS Redshift](https://img.shields.io/badge/-AWS_Redshift-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS DMS](https://img.shields.io/badge/-AWS_DMS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=Celery&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=Django&logoColor=white)
![Django Ninja](https://img.shields.io/badge/-Django_Ninja-092E20?style=flat-square&logo=Django&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Pulumi](https://img.shields.io/badge/-Pulumi-8A3391?style=flat-square&logo=pulumi&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=Redis&logoColor=white)
![Selenium](https://img.shields.io/badge/-Selenium-43B02A?style=flat-square&logo=Selenium&logoColor=white)
![Windows Server](https://img.shields.io/badge/-Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)

### 에이젠글로벌 (AIZEN Global) - 백엔드 엔지니어
**2022년 12월 - 2023년 8월**

우리카드 FDS 고도화 프로젝트에 참여하여 대용량 데이터 처리 시스템의 유지보수 및 개발 업무를 수행하였습니다.

#### 📝 주요 담당 업무

- **우리카드 FDS 고도화**
  - 일일 약 700만 건의 요청을 처리하는 Python Twisted 기반 FDS 스코어링 서버의 유지보수 및 신규 기능 개발
  - 스코어 산출에 사용 중인 ClickHouse를 관리하며 대용량 데이터를 처리하고 분석

#### 🛠️ 사용 기술
![ClickHouse](https://img.shields.io/badge/-ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Docker Compose](https://img.shields.io/badge/-Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=Redis&logoColor=white)
![Twisted](https://img.shields.io/badge/-Twisted-000000?style=flat-square&logo=Python&logoColor=white)

### 얼리페이 (EarlyPay) - 백엔드 엔지니어
**2021년 6월 - 2021년 12월**

얼리페이 스타트업 초기 멤버로 참여하여 오프라인 매출 선정산 서비스의 기반을 구축하였습니다.

#### 📝 주요 담당 업무

- **오프라인 선정산 서비스 개발**
  - Django 프레임워크를 활용한 웹 서버 개발
  - PostgreSQL 데이터베이스 구축 및 관리, Redis를 캐시 서버로 사용
  - 프론트엔드와의 통신을 위해 Django REST Framework를 활용한 API 서버 개발
  - Celery 및 Celery Beat를 활용한 비동기 작업 및 주기적인 작업 처리
  - 매출을 비롯한 여러 정산 데이터 수집 및 정산 작업 수행, Redis를 메시지 브로커로 사용
  - Celery Beat를 활용한 주기적인 작업 관리 및 Flower를 활용한 작업 모니터링
  - AWS Elastic Beanstalk을 활용한 서버 배포 및 GitHub Actions를 활용한 배포 자동화

- **카드매출 데이터 수집을 위한 웹 크롤러 개발**
  - 카드 매출 및 다양한 정산 데이터를 수집하기 위한 크롤러 서버 개발
  - 약 10개 남짓의 VAN사 및 CFA, 카드사 가맹점 정보 등 다양한 사이트에서 데이터 수집
  - HTTP 기반 및 Selenium을 활용한 웹 브라우저 기반 크롤러 구현
  - 기존 Flask 기반 크롤러 구현을 FastAPI로 재작성하여 성능 개선

#### 🛠️ 사용 기술
![AWS Elastic Beanstalk](https://img.shields.io/badge/-AWS_Elastic_Beanstalk-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=Celery&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=Django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/-Django_REST_Framework-A30000?style=flat-square&logo=Django&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=Redis&logoColor=white)
![Selenium](https://img.shields.io/badge/-Selenium-43B02A?style=flat-square&logo=Selenium&logoColor=white)

## 🎓 학력

### 서울과학기술대학교 (Seoul National University of Science and Technology)
**2014년 3월 - 2020년 2월**

- 컴퓨터공학 학사 (Bachelor's degree in Computer Engineering)
- 학점: 4.11/4.5

## 📜 자격증

- **정보처리기사** - 한국산업인력공단 (2020년 8월 28일)
- **TOEIC** - ETS (2018년 9월 15일) - 점수: 935/990
- **정보기기운용기능사** - 한국산업인력공단 (2016년 12월 5일)
- **정보처리기능사** - 한국산업인력공단 (2015년 2월 5일)

---

<div align="center">

_Updated with assist of AI at 2025-07-03T10:32:02Z_

</div>
