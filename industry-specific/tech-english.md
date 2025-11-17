# Technology & IT English
# 기술 및 IT 영어

## Table of Contents | 목차

1. [Software Development](#software-development)
2. [Cloud Computing](#cloud-computing)
3. [AI & Machine Learning](#ai--machine-learning)
4. [Cybersecurity](#cybersecurity)
5. [DevOps & Agile](#devops--agile)
6. [Product Management](#product-management)
7. [System Architecture](#system-architecture)
8. [Data Engineering](#data-engineering)
9. [Example Dialogues](#example-dialogues)
10. [Practice Exercises](#practice-exercises)

---

## Software Development

### Core Programming Terms | 핵심 프로그래밍 용어 (150 terms)

#### Programming Fundamentals

| English Term | Korean | Definition | Example Sentence |
|--------------|--------|------------|------------------|
| Algorithm | 알고리즘 | Step-by-step procedure for solving problem | We optimized the sorting algorithm for better performance. |
| API (Application Programming Interface) | API | Interface for software interaction | The REST API returns JSON responses. |
| Array | 배열 | Collection of elements | Store the values in an array for quick access. |
| Boolean | 불리언 | True/false value | The boolean flag indicates whether the user is logged in. |
| Bug | 버그 | Error in code | We found a critical bug in the payment module. |
| Cache | 캐시 | Temporary data storage | Implement caching to reduce database queries. |
| Class | 클래스 | Blueprint for objects | Create a User class with authentication methods. |
| Compile | 컴파일 | Convert code to executable | The code compiles without errors. |
| Concurrency | 동시성 | Multiple processes running simultaneously | Handle concurrency with thread locks. |
| Constructor | 생성자 | Method that initializes object | The constructor sets default values. |
| Data Structure | 자료구조 | Way of organizing data | Choose the right data structure for efficiency. |
| Debug | 디버그 | Find and fix errors | I'm debugging the authentication flow. |
| Dependency | 의존성 | Required external code/library | Update all dependencies to latest versions. |
| Deployment | 배포 | Release code to production | We're deploying to production tonight. |
| Encryption | 암호화 | Converting data to secure format | Use AES encryption for sensitive data. |
| Exception | 예외 | Error during execution | Handle exceptions gracefully. |
| Framework | 프레임워크 | Reusable code structure | We're using React framework for the frontend. |
| Function | 함수 | Reusable block of code | Write a function to validate email addresses. |
| Git | 깃 | Version control system | Commit your changes to git. |
| Hash | 해시 | Convert data to fixed-size value | Hash the password before storing. |
| IDE (Integrated Development Environment) | 통합개발환경 | Software for coding | VSCode is my preferred IDE. |
| Inheritance | 상속 | Class deriving from another | The Admin class inherits from User. |
| Iterator | 반복자 | Object for traversing collection | Use an iterator to loop through the array. |
| JSON (JavaScript Object Notation) | JSON | Data interchange format | The API returns data in JSON format. |
| Library | 라이브러리 | Collection of reusable code | Import the datetime library. |

#### Advanced Development Concepts

| English Term | Korean | Definition | Example Sentence |
|--------------|--------|------------|------------------|
| Abstraction | 추상화 | Hiding implementation details | Use abstraction to simplify the interface. |
| Asynchronous | 비동기 | Non-blocking execution | Make asynchronous API calls for better UX. |
| Closure | 클로저 | Function with access to outer scope | Closures help maintain private variables. |
| Decorator | 데코레이터 | Pattern for adding functionality | Apply decorators to add logging. |
| Design Pattern | 디자인 패턴 | Reusable solution template | Implement the singleton pattern. |
| Encapsulation | 캡슐화 | Bundling data with methods | Encapsulation promotes data hiding. |
| Garbage Collection | 가비지 컬렉션 | Automatic memory management | The garbage collector freed up memory. |
| Immutable | 불변 | Cannot be changed after creation | Use immutable data structures in React. |
| Lazy Loading | 지연 로딩 | Load resources on demand | Implement lazy loading for images. |
| Memory Leak | 메모리 누수 | Failure to release unused memory | Fix the memory leak in the event listener. |
| Middleware | 미들웨어 | Software between components | Add authentication middleware. |
| Mutex | 뮤텍스 | Mutual exclusion lock | Use mutex to prevent race conditions. |
| Null Pointer | 널 포인터 | Reference to nothing | Check for null pointers to avoid crashes. |
| Object-Oriented Programming (OOP) | 객체지향 프로그래밍 | Programming paradigm using objects | OOP principles improve code maintainability. |
| Polymorphism | 다형성 | Same interface, different implementations | Polymorphism allows flexible code design. |
| Recursion | 재귀 | Function calling itself | Use recursion for tree traversal. |
| Refactoring | 리팩토링 | Restructuring existing code | We're refactoring the legacy codebase. |
| Regular Expression (Regex) | 정규표현식 | Pattern matching | Use regex to validate phone numbers. |
| Repository | 저장소 | Code storage location | Clone the repository from GitHub. |
| Scalability | 확장성 | Ability to handle growth | Design for scalability from the start. |
| Serialization | 직렬화 | Convert object to storable format | Serialize the object before caching. |
| Thread | 스레드 | Smallest unit of processing | Spawn multiple threads for parallel processing. |
| Type Safety | 타입 안정성 | Preventing type errors | TypeScript provides type safety. |
| Unit Test | 단위 테스트 | Test of individual component | Write unit tests for all functions. |
| Webhook | 웹훅 | HTTP callback | Set up webhooks for real-time notifications. |

### Software Development Phrases | 소프트웨어 개발 표현

**Code Review Comments:**
- "This looks good, but we should add error handling here"
- "이 부분은 좋아 보이지만, 여기에 에러 처리를 추가해야 합니다"
- "Can we extract this into a separate function for reusability?"
- "재사용성을 위해 이것을 별도 함수로 추출할 수 있을까요?"
- "LGTM (Looks Good To Me), approved for merge"
- "제게는 좋아 보입니다, 병합 승인합니다"
- "Let's add unit tests before merging this PR"
- "이 PR을 병합하기 전에 단위 테스트를 추가합시다"

**Technical Discussions:**
- "We're experiencing race conditions in the multi-threaded environment"
- "다중 스레드 환경에서 경쟁 조건이 발생하고 있습니다"
- "The database query is causing a bottleneck"
- "데이터베이스 쿼리가 병목을 일으키고 있습니다"
- "We need to implement pagination for better performance"
- "더 나은 성능을 위해 페이지네이션을 구현해야 합니다"
- "Let's use dependency injection for better testability"
- "더 나은 테스트 가능성을 위해 의존성 주입을 사용합시다"

### Sample Dialogue: Sprint Planning | 스프린트 계획 대화

**Product Owner (PO):** Let's go through the backlog for the next sprint. The top priority is the user authentication feature.
**제품 책임자:** 다음 스프린트를 위한 백로그를 살펴봅시다. 최우선은 사용자 인증 기능입니다.

**Developer 1 (D1):** What's the scope? Are we implementing OAuth or building our own auth system?
**개발자 1:** 범위가 어떻게 되나요? OAuth를 구현하는 건가요, 아니면 자체 인증 시스템을 구축하나요?

**PO:** Let's use OAuth 2.0 with support for Google and GitHub sign-in. We also need JWT token management.
**제품 책임자:** Google과 GitHub 로그인을 지원하는 OAuth 2.0을 사용합시다. JWT 토큰 관리도 필요합니다.

**Developer 2 (D2):** That's at least 13 story points. We'll need to set up the OAuth flow, implement the callback handlers, and create the JWT middleware.
**개발자 2:** 최소 13 스토리 포인트입니다. OAuth 플로우 설정, 콜백 핸들러 구현, JWT 미들웨어 생성이 필요합니다.

**D1:** Don't forget about session management and refresh token logic. Should we also include rate limiting to prevent brute force attacks?
**개발자 1:** 세션 관리와 리프레시 토큰 로직도 잊지 마세요. 무차별 대입 공격 방지를 위한 속도 제한도 포함해야 할까요?

**PO:** Good point. Yes, add rate limiting. What about the database schema changes?
**제품 책임자:** 좋은 지적입니다. 네, 속도 제한을 추가하세요. 데이터베이스 스키마 변경은 어떻습니까?

**D2:** We'll need to add a users table with email, oauth_provider, and token columns. I'll write the migration scripts.
**개발자 2:** 이메일, oauth_provider, 토큰 컬럼이 있는 users 테이블을 추가해야 합니다. 마이그레이션 스크립트를 작성하겠습니다.

**Tech Lead (TL):** Make sure to encrypt the tokens at rest. Also, let's add comprehensive logging for security auditing.
**기술 리더:** 토큰을 저장 시 암호화해야 합니다. 또한 보안 감사를 위한 포괄적인 로깅을 추가합시다.

**D1:** I'll take this story. I estimate 3 days for implementation and 1 day for testing.
**개발자 1:** 이 스토리를 맡겠습니다. 구현에 3일, 테스팅에 1일로 추정합니다.

---

## Cloud Computing

### Cloud Services Terminology | 클라우드 서비스 용어 (100 terms)

#### Cloud Fundamentals

| English Term | Korean | Definition | Example Sentence |
|--------------|--------|------------|------------------|
| IaaS (Infrastructure as a Service) | 서비스형 인프라 | Virtual computing resources | AWS EC2 is an IaaS offering. |
| PaaS (Platform as a Service) | 서비스형 플랫폼 | Platform for app development | Heroku is a popular PaaS solution. |
| SaaS (Software as a Service) | 서비스형 소프트웨어 | Software delivered over internet | Salesforce is a SaaS application. |
| Virtual Machine (VM) | 가상머신 | Emulated computer system | Spin up a new VM in the cloud. |
| Container | 컨테이너 | Isolated application environment | Deploy the app in Docker containers. |
| Serverless | 서버리스 | Cloud provider manages servers | Use AWS Lambda for serverless functions. |
| Auto-scaling | 자동 스케일링 | Automatic capacity adjustment | Configure auto-scaling based on CPU usage. |
| Load Balancer | 로드 밸런서 | Traffic distribution system | The load balancer distributes requests evenly. |
| CDN (Content Delivery Network) | 콘텐츠 전송 네트워크 | Distributed server network | Use CloudFront CDN for faster delivery. |
| Object Storage | 객체 스토리지 | Scalable file storage | Store images in S3 object storage. |
| Compute Instance | 컴퓨팅 인스턴스 | Virtual server | Launch a t3.medium compute instance. |
| Region | 리전 | Geographical location | Deploy in the us-east-1 region. |
| Availability Zone | 가용 영역 | Isolated datacenter | Distribute across multiple availability zones. |
| Elastic IP | 탄력적 IP | Static IP address | Allocate an Elastic IP for the server. |
| VPC (Virtual Private Cloud) | 가상 프라이빗 클라우드 | Isolated cloud network | Create a VPC with public and private subnets. |
| Security Group | 보안 그룹 | Virtual firewall | Configure security group rules. |
| Snapshot | 스냅샷 | Point-in-time backup | Take daily snapshots of the volume. |
| Elastic Block Store (EBS) | 탄력적 블록 스토어 | Block-level storage | Attach an EBS volume for persistent storage. |
| Cloud Migration | 클라우드 마이그레이션 | Moving to cloud | Plan the cloud migration strategy. |
| Hybrid Cloud | 하이브리드 클라우드 | On-premise and cloud mix | Implement a hybrid cloud architecture. |

#### AWS Services (Amazon Web Services)

| English Term | Korean | Definition | Example Sentence |
|--------------|--------|------------|------------------|
| EC2 (Elastic Compute Cloud) | EC2 | Virtual servers | Launch EC2 instances on demand. |
| S3 (Simple Storage Service) | S3 | Object storage service | Upload files to S3 bucket. |
| RDS (Relational Database Service) | RDS | Managed database | Create a PostgreSQL RDS instance. |
| Lambda | 람다 | Serverless compute | Trigger Lambda functions on S3 upload. |
| CloudWatch | 클라우드와치 | Monitoring service | Set up CloudWatch alarms for CPU. |
| IAM (Identity Access Management) | IAM | Access control | Create IAM roles for EC2 instances. |
| Route 53 | 라우트 53 | DNS service | Configure Route 53 for domain routing. |
| CloudFront | 클라우드프론트 | CDN service | Distribute content via CloudFront. |
| ECS (Elastic Container Service) | ECS | Container orchestration | Deploy Docker containers on ECS. |
| EKS (Elastic Kubernetes Service) | EKS | Managed Kubernetes | Run Kubernetes on EKS. |
| DynamoDB | 다이나모DB | NoSQL database | Store session data in DynamoDB. |
| SQS (Simple Queue Service) | SQS | Message queue | Decouple services using SQS. |
| SNS (Simple Notification Service) | SNS | Pub/sub messaging | Send notifications via SNS. |
| API Gateway | API 게이트웨이 | API management | Create REST APIs with API Gateway. |
| CloudFormation | 클라우드포메이션 | Infrastructure as code | Deploy infrastructure using CloudFormation. |

### Cloud Communication Phrases | 클라우드 커뮤니케이션 표현

**Architecture Discussions:**
- "We're adopting a multi-cloud strategy to avoid vendor lock-in"
- "벤더 종속을 피하기 위해 멀티 클라우드 전략을 채택하고 있습니다"
- "The application is deployed across three availability zones for high availability"
- "고가용성을 위해 애플리케이션이 세 개의 가용 영역에 배포되어 있습니다"
- "We need to implement blue-green deployment for zero-downtime updates"
- "무중단 업데이트를 위해 블루-그린 배포를 구현해야 합니다"

**Cost Optimization:**
- "We can reduce costs by using Reserved Instances instead of On-Demand"
- "온디맨드 대신 예약 인스턴스를 사용하여 비용을 절감할 수 있습니다"
- "Right-size the instances based on actual usage patterns"
- "실제 사용 패턴에 따라 인스턴스를 적정 크기로 조정하세요"
- "Implement lifecycle policies to archive old S3 objects to Glacier"
- "오래된 S3 객체를 Glacier로 아카이브하는 수명 주기 정책을 구현하세요"

---

## AI & Machine Learning

### AI/ML Terminology | AI/ML 용어 (100 terms)

#### Machine Learning Basics

| English Term | Korean | Definition | Example Sentence |
|--------------|--------|------------|------------------|
| Machine Learning | 머신러닝 | Algorithms that learn from data | Machine learning improves predictions over time. |
| Deep Learning | 딥러닝 | ML using neural networks | Deep learning powers image recognition. |
| Neural Network | 신경망 | Interconnected node layers | Train a neural network on the dataset. |
| Training Data | 훈련 데이터 | Data used to train model | We need more training data for accuracy. |
| Test Data | 테스트 데이터 | Data used to evaluate model | Evaluate performance on test data. |
| Feature | 특성 | Input variable for model | Extract features from raw data. |
| Label | 레이블 | Output/target variable | Label the dataset for supervised learning. |
| Model | 모델 | Trained algorithm | Deploy the model to production. |
| Accuracy | 정확도 | Correct predictions ratio | The model achieved 95% accuracy. |
| Precision | 정밀도 | True positive rate | Precision is high but recall is low. |
| Recall | 재현율 | Sensitivity measure | Improve recall to catch all positive cases. |
| F1 Score | F1 점수 | Harmonic mean of precision/recall | The F1 score balances precision and recall. |
| Overfitting | 과적합 | Model too specific to training data | Regularization prevents overfitting. |
| Underfitting | 과소적합 | Model too simple | The model is underfitting the data. |
| Hyperparameter | 하이퍼파라미터 | Configuration setting | Tune hyperparameters for better performance. |
| Gradient Descent | 경사하강법 | Optimization algorithm | Use gradient descent to minimize loss. |
| Loss Function | 손실 함수 | Error measurement | Minimize the loss function during training. |
| Backpropagation | 역전파 | Training algorithm for neural nets | Backpropagation updates the weights. |
| Epoch | 에포크 | Full pass through training data | Train for 100 epochs. |
| Batch | 배치 | Subset of training data | Use batch size of 32. |
| Learning Rate | 학습률 | Step size in optimization | Decrease the learning rate gradually. |
| Transfer Learning | 전이 학습 | Reusing pre-trained model | Apply transfer learning from BERT. |
| Fine-tuning | 파인튜닝 | Adjusting pre-trained model | Fine-tune the model on our dataset. |
| Inference | 추론 | Making predictions | Run inference on new images. |
| Embedding | 임베딩 | Dense vector representation | Create word embeddings for text. |

#### Advanced AI Concepts

| English Term | Korean | Definition | Example Sentence |
|--------------|--------|------------|------------------|
| Convolutional Neural Network (CNN) | 합성곱 신경망 | Neural net for image processing | CNNs excel at image classification. |
| Recurrent Neural Network (RNN) | 순환 신경망 | Neural net for sequential data | RNNs process time-series data. |
| Transformer | 트랜스포머 | Attention-based architecture | GPT uses transformer architecture. |
| Attention Mechanism | 어텐션 메커니즘 | Focus on relevant parts | Attention improves translation quality. |
| Generative AI | 생성 AI | AI that creates content | ChatGPT is a generative AI model. |
| Large Language Model (LLM) | 대규모 언어 모델 | AI trained on massive text | LLMs understand and generate text. |
| Prompt Engineering | 프롬프트 엔지니어링 | Crafting AI inputs | Effective prompt engineering improves results. |
| Reinforcement Learning | 강화학습 | Learning through rewards | Use reinforcement learning for game AI. |
| Computer Vision | 컴퓨터 비전 | Visual data processing | Computer vision detects objects in images. |
| Natural Language Processing (NLP) | 자연어 처리 | Processing human language | NLP enables chatbots to understand users. |
| Tokenization | 토큰화 | Breaking text into units | Tokenization is the first NLP step. |
| Named Entity Recognition (NER) | 개체명 인식 | Identifying entities in text | NER extracts person and location names. |
| Sentiment Analysis | 감성 분석 | Determining emotional tone | Sentiment analysis gauges customer satisfaction. |
| Classification | 분류 | Categorizing inputs | Binary classification for spam detection. |
| Regression | 회귀 | Predicting continuous values | Linear regression for price prediction. |
| Clustering | 군집화 | Grouping similar data | K-means clustering for segmentation. |
| Dimensionality Reduction | 차원 축소 | Reducing feature count | PCA for dimensionality reduction. |
| Ensemble Learning | 앙상블 학습 | Combining multiple models | Random forest uses ensemble learning. |
| Model Deployment | 모델 배포 | Putting model into production | Deploy the model via REST API. |
| MLOps | MLOps | ML operations practices | Implement MLOps for model lifecycle. |

### Sample Dialogue: ML Model Discussion | ML 모델 논의

**Data Scientist (DS):** I've finished training the customer churn prediction model. We're seeing 87% accuracy on the test set.
**데이터 과학자:** 고객 이탈 예측 모델 훈련을 마쳤습니다. 테스트 세트에서 87% 정확도를 보고 있습니다.

**ML Engineer (MLE):** What about precision and recall? For churn prediction, we care more about recall.
**ML 엔지니어:** 정밀도와 재현율은 어떤가요? 이탈 예측에서는 재현율이 더 중요합니다.

**DS:** Precision is 82%, recall is 78%. We could adjust the threshold to improve recall at the cost of some precision.
**데이터 과학자:** 정밀도는 82%, 재현율은 78%입니다. 정밀도를 일부 희생하여 재현율을 높이도록 임계값을 조정할 수 있습니다.

**Product Manager (PM):** What features are most important for the prediction?
**제품 관리자:** 예측에 가장 중요한 특성은 무엇인가요?

**DS:** Feature importance analysis shows that engagement frequency, support ticket count, and subscription length are the top three predictors.
**데이터 과학자:** 특성 중요도 분석 결과 참여 빈도, 지원 티켓 수, 구독 기간이 상위 3개 예측 변수입니다.

**MLE:** How do we plan to deploy this? Real-time API or batch processing?
**ML 엔지니어:** 어떻게 배포할 계획인가요? 실시간 API인가요 아니면 배치 처리인가요?

**PM:** We need daily batch predictions for the retention team. Can you set up an automated pipeline?
**제품 관리자:** 리텐션 팀을 위한 일일 배치 예측이 필요합니다. 자동화된 파이프라인을 설정할 수 있나요?

**MLE:** Sure. I'll containerize the model with Docker, set up a cron job, and store predictions in the data warehouse. We should also implement model monitoring to detect drift.
**ML 엔지니어:** 물론입니다. Docker로 모델을 컨테이너화하고, 크론 작업을 설정하며, 예측 결과를 데이터 웨어하우스에 저장하겠습니다. 드리프트 감지를 위한 모델 모니터링도 구현해야 합니다.

**DS:** Good point. I'll set up alerts for when accuracy drops below 80%.
**데이터 과학자:** 좋은 지적입니다. 정확도가 80% 미만으로 떨어질 때 알림을 설정하겠습니다.

---

## Cybersecurity

### Security Terminology | 보안 용어 (100 terms)

#### Security Fundamentals

| English Term | Korean | Definition | Example Sentence |
|--------------|--------|------------|------------------|
| Vulnerability | 취약점 | Security weakness | We discovered a critical vulnerability. |
| Exploit | 익스플로잇 | Attack using vulnerability | Hackers developed an exploit for the bug. |
| Threat | 위협 | Potential security danger | Assess threats to the system. |
| Risk | 위험 | Probability of threat | Quantify the security risk. |
| Attack Vector | 공격 벡터 | Method of attack | Phishing is a common attack vector. |
| Malware | 악성코드 | Malicious software | The malware infected 500 machines. |
| Ransomware | 랜섬웨어 | Data encryption malware | Ransomware locked all our files. |
| Phishing | 피싱 | Fraudulent email attack | Train employees to recognize phishing. |
| SQL Injection | SQL 인젝션 | Database attack method | Prevent SQL injection with parameterized queries. |
| Cross-Site Scripting (XSS) | 크로스 사이트 스크립팅 | Web vulnerability | Sanitize inputs to prevent XSS. |
| Firewall | 방화벽 | Network security system | Configure firewall rules. |
| Encryption | 암호화 | Data protection method | Use 256-bit encryption. |
| Authentication | 인증 | Identity verification | Implement two-factor authentication. |
| Authorization | 인가 | Permission granting | Role-based authorization controls access. |
| SSL/TLS | SSL/TLS | Secure communication protocol | Enable TLS 1.3 for all connections. |
| VPN (Virtual Private Network) | 가상 사설망 | Encrypted network connection | Connect via VPN for remote access. |
| Penetration Testing | 침투 테스트 | Simulated cyber attack | Conduct annual penetration testing. |
| Zero-Day | 제로데이 | Unknown vulnerability | A zero-day exploit was discovered. |
| Patch | 패치 | Security update | Apply security patches immediately. |
| Incident Response | 사고 대응 | Handling security breach | Activate incident response plan. |
| DDoS (Distributed Denial of Service) | 분산 서비스 거부 | Overwhelming traffic attack | Mitigate DDoS attacks with CDN. |
| Intrusion Detection | 침입 탐지 | Monitoring for attacks | IDS alerted on suspicious activity. |
| Access Control | 접근 제어 | Restricting permissions | Implement least privilege access control. |
| Data Breach | 데이터 유출 | Unauthorized data access | The breach exposed customer data. |
| Compliance | 규정 준수 | Meeting security standards | Ensure GDPR compliance. |

#### Advanced Security Concepts

| English Term | Korean | Definition | Example Sentence |
|--------------|--------|------------|------------------|
| Zero Trust | 제로 트러스트 | Never trust, always verify | Implement zero trust architecture. |
| SIEM (Security Information & Event Management) | SIEM | Security monitoring system | Splunk is our SIEM solution. |
| SOC (Security Operations Center) | 보안관제센터 | Security monitoring team | The SOC detected the intrusion. |
| Threat Intelligence | 위협 인텔리전스 | Information about threats | Leverage threat intelligence feeds. |
| Red Team | 레드팀 | Offensive security team | Red team simulates attacks. |
| Blue Team | 블루팀 | Defensive security team | Blue team strengthens defenses. |
| Bug Bounty | 버그 바운티 | Reward for finding bugs | Launch a bug bounty program. |
| Security Audit | 보안 감사 | Security assessment | Schedule quarterly security audits. |
| Honeypot | 허니팟 | Decoy system | Deploy honeypots to detect attackers. |
| Sandbox | 샌드박스 | Isolated testing environment | Analyze malware in a sandbox. |

### Security Communication | 보안 커뮤니케이션

**Incident Reporting:**
```
SECURITY INCIDENT REPORT

Incident ID: SEC-2024-001
Severity: CRITICAL
Detected: 2024-11-17 09:15 UTC

Summary:
Unauthorized access attempt detected on production database server.
프로덕션 데이터베이스 서버에서 무단 접근 시도 감지됨.

Details:
- Source IP: 192.168.1.XXX (external)
- Method: SQL injection via login form
- Status: Blocked by WAF
- WAF에 의해 차단됨

Actions Taken:
1. Blocked source IP at firewall
2. Reviewed application logs
3. Verified no data exfiltration
4. Notified security team

Recommendations:
- Implement input validation
- Update WAF rules
- Conduct code review of login module
```

**Security Best Practices:**
- "Always follow the principle of least privilege"
- "항상 최소 권한 원칙을 따르세요"
- "Never commit credentials to version control"
- "절대 자격 증명을 버전 관리에 커밋하지 마세요"
- "Enable MFA for all production access"
- "모든 프로덕션 접근에 MFA를 활성화하세요"
- "Encrypt data at rest and in transit"
- "저장 중인 데이터와 전송 중인 데이터를 암호화하세요"

---

## DevOps & Agile

### DevOps Terminology | DevOps 용어 (100 terms)

#### DevOps Practices

| English Term | Korean | Definition | Example Sentence |
|--------------|--------|------------|------------------|
| CI/CD (Continuous Integration/Deployment) | 지속적 통합/배포 | Automated build and deploy | Set up CI/CD pipeline with Jenkins. |
| Pipeline | 파이프라인 | Automated workflow | The pipeline runs tests and deploys code. |
| Build | 빌드 | Compile and package code | The build failed due to test errors. |
| Artifact | 아티팩트 | Build output | Store artifacts in Artifactory. |
| Deployment | 배포 | Release to environment | Schedule deployment for tonight. |
| Rollback | 롤백 | Revert to previous version | Rollback the deployment due to bugs. |
| Blue-Green Deployment | 블루-그린 배포 | Two identical environments | Switch traffic to green environment. |
| Canary Deployment | 카나리 배포 | Gradual rollout | Deploy to 5% of users first. |
| Feature Flag | 기능 플래그 | Toggle feature on/off | Use feature flags for testing. |
| Infrastructure as Code (IaC) | 코드형 인프라 | Infrastructure defined in code | Manage infrastructure with Terraform. |
| Configuration Management | 구성 관리 | Managing system configs | Use Ansible for configuration management. |
| Monitoring | 모니터링 | System observation | Set up monitoring with Prometheus. |
| Logging | 로깅 | Recording events | Centralize logs in ELK stack. |
| Alerting | 알림 | Notification of issues | Configure alerts for high CPU. |
| Observability | 관찰가능성 | System insight | Improve observability with tracing. |
| Service Mesh | 서비스 메시 | Microservices networking | Implement Istio service mesh. |
| Container Orchestration | 컨테이너 오케스트레이션 | Managing containers | Kubernetes handles orchestration. |
| GitOps | 깃옵스 | Git-based operations | Practice GitOps for deployments. |
| Immutable Infrastructure | 불변 인프라 | Never modify servers | Replace servers instead of updating. |
| Chaos Engineering | 카오스 엔지니어링 | Testing failure scenarios | Use Chaos Monkey for resilience testing. |

#### Agile Methodology

| English Term | Korean | Definition | Example Sentence |
|--------------|--------|------------|------------------|
| Sprint | 스프린트 | Time-boxed iteration | We run two-week sprints. |
| Scrum | 스크럼 | Agile framework | Our team practices Scrum. |
| Kanban | 칸반 | Visual workflow system | Use Kanban board for task tracking. |
| Backlog | 백로그 | Prioritized work list | Groom the backlog weekly. |
| User Story | 사용자 스토리 | Feature from user perspective | Write user stories with acceptance criteria. |
| Story Points | 스토리 포인트 | Effort estimation unit | This task is 5 story points. |
| Velocity | 벨로시티 | Work completed per sprint | Our velocity is 40 points per sprint. |
| Standup | 스탠드업 | Daily team meeting | Daily standup at 9 AM. |
| Retrospective | 회고 | Sprint reflection meeting | Discuss improvements in retrospective. |
| Demo | 데모 | Showcase completed work | Present features in sprint demo. |
| Epic | 에픽 | Large user story | Break the epic into smaller stories. |
| Burndown Chart | 번다운 차트 | Work remaining over time | The burndown chart shows good progress. |
| Definition of Done | 완료의 정의 | Completion criteria | Code review is part of our DoD. |
| Pair Programming | 페어 프로그래밍 | Two developers, one computer | Pair programming improves code quality. |
| Technical Debt | 기술 부채 | Shortcuts needing rework | Allocate time to address technical debt. |

### Sample Dialogue: DevOps Discussion | DevOps 논의

**DevOps Engineer (DE):** The deployment failed in production last night. The health check was timing out.
**DevOps 엔지니어:** 어젯밤 프로덕션 배포가 실패했습니다. 헬스 체크가 타임아웃되었습니다.

**Developer (D):** What was the error? Did the application logs show anything?
**개발자:** 에러가 무엇이었나요? 애플리케이션 로그에 뭔가 나왔나요?

**DE:** The new version increased memory usage significantly. The pods were OOMKilled (Out of Memory Killed).
**DevOps 엔지니어:** 새 버전이 메모리 사용량을 크게 증가시켰습니다. 파드들이 OOMKilled되었습니다.

**D:** We added caching in this release. I'll check if there's a memory leak.
**개발자:** 이번 릴리스에서 캐싱을 추가했습니다. 메모리 누수가 있는지 확인하겠습니다.

**DE:** In the meantime, I've rolled back to the previous version. All services are healthy now.
**DevOps 엔지니어:** 그동안 이전 버전으로 롤백했습니다. 모든 서비스가 현재 정상입니다.

**Tech Lead (TL):** Good. Let's implement better load testing before deployments. We should catch these issues in staging.
**기술 리더:** 좋습니다. 배포 전에 더 나은 부하 테스트를 구현합시다. 스테이징에서 이런 문제를 잡아야 합니다.

**DE:** Agreed. I'll also increase the memory limits for the pods and set up better monitoring for resource usage.
**DevOps 엔지니어:** 동의합니다. 파드의 메모리 제한도 늘리고 리소스 사용량에 대한 더 나은 모니터링을 설정하겠습니다.

**D:** I'll profile the application to identify the memory hotspots and optimize the caching logic.
**개발자:** 메모리 핫스팟을 식별하고 캐싱 로직을 최적화하기 위해 애플리케이션을 프로파일링하겠습니다.

---

## Product Management

### Product Management Terms | 제품 관리 용어 (80 terms)

| English Term | Korean | Definition | Example Sentence |
|--------------|--------|------------|------------------|
| Product Roadmap | 제품 로드맵 | Strategic product plan | Share the Q3 product roadmap. |
| MVP (Minimum Viable Product) | 최소기능제품 | Product with core features | Launch an MVP to test market fit. |
| Product-Market Fit | 제품-시장 적합성 | Product meets market need | We've achieved product-market fit. |
| Feature Request | 기능 요청 | User-requested capability | Prioritize feature requests from enterprise clients. |
| A/B Testing | A/B 테스팅 | Comparing two versions | Run A/B tests on the new UI. |
| Funnel | 퍼널 | Conversion path | Optimize the checkout funnel. |
| Churn | 이탈 | Customer loss rate | Reduce churn by improving onboarding. |
| Retention | 리텐션 | Customer keeping rate | Retention increased to 85%. |
| Engagement | 참여도 | User interaction level | Daily active user engagement is up. |
| KPI (Key Performance Indicator) | 핵심성과지표 | Success metric | Track KPIs weekly. |
| OKR (Objectives & Key Results) | 목표 및 핵심 결과 | Goal-setting framework | Set quarterly OKRs. |
| User Persona | 사용자 페르소나 | Fictional user archetype | Create personas based on research. |
| User Journey | 사용자 여정 | User experience path | Map the user journey. |
| Pain Point | 고충점 | User problem/frustration | Identify customer pain points. |
| Value Proposition | 가치 제안 | Unique benefit offered | Articulate our value proposition. |
| Go-to-Market Strategy | 시장진출전략 | Product launch plan | Develop GTM strategy for new product. |
| Beta Testing | 베타 테스팅 | Pre-release testing | Invite users for beta testing. |
| Launch | 론치 | Product release | Launch date is set for December 1. |
| Sunset | 서비스 종료 | End of product life | Sunset the legacy product next year. |
| Pivot | 피벗 | Strategic direction change | We decided to pivot to B2B. |

### Product Communication | 제품 커뮤니케이션

**Product Requirements Document (PRD):**
```
PRODUCT REQUIREMENTS DOCUMENT

Feature: Advanced Search Functionality
고급 검색 기능

Objective:
Enable users to filter and find content more efficiently.
사용자가 더 효율적으로 콘텐츠를 필터링하고 찾을 수 있도록 함.

User Story:
As a power user, I want to use advanced filters so that I can quickly find relevant content.

Success Metrics:
- 30% reduction in search time
- 20% increase in search usage
- 90% user satisfaction score

Requirements:
1. Multi-field search (title, author, date, tags)
2. Autocomplete suggestions
3. Save search preferences
4. Export search results

Technical Considerations:
- Implement Elasticsearch for scalability
- Response time < 200ms
- Support fuzzy matching

Timeline:
- Design: 2 weeks
- Development: 4 weeks
- Testing: 1 week
- Launch: Week of Dec 15
```

---

## Practice Exercises | 연습 문제

### Exercise 1: Technical Vocabulary | 기술 어휘

Match the term with its definition:

1. Containerization
2. Microservices
3. API
4. Continuous Integration
5. Machine Learning

A. Automated testing and merging
B. Isolated application packages
C. Algorithms that learn from data
D. Small, independent services
E. Interface for software communication

**Answers:** 1-B, 2-D, 3-E, 4-A, 5-C

### Exercise 2: Scenario Response | 시나리오 대응

**Scenario:** Your application is experiencing intermittent outages. How would you communicate this to stakeholders?

**Sample Answer:**
```
Subject: Production Issue Update - Intermittent Service Disruptions

Dear Team,

I want to update you on the service issues we're experiencing:

Current Situation:
- Users are experiencing intermittent 503 errors
- Approximately 5% of requests are affected
- Average duration: 2-3 minutes per incident
- Frequency: 3-4 times per hour

Root Cause:
Our initial investigation suggests a memory leak in the payment service causing pods to crash and restart.

Actions Taken:
1. Increased pod replicas for redundancy
2. Implemented more aggressive health checks
3. Added detailed logging for debugging
4. Escalated to senior engineering team

Next Steps:
- Deploy hotfix by 6 PM today
- Conduct post-mortem tomorrow
- Implement monitoring improvements

We apologize for the disruption and are working urgently to resolve this.

Best,
[Your Name]
```

### Exercise 3: Code Review Comment | 코드 리뷰 코멘트

Write constructive code review comments for these scenarios:

**Scenario 1:** Function lacks error handling
**Your Comment:**
"Consider adding try-catch blocks to handle potential errors gracefully. What happens if the API call fails or returns unexpected data?"

**Scenario 2:** Hard-coded values
**Your Comment:**
"Let's move these magic numbers to constants or a configuration file for better maintainability. This will make it easier to adjust values without changing code."

**Scenario 3:** Missing tests
**Your Comment:**
"Could you add unit tests for this function? Particularly test cases for edge cases like empty input, null values, and boundary conditions."

### Exercise 4: Technical Email | 기술 이메일

Write an email explaining a technical decision to non-technical stakeholders.

**Topic:** Migrating from monolith to microservices

**Sample Email:**
```
Subject: Technology Upgrade - Moving to Modern Architecture

Dear Leadership Team,

I wanted to explain an important technical upgrade we're planning.

What We're Doing:
We're modernizing our application architecture by breaking our single large application into smaller, independent services (called microservices).

Why This Matters:
1. Faster Development: Teams can work independently and deploy updates without affecting others
2. Better Reliability: If one component fails, others continue working
3. Easier Scaling: We can add resources to only the parts that need them
4. Cost Savings: More efficient resource usage reduces cloud costs by ~30%

Timeline:
- Phase 1 (Q1): Split out payment processing
- Phase 2 (Q2): Separate user authentication
- Phase 3 (Q3): Migrate remaining services

Impact:
- No downtime for users
- Improved performance within 3 months
- Long-term cost reduction

I'm happy to discuss this in more detail.

Best regards,
[Your Name]
```

---

## Additional Resources | 추가 자료

### Online Learning Platforms | 온라인 학습 플랫폼

- **Coursera** - CS and ML courses
- **Udacity** - Tech nanodegrees
- **Pluralsight** - Developer training
- **A Cloud Guru** - Cloud certifications
- **Udemy** - Practical tech courses

### Documentation | 문서

- **AWS Documentation** - Cloud services
- **Kubernetes Docs** - Container orchestration
- **TensorFlow Tutorials** - ML framework
- **React Docs** - Frontend library
- **Python Docs** - Programming language

### Tech Blogs | 기술 블로그

- **Netflix Tech Blog** - Scalability insights
- **Uber Engineering** - System design
- **Airbnb Engineering** - Best practices
- **Google Cloud Blog** - Cloud innovations
- **AWS Blog** - Cloud updates

### Podcasts | 팟캐스트

- **Software Engineering Daily** - Tech interviews
- **The Changelog** - Open source
- **Syntax** - Web development
- **Talk Python** - Python topics
- **DevOps Paradox** - DevOps practices

---

## Summary | 요약

This technology module covers essential English communication for:

**Software Development:**
- Programming terminology and concepts
- Code review and collaboration
- Technical discussions

**Cloud & Infrastructure:**
- Cloud service terminology
- Architecture discussions
- Cost and performance optimization

**AI & Machine Learning:**
- ML concepts and vocabulary
- Model development and deployment
- Data science communication

**Security:**
- Cybersecurity terminology
- Incident response
- Security best practices

**DevOps:**
- CI/CD and automation
- Monitoring and observability
- Agile methodology

**Product Management:**
- Product strategy vocabulary
- User-centric communication
- Metrics and KPIs

Practice these terms in real-world scenarios to build confidence in technical English communication!

기술 영어 커뮤니케이션에 자신감을 갖기 위해 실제 시나리오에서 이 용어들을 연습하세요!
