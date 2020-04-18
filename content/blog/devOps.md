---
path: devOps/AWS-Docker
date: 2020-04-18T08:23:42.319Z
title: "Let's Learn AWS and DevOps "
description: Go DevOps!
---

## Contents
1. AWS & Docker를 활용한 DevOps 구축하기
2. AWS 서버리스 프로젝트

## 1. AWS & Docker를 활용한 DevOps 구축하기

### 01. Ch 01. 오리엔테이션과 시작하기 - 01. devOps의 필요성
2:24

- 기획 - 코딩 - 테스트 - 배포 - 운영

- 개발과 운영 사이의 역할
- 효율적이고 빠르게 개발과 운영 사이를 도와줄 것인가
- 2008년 애자일 컨퍼런스에서 Andrew Clay Shafer와 Patrick Debois가 "애자일 인프라스트럭처"에 대해 논의하며 처음으로 사용

> DEVOPS's Tools   
- 툴체인: Jira, Confuence, Bitbucket, Jenkins
- 업무환경(클라우드): CLOUD SERVER(EC2, S3, RDS), DOCKER

### 02. Ch 01. 오리엔테이션과 시작하기 - 02. Jira Confluence 설명
6:11

> 개발 프로세스   
- 기획/디자인 => 업무 정의서(지시서)
- 코드 작성
- 빌드 프로세스(소스 컴파일)
- 테스트
- 패키지(코드 묶기, war for java)
- 릴리즈
- 모니터링(log 파일, 분석도구)

- 구성(IaC) (인프라스트럭처, 장애/보안)

> 업무 효율화   
- Jira: 보드를 이용하여 관리, 업무 트래킹, 업무 배정/처리 소스보기
- Jira Confluence: 업무 자료 정리, (잔디/슬랙), 노션
- Bitbucket: 형상관리툴, 동시수정, 소스 비교 - Jira 연동 업무소스 파악
- Jenkins: Bitbucket 소스를 mvn 빌드, 패키지화와 배포

### 03. Ch 01. 오리엔테이션과 시작하기 - 03. AWS와 Docker의 필요성
20:46

> AWS: Amazon Web Service   
- 전통적 IDC(International Data Corporation)
- 점차 클라우드 서비스 중요도 증대
- 빠르게 서버를 세팅
- 국내 호스팅도 가격 경쟁력 갖춰가고 있으나 기술적인 측면에서 AWS가 우위

> AWS 장점:   
- 탄력적인 웹 규모 컴퓨팅
- 다양한 Command(API) 제공
- 유연한 클라우드 호스팅
- 통합
- 안정성
- 보안

> AWS 단점:   
- 베어 메탈 성능을 원할 때
- 웹 페이지가 몇개뿐일 때
- 솔루션에 적합
- 가격

> AWS 종류   
- Server: 
    1. EC2(Elastic Compute Cloud) 
        - 안전하고 크기 조정가능한 컴퓨팅 파워
        - 개발자가 더 쉽게 웹 규모의 클라우딩 컴퓨팅 작업
        - 장점: 탄력적인 웹 규모 컴퓨팅인 오토 스케일링 자동확장 및 축소
        - 완전 제어 가능, cli 제공, 다양한 command api 제공
        - 스토리지, RDS, VCP와 통합 가능
        - 안전성과 보안
    2. Lambda 
        - 서버 프로비저닝하거나 관리할 필요 없이 코드 실행할 수 있음
    3. VPC(Virtual Private Cloud)
- Storage: 
    1. S3 
    2. EBS(Elastic Block Store)
- DataBase: 
    1. RDS 
    2. DynamoDB 
    3. RedShift 
    4. AuroraDB

> Docker   
- 오픈소스 컨테이너 프로젝트로 만들어짐
- 간단한 프로젝트 도커로 만들기
- 프로젝트 환경 스택(JAVA, MariaDB(RDS), Maven, iBatis, Spring Boot, 스프링 시큐리티, S3(이미지))
- 카카오로 로그인 + 오프라인 후기 서비스 -> 도커 관리 

### 04. Ch 02. 협업 툴 활용 A-Z - 01. Jira 협업툴 소개
9:26

### 05. Ch 02. 협업 툴 활용 A-Z - 03. Jira 협업툴 설치하기
22:30

### 06. Ch 02. 협업 툴 활용 A-Z- 02. AWS 설치 및 제거요강
5:17

### 07. Ch 02. 협업 툴 활용 A-Z - 04. Jira 이슈 이해하기
11:00

### 08. Ch 02. 협업 툴 활용 A-Z - 05. Jira API 소개 및 Postman 활용하기
20:27

### 09. Ch 02. 협업 툴 활용 A-Z - 06. Jira 관리자 소개
20:21

### 10. Chapter. 02 협업 툴 활용 A_Z - Jira 워크 플로우 설정하기
10:04

### 11. Chapter. 02 협업 툴 활용 A_Z - Jira 워크 플로우 설정하기 (실습)
15:44

### 12. Chapter. 02 협업 툴 활용 A_Z - Jira CustomField 설정하기
17:11

### 13. Chapter. 02 협업 툴 활용 A_Z - Jira DB 구조 설명
15:04

### 14. Chapter. 02 협업 툴 활용 A_Z - Confluence 협업툴 소개
13:08

### 15. Chapter. 02 협업 툴 활용 A_Z - Confluence 협업툴 사용방법
21:42

### 16. Chapter 03. 스프링 프로젝트 세팅(1)
10:20

17. Chapter 03. 스프링 프로젝트 세팅(2)
14:08

18. Chapter 03. 스프링 프로젝트 세팅 실습(1) - 1
13:42

19. Chapter 03. 스프링 프로젝트 세팅 실습(1) - 2
24:47

20. Chapter 03. 스프링 프로젝트 세팅 실습 (2)
21:56

21. Chapter 03. 빗버킷 소개(3)
14:37

22. Chapter 03. 빗버킷 활용(4)
19:20

23. Chapter 03. 빗버킷 소개(3)_실습
13:34

24. Chapter 03. 빗버킷 활용(4)_실습
14:10

25. Chapter 03. Jenkins 소개 및 설치#1
12:43

26. Chapter 03. Jenkins 소개 및 설치#1 실습
15:55

27. Chapter 03. Jenkins 소개 및 설치#2
21:53

28. Chapter 03. Jenkins 소개 및 설치#2(실습)
9:55

29. Chapter 03. Jenkins 배포 및 파이프라인#3
16:04

30. Chapter 03. Jenkins 배포 및 파이프라인#3(실습)
17:16

31. Ch 04. AWS Server - RDS 설정 - 1
14:55

32. Ch 04. AWS Server - RDS 설정 - 2
14:20

33. Ch 04. AWS Server - RDS 설정 - 3
13:23

34. Ch 04. AWS Server - RDS 설정 - 4
17:39

35. Ch 04. AWS Server - RDS 설정 - 5
15:42

36. Ch 04. AWS Server - S3 설정 및 이미지 업로드
19:00

37. Ch 04. AWS Server - 카카오 로그인 - 1
8:08

38. Ch 04. AWS Server - 카카오 로그인 - 2
13:33

39. Ch 04. AWS Server - 카카오 로그인 - 3
14:04

40. Ch 04. AWS Server - 카카오 로그인 - 4
19:34

41. Ch 04. AWS Server - S3로 이미지 업로드 및 API 활용 - 1
15:54

42. Ch 04. AWS Server - S3로 이미지 업로드 및 API 활용 - 2
18:39

43. Ch 04. AWS Server - S3로 이미지 업로드 및 API 활용 - 3
23:23

44. Ch 04. AWS Server - S3로 이미지 업로드 및 API 활용 - 4
19:42

45. Ch 04. AWS Server - S3로 이미지 업로드 및 API 활용 - 5
22:05

46. Ch 04. AWS Server - 지라 이슈 ID, BitBucket 연결 - 1
10:02

47. Ch 04. AWS Server - 지라 이슈 ID, BitBucket 연결 - 2
8:24

48. Ch 04. AWS Server - Jenkins Pipe Line 만들기 - 1
14:21

49. Ch 04. AWS Server - Jenkins Pipe Line 만들기 - 2
11:25

50. Ch 05. DOCKER 활용하기 - 도커 설치하기 & 컨테이너 접속하기
6:59

51. Ch 05. DOCKER 활용하기 - 도커 이미지 만들기 (Dockerfile) 및 실행 - 1
14:34

52. Ch 05. DOCKER 활용하기 - 도커 이미지 만들기 (Dockerfile) 및 실행 - 2
11:46

53. Ch 05. DOCKER 활용하기 - Docker Hub & Docker API - 1
16:34

54. Ch 05. DOCKER 활용하기 - Docker Hub & Docker API - 2
19:25

55. Ch 05. DOCKER 활용하기 - DevOps 강의를 마치며
4:28