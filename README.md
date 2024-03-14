# 공부 많이 했어?
## Notion
https://unleashed-metacarpal-944.notion.site/app-5c214ca8fece4138b656bb1bad6756e7?pvs=4

## 공부 시간 기록 어플리케이션
공부로 얻는 성취감에는 얼마나 공부를 했는지 기록하는 것도 있다고 생각합니다.
공부를 컴퓨터로 하는 저는 컴퓨터 타이머로 제 시간을 기록합니다.
도서관에 가서 공부하는 저는 휴대폰 타이머로 제 시간을 기록합니다.
이 2개를 통합해서 한곳에서 기록하고 싶었습니다.
또한 가끔 시간 기록하는걸 까먹어서 그날을 기록하지 못합니다.
이는 저에게 성취감을 저하시키는 요인이 됐고 타이머로만 공부한 시간을 기록하고 싶지 않습니다.
그래서 이 앱을 만드려고 합니다.
msa구조로 만드려고 합니다.
## 기능적 요구사항

### 1. 타이머 기능
- **1-1. 시작**: 사용자는 공부를 시작할 때 타이머를 시작할 수 있습니다.
- **1-2. 정지**: 사용자는 공부를 중단할 때 타이머를 정지할 수 있습니다.
- **1-3. 기록**: 타이머가 정지되면, 해당 기간의 공부 시간을 기록할 수 있습니다.
- **1-4. 일시 정지 및 재개**: 사용자는 타이머를 일시 정지하고 재개할 수 있습니다.

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
- React, React Native

### 2. Back-end
- Spring Boot, Spring Security, JWT

### 3. Database
- MYSQL

### 4. Container Orchestration
- Docker, Kubernetes

### 5. CI/CD Automation
- JenKins, Gradle

### 6. Data Sync
- kafka

### 7. 추가 도구 및 서비스
- Google Maps API, Git, UnivCert(학교 이메일 인증 API)

## Entity 구성

### 1. 타이머 시간 모델
-각 시간 기록 Entity
| Entity       | Field            | Type     | Description               |
|--------------|------------------|----------|---------------------------|
| StudySession | SessionId (PK)   | Integer  | 공부 세션의 고유 식별자   |
|              | UserId (FK)      | Integer  | 사용자 식별자             |
|              | StartTime        | DateTime | 공부 시작 시간            |
|              | EndTime          | DateTime | 공부 종료 시간            |
|              | CategoryId       | LongText | 카테고리 종류             |
|              | IsManualEntry    | Boolean  | 수동 입력 여부            |
|              | CreatedAt        | DateTime | 기록 생성 시간            |
|              | Location         | String   | 위치 정보                 |

### 2. 통합 시간 기록 모델
-날짜당 기록 시간
| Entity          | Field            | Type     | Description             |
|-----------------|------------------|----------|-------------------------|
| StudyRecordView | RecordId (PK)    | Integer  | 기록 뷰의 고유 식별자   |
|                 | UserId (FK)      | Integer  | 사용자 식별자           |
|                 | Date             | Date     | 날짜                    |
|                 | TotalStudyTime   | Integer  | 총 공부 시간            |
|                 | RankUsedTime     | Integer  | 비 입력 공부 시간       |
|                 | CategoriesSummary | Text    | 카테고리별 요약 정보    |

### 3. 사용자, 학교, 위치 기록 모델
-사용자 Entity
| Entity  | Field         | Type     | Description             |
|---------|---------------|----------|-------------------------|
| User    | UserId (PK)   | Integer  | 사용자의 고유 식별자    |
|         | Email         | String   | 이메일 주소             |
|         | PasswordHash  | String   | 비밀번호 해시           |
|         | FullName      | String   | 전체 이름               |
|         | SchoolId (FK) | Integer  | 학교 식별자             |
|         | IsEmailVerified | Boolean | 이메일 인증 여부       |

-학교 Entity
| Entity  | Field         | Type     | Description             |
|---------|---------------|----------|-------------------------|
| School  | SchoolId (PK) | Integer  | 학교의 고유 식별자      |
|         | Name          | String   | 학교 이름               |
|         | Domain        | String   | 이메일 도메인           |

-위치 Entity
| Entity    | Field             | Type     | Description             |
|-----------|-------------------|----------|-------------------------|
| Location  | LocationlId (PK)  | Integer  | 위치의 고유 식별자      |
|           | Name              | String   | 위치 이름               |

### 4. 공부 시간 경쟁 서비스 모델
-공부 시간 랭킹 기록 Entitiy
| Entity           | Field              | Type     | Description               |
|------------------|--------------------|----------|---------------------------|
| StudyCompetition | CompetitionId (PK) | Integer  | 경쟁의 고유 식별자        |
|                  | UserId (FK)        | Integer  | 사용자 식별자             |
|                  | Period             | String   | 기간 (예: 주간, 월간)     |
|                  | Rank               | Integer  | 순위                      |
|                  | TotalStudyRankTime | Integer  | 총 공부 시간              |
|                  | SchoolId (FK)      | Integer  | 학교 식별자               |
|                  | Location (FK)      | Integer  | 위치 정보                 |

## MSA 구조
### 1. 인증 및 사용자 관리 서비스 (Authentication & User Management Service)

-사용자 등록, 로그인, 비밀번호 변경 등 사용자 관리 기능을 담당합니다.
-사용자의 인증 및 인가를 처리합니다.
-UnivCert(학교 이메일 인증 API)와 연동하여 학교 이메일을 통한 계정 인증을 처리합니다.
-데이터베이스에 사용자 정보를 저장하고 관리합니다.

### 2. 타이머 및 공부 시간 기록 서비스 (Timer & Study Time Recording Service)

-사용자의 공부 시간을 타이머로 기록하고 관리합니다.
-타이머 시작, 정지, 일시 정지, 재개 등의 기능을 제공합니다.
-수동 입력된 공부 시간을 처리합니다.
-카테고리 별로 공부 시간을 분류하고 관리합니다.
-위치 정보를 기록합니다.
-Kafka를 사용하여 데이터 동기화를 처리합니다.

### 3. 공부 내용 및 카테고리 관리 서비스 (Study Content & Category Management Service)

-사용자가 공부한 내용을 관리합니다.
-공부 내용의 추가, 수정, 삭제 기능을 제공합니다.
-공부한 내용을 카테고리 별로 분류합니다.
-데이터베이스에 공부 내용 및 카테고리 정보를 저장하고 관리합니다.
### 4. 시간 기록 조회 서비스 (Study Time Record Query Service)

-달력 뷰를 통해 특정 날짜의 공부 시간을 조회합니다.
-차트 및 그래프를 통해 일정 기간동안의 공부 시간 통계를 제공합니다.
-카테고리별 공부 시간을 조회합니다.

### 5. 학교 및 지역 기반 경쟁 서비스 (School & Location-based Competition Service)

-학교별, 지역별, 전체 랭킹을 조회합니다.
-랭킹을 업데이트하고 관리합니다.

## CI/CD 파이프라인 구상도
![제목 없는 다이어그램 drawio](https://github.com/parkswon1/Studyapp/assets/74632742/cb044daf-e4cf-4352-99a3-84296208dbe1)

## class Diagram
https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=%ED%81%B4%EB%9E%98%EC%8A%A4%20%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8.drawio#R7V1rb6M4FP01SLsrteId%2BJhXZ7rTrrqTzmM%2FusFJUAnOAmma%2BfVrg50ADnmD06yl0QjfGPPw8T33XNtUMbrT908RmE0ekQcDRVe9d8XoKbruagb%2BnxiW1GDYmWEc%2BV5mUteGgf8LZkaNWee%2BB2Nqy0wJQkHiz4rGIQpDOEwKNhBFaFGsNkKBVzDMwBhyhsEQBLz1h%2B8lk8zq6K21%2FTP0xxN2Zc12s1%2BmgFWmTxJPgIcWOZPRV4xuhFCSHU3fuzAg7469lx%2F3yx%2FBw6v96c%2B%2F43%2FBt86X57%2B%2B32SN3R1yyuoRIhgmRzf99WE8e7NGwdvzt%2FkbnPyC3Z9vN1bW9BsI5vR9Kf2u4nQUt6v020pHVRwT%2F54eO6TY7yhtTXF79JUkS%2Fae44U%2FDUCIS50RCpMB%2FUXF5eHED7wHsERzcvdxAoavrNSZoMj%2FheuDAP%2BkYQP%2BOUoojHSbtOYHQRcFKMKGEKUXWJ80II3Ry0Qwxqc9sbeklUyP4L1Q8QHECbtBFARgFvsv6S2TE6cgGvthByUJmtJKi4mfwMEMDEmdBR4r5EaSKbtv%2BiJhlMD3EvJ2dJu2whIegxBNYRIt8XlsAFKg0uGn2xSNizWYNZPaJjkg64ZJBxEdQONV06urfcUDDoRj%2FNSryxls3NLrWTp%2FPWfD5Qy1eDUQJDAKQQI7aB56cR6Z%2BCD3oGtTitcDsGtz2B3AOPZReO9h829PX37nQIr7JkkxFqFXWALVBpyBwB%2BHuBjAETmNdK6PPUubmhNEMBBjSPjh%2BCGt0zPXlq%2F07RATwueOgtR7THzPgyGBIUpAAl5Ww2SG%2FDBJX5%2FVwf%2FwC%2B2qt5Zi4Rvv4rK2LuN%2FpHqUdFGInwX4Kb4gBvQCElCfBavV%2FoLH6gqce2LTroZmASWHQqLFQeJbDKP7HsHDncRD03iwdMF4cHgXQejl2Z9CiYVmsdByBGNB1zkw9ENPQqF5KGiqKRoLGoeFLo5VxihakuBBwqFROBj7hrS1wUHl4HAfP4JwDoJ%2ByC4gEdEcIizRgaRu8g4igthFeO1EoqFhNDiiw0jd4NDwgIYgwVpTgqFhiakKjyN5kZnmzHSl3SUHbltpu%2BlBX3FVDh8yT1ZPnszQi4mrvRNlK%2FdytYkynZfBaVpEpsnq8mGZj7jcPJnBB7z9KfADiYSGkSA8Q2bwSvipHccLFHmfQTyRgGgYEMLTZAafJrubB8FfQObJGgeD%2BESZwSufwXCCUJAFD3JORQAohKfLDD45ch%2Bn8cN3GPkjH8oUauOgEJ4xMzbJ4p7iWorrpstHLKmGm1PDFqNxFmcyR75TDavXvmzE2DApnFKaL%2FVwXd7LuHQ97HKYkAGvACAIl8MmnxjpIfx%2BJBIaRoJwHWxuXhrrdsmKWHzQcRXXkfGMmFWwlqXtBw8Go6uNZkx%2BFSybmgxkgr8272Ve%2BEJYk1djMqARAATxAQ0f2RJZ7thEkGf6vI2rqHLbx2URnmUWKUhOZ68XiPAxOn4gFHmS7%2Bpzc%2B5l853FT2OulzjIWYrmESGc%2BNgN5JU8dksSCA0DQbiQt%2FgpzGeUxhBzbym3fwiAhPhp7dUd5GMIEL5izpA7goRAQviktrVhxX%2B2JciH8WA%2BxdJA7gNpHBbCp7VtPoxIVbGR6ueO0rEVIouq9HOHrAJv91LJrZOcsdTPzehnQzMLetZ09%2BScFeSuVj%2FbfEDURdMZTPxEfjyhTmeX%2BZLLFdE2T4FSRItEhHARbfOToE8w8pEnodAwFITLaJufaCSKSQKhYSCIF882P7e4TqgQTEgFLQIXwhV0i8%2FBb1oxI1WROFWkl1SRva8quvp1NC1e53PraLAXkFFwDZ6tVQHaS9FFLV4wy8U0AoAgXA61eIG8aY%2BLZDhxDGeyb7VIhiuDl9fyZN%2FLatuLZLeanJp54ezGC3vJbgKAIJzdnA36rQwCGHpt8lF2XHoJEOGS%2FLuJiPOCHu0ThoAhfi0w2oCBF8oXHdzqnU9uNj0vAC8w6GCiGqftlXCF61K6c0jp3U9%2BkvNw52alf2gr5Lj3ni8sWYF80o%2BepGrMQM7TblVzZVifnJYKZ5MkKH7p5KkyozeGjMIxtCZojEIQ9NdWChtS7wi2w12A5tEQ7gSXruJwYAy3phEq9t1EMMBq5614e1vI8ImMuBzvshV4FM2rD%2ByzJrInoGetkco1ZGs7GsqekGsIwxIsc9WoR6i%2BYbcUKFB%2BrLovwzG31ccH2R2clbPZWt5tQzINz3KuMDced47AzAtvH3DZBemfZ6DXUVZ%2FFOEYR%2BhUhHB7Q%2FA0N7chiL96N9fKuzn11sVR8sd0c%2BxPiAhyc3rZCzjucW7OcKxiQ26J1s%2Fk5rgb3unmrG31a3JzG%2FZaXoGbq4j3GnJzG77HscXNsVRBlZfLeSDNzPkgHDIZ290QLnB%2BZOWaim7J2uWUhPsftq9up%2F9pVczWnOh%2FrOI%2BWEcv5RH2dT%2B6tqOhCvdzthHPf4TjDx6euBsfyKBlSajtw79Caa7ol0pLbLJY1i1jWM2pZ%2FxXUBBthmHuRETc6IWOLCeW0GgUw3q6kN9ZqJ3ahVEmc6v7MN9rpoheO1OnFUn5xmiq09zDgt%2BdrMAc%2BY16qxa1NLZkRHFwkEmZBjOLWoh2bx3zYKapmw%2BcPenAqIcOytGd4VpH8gHLKrHlRqreKB%2B4fAR4dXzgVsSDV8IHLp9HvgY%2B2NFrH50P6lIJrmsWfbe9b7JCVe2iKnDsY2mkaTYw9s1OWDWpA7O06aF1ZHbC1lvbG6qbDv4H8sBtRB7YxXROc47lOtXBjk47Exu0St%2F%2B0JrqNU09bA7wgKyRaRT4wLVPSBtpykdLG6l7EkOr4nNCJ6eN3Fu9yA22VfIF%2B3ODWW6rVd4zVzM9aEydXDM%2F0LF4tXpBU%2FlllddAEbv67YMrBk3dY7LmOIo4ZmrTdAtTm2QFh%2F4xpzbZTvPd4uHUeaWKBRFs%2Fc%2ByVD6UICzb2N7QmaY2yysyTNvZTlyltZql%2BvVMbWoqL2VOGi65Wf1CFLQL9McMM%2BFjwtpzSFR9RuLEIWGUvqKv2UdOt5mlfTdcQ2caEppd1O2MzvcdEqX6hw4JXIwQSvLVIzCbPCKP8Hf%2FPw%3D%3D

