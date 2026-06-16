# ECS Cluster 생성

## 메타 정보

* ID: AWS-ECS-001
* 난이도: 초급
* 예상 학습시간: 15분
* 선수지식: Docker 기본 개념
* 카테고리: AWS / ECS

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

원인:
권한 부족

해결:
IAM 권한 확인

## 핵심 요약

* ECS Cluster는 컨테이너 실행 환경이다.
* 하나의 Cluster 안에 여러 Service를 배포할 수 있다.

## 다음 학습

* ECS Task Definition 생성
