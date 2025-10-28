# Week 5 - Day 2 (화요일): IT & Technical English - IT 기술 영어

## 📚 오늘의 학습 목표
- 소프트웨어 개발 생명주기(SDLC) 용어 마스터
- 시스템 아키텍처 및 인프라 영어
- 기술 문서 작성 (API docs, user manuals)
- IT 프로젝트 커뮤니케이션

**학습 시간**: 90분

---

## 1️⃣ Core IT Vocabulary (30분)

### A. Software Development Lifecycle (SDLC)

#### Development Methodologies (개발 방법론)
```
Waterfall (폭포수 모델)
├─ Requirements gathering (요구사항 수집)
├─ Design (설계)
├─ Implementation (구현)
├─ Testing (테스트)
├─ Deployment (배포)
└─ Maintenance (유지보수)

Agile (애자일)
├─ Sprint planning (스프린트 계획)
├─ Daily standup (데일리 스탠드업)
├─ Sprint review (스프린트 리뷰)
├─ Sprint retrospective (회고)
└─ Continuous delivery (지속적 배포)

Scrum Framework:
- Product backlog (제품 백로그)
- Sprint backlog (스프린트 백로그)
- User stories (사용자 스토리)
- Story points (스토리 포인트)
- Velocity (속도)
- Burndown chart (번다운 차트)

DevOps:
- CI/CD (Continuous Integration/Continuous Deployment)
- Infrastructure as Code (IaC, 코드형 인프라)
- Automated testing (자동화 테스트)
- Monitoring & logging (모니터링 및 로깅)
- Incident management (장애 관리)
```

#### Development Terms (개발 용어)
```
Code Management:
- Version control (버전 관리)
- Repository / Repo (저장소)
- Commit (커밋)
- Branch (브랜치)
- Merge (병합)
- Pull request / PR (풀 리퀘스트)
- Code review (코드 리뷰)
- Merge conflict (병합 충돌)

Code Quality:
- Technical debt (기술 부채)
- Refactoring (리팩토링)
- Code smell (코드 스멜)
- Clean code (클린 코드)
- Best practices (모범 사례)
- Design patterns (디자인 패턴)
- Code coverage (코드 커버리지)
- Static analysis (정적 분석)

Testing:
- Unit testing (단위 테스트)
- Integration testing (통합 테스트)
- System testing (시스템 테스트)
- UAT (User Acceptance Testing, 사용자 인수 테스트)
- Regression testing (회귀 테스트)
- Load testing (부하 테스트)
- Penetration testing (침투 테스트)
- Bug / Defect (버그 / 결함)
```

### B. System Architecture & Infrastructure

#### Architecture Types (아키텍처 유형)
```
Application Architecture:
- Monolithic architecture (모놀리식)
- Microservices architecture (마이크로서비스)
- Serverless architecture (서버리스)
- Event-driven architecture (이벤트 드리븐)
- Service-oriented architecture (SOA)

Layers:
- Frontend / Client-side (프론트엔드)
- Backend / Server-side (백엔드)
- Database layer (데이터베이스 계층)
- API layer (API 계층)
- Middleware (미들웨어)

Patterns:
- MVC (Model-View-Controller)
- MVP (Model-View-Presenter)
- MVVM (Model-View-ViewModel)
- RESTful API
- GraphQL
```

#### Infrastructure Terms (인프라 용어)
```
Cloud Computing:
- IaaS (Infrastructure as a Service)
- PaaS (Platform as a Service)
- SaaS (Software as a Service)
- Public cloud (퍼블릭 클라우드)
- Private cloud (프라이빗 클라우드)
- Hybrid cloud (하이브리드 클라우드)
- Multi-cloud (멀티 클라우드)

Deployment:
- Container (컨테이너)
- Docker
- Kubernetes (K8s)
- Orchestration (오케스트레이션)
- Load balancer (로드 밸런서)
- Auto-scaling (오토 스케일링)
- Blue-green deployment (블루-그린 배포)
- Canary deployment (카나리 배포)

Networking:
- API Gateway
- CDN (Content Delivery Network)
- DNS (Domain Name System)
- VPN (Virtual Private Network)
- Firewall (방화벽)
- SSL/TLS certificate
- Bandwidth (대역폭)
- Latency (지연시간)
- Throughput (처리량)

Storage:
- Block storage (블록 스토리지)
- Object storage (객체 스토리지)
- Database (데이터베이스)
  ├─ Relational DB / SQL (관계형 DB)
  ├─ NoSQL (비관계형 DB)
  ├─ In-memory DB (인메모리 DB)
  └─ Data warehouse (데이터 웨어하우스)
- Backup (백업)
- Disaster recovery (DR, 재해 복구)
```

### C. Performance & Security

#### Performance Metrics (성능 지표)
```
- Response time (응답 시간)
- Uptime / Availability (가동 시간 / 가용성)
  * 99.9% uptime = "three nines"
  * 99.99% uptime = "four nines"
- Scalability (확장성)
- Throughput (처리량)
- Concurrent users (동시 사용자)
- Memory usage (메모리 사용량)
- CPU utilization (CPU 사용률)
- Disk I/O (디스크 입출력)
```

#### Security Terms (보안 용어)
```
Authentication & Authorization:
- Authentication (인증) - Who you are
- Authorization (인가) - What you can do
- Single Sign-On (SSO)
- Multi-factor Authentication (MFA)
- OAuth, JWT

Security Practices:
- Encryption (암호화)
- Hashing (해싱)
- SSL/TLS
- Security audit (보안 감사)
- Vulnerability assessment (취약점 평가)
- Penetration testing (모의 침투)
- DDoS attack (분산 서비스 거부 공격)
- SQL injection (SQL 인젝션)
- XSS (Cross-Site Scripting)

Compliance:
- GDPR (General Data Protection Regulation)
- ISO 27001
- SOC 2
- PCI DSS (Payment Card Industry Data Security Standard)
```

---

## 2️⃣ Reading Technical Documents (25분)

### Example 1: Technical Specification Document

```
PROJECT: Customer Portal Redesign
VERSION: 1.0
DATE: 2024-06-15

1. OVERVIEW
This document outlines the technical specifications for redesigning
the customer portal with improved performance and user experience.

2. SYSTEM REQUIREMENTS

2.1 Frontend
- Framework: React 18.x
- State Management: Redux Toolkit
- UI Library: Material-UI v5
- Build Tool: Vite
- Browser Support: Chrome 90+, Firefox 88+, Safari 14+

2.2 Backend
- Runtime: Node.js 18.x LTS
- Framework: Express.js 4.x
- Database: PostgreSQL 14.x
- Cache: Redis 7.x
- API Style: RESTful

2.3 Infrastructure
- Cloud Provider: AWS
- Compute: ECS (Elastic Container Service)
- Database: RDS (Relational Database Service)
- Storage: S3
- CDN: CloudFront
- Monitoring: CloudWatch + DataDog

3. ARCHITECTURE

3.1 High-Level Architecture
- Client (React SPA) → API Gateway → Backend Services → Database
- Microservices approach with 5 core services:
  * Authentication Service
  * User Management Service
  * Order Service
  * Payment Service
  * Notification Service

3.2 API Design
- RESTful endpoints
- JWT-based authentication
- Rate limiting: 100 requests/minute per user
- Response format: JSON
- Versioning: /api/v1/, /api/v2/

4. PERFORMANCE REQUIREMENTS
- Page load time: < 2 seconds
- API response time: < 200ms (95th percentile)
- Uptime: 99.9% (three nines)
- Concurrent users: 10,000
- Database queries: < 100ms

5. SECURITY REQUIREMENTS
- All communication over HTTPS
- OAuth 2.0 + MFA for authentication
- Data encryption at rest (AES-256)
- Regular security audits (quarterly)
- GDPR compliance for EU users
- PCI DSS Level 1 for payment processing

6. TESTING STRATEGY
- Unit tests: > 80% code coverage
- Integration tests: All API endpoints
- E2E tests: Critical user journeys
- Load testing: 15,000 concurrent users
- Security testing: OWASP Top 10

7. DEPLOYMENT
- CI/CD pipeline: GitHub Actions
- Containerization: Docker
- Orchestration: Kubernetes
- Deployment strategy: Blue-green
- Rollback capability: Automated

8. TIMELINE
Phase 1 (8 weeks): Backend development
Phase 2 (6 weeks): Frontend development
Phase 3 (4 weeks): Testing & QA
Phase 4 (2 weeks): Deployment & monitoring
```

### Example 2: API Documentation

```
# User Management API v2.0

## Authentication
All endpoints require JWT bearer token in header:
Authorization: Bearer <your_token>

## Base URL
https://api.example.com/v2

---

## Endpoints

### 1. Get User Profile
Retrieves the authenticated user's profile information.

**Endpoint:** GET /users/me

**Request Headers:**
Authorization: Bearer <token>

**Response (200 OK):**
{
  "id": "user_123",
  "email": "john.doe@example.com",
  "firstName": "John",
  "lastName": "Doe",
  "role": "admin",
  "createdAt": "2024-01-15T10:30:00Z",
  "lastLogin": "2024-06-20T14:22:00Z"
}

**Error Responses:**
- 401 Unauthorized: Invalid or expired token
- 404 Not Found: User not found
- 500 Internal Server Error: Server error

---

### 2. Update User Profile
Updates the authenticated user's profile.

**Endpoint:** PUT /users/me

**Request Headers:**
Authorization: Bearer <token>
Content-Type: application/json

**Request Body:**
{
  "firstName": "John",
  "lastName": "Smith",
  "phoneNumber": "+1-555-0123"
}

**Response (200 OK):**
{
  "id": "user_123",
  "email": "john.doe@example.com",
  "firstName": "John",
  "lastName": "Smith",
  "phoneNumber": "+1-555-0123",
  "updatedAt": "2024-06-20T15:00:00Z"
}

**Validation Rules:**
- firstName: 1-50 characters, letters only
- lastName: 1-50 characters, letters only
- phoneNumber: Valid E.164 format

**Error Responses:**
- 400 Bad Request: Invalid input data
- 401 Unauthorized: Invalid token
- 422 Unprocessable Entity: Validation failed

---

## Rate Limiting
- 100 requests per minute per user
- 429 Too Many Requests returned when exceeded
- Rate limit resets every minute

## Pagination
List endpoints support pagination:
- page: Page number (default: 1)
- limit: Items per page (default: 20, max: 100)

Example: GET /users?page=2&limit=50

## Error Format
{
  "error": {
    "code": "VALIDATION_ERROR",
    "message": "Invalid input data",
    "details": [
      {
        "field": "email",
        "message": "Invalid email format"
      }
    ]
  }
}
```

---

## 3️⃣ Writing Technical Documents (30분)

### Task 1: Write a Bug Report (15분 | 200단어)

**상황**:
프로덕션 환경에서 결제 시스템에 버그 발견. 개발팀에 상세한 버그 리포트를 작성하세요.

**템플릿**:
```
BUG REPORT #[number]

SUMMARY:
[One-line description of the bug]

SEVERITY: [Critical / High / Medium / Low]
PRIORITY: [P0 / P1 / P2 / P3]
STATUS: [Open / In Progress / Resolved / Closed]

ENVIRONMENT:
- Environment: [Production / Staging / Development]
- Browser: [Chrome 115.0, Safari 16.5, etc.]
- OS: [Windows 11, macOS 13.4, etc.]
- App Version: [v2.3.1]
- Server: [AWS us-east-1]

DESCRIPTION:
[Detailed description of the issue]

STEPS TO REPRODUCE:
1. [First step]
2. [Second step]
3. [Third step]
...

EXPECTED BEHAVIOR:
[What should happen]

ACTUAL BEHAVIOR:
[What actually happens]

IMPACT:
- Affected users: [number or percentage]
- Business impact: [revenue loss, user experience, etc.]
- Frequency: [Always / Sometimes / Rarely]

ERROR MESSAGES / LOGS:
```
[Paste relevant error messages or stack traces]
```

SCREENSHOTS / RECORDINGS:
[Attach or describe]

WORKAROUND:
[Temporary solution if available, or "None"]

RELATED ISSUES:
[Links to related bugs or tickets]

ASSIGNED TO: [Developer name]
REPORTED BY: [Your name]
DATE REPORTED: [Date]
```

**실전 예시 작성**:
고객이 $100 이상 결제 시 "Payment failed" 에러 발생

### Task 2: Write Technical Email to Stakeholders (15분 | 250단어)

**상황**:
시스템 장애가 발생하여 2시간 동안 서비스가 중단되었습니다. 복구 완료 후 CEO와 이해관계자들에게 상황을 설명하는 이메일을 작성하세요.

**포함 사항**:
- 장애 개요 (무슨 일이 있었는지)
- 영향 범위 (얼마나 많은 사용자에게 영향)
- 원인 (기술적이지만 이해하기 쉽게)
- 복구 조치 (무엇을 했는지)
- 재발 방지 대책
- 사과 및 향후 계획

**템플릿**:
```
TO: Executive Team, Key Stakeholders
FROM: CTO / IT Director
SUBJECT: [Date] Service Disruption - Post-Incident Report

INCIDENT SUMMARY
On [date] at [time], we experienced a service disruption that affected
[description]. The issue was fully resolved at [time], with total
downtime of [X hours/minutes].

IMPACT
- Duration: [X hours/minutes]
- Affected services: [list]
- Affected users: [number or percentage]
- Business impact: [estimated impact]

ROOT CAUSE
[Explain in non-technical terms what caused the issue]

IMMEDIATE ACTIONS TAKEN
1. [Action 1]
2. [Action 2]
3. [Action 3]

LONG-TERM PREVENTIVE MEASURES
To prevent recurrence, we will:
1. [Measure 1]
2. [Measure 2]
3. [Measure 3]

Timeline: [When these will be implemented]

COMMUNICATION
- Internal: [What was communicated to employees]
- External: [What was communicated to customers]

We sincerely apologize for this disruption and any inconvenience caused.
We are committed to maintaining the highest level of service reliability.

If you have any questions or concerns, please don't hesitate to contact me.

Best regards,
[Your name]
[Title]
```

---

## 4️⃣ Role-Play Scenarios (15분)

### Scenario 1: Sprint Planning Meeting (5분)

**상황**: Scrum 마스터가 스프린트 계획 회의 진행

```
Scrum Master (You):
"Good morning, team. Let's begin our Sprint 12 planning.
Our velocity last sprint was 45 story points. Let's review the backlog."

Developer 1:
"The authentication refactoring looks complex. I estimate 13 story points."

You:
[Facilitate discussion, clarify requirements]

Product Owner:
"Can we also include the payment gateway integration?"

You:
[Assess capacity, manage expectations]

Developer 2:
"We still have technical debt from Sprint 10. Should we address it?"

You:
[Balance new features vs. technical debt]
```

**핵심 표현**:
```
Planning:
- "Let's estimate the complexity of..."
- "How many story points would you assign to...?"
- "Our capacity for this sprint is..."
- "Let's break this user story down into smaller tasks..."

Discussing scope:
- "Given our velocity, we can realistically commit to..."
- "This might be too ambitious for one sprint..."
- "Let's prioritize based on business value..."
- "We need to leave buffer for unknowns..."

Addressing concerns:
- "That's a valid concern. Let's discuss..."
- "We'll need to allocate time for technical debt..."
- "Let's add this to the backlog for future sprints..."
```

### Scenario 2: Technical Design Review (5분)

**상황**: 아키텍트가 새로운 시스템 설계를 설명

```
You (Architect):
"I'd like to present the proposed architecture for our new analytics platform."

Senior Engineer:
"Why are you recommending microservices over monolithic?"

You:
[Explain trade-offs, scalability, team structure]

DevOps Lead:
"How will this impact our deployment process?"

You:
[Discuss CI/CD, containerization, orchestration]

Security Engineer:
"What about data security and compliance?"

You:
[Address security concerns, encryption, access control]

CTO:
"What's the estimated timeline and resource requirements?"

You:
[Provide realistic estimates]
```

**핵심 표현**:
```
Presenting architecture:
- "The system will consist of three main layers..."
- "We'll use a microservices architecture to enable..."
- "Data will flow from... to... to..."
- "This approach provides better scalability because..."

Explaining technical decisions:
- "We chose X over Y because..."
- "The trade-off is... but the benefit is..."
- "This aligns with our long-term strategy to..."
- "Based on our traffic patterns, this will handle..."

Addressing concerns:
- "That's an excellent point. We'll mitigate that by..."
- "Security is built in at every layer through..."
- "For disaster recovery, we'll implement..."
```

### Scenario 3: Production Incident Call (5분)

**상황**: 프로덕션 장애 대응 긴급 회의

```
Incident Commander (You):
"We have a P0 incident. API response times are 10x normal. Status update?"

SRE:
"Database CPU at 95%. Slow queries detected."

You:
[Prioritize actions, delegate tasks]

Backend Lead:
"Should we roll back the latest deployment?"

You:
[Make decision based on evidence]

Customer Success:
"Customers are complaining. What should we tell them?"

You:
[Provide communication guidance]

Database Admin:
"I can optimize the queries but need 30 minutes."

You:
[Decide: quick fix vs. proper fix]
```

**핵심 표현**:
```
Incident management:
- "Current severity level is P0/P1/P2..."
- "What's the blast radius?" (영향 범위)
- "Let's focus on mitigation first, then root cause..."
- "Who's available to investigate...?"

Making decisions:
- "Based on the data, we should..."
- "Let's implement the hotfix now and proper fix later..."
- "I'm making the call to roll back..."
- "Priority one is restoring service..."

Communication:
- "Update the status page with..."
- "Notify customers every 30 minutes..."
- "Internal comms: keep everyone informed..."
- "Document everything for post-mortem..."
```

---

## 5️⃣ Daily Assessment (70점)

### Part A: Vocabulary Test (20점)

**Fill in the blanks** (각 2점, 10문제):

1. We use __________ to manage multiple versions of our codebase.
2. The system's __________ is 99.99%, meaning very little downtime.
3. A __________ is a security process to verify user identity.
4. __________ testing ensures individual components work correctly.
5. We deploy using __________ to package applications with dependencies.
6. The __________ measures how fast we complete story points.
7. __________ is the practice of automating build, test, and deployment.
8. A __________ vulnerability allows attackers to inject malicious code.
9. We use __________ to distribute traffic across multiple servers.
10. __________ recovery ensures business continuity after disasters.

### Part B: Technical Writing (30점)

**Write an API endpoint documentation** (300단어):

```
Endpoint: POST /api/v1/orders
Purpose: Create a new order

Document the following:
1. Authentication requirements
2. Request format (headers, body structure)
3. Request parameters and validation rules
4. Success response (200 or 201)
5. Error responses (400, 401, 404, 500)
6. Example request and response
7. Rate limiting
```

**평가 기준**:
- Completeness (모든 요소 포함) (10점)
- Clarity (명확성) (10점)
- Technical accuracy (기술적 정확성) (5점)
- Formatting (가독성) (5점)

### Part C: Scenario Response (20점)

**Situation**: Your team missed the sprint goal for the 3rd consecutive sprint.
Write an email to your manager explaining the situation and proposing solutions.
(200단어)

**포함 사항**:
- Honest assessment of the problem
- Root causes identified
- Proposed solutions
- Commitment to improvement

---

## ✅ 학습 완료 체크
- [ ] SDLC 및 Agile/Scrum 용어 학습
- [ ] 시스템 아키텍처 및 인프라 용어 이해
- [ ] 기술 문서 읽기 (스펙, API 문서)
- [ ] 버그 리포트 작성 완료
- [ ] 기술 이메일 작성 완료
- [ ] IT 시나리오 롤플레이 완료
- [ ] Daily assessment 완료 (60% 이상)

**다음 학습**: Day 3 - Marketing & Sales English

---

## 📌 추가 학습 자료

### 추천 리소스:
```
📚 Documentation:
- MDN Web Docs (JavaScript, APIs)
- AWS Documentation
- Kubernetes Documentation

🌐 Learning Platforms:
- Stack Overflow
- GitHub
- Dev.to

🎧 Podcasts:
- Software Engineering Daily
- The Changelog
- CoRecursive
```

**💡 오늘의 팁**:
기술 영어는 명확성과 정확성이 핵심입니다.
Jargon(전문 용어)을 적절히 사용하되, 청중의 기술 수준에 맞춰 조정하세요.
비기술 팀원에게는 쉽게 풀어서 설명하는 능력이 중요합니다!
