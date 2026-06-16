
# 메타 정보
* id: AWS-ECS-001
* title: ECS Cluster 생성
* difficulty: beginner
* duration: 15m
* prerequisites: Docker 기본 개념
* category: AWS/ECS
* version: "2026.1"
* last_updated: 2026-06-16
* tags: aws ecs container

# ECS Cluster 생성

## 학습 목표

* ECS Cluster의 역할을 설명할 수 있다.
* ECS Cluster를 생성할 수 있다.

## 개요

ECS Cluster는 ECS 서비스와 태스크를 실행하기 위한 논리적 그룹이다.

## 실습

### Step 1

AWS Console 접속

### Step 2

ECS → Cluster 이동

### Step 3

Cluster 생성

## 결과 확인

* Cluster 상태가 Active 인지 확인

## Trouble Shooting

### Cluster 생성 실패

원인: 권한 부족

해결: IAM 권한 확인

## 핵심 요약

* ECS Cluster는 컨테이너 실행 환경이다.
* 하나의 Cluster 안에 여러 Service를 배포할 수 있다.

## 강의 메모

### 학생들이 자주 하는 실수

* ECS Cluster와 ECS Service를 동일한 개념으로 이해함
* Cluster 생성만 하면 애플리케이션이 실행된다고 생각함

### 질문 포인트

* ECS Cluster와 Kubernetes Cluster의 차이점은?
* Fargate와 EC2 Launch Type의 차이점은?

### 현업 관점

실무에서는 AWS Console보다 Terraform 또는 CloudFormation을 이용하여 ECS Cluster를 생성하는 경우가 많다.

## 왜 중요한가?

ECS Service, Task Definition, Auto Scaling 등
모든 ECS 구성요소는 Cluster를 기준으로 동작한다.

따라서 ECS 운영을 이해하기 위해서는
Cluster 개념을 먼저 이해해야 한다.

## 다음 학습

- AWS-ECS-002 ECS Task Definition 생성
