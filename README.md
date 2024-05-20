# 공부 많이 했어?

## 공부 시간 기록 어플리케이션
공부로 얻는 성취감에는 얼마나 공부를 했는지 기록하는 것도 있다고 생각합니다.
공부를 컴퓨터로 하는 저는 컴퓨터 타이머로 제 시간을 기록합니다.
도서관에 가서 공부하는 저는 휴대폰 타이머로 제 시간을 기록합니다.
이 2개를 통합해서 한곳에서 기록하고 싶었습니다.
또한 가끔 시간 기록하는걸 까먹어서 그날을 기록하지 못합니다.
이는 저에게 성취감을 저하시키는 요인이 됐고 타이머로만 공부한 시간을 기록하고 싶지 않습니다.
그래서 이 앱을 만드려고 합니다.

# 요구사항
## 기능적 요구사항

### 1. 타이머 기능
- **1-1. 시작**: 사용자는 공부를 시작할 때 타이머를 시작할 수 있습니다.
- **1-2. 정지**: 사용자는 공부를 중단할 때 타이머를 정지할 수 있습니다.
- **1-3. 기록**: 타이머가 정지되면, 해당 기간의 공부 시간을 기록할 수 있습니다
- **1-4. 위치 기록**: 1-3이 수행되는 동안 위치를 같이 기록할 수 있습니다.
- **1-5. 날짜 기록**: 1-3이 수행되는 동안 날짜를 기록합니다.
- **1-6. 일시 정지 및 재개**: 사용자는 타이머를 일시 정지하고 재개할 수 있습니다.

### 2. 수동 시간 기입
- **2-1. 수동 입력**: 사용자는 특정 날짜와 시간에 대해 수동으로 공부 시간을 입력할 수 있습니다.

### 3. 공부 내용 기입
- **3-1. 내용 기입**: 사용자는 공부한 내용을 시간과 함께 적을 수 있습니다.
- **3-2. 카테고리 분류**: 사용자는 공부한 내용을 카테고리 별로 분류할 수 있습니다.
- **3-3. 내용 수정**: 사용자는 적은 내용을 수정할 수 있습니다.
- **3-4. 내용 삭제**: 사용자는 적은 내용을 삭제할 수 있습니다.

### 4. 시간 기록 조회
- **4-1. 달력 뷰**: 사용자는 달력 뷰를 통해 특정 날짜의 공부 시간을 볼 수 있습니다.
- **4-2. 차트 및 그래프**: 사용자는 차트 또는 그래프를 통해 일정 기간동안의 공부 시간 통계를 볼 수 있습니다.
- **4-3. 카테고리별 조회**: 사용자는 카테고리별 공부 시간을 조회할 수 있습니다.

### 5. 사용자 인증 및 관리
- **5-1. 로그인**: 사용자는 이메일과 비밀번호를 통해 로그인 할 수 있습니다.
- **5-2. 계정 인증**: 사용자는 학교 이메일을 통해 계정을 인증할 수 있습니다.
- **5-3. 계정 정보 관리**: 사용자는 비밀번호를 변경하거나 계정 정보를 업데이트 할 수 있습니다.
- **5-4. 회원 가입**: 사용자는 서비스를 이용하기위해 회원가입을 할 수 있습니다.
- **5-5. 회원 탈퇴**: 사용자는 서비스를 이용하지 않으면 회원 탈퇴를 할 수 있습니다.

### 6. 학교 및 지역 기반 경쟁
- **6-1. 학교별 랭킹**: 사용자는 학교별 랭킹을 조회할 수 있습니다.
- **6-2. 지역별 랭킹**: 사용자는 지역별 랭킹을 조회할 수 있습니다.
- **6-3. 전체 랭킹**: 사용자는 전체 랭킹을 조회할 수 있습니다.
- **6-4. 랭킹 업데이트**: 시스템은 주기적으로 랭킹을 업데이트 합니다.

## 비기능적 요구사항

### 1. 성능
- **1-1. 응답 시간**: 앱의 모든 기능은 사용자 요청에 대해 1초 이내에 응답해야 합니다.
- **1-2. 데이터 처리 속도**: 대량의 데이터 조회 및 처리 작업은 3초 이내에 완료되어야 합니다.

### 2. 가용성
- **2-1. 시스템 가용성**: 앱은 24시간 운영되며 99% 이상의 가용성을 유지해야 합니다.

### 3. 확장성
- **3-1. 사용자 및 데이터 증가 대응**: 시스템은 사용자 수와 데이터 양의 증가에 유연하게 대응할 수 있어야 하며, 수평적 확장이 가능해야 합니다.

### 4. 보안
- **4-1. 데이터 보호**: 사용자의 개인 정보는 암호화하여 저장되어야 합니다.
- **4-2. 인증 및 인가**: 시스템은 안전한 인증 방식을 사용하여 사용자의 인증을 처리해야 합니다.

### 5. 유지 보수성
- **5-1. 코드 품질**: 코드는 잘 구조화되고, 명확하게 문서화되어 있어야 합니다.
- **5-2. 버전 관리**: 모든 코드 변경 사항은 체계적인 버전 관리 시스템을 통해 관리되어야 합니다.

### 6. 호환성
- **6-1. 멀티 플랫폼 지원**: 앱은 다양한 운영 체제와 브라우저에서 문제없이 작동해야 합니다.

### 7. 사용성
- **7-1. 사용자 인터페이스**: 앱은 직관적이고 사용하기 쉬운 인터페이스를 제공해야 합니다.

## 기술 스택

### 1. Front-end
- React, React Native, Nginx

### 2. Back-end
- Spring Boot, Spring Security, JWT

### 3. Database
- PostgreSQL

### 4. Container Orchestration
- Docker, Kubernetes

### 5. CI/CD Automation
- JenKins, Gradle

### 6. Data Sync
- kafka

### 7. 추가 도구 및 서비스
- Google Maps API, Git, UnivCert(학교 이메일 인증 API)
  
# 시스템 동작
## UsecaseDiagram
![UsecaseDiagram](https://github.com/parkswon1/Studyapp/assets/74632742/a59cb3b6-a0cb-48ca-8575-bad620f4ec04)

# 데이터 명세
## Entity 구성

### 1. 타이머 시간 모델 - 각 시간 기록 Entity

| Entity      | Field          | Type         | Size  | Constraint | Description              |
|-------------|----------------|--------------|-------|------------|--------------------------|
| StudySession| SessionId      | Integer      |       | PK         | 공부 세션의 고유 식별자  |
|             | UserId         | Integer      |       | FK         | 사용자 식별자            |
|             | StartTime      | DateTime     |       |            | 공부 시작 시간           |
|             | EndTime        | DateTime     |       |            | 공부 종료 시간           |
|             | CategoryID     | Integer      |       | FK         | 카테고리의 고유 식별자   |
|             | IsManualEntry  | Boolean      |       |            | 수동 입력 여부           |
|             | CreatedAt      | DateTime     |       |            | 기록 생성 시간           |
|             | Location       | String       |       |            | 위치 정보                |

### 2. 통합 시간 기록 모델 - 날짜당 기록 시간

| Entity         | Field          | Type         | Size  | Constraint | Description                |
|----------------|----------------|--------------|-------|------------|----------------------------|
| StudyRecordView| RecordId       | Integer      |       | PK         | 기록 뷰의 고유 식별자      |
|                | UserId         | Integer      |       | FK         | 사용자 식별자              |
|                | Date           | Date         |       |            | 날짜                       |
|                | TotalStudyTime | Integer      |       |            | 총 공부 시간               |
|                | RankUsedTime   | Integer      |       |            | 비 입력 공부 시간          |
|                | CategoryId     | Integer      |       | FK         | 카테고리의 고유 식별자     |

### 3. 사용자 카테고리 모델 - 사용자 지정 카테고리

| Entity   | Field          | Type         | Size  | Constraint | Description                    |
|----------|----------------|--------------|-------|------------|--------------------------------|
| Category | CategoryId     | Integer      |       | PK         | 카테고리의 고유 식별자         |
|          | UserId         | Integer      |       | FK         | 사용자의 고유 식별자           |
|          | CustomName     | String       | 255   |            | 사용자가 지정한 카테고리 이름  |

### 4. 사용자 - 사용자 Entity

| Entity  | Field          | Type         | Size  | Constraint | Description             |
|---------|----------------|--------------|-------|------------|-------------------------|
| User    | UserId         | Integer      |       | PK         | 사용자의 고유 식별자    |
|         | Email          | String       | 255   |            | 이메일 주소             |
|         | PasswordHash   | String       | 255   |            | 비밀번호 해시           |
|         | FullName       | String       | 255   |            | 전체 이름               |
|         | SchoolId       | Integer      |       | FK         | 학교 식별자             |
|         | IsEmailVerified | Boolean      |       |            | 이메일 인증 여부       |

| Entity  | Field          | Type         | Size  | Constraint | Description             |
|---------|----------------|--------------|-------|------------|-------------------------|
| School  | SchoolId       | Integer      |       | PK         | 학교의 고유 식별자      |
|         | Name           | String       | 255   |            | 학교 이름               |
|         | Domain         | String       | 255   |            | 이메일 도메인           |

| Entity    | Field          | Type         | Size  | Constraint | Description             |
|-----------|----------------|--------------|-------|------------|-------------------------|
| Location  | LocationId     | Integer      |       | PK         | 위치의 고유 식별자      |
|           | Name           | String       | 255   |            | 위치 이름               |

### 5. 공부 시간 경쟁 서비스 모델 - 공부 시간 랭킹 기록 Entitiy

| Entity           | Field            | Type     | Size     | Constraint | Description               |
|------------------|------------------|----------|----------|------------|---------------------------|
| StudyCompetition | CompetitionId    | Integer  |          | PK         | 경쟁의 고유 식별자        |
|                  | UserId           | Integer  |          | FK         | 사용자 식별자             |
|                  | Period           | String   |          |            | 기간 (예: 주간, 월간)     |
|                  | Rank             | Integer  |          |            | 순위                      |
|                  | TotalStudyRankTime | Integer |          |            | 총 공부 시간             |

### 6. 학교, 위치 랭킹 모델 - 공부 시간 경쟁 서비스 모델 상속 Entitiy

| Entity           | Field            | Type     | Size     | Constraint | Description               |
|------------------|------------------|----------|----------|------------|---------------------------|
| SchoolRank       | SchoolId         | Integer  |          | PK         | 학교의 고유 식별자        |

| Entity           | Field            | Type     | Size     | Constraint | Description               |
|------------------|------------------|----------|----------|------------|---------------------------|
| LocationRank     | LocationId       | Integer  |          | PK         | 위치의 고유 식별자        |

## class Diagram
![클래스 다이어그램 drawio](https://github.com/parkswon1/Studyapp/assets/74632742/69cffc8c-d51e-4696-ad3d-4150845d2851)

# 아키텍처 설계

## 1. 타이머 서비스 (Timer Service)

- 기능: 타이머 시작, 정지, 기록, 위치 기록, 날짜 기록, 일시 정지 및 재개
- 데이터 모델: StudySession
- 엔드포인트: /timer/start, /timer/stop, /timer/record, /timer/pause-resume
  
## 2. 시간 기록 서비스 (Time Record Service)

- 기능: 공부 시간 기록 조회 (달력 뷰, 차트 및 그래프 조회, 카테고리별 조회)
- 데이터 모델: StudyRecordView
- 엔드포인트: /time-record/calendar-view, /time-record/stats-view, /time-record/category-view
  
## 3. 사용자 관리 서비스 (User Management Service)

- 기능: 사용자 관리 (인증, 계정 인증, 정보 관리, 회원 가입, 회원 탈퇴)
- 데이터 모델: User, School
- 엔드포인트: /user/login, /user/signup, /user/update, /user/delete

## 4. 공부 내용 관리 서비스 (Study Entry Service)

- 기능: 공부 내용 관리 (내용 기입, 카테고리 분류, 수정, 삭제)
- 데이터 모델: StudySession, Category
- 엔드포인트: /study-entry/create, /study-entry/update, /study-entry/delete

## 5. 경쟁 서비스 (Competition Service)

- 기능: 학교 및 지역 기반 경쟁 서비스, 랭킹 업데이트
- 데이터 모델: StudyCompetition, SchoolRank, LocationRank
- 엔드포인트: /competition/school-rank, /competition/location-rank, /competition/overall-rank

# API 명세서
[![GitBook](https://img.shields.io/badge/GitBook-Read%20Documentation-blue)](https://seoks-organization-1.gitbook.io/study-api-reference/)

# CI/CD 파이프라인 구상도
![CICD파이프라인 drawio](https://github.com/parkswon1/Studyapp/assets/74632742/76f44aed-3b7a-407b-8196-238d588bb0bb)
