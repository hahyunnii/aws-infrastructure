# AWS Infrastructure & Server Engineering Portfolio

AWS 기반 인프라 구축 및 자동화, 고가용성 아키텍처, 성능 테스트 및 모니터링 프로젝트를 정리한 포트폴리오입니다.

서버 인프라 구성부터 서비스 가용성 확보, 성능 검증 및 모니터링까지 서버 엔지니어링과 관련된 프로젝트 경험을 담았습니다.

## Featured Projects

### 1. Approval Load Test & Monitoring

**AWS 기반 웹 애플리케이션 성능 테스트 및 통합 모니터링 체계 구축**

[GitHub Repository](https://github.com/hahyunnii/approval-loadtest-monitoring)

1만 명 규모의 사내 업무시스템을 가정하여 결재 시스템의 부하 테스트, 성능 병목 분석, 인프라 확장 및 장애 탐지·알림 체계를 검증한 프로젝트입니다.

**Technologies**
- **AWS Infrastructure:** EC2, Application Load Balancer (ALB), Amazon RDS for MySQL, S3, IAM, Systems Manager (SSM)
- **Infrastructure as Code:** Terraform
- **Backend:** Java 21, Spring Boot 3, Apache Tomcat, HikariCP
- **Load Testing:** k6, HTTP API 부하 테스트, 성능 지표 분석
- **Monitoring & Alerting:** Amazon CloudWatch Dashboards, CloudWatch Alarms, 응답시간(p50/p99), HTTP 5xx, CPU·메모리 사용률, 헬스체크
- **Database Optimization:** MySQL 복합 인덱스, 실행 계획(EXPLAIN), 쿼리 성능 분석
- **Resilience Testing:** 서버 장애 주입, ALB 헬스체크 기반 장애 탐지 및 복구 시간 측정
- **Security:** 보안 그룹, IAM 최소 권한, Systems Manager Session Manager 기반 접근 제어

**Key Results**
- MySQL 인덱스 최적화를 통해 단건 조회 시간 **404ms → 10ms**로 단축
- 800명 부하 테스트에서 최대 약 **3,600 requests/sec** 처리량 측정
- 앱 서버 3대 구성 및 서버 장애 상황에서 장애 탐지와 CloudWatch 알람 전달 시간 검증

### 2. WordPress High Availability — Final Project

**AWS 기반 웹 서비스 인프라 구축 및 고가용성(HA) 아키텍처 구현**

[GitHub Repository](https://github.com/hahyunnii/final-project-wordpress-ha)

AWS 인프라 구성 요소를 활용하여 WordPress 서비스의 고가용성 환경을 구축한 프로젝트입니다.

**Technologies**
- **AWS:** EC2, VPC, Application Load Balancer (ALB), RDS, S3
- **Infrastructure as Code:** Terraform
- **Architecture:** Cloud Infrastructure, High Availability, Load Balancing
- **Service:** WordPress

## Additional Projects

### 3. Cloud Infrastructure & Automation

| Project | Description |
|---|---|
| [EC2 & RDS with Terraform](https://github.com/hahyunnii/aws-06-ec2-rds-with-terraform-hahyunnii) | Terraform 기반 EC2 및 RDS 인프라 구축 |
| [Terraform EC2 & ALB](https://github.com/hahyunnii/aws-03-terraform-ec2-alb-hahyunni) | Terraform 기반 EC2 및 ALB 구성 |
| [EC2 & ALB](https://github.com/hahyunnii/aws-02-ec2-alb-hahyunnii) | EC2 및 Application Load Balancer 구성 |
| [S3 Static Web Hosting](https://github.com/hahyunnii/aws-01-s3-static-web-hosting-hahyunnii) | S3 기반 정적 웹 호스팅 |

### 4. High Availability & Performance Testing

| Project | Description |
|---|---|
| [WordPress HA Configuration](https://github.com/hahyunnii/aws-05-2-wp-with-ha-setting-hahyunnii) | WordPress 고가용성 환경 구성 |
| [ApacheBench Benchmark](https://github.com/hahyunnii/aws-04-benchmark-using-ab-hahyunnii) | ApacheBench 기반 웹 서버 부하 테스트 및 성능 측정 |

## Technical Skills

- **Cloud Infrastructure:** AWS EC2, VPC, ALB, RDS, S3, IAM
- **Infrastructure as Code:** Terraform
- **High Availability:** 고가용성 아키텍처, 로드 밸런싱, 헬스체크
- **Performance Engineering:** k6, ApacheBench, 부하 테스트, 데이터베이스 쿼리 최적화
- **Monitoring & Alerting:** Amazon CloudWatch, 대시보드, 알람, 성능 지표 분석
- **Backend Environment:** Java, Spring Boot, Apache Tomcat, MySQL

---

각 프로젝트의 상세 구현 과정, 인프라 구성 및 테스트 결과는 개별 레포지토리에서 확인할 수 있습니다.
