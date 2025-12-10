---
title: "Event 4"

weight: 1
chapter: false
pre: " <b> 4.4. </b> "
---

# Báo cáo sự kiện: DevOps on AWS Workshop

## Tổng quan sự kiện

**Tên sự kiện:** DevOps on AWS Workshop

**Thời gian:** Thứ Hai, ngày 17 tháng 11 năm 2025, 8:30 – 17:00

**Địa điểm:** Văn phòng AWS Vietnam

**Vai trò của tôi:** Người tham dự

---

## Mục đích sự kiện

DevOps on AWS Workshop được thiết kế để cung cấp kiến thức toàn diện và trải nghiệm thực hành với các dịch vụ AWS DevOps. Sự kiện bao gồm:

- **CI/CD Pipelines:** Hiểu về workflow tích hợp và triển khai liên tục
- **Infrastructure as Code:** Khám phá cách quản lý hạ tầng tự động
- **Container Services:** Tìm hiểu containerization và orchestration trên AWS
- **Monitoring & Observability:** Nắm vững giám sát và theo dõi hiệu suất hệ thống

Mục tiêu chính là giúp người tham dự hiểu văn hóa, nguyên tắc và best practices của DevOps, đồng thời khám phá triển khai thực tế trên AWS. Sự kiện nhấn mạnh DevOps không chỉ là công cụ mà là sự chuyển đổi văn hóa giúp tổ chức phát triển phần mềm nhanh hơn, đáng tin cậy hơn.

---

## Tổng quan chương trình

### Buổi sáng (8:30 – 12:00)

#### 8:30 – 9:00 | Chào mừng & Tư duy DevOps

**Văn hóa và Nguyên tắc DevOps:**
- Chuyển đổi từ IT truyền thống sang team hợp tác đa chức năng
- Nguyên tắc cốt lõi: Collaboration, Automation, Continuous Improvement
- Thay đổi tư duy từ "ném code qua tường" sang chia sẻ trách nhiệm

**DORA Metrics:**
- **Deployment Frequency:** Tần suất triển khai code lên production
- **Lead Time for Changes:** Thời gian từ commit đến production
- **Mean Time To Recovery (MTTR):** Thời gian phục hồi sau sự cố
- **Change Failure Rate:** Tỷ lệ deployment thất bại

#### 9:00 – 10:30 | Dịch vụ AWS DevOps – CI/CD Pipeline

**Source Control: AWS CodeCommit, Git Strategies**
- CodeCommit: Dịch vụ quản lý source code được quản lý hoàn toàn
- GitFlow và Trunk-Based Development: Chiến lược branching phù hợp

**Build & Test: CodeBuild Configuration**
- CodeBuild: Dịch vụ build tự động, hỗ trợ đa ngôn ngữ
- Buildspec files, environment variables, build artifacts
- Testing pipelines: Unit tests, integration tests, automated execution

**Deployment: CodeDeploy**
- **Blue/Green:** Zero-downtime deployment với hai môi trường giống nhau
- **Canary:** Triển khai dần dần cho một phần nhỏ người dùng
- **Rolling Updates:** Triển khai tăng dần với khả năng rollback tự động

**Orchestration: CodePipeline**
- Tự động hóa pipeline từ source đến production
- Tích hợp CodeCommit, CodeBuild, CodeDeploy
- Visual pipeline, automated triggers, parallel execution

**Demo:** Xây dựng CI/CD pipeline hoàn chỉnh từ đầu đến cuối

#### 10:30 – 10:45 | Nghỉ giải lao

#### 10:45 – 12:00 | Infrastructure as Code (IaC)

**AWS CloudFormation:**
- Templates JSON/YAML để định nghĩa tài nguyên AWS
- Stack management, drift detection, change sets
- Best practices: Template organization, parameterization, nested stacks

**AWS CDK:**
- Định nghĩa hạ tầng bằng ngôn ngữ lập trình (TypeScript, Python, Java, C#, Go)
- Constructs (L1, L2, L3), reusable patterns
- Type safety, IDE support, testing capabilities

**Demo:** So sánh triển khai với CloudFormation và CDK

**Thảo luận:** Lựa chọn giữa CloudFormation và CDK dựa trên team expertise và project requirements

### Buổi chiều (13:00 – 17:00)

#### 13:00 – 14:30 | Container Services trên AWS

**Docker Fundamentals:**
- Containerization concepts, microservices architecture
- Dockerfile, image building, container lifecycle

**Amazon ECR:**
- Container registry được quản lý hoàn toàn
- Image scanning, lifecycle policies, tích hợp với ECS/EKS

**Amazon ECS & EKS:**
- **ECS:** Container orchestration được quản lý, task definitions, services
- **EKS:** Managed Kubernetes, pods, services, deployments
- Deployment strategies: Rolling updates, Blue/Green, Canary
- Auto-scaling: Service và cluster autoscaling

**AWS App Runner:**
- Dịch vụ đơn giản để deploy containerized applications
- Auto-scaling, built-in CI/CD

**Demo & Case Study:** So sánh triển khai microservices với App Runner, ECS, EKS

#### 14:30 – 14:45 | Nghỉ giải lao

#### 14:45 – 16:00 | Monitoring & Observability

**CloudWatch:**
- Metrics, Logs, Alarms, Dashboards
- Custom metrics, log groups, alarm configuration
- Best practices: Metric naming, log retention, dashboard design

**AWS X-Ray:**
- Distributed tracing cho ứng dụng phân tán
- Service maps, performance insights, bottleneck identification
- Integration với applications và AWS services

**Demo:** Thiết lập observability hoàn chỉnh với CloudWatch và X-Ray

**Best Practices:**
- Alerting strategy, tránh alert fatigue
- Dashboard design cho các đối tượng khác nhau
- On-call processes, SLO/SLI

#### 16:00 – 16:45 | DevOps Best Practices & Case Studies

**Deployment Strategies:**
- Feature flags, A/B testing với AWS AppConfig
- Gradual rollouts, canary releases, instant rollbacks

**Automated Testing:**
- Testing pyramid: Unit, integration, end-to-end tests
- CI/CD integration, quality gates, test coverage

**Incident Management:**
- Incident response procedures, postmortems
- Blameless culture, continuous improvement

**Case Studies:**
- Startup: Rapid scaling với DevOps practices
- Enterprise: Large-scale migration, cultural transformation
- Lessons learned, ROI measurement

#### 16:45 – 17:00 | Q&A & Tổng kết

- DevOps career pathways, required skills
- AWS Certification roadmap
- Next steps và learning resources

---

## Điểm nổi bật

### CI/CD Pipeline

AWS CodePipeline cung cấp giải pháp hoàn chỉnh để tự động hóa software delivery từ source code đến production. Tích hợp CodeCommit, CodeBuild, CodeDeploy tạo workflow liền mạch, giảm can thiệp thủ công và lỗi deployment.

### Infrastructure as Code

CloudFormation và CDK đều mạnh mẽ, mỗi công cụ có ưu điểm riêng. CloudFormation dựa trên template, CDK dựa trên code với developer experience tốt hơn, type safety và testing.

### Container Services

AWS cung cấp nhiều lựa chọn (ECS, EKS, App Runner) cho các use case và mức độ phức tạp khác nhau, cho phép tổ chức chọn dịch vụ phù hợp.

### Observability

CloudWatch và X-Ray cung cấp khả năng monitoring và tracing toàn diện, cần thiết để duy trì hệ thống đáng tin cậy.

### DevOps Culture

Thành công DevOps đòi hỏi thay đổi văn hóa, không chỉ công cụ. Sự chuyển đổi hướng tới collaboration, automation và continuous improvement là nền tảng.

---

## Những điều học được

### Insights chiến lược

1. **DevOps là Văn hóa trước:** Công cụ quan trọng nhưng chuyển đổi văn hóa là nền tảng của thành công DevOps.

2. **Tác động CI/CD Automation:** Tự động hóa toàn bộ pipeline cải thiện đáng kể tốc độ, độ tin cậy và chất lượng.

3. **Lợi ích IaC:** Infrastructure as Code cho phép version control, repeatability và thay đổi hạ tầng nhanh hơn.

4. **Chiến lược Container:** Chọn dịch vụ container phù hợp phụ thuộc vào độ phức tạp, chuyên môn team và yêu cầu vận hành.

5. **Tầm quan trọng Observability:** Monitoring và tracing toàn diện là thiết yếu để duy trì hệ thống đáng tin cậy.

6. **Cải thiện liên tục:** DevOps là về học tập và cải thiện liên tục, không phải triển khai một lần.

### Insights kỹ thuật

1. **Pipeline Design:** CI/CD pipeline được thiết kế tốt giảm đáng kể thời gian và lỗi deployment.

2. **Lựa chọn IaC Tool:** Lựa chọn giữa CloudFormation và CDK phụ thuộc vào sở thích team, độ phức tạp project.

3. **Lựa chọn Container Service:** Hiểu trade-offs giữa App Runner, ECS và EKS là quan trọng.

4. **Chiến lược Monitoring:** Monitoring hiệu quả cần cân bằng giữa coverage và tránh alert fatigue.

---

## Ứng dụng vào công việc

### Hành động ngay

1. **Triển khai CI/CD:** Thiết lập CodePipeline cho automated deployments, cấu hình CodeBuild và CodeDeploy

2. **Áp dụng IaC:** Bắt đầu sử dụng CloudFormation hoặc CDK để quản lý hạ tầng

3. **Container Migration:** Đánh giá cơ hội containerization cho ứng dụng hiện có

4. **Cải thiện Monitoring:** Nâng cao CloudWatch dashboards và alarms, triển khai X-Ray tracing

5. **Thực hành DevOps:** Áp dụng nguyên tắc DevOps trong công việc hàng ngày

6. **Incident Management:** Thiết lập quy trình incident response và postmortem practices

### Chiến lược dài hạn

1. **DevOps Maturity:** Cải thiện liên tục practices, đo lường DORA metrics

2. **Phát triển kỹ năng:** Nâng cao chuyên môn CI/CD, IaC, container orchestration

3. **Certification:** Theo đuổi AWS Certified DevOps Engineer certification

---

## Trải nghiệm cá nhân

Workshop DevOps cả ngày này toàn diện, thực tế và chuyển đổi. Sự kết hợp giữa kiến thức lý thuyết, demo thực hành và case studies thực tế cung cấp nền tảng vững chắc để hiểu và triển khai DevOps practices trên AWS.

### Học hỏi từ demo

**CI/CD Pipeline Demo:** Đặc biệt có giá trị, cho thấy cách tự động hóa toàn bộ quy trình software delivery. Demo làm rõ lợi ích của automation và cách AWS services tích hợp liền mạch.

**So sánh IaC Tools:** Giúp hiểu khi nào sử dụng CloudFormation vs CDK, so sánh trade-offs giữa template-based và code-based approaches.

**So sánh Container Services:** Cung cấp hướng dẫn rõ ràng về chọn dịch vụ phù hợp, thể hiện sự khác biệt về setup complexity và operational overhead.

**Observability Setup:** Nhấn mạnh tầm quan trọng của monitoring và tracing, cho thấy cách CloudWatch và X-Ray làm việc cùng nhau.

### Nhận thức chính

**Văn hóa là nền tảng:** DevOps về cơ bản là văn hóa, không chỉ công cụ. Chuyển đổi văn hóa hướng tới collaboration, automation và continuous improvement là điều thúc đẩy thành công.

**Automation là chìa khóa:** Automation chuyển đổi software delivery, giảm lỗi và tăng độ tin cậy đáng kể.

**Observability là thiết yếu:** Monitoring và tracing toàn diện không phải tùy chọn mà là thiết yếu cho production systems.

### Tác động sự nghiệp

Workshop này đã mở rộng đáng kể hiểu biết về DevOps practices và cách triển khai trên AWS. Trải nghiệm thực hành đã cung cấp kỹ năng thực tế có thể áp dụng ngay. Workshop cũng truyền cảm hứng để:

- Theo đuổi DevOps engineering như một con đường sự nghiệp
- Cải thiện liên tục kỹ năng và kiến thức DevOps
- Đóng góp vào DevOps transformations trong tổ chức

---

## Điểm chính rút ra

1. **Bắt đầu nhỏ:** Bắt đầu với CI/CD automation cơ bản và dần mở rộng DevOps practices

2. **Văn hóa quan trọng:** Thành công DevOps đòi hỏi collaboration và thay đổi văn hóa team

3. **Chọn công cụ phù hợp:** Chọn công cụ dựa trên chuyên môn team và yêu cầu project

4. **Monitor mọi thứ:** Observability toàn diện là thiết yếu cho hệ thống đáng tin cậy

5. **Học tập liên tục:** DevOps practices phát triển nhanh, đòi hỏi học tập liên tục

6. **Đo lường thành công:** Sử dụng DORA metrics để theo dõi cải thiện và ROI

---

## Hình ảnh sự kiện

*Thêm hình ảnh sự kiện của bạn tại đây*

---

> DevOps on AWS Workshop là trải nghiệm toàn diện và chuyển đổi, cung cấp insights sâu sắc về văn hóa, practices và công cụ DevOps. Sự kết hợp giữa kiến thức lý thuyết, demo thực tế và case studies đã trang bị kiến thức và kỹ năng cần thiết để triển khai DevOps practices hiệu quả. Workshop củng cố rằng DevOps là chuyển đổi văn hóa được hỗ trợ bởi công cụ, không chỉ là bộ công cụ. Những insights thu được sẽ hướng dẫn cách tiếp cận của tôi về phát triển phần mềm, quản lý hạ tầng và collaboration team trong suốt sự nghiệp.
