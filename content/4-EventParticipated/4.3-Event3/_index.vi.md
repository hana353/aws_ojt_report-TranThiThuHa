---
title: "Event 3"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: " <b> 4.3. </b> "
---

# Báo cáo sự kiện: AI/ML/GenAI on AWS Workshop

## Tổng quan sự kiện

**Tên sự kiện:** AI/ML/GenAI on AWS Workshop

**Thời gian:** Thứ Bảy, ngày 15 tháng 11 năm 2025, 8:30 – 12:00

**Địa điểm:** Văn phòng AWS Vietnam

**Vai trò của tôi:** Người tham dự

---

## Mục đích sự kiện

AI/ML/GenAI on AWS Workshop được thiết kế cẩn thận để cung cấp trải nghiệm thực hành toàn diện với các dịch vụ trí tuệ nhân tạo và machine learning của AWS. Sự kiện tập trung chiến lược vào hai lĩnh vực quan trọng:

- **Amazon SageMaker:** Khám phá các workflow machine learning truyền thống, bao gồm hành trình hoàn chỉnh từ chuẩn bị dữ liệu đến triển khai và giám sát model
- **Amazon Bedrock:** Đi sâu vào các ứng dụng generative AI, khám phá khả năng tiên tiến để xây dựng các giải pháp thông minh, được hỗ trợ bởi AI

Mục tiêu chính của workshop là kết nối khoảng cách giữa hiểu biết lý thuyết và triển khai thực tế, trao quyền cho người tham dự để xây dựng, triển khai và quản lý các giải pháp AI/ML thực tế trên hạ tầng AWS.

---

## Tổng quan chương trình

### 8:30 – 9:00 | Chào mừng & Giới thiệu

Workshop bắt đầu với phiên chào mừng hấp dẫn, thiết lập nền tảng cho trải nghiệm học tập tương tác:

**Đăng ký & Kết nối:**
- Quy trình đăng ký suôn sẻ với phân phối tài liệu workshop toàn diện
- Cơ hội networking giá trị kết nối với các người tham dự khác, chuyên gia kỹ thuật AWS và chuyên gia ngành
- Cuộc trò chuyện không chính thức về sở thích AI/ML, kinh nghiệm và nguyện vọng sự nghiệp

**Tổng quan & Mục tiêu Workshop:**
- Trình bày rõ ràng về mục tiêu học tập và kết quả mong đợi
- Hướng dẫn chi tiết về chương trình trong ngày và cấu trúc phiên
- Giới thiệu hệ sinh thái AWS AI/ML và tầm quan trọng ngày càng tăng trong chuyển đổi công nghệ của Việt Nam

**Hoạt động phá băng:**
- Bài tập cộng tác được thiết kế để xây dựng kết nối giữa các người tham dự
- Thảo luận nhóm về use case AI/ML và thách thức theo ngành
- Thiết lập bầu không khí cộng tác, tương tác để chia sẻ kiến thức

**Bối cảnh AI/ML tại Việt Nam:**
- Tổng quan về xu hướng áp dụng AI/ML hiện tại trong các doanh nghiệp Việt Nam
- Cơ hội thị trường và thách thức độc đáo trong bối cảnh Việt Nam
- Vai trò chiến lược của AWS trong việc hỗ trợ chuyển đổi số của Việt Nam thông qua đổi mới AI/ML

### 9:00 – 10:30 | Tổng quan dịch vụ AWS AI/ML

Phiên toàn diện này cung cấp insights kỹ thuật sâu sắc về Amazon SageMaker, nền tảng machine learning được tích hợp đầy đủ của AWS.

#### Amazon SageMaker – Nền tảng ML hoàn chỉnh

**Chuẩn bị dữ liệu và gán nhãn:**

Phiên này bao gồm các kỹ thuật chuẩn bị dữ liệu thiết yếu cho thành công machine learning:

- **Phương pháp làm sạch dữ liệu:** Hiểu các cách tiếp cận có hệ thống để chuẩn bị datasets, bao gồm xử lý giá trị thiếu, xác định và quản lý outliers, và giải quyết các vấn đề chất lượng dữ liệu có thể ảnh hưởng đến hiệu suất model
- **Chiến lược Feature Engineering:** Học các phương pháp nâng cao để chuyển đổi dữ liệu thô thành các features có ý nghĩa, dự đoán để nâng cao độ chính xác và khả năng tổng quát hóa của model
- **Giải pháp gán nhãn tự động:** Khám phá khả năng SageMaker Ground Truth để tạo datasets training chất lượng cao với can thiệp thủ công tối thiểu, giảm đáng kể chi phí và thời gian gán nhãn
- **Pipeline dữ liệu có thể mở rộng:** Hiểu cách xây dựng các workflow tiền xử lý dữ liệu mạnh mẽ, có thể mở rộng để xử lý datasets quy mô lớn hiệu quả

**Training, Tuning và Triển khai Model:**

Bao phủ toàn diện vòng đời phát triển model:

- **Hạ tầng Training phân tán:** Khám phá khả năng training phân tán mạnh mẽ của SageMaker để xử lý datasets khổng lồ và các deep learning models phức tạp trên nhiều instances
- **Tối ưu Hyperparameter tự động:** Học cách tận dụng SageMaker Automatic Model Tuning để tìm hyperparameters tối ưu một cách có hệ thống, giảm thời gian thử nghiệm thủ công
- **Tùy chọn triển khai linh hoạt:**
  - **Real-time Inference:** Triển khai models cho dự đoán độ trễ thấp sử dụng SageMaker endpoints, phù hợp cho các ứng dụng tương tác
  - **Batch Inference:** Xử lý datasets lớn hiệu quả sử dụng batch transform jobs cho dự đoán hàng loạt hiệu quả về chi phí
  - **Serverless Inference:** Hiểu các tùy chọn triển khai hiệu quả về chi phí cho workloads biến đổi với auto-scaling
- **Kỹ thuật tối ưu Model:** Chiến lược để giảm kích thước model, cải thiện tốc độ inference và tối ưu chi phí mà không hy sinh độ chính xác

**Khả năng MLOps tích hợp:**

Vận hành machine learning sẵn sàng cho production:

- **Versioning và Registry Model:** Học về SageMaker Model Registry để theo dõi toàn diện các phiên bản model, metadata và lineage
- **Giám sát Production:** Hiểu cách giám sát hiệu suất model trong production sử dụng SageMaker Model Monitor, phát hiện data drift và suy giảm hiệu suất
- **Pipeline retraining tự động:** Xây dựng CI/CD pipelines để cải thiện model liên tục, đảm bảo models luôn cập nhật với các pattern dữ liệu đang phát triển
- **Theo dõi thử nghiệm:** Sử dụng SageMaker Experiments để theo dõi, so sánh và phân tích các lần training model khác nhau một cách có hệ thống
- **Quản trị Model:** Best practices để quản lý vòng đời model hoàn chỉnh và đảm bảo tuân thủ quy định

#### Demo trực tiếp: Hướng dẫn SageMaker Studio

Demo thể hiện SageMaker Studio, môi trường phát triển thống nhất cách mạng hóa workflow machine learning:

**Tích hợp Jupyter Notebook:**
- Tích hợp liền mạch với Jupyter notebooks cho phát triển tương tác, khám phá
- Tính năng cộng tác cho phép các dự án ML dựa trên team với shared workspaces
- Môi trường được cấu hình sẵn với các framework ML phổ biến (TensorFlow, PyTorch, Scikit-learn) sẵn sàng sử dụng

**Theo dõi thử nghiệm và Model Registry:**
- Giao diện trực quan trực quan để theo dõi thử nghiệm và so sánh metrics hiệu suất model
- Model registry tập trung để tổ chức, catalog và quản lý các models đã được training
- Công cụ so sánh dễ dàng để phân tích các phiên bản model khác nhau và đặc điểm hiệu suất của chúng

**Visual Workflow Builder:**
- Giao diện kéo-thả để xây dựng MLOps pipelines phức tạp mà không cần coding nhiều
- Biểu diễn trực quan của các workflow xử lý dữ liệu, training và deployment
- Tích hợp với AWS Step Functions cho orchestration workflow tinh vi

**Tích hợp dịch vụ AWS:**
- Tích hợp liền mạch với S3 cho lưu trữ và truy xuất dữ liệu có thể mở rộng
- Kết nối với các dịch vụ xử lý dữ liệu AWS (Glue, EMR, Athena) cho data pipelines toàn diện
- Tích hợp với CloudWatch cho giám sát, logging và cảnh báo toàn diện

**Insight chính:** SageMaker Studio loại bỏ nhu cầu truyền thống phải chuyển đổi giữa nhiều công cụ, cải thiện đáng kể năng suất developer và giảm thời gian từ khái niệm ban đầu đến model được triển khai, sẵn sàng cho production.

### 10:30 – 10:45 | Nghỉ giải lao

Khoảng nghỉ được tính toán kỹ lưỡng cung cấp cơ hội giá trị cho:

- Networking với các người tham dự khác và chuyên gia kỹ thuật AWS
- Thảo luận không chính thức về use case AI/ML, thách thức và giải pháp
- Đồ uống và cuộc trò chuyện thân mật về nội dung workshop và ứng dụng
- Chia sẻ kinh nghiệm và học hỏi từ góc nhìn của đồng nghiệp

### 10:45 – 12:00 | Generative AI với Amazon Bedrock

Phiên này khám phá khả năng cách mạng của Amazon Bedrock để xây dựng các ứng dụng generative AI thế hệ tiếp theo.

#### Foundation Models: Claude, Llama, Titan – Hướng dẫn so sánh & lựa chọn

**Hiểu về Foundation Models:**

Phiên này cung cấp insights toàn diện về hệ sinh thái foundation model:

- **Tổng quan hệ sinh thái Model:** Kiểm tra chi tiết các foundation models khác nhau có sẵn trên Bedrock, bao gồm Claude (Anthropic), Llama (Meta), Titan (AWS) và các models hàng đầu khác
- **Hiểu về kiến trúc:** Hiểu các kiến trúc cơ bản và điểm mạnh, đặc điểm độc đáo của chúng
- **So sánh khả năng:** So sánh có hệ thống khả năng model trên các tác vụ đa dạng bao gồm tạo văn bản, tóm tắt, trả lời câu hỏi và tạo code

**Chiến lược lựa chọn Model:**

Hướng dẫn thực tế để chọn model phù hợp:

- **Đặc điểm hiệu suất:** So sánh models trên các benchmarks và use case thực tế khác nhau để hiểu trade-offs hiệu suất
- **Phù hợp use case:** Hiểu models nào xuất sắc cho các ứng dụng cụ thể (ví dụ: viết sáng tạo, tài liệu kỹ thuật, tạo code)
- **Phân tích chi phí:** Phân tích mô hình định giá, chi phí token và chiến lược tối ưu cho các models khác nhau
- **Latency và Throughput:** So sánh tốc độ inference, khả năng mở rộng và đặc điểm thời gian phản hồi

**Best practices cho lựa chọn Model:**

- Tiêu chí để chọn model tối ưu dựa trên nhu cầu và yêu cầu kinh doanh cụ thể
- Cân bằng yêu cầu hiệu suất, chi phí và latency để tìm sự phù hợp đúng
- Chiến lược thử nghiệm với nhiều models để xác định lựa chọn tốt nhất
- Khi nào sử dụng nhiều models cho các thành phần khác nhau của một ứng dụng

**Chiến lược tối ưu chi phí:**

- Hiểu mô hình định giá và chi phí dựa trên token cho các foundation models khác nhau
- Kỹ thuật giảm chi phí inference thông qua caching, batching và thiết kế prompt hiệu quả
- Chiến lược caching cho prompts và responses thường xuyên sử dụng
- Cách tiếp cận batch processing cho scaling hiệu quả về chi phí

#### Prompt Engineering: Kỹ thuật, Chain-of-Thought Reasoning, Few-shot Learning

**Nguyên tắc cơ bản Prompt Engineering:**

Thành thạo nghệ thuật thiết kế prompt hiệu quả:

- **Tạo Prompts hiệu quả:** Học các cách tiếp cận có hệ thống để thiết kế prompts tạo ra outputs mong muốn từ language models
- **Tác động cấu trúc Prompt:** Hiểu mối quan hệ quan trọng giữa cấu trúc prompt, độ rõ ràng và chất lượng phản hồi model
- **Kỹ thuật cải thiện:** Phương pháp để nâng cao độ rõ ràng, cụ thể và hiệu quả của prompt
- **Cạm bẫy phổ biến:** Xác định và tránh các sai lầm thường gặp trong thiết kế prompt dẫn đến kết quả kém

**Chain-of-Thought Reasoning:**

Kỹ thuật lý luận nâng cao cho giải quyết vấn đề phức tạp:

- **Hướng dẫn từng bước:** Hiểu cách hướng dẫn models qua các quy trình lý luận có cấu trúc, từng bước
- **Phân rã vấn đề:** Kỹ thuật để chia nhỏ các vấn đề phức tạp thành các bước có thể quản lý, tuần tự
- **Ví dụ thực tế:** Ví dụ thực tế về chain-of-thought prompting cho các tác vụ toán học, logic và phân tích
- **Cải thiện độ chính xác:** Cách chain-of-thought reasoning cải thiện đáng kể độ chính xác model trên các tác vụ lý luận phức tạp

**Few-shot Learning:**

Tận dụng ví dụ để nâng cao hiệu suất model:

- **Học dựa trên ví dụ:** Kỹ thuật cung cấp ví dụ chiến lược để cải thiện hiệu suất model trên các tác vụ cụ thể
- **Ảnh hưởng ví dụ:** Hiểu cách few-shot examples định hình và ảnh hưởng hành vi model
- **Best practices:** Hướng dẫn cho việc chọn, định dạng và sắp xếp ví dụ để tối đa hóa hiệu quả
- **Khi nào sử dụng:** Xác định khi nào few-shot learning hiệu quả hơn fine-tuning cho các use case cụ thể
- **Chất lượng vs. Số lượng:** Cân bằng số lượng và chất lượng ví dụ cho kết quả tối ưu

**Kỹ thuật Prompting nâng cao:**

- Role-based prompting cho outputs nhất quán, phù hợp với nhân vật
- Cách tiếp cận template-based cho outputs có cấu trúc, dự đoán được
- Prompt chaining cho các tác vụ phức tạp, nhiều bước
- Xử lý lỗi và chiến lược retry cho ứng dụng mạnh mẽ

#### Retrieval-Augmented Generation (RAG): Kiến trúc & Tích hợp Knowledge Base

**Tổng quan kiến trúc RAG:**

Hiểu pattern RAG và tác động chuyển đổi của nó:

- **Nguyên tắc cơ bản RAG:** Hiểu cách RAG kết hợp một cách tinh tế việc truy xuất thông tin với khả năng generative
- **Vai trò Vector Database:** Vai trò quan trọng của vector databases trong hệ thống RAG cho semantic search và retrieval
- **Cải thiện độ chính xác:** Cách RAG cải thiện đáng kể độ chính xác và giảm hallucinations so với generation độc lập
- **So sánh với Fine-tuning:** So sánh cách tiếp cận RAG với các phương pháp fine-tuning truyền thống

**Tích hợp Knowledge Base:**

Triển khai thực tế knowledge bases:

- **Tích hợp Vector Database:** Học cách kết nối Bedrock với vector databases và knowledge bases
- **Amazon OpenSearch:** Sử dụng OpenSearch như một vector store mạnh mẽ cho ứng dụng RAG với khả năng semantic search
- **Amazon Kendra:** Tận dụng khả năng intelligent search và quản lý kiến thức của Kendra
- **Knowledge Bases tùy chỉnh:** Xây dựng knowledge bases tùy chỉnh sử dụng S3 và vector databases cho ứng dụng theo domain
- **Thu thập dữ liệu:** Best practices để thu thập, xử lý và indexing documents hiệu quả

**Pattern triển khai:**

- Best practices để xây dựng ứng dụng RAG cung cấp responses chính xác, nhận biết ngữ cảnh
- Chiến lược chunking documents cho hiệu suất retrieval tối ưu
- Tạo, lưu trữ và tối ưu embeddings
- Chiến lược retrieval nâng cao và ranking algorithms
- Kỹ thuật tạo response kết hợp hiệu quả retrieved context

**Tối ưu RAG:**

- Chiến lược cải thiện độ chính xác và relevance của retrieval
- Kỹ thuật giảm latency trong hệ thống RAG
- Cách tiếp cận tối ưu chi phí cho ứng dụng RAG
- Metrics giám sát và đánh giá cho hiệu suất RAG

#### Bedrock Agents: Workflows nhiều bước và Tích hợp công cụ

**Kiến trúc Agent:**

Hiểu khả năng agent thông minh:

- **Orchestration Workflow:** Hiểu cách Bedrock Agents có thể điều phối các workflows phức tạp, nhiều bước một cách thông minh
- **Phân rã tác vụ:** Vai trò của agents trong việc chia nhỏ các tác vụ phức tạp thành các bước có thể quản lý
- **Ra quyết định:** Khả năng ra quyết định và lập kế hoạch của agents cho hoạt động tự chủ
- **So sánh với cách tiếp cận đơn giản:** Hiểu khi nào agents cung cấp giá trị so với các cách tiếp cận dựa trên prompt đơn giản

**Tích hợp công cụ:**

Kết nối agents với hệ thống bên ngoài:

- **Tích hợp API bên ngoài:** Học cách kết nối agents với APIs bên ngoài, databases và dịch vụ AWS
- **Phát triển công cụ tùy chỉnh:** Xây dựng công cụ tùy chỉnh cho agents để mở rộng chức năng
- **Tích hợp Lambda:** Tích hợp với Lambda functions cho business logic tùy chỉnh
- **Kết nối Database:** Kết nối với các databases và nguồn dữ liệu khác nhau
- **Pattern tích hợp API:** Best practices cho tích hợp API đáng tin cậy

**Thiết kế Workflow:**

- Patterns để thiết kế ứng dụng dựa trên agent xử lý các yêu cầu người dùng phức tạp một cách tinh tế
- Xử lý cuộc trò chuyện nhiều lượt và quản lý ngữ cảnh
- Chiến lược phục hồi lỗi và fallback cho ứng dụng mạnh mẽ
- Quản lý trạng thái trong workflows agent
- Cân nhắc trải nghiệm người dùng cho tương tác agent

**Khả năng Agent:**

- Lập kế hoạch và thực thi tác vụ thông minh
- Lựa chọn và sử dụng công cụ động
- Tinh chỉnh lặp lại responses dựa trên phản hồi
- Xử lý yêu cầu người dùng mơ hồ và không đầy đủ

#### Guardrails: An toàn và Lọc nội dung

**An toàn nội dung:**

Đảm bảo ứng dụng AI an toàn:

- **Bedrock Guardrails:** Hiểu Bedrock Guardrails để lọc toàn diện nội dung có hại hoặc không phù hợp
- **Bộ lọc được xây dựng sẵn:** Khám phá các bộ lọc an toàn được xây dựng sẵn và khả năng của chúng
- **Lọc thời gian thực:** Lọc nội dung thời gian thực trong quá trình inference để ngăn chặn outputs có hại
- **Chiến lược chặn:** Chiến lược chặn và lọc hiệu quả cho các loại nội dung khác nhau

**Chính sách tùy chỉnh:**

Tùy chỉnh an toàn theo nhu cầu kinh doanh:

- **Cấu hình tùy chỉnh:** Học cách cấu hình bộ lọc nội dung tùy chỉnh dựa trên yêu cầu kinh doanh cụ thể
- **Định nghĩa chính sách:** Định nghĩa chính sách guardrail tùy chỉnh cho nhu cầu theo ngành
- **Yêu cầu tuân thủ:** Giải quyết yêu cầu tuân thủ theo ngành cụ thể
- **Tối ưu cân bằng:** Cân bằng các biện pháp an toàn với chức năng ứng dụng

**Tuân thủ và Quản trị:**

- Best practices để đảm bảo ứng dụng AI đáp ứng các tiêu chuẩn quy định và đạo đức
- Audit trails và logging toàn diện để xác minh tuân thủ
- Cân nhắc quyền riêng tư dữ liệu và tuân thủ GDPR
- Thực hành AI đạo đức và phát triển AI có trách nhiệm
- Framework tuân thủ quy định (GDPR, CCPA, v.v.)

**Best practices triển khai:**

- Tích hợp guardrails liền mạch vào ứng dụng
- Chiến lược testing và xác thực cho hiệu quả guardrail
- Giám sát hiệu suất và hiệu quả guardrail
- Cải thiện liên tục các biện pháp an toàn dựa trên sử dụng thực tế

#### Demo trực tiếp: Xây dựng Chatbot Generative AI sử dụng Bedrock

Demo cung cấp hướng dẫn hoàn chỉnh, end-to-end về xây dựng ứng dụng chatbot sẵn sàng cho production:

**Thiết lập Bedrock Foundation Model:**
- Chọn và cấu hình foundation model phù hợp cho use case
- Thiết lập tham số model và cài đặt inference cho hiệu suất tối ưu
- Hiểu khả năng, giới hạn và best use cases của model

**Triển khai RAG với tích hợp Knowledge Base:**
- Tạo knowledge base toàn diện với documents liên quan
- Thiết lập vector embeddings và cơ chế retrieval hiệu quả
- Tích hợp RAG liền mạch vào workflow chatbot
- Testing và xác thực độ chính xác retrieval

**Cấu hình Bedrock Agents:**
- Thiết lập agents thông minh cho cuộc trò chuyện nhiều lượt tinh vi
- Định nghĩa công cụ, khả năng và logic ra quyết định của agents
- Cấu hình hành vi, tính cách và phong cách phản hồi của agents
- Triển khai quản lý ngữ cảnh cuộc trò chuyện

**Thêm Guardrails:**
- Triển khai bộ lọc an toàn nội dung toàn diện
- Cấu hình chính sách guardrail tùy chỉnh cho yêu cầu cụ thể
- Testing hiệu quả guardrail với các inputs khác nhau
- Cân bằng biện pháp an toàn với trải nghiệm người dùng

**Triển khai Chatbot:**
- Kiến trúc triển khai và cân nhắc khả năng mở rộng
- Tích hợp với ứng dụng frontend và giao diện người dùng
- Thiết lập giám sát và logging toàn diện
- Chiến lược scaling cho production workloads

**Insight chính:** Demo chứng minh rằng xây dựng các ứng dụng AI tinh vi, sẵn sàng cho production hiện dễ tiếp cận hơn bao giờ hết, với AWS cung cấp các công cụ và hạ tầng toàn diện cần thiết để chuyển đổi khái niệm thành các giải pháp được triển khai một cách nhanh chóng.

---

## Điểm nổi bật chính

### Nền tảng ML toàn diện

**Giải pháp End-to-End của SageMaker:**

SageMaker cung cấp giải pháp hoàn chỉnh, tích hợp cho machine learning bao gồm mọi giai đoạn từ khám phá dữ liệu ban đầu đến triển khai production và giám sát liên tục. Nền tảng toàn diện này loại bỏ sự phức tạp của việc tích hợp nhiều công cụ khác nhau, giảm đáng kể overhead vận hành và cải thiện năng suất team.

**Lợi ích chính:**
- Giao diện thống nhất tối ưu hóa toàn bộ vòng đời ML
- Khả năng MLOps tích hợp cho triển khai production đáng tin cậy
- Hạ tầng có thể mở rộng xử lý liền mạch mọi thứ từ thử nghiệm đến production workloads
- Best practices, tính năng bảo mật và công cụ tuân thủ được tích hợp sẵn

### Khả năng Generative AI

**Truy cập Foundation Model của Amazon Bedrock:**

Amazon Bedrock cung cấp truy cập linh hoạt vào nhiều foundation models tiên tiến, cho phép thử nghiệm dễ dàng và lựa chọn thông minh model tối ưu cho mỗi use case cụ thể. Tính linh hoạt này rất quan trọng để xây dựng ứng dụng đáp ứng chính xác các yêu cầu kinh doanh độc đáo.

**Ưu điểm:**
- Nhiều tùy chọn model không bị ràng buộc nhà cung cấp, cung cấp tính linh hoạt và lựa chọn
- Thử nghiệm và so sánh dễ dàng giữa các models khác nhau
- Truy cập hiệu quả về chi phí vào các models tiên tiến mà không cần đầu tư hạ tầng
- Giao diện API nhất quán trên các models khác nhau, đơn giản hóa tích hợp

### Kiến trúc RAG

**Ứng dụng AI tăng cường kiến thức:**

Pattern RAG cho phép xây dựng các ứng dụng AI tinh vi có thể truy cập và sử dụng các knowledge bases cụ thể, liên quan đến domain, cải thiện đáng kể độ chính xác và relevance. Kiến trúc này rất cần thiết cho các ứng dụng cần cung cấp thông tin chính xác, cập nhật và phù hợp với ngữ cảnh.

**Lợi ích:**
- Truy cập kiến thức cụ thể, theo domain mà không cần retrain model
- Giảm đáng kể hallucinations và cải thiện độ chính xác thực tế
- Không cần fine-tuning model tốn kém và mất thời gian
- Dễ dàng cập nhật knowledge bases khi thông tin phát triển

### MLOps sẵn sàng cho Production

**MLOps tích hợp của SageMaker:**

Khả năng MLOps toàn diện của SageMaker đơn giản hóa quy trình phức tạp của việc triển khai và duy trì ML models trong môi trường production. Điều này rất quan trọng cho các tổ chức cần hệ thống ML đáng tin cậy, có thể mở rộng và dễ bảo trì.

**Tính năng:**
- Versioning model tự động và theo dõi toàn diện
- Giám sát production với cảnh báo tự động
- Pipeline retraining tự động để cải thiện liên tục
- Quản trị model và quản lý tuân thủ

### An toàn là ưu tiên

**Bedrock Guardrails:**

Bedrock Guardrails đảm bảo rằng các ứng dụng generative AI an toàn, tuân thủ và phù hợp với giá trị kinh doanh và tiêu chuẩn đạo đức. Điều này rất cần thiết để triển khai ứng dụng AI trong môi trường production nơi an toàn và niềm tin là tối quan trọng.

**Tầm quan trọng:**
- Bảo vệ người dùng khỏi nội dung có hại, không phù hợp hoặc thiên vị
- Đảm bảo tuân thủ quy định và bảo vệ pháp lý
- Duy trì danh tiếng thương hiệu và niềm tin người dùng
- Xây dựng niềm tin vào các ứng dụng được hỗ trợ bởi AI

---

## Những điều học được

### Insights kỹ thuật

1. **Năng suất SageMaker Studio:**
   SageMaker Studio cung cấp giao diện thống nhất cho toàn bộ vòng đời ML, cải thiện đáng kể năng suất developer. Khả năng làm việc trong một môi trường tích hợp duy nhất loại bỏ việc chuyển đổi ngữ cảnh, giảm thời gian thiết lập và tối ưu hóa workflow phát triển từ thử nghiệm đến production.

2. **Lựa chọn Foundation Model:**
   Lựa chọn foundation model rất quan trọng và phụ thuộc nhiều vào use case cụ thể, yêu cầu hiệu suất và ràng buộc chi phí. Không có giải pháp phổ quát, và thử nghiệm có hệ thống là thiết yếu để xác định model tối ưu cho mỗi ứng dụng.

3. **Tầm quan trọng Prompt Engineering:**
   Prompt engineering là kỹ năng quan trọng có thể cải thiện đáng kể outputs model mà không cần fine-tuning tốn kém. Prompts được tạo tốt có thể chuyển đổi kết quả trung bình thành hiệu suất xuất sắc, làm cho kỹ năng này thiết yếu cho AI developers.

4. **Tính thiết yếu kiến trúc RAG:**
   Kiến trúc RAG rất cần thiết để xây dựng ứng dụng AI cần truy cập thông tin cụ thể, cập nhật. Pattern này đang nhanh chóng trở thành tiêu chuẩn cho ứng dụng tập trung vào kiến thức, cung cấp độ chính xác và relevance mà các models độc lập không thể so sánh.

5. **Sự tinh vi của Bedrock Agents:**
   Bedrock Agents cho phép xây dựng ứng dụng AI tinh vi có thể xử lý các workflows phức tạp, nhiều bước một cách tự chủ. Khả năng này mở ra khả năng xây dựng ứng dụng thực sự thông minh có thể lý luận, lập kế hoạch và thực thi các tác vụ phức tạp.

6. **Ưu tiên an toàn nội dung:**
   An toàn nội dung phải được xem xét ngay từ đầu khi xây dựng ứng dụng generative AI. Guardrails nên được tích hợp vào kiến trúc thiết kế, không được thêm vào như một suy nghĩ sau, để đảm bảo bảo vệ toàn diện.

### Insights chiến lược

1. **Bắt đầu với Use Cases:**
   Luôn bắt đầu bằng cách xác định các vấn đề và yêu cầu kinh doanh cụ thể trước khi chọn giải pháp AI/ML. Công nghệ nên phục vụ mục tiêu kinh doanh, không phải thúc đẩy chúng. Hiểu sâu vấn đề dẫn đến lựa chọn và triển khai giải pháp tốt hơn.

2. **Foundation Models mạnh mẽ:**
   Pre-trained foundation models có thể giải quyết nhiều vấn đề hiệu quả mà không cần training tùy chỉnh, giảm đáng kể time-to-market và chi phí phát triển. Tận dụng các models này một cách thông minh có thể tăng tốc đổi mới.

3. **RAG là thiết yếu:**
   Đối với ứng dụng yêu cầu kiến thức cụ thể hoặc chuyên môn domain, kiến trúc RAG là cách tiếp cận tối ưu. Nó cung cấp độ chính xác, relevance và khả năng cập nhật cần thiết cho ứng dụng production mà không có sự phức tạp và chi phí của fine-tuning model.

4. **MLOps quan trọng:**
   Thực hành MLOps đúng đắn rất quan trọng để duy trì ML models trong production. Không có MLOps mạnh mẽ, models có thể suy giảm theo thời gian, trở nên không đáng tin cậy và không đạt được giá trị kinh doanh mong đợi.

5. **An toàn không thể bỏ qua:**
   Lọc nội dung và biện pháp an toàn phải được tích hợp từ giai đoạn thiết kế. Giải quyết an toàn như một suy nghĩ sau có thể dẫn đến vấn đề đáng kể, vấn đề tuân thủ và thiệt hại cho danh tiếng thương hiệu.

6. **Học tập liên tục:**
   Bối cảnh AI/ML phát triển với tốc độ chưa từng có, đòi hỏi học tập, thử nghiệm và thích ứng liên tục. Luôn cập nhật với các models, kỹ thuật và best practices mới là thiết yếu cho thành công lâu dài trong lĩnh vực đang thay đổi nhanh chóng này.

---

## Ứng dụng vào công việc

Dựa trên insights toàn diện thu được từ workshop này, tôi dự định áp dụng các chiến lược sau trong kỳ thực tập và các dự án tương lai:

### Hành động ngay

1. **Thử nghiệm với SageMaker:**
   - Thiết lập SageMaker Studio để khám phá phát triển ML model cho các dự án phân tích dữ liệu và predictive analytics
   - Xây dựng ML pipelines end-to-end thể hiện workflow hoàn chỉnh từ dữ liệu đến deployment
   - Thử nghiệm với các algorithms khác nhau, hyperparameter tuning và kỹ thuật tối ưu model

2. **Xây dựng ứng dụng RAG:**
   - Triển khai kiến trúc RAG sử dụng Bedrock và knowledge bases cho ứng dụng thực tế
   - Tạo hệ thống Q&A tài liệu nội bộ có thể trả lời câu hỏi về quy trình và chính sách công ty
   - Xây dựng knowledge assistants theo domain có thể cung cấp thông tin chính xác, nhận biết ngữ cảnh

3. **Thực hành Prompt Engineering:**
   - Phát triển kỹ năng prompt engineering bằng cách tạo templates và best practices cho use cases phổ biến
   - Xây dựng thư viện prompts hiệu quả có thể tái sử dụng trên các dự án
   - Thực hành kỹ thuật chain-of-thought và few-shot learning để cải thiện outputs model

4. **Tích hợp MLOps:**
   - Áp dụng khả năng MLOps của SageMaker để tự động hóa pipeline training và deployment model
   - Thiết lập giám sát model và pipeline retraining tự động để cải thiện liên tục
   - Triển khai thực hành CI/CD cho ML models để đảm bảo triển khai đáng tin cậy, có thể lặp lại

5. **Triển khai an toàn:**
   - Tích hợp Bedrock Guardrails vào bất kỳ ứng dụng generative AI nào tôi phát triển
   - Phát triển chính sách guardrail tùy chỉnh phù hợp với use cases và yêu cầu cụ thể
   - Đảm bảo cân nhắc tuân thủ và an toàn được giải quyết từ giai đoạn thiết kế

### Chiến lược dài hạn

1. **Phát triển kỹ năng AI/ML:**
   - Học tập liên tục về các foundation models mới và khả năng đang phát triển của chúng
   - Luôn cập nhật với best practices trong prompt engineering và tối ưu RAG
   - Khám phá các patterns và kỹ thuật nâng cao để xây dựng ứng dụng AI tinh vi

2. **Triển khai Production:**
   - Học cách triển khai ML models và ứng dụng GenAI vào môi trường production
   - Hiểu chiến lược scaling, tối ưu chi phí và performance tuning
   - Thành thạo giám sát, bảo trì và cải thiện liên tục hệ thống AI

3. **Thực hành AI đạo đức:**
   - Phát triển chuyên môn về an toàn AI, tuân thủ và cân nhắc đạo đức
   - Hiểu yêu cầu quy định cho ứng dụng AI trong các ngành khác nhau
   - Đóng góp vào việc xây dựng hệ thống AI có trách nhiệm, đáng tin cậy

---

## Trải nghiệm cá nhân

Workshop này cung cấp giới thiệu thực hành xuất sắc về các dịch vụ AWS AI/ML, kết hợp một cách điêu luyện kiến thức lý thuyết với demo thực tế và các kịch bản ứng dụng thực tế.

### Học hỏi từ các demo

**Demo SageMaker Studio:**

Demo SageMaker Studio đặc biệt ấn tượng và mở mang tầm mắt. Nó thể hiện cách một nền tảng thống nhất có thể tối ưu hóa đáng kể toàn bộ ML workflow, từ khám phá dữ liệu ban đầu qua triển khai model. Khả năng làm việc trong một môi trường tích hợp duy nhất loại bỏ ma sát truyền thống của việc chuyển đổi giữa nhiều công cụ. Visual workflow builder và khả năng MLOps tích hợp thể hiện cách các nền tảng ML hiện đại có thể giảm đáng kể sự phức tạp của việc xây dựng hệ thống ML production, làm cho ML nâng cao dễ tiếp cận hơn cho phạm vi rộng hơn của developers.

**Hiểu về kiến trúc RAG:**

Học về kiến trúc RAG là chuyển đổi. Các ví dụ thực tế đã chứng minh rõ ràng cách xây dựng ứng dụng AI có thể tận dụng knowledge bases cụ thể một cách hiệu quả. Phiên này cho thấy cách RAG có thể cung cấp responses chính xác, nhận biết ngữ cảnh bằng cách kết hợp thông minh việc truy xuất thông tin với khả năng generative. Hiểu biết này rất quan trọng để xây dựng ứng dụng AI cần cung cấp thông tin chính xác, theo domain, điều này rất cần thiết cho hầu hết các ứng dụng kinh doanh thực tế.

**Demo Bedrock Agents:**

Demo Bedrock Agents tiết lộ tiềm năng to lớn để xây dựng ứng dụng AI tinh vi có thể xử lý các workflows phức tạp, nhiều bước một cách tự chủ. Nhìn thấy cách agents có thể chia nhỏ các tác vụ phức tạp, chọn và sử dụng công cụ thông minh, và điều phối các quy trình nhiều bước là truyền cảm hứng. Khả năng này mở ra khả năng xây dựng ứng dụng thực sự thông minh có thể xử lý sự phức tạp thực tế, vượt ra ngoài trả lời câu hỏi đơn giản đến giải quyết vấn đề tinh vi.

**Tập trung Prompt Engineering:**

Tập trung thực tế vào prompt engineering cung cấp kỹ năng có thể áp dụng ngay lập tức cho làm việc với language models. Học các kỹ thuật như chain-of-thought reasoning và few-shot learning đã cho tôi các công cụ cụ thể, có thể hành động để cải thiện đáng kể outputs model. Nhấn mạnh vào prompt engineering như một kỹ năng quan trọng làm nổi bật rằng làm việc hiệu quả với AI models đòi hỏi cả kiến thức kỹ thuật và khả năng giải quyết vấn đề sáng tạo.

**Hiểu về Guardrails:**

Hiểu về Guardrails giúp tôi đánh giá cao tầm quan trọng cơ bản của an toàn và tuân thủ trong ứng dụng AI. Demo cho thấy cách guardrails có thể được tích hợp liền mạch trong khi duy trì chức năng ứng dụng và trải nghiệm người dùng. Điều này củng cố rằng xây dựng AI có trách nhiệm không chỉ về công nghệ mà đòi hỏi thiết kế cẩn thận, triển khai cẩn thận và giám sát liên tục.

### Nhận thức chính

**Khả năng tiếp cận AI/ML:**

Workshop chứng minh rằng xây dựng ứng dụng AI/ML hiện dễ tiếp cận hơn bao giờ hết. AWS cung cấp các công cụ và hạ tầng toàn diện cần thiết để chuyển đổi khái niệm thành hệ thống production mà không cần chuyên môn sâu trong mọi khía cạnh của ML. Sự dân chủ hóa AI này trao quyền cho developers ở mọi cấp độ, cho phép đổi mới trước đây bị giới hạn cho các team chuyên biệt.

**Tầm quan trọng của kiến trúc:**

Workshop củng cố rằng chọn kiến trúc đúng (RAG, agents, v.v.) rất quan trọng để xây dựng ứng dụng AI hiệu quả. Hiểu khi nào sử dụng các patterns khác nhau, cách kết hợp chúng hiệu quả và cách tối ưu chúng cho use cases cụ thể là kỹ năng chính cho AI developers. Quyết định kiến trúc có tác động sâu sắc đến hiệu suất, chi phí và khả năng bảo trì.

**An toàn như nền tảng:**

Nhấn mạnh vào guardrails và an toàn làm nổi bật rằng phát triển AI có trách nhiệm đòi hỏi suy nghĩ về an toàn ngay từ đầu của quy trình thiết kế. Điều này không chỉ về tuân thủ mà về xây dựng niềm tin, đảm bảo trải nghiệm người dùng tích cực và bảo vệ danh tiếng thương hiệu. An toàn nên là cân nhắc nền tảng, không phải add-on.

**Tiến hóa liên tục:**

Workshop làm rõ rằng bối cảnh AI/ML đang phát triển với tốc độ chưa từng có. Các models, kỹ thuật và best practices mới xuất hiện thường xuyên, đòi hỏi học tập, thích ứng và thử nghiệm liên tục. Luôn cập nhật không phải tùy chọn mà là thiết yếu cho thành công trong lĩnh vực đang thay đổi nhanh chóng này.

### Tác động đến sự nghiệp của tôi

Workshop này đã mở rộng đáng kể hiểu biết của tôi về khả năng AI/ML và cách xây dựng ứng dụng sẵn sàng cho production hiệu quả. Trải nghiệm thực hành với SageMaker và Bedrock đã cho tôi các kỹ năng thực tế, có thể áp dụng ngay lập tức mà tôi có thể sử dụng trong các dự án thực tế. Workshop cũng đã truyền cảm hứng cho tôi để:

- Khám phá các kỹ thuật và patterns AI/ML nâng cao hơn
- Xây dựng ứng dụng AI thực tế giải quyết các vấn đề kinh doanh thực tế
- Đóng góp vào thực hành phát triển AI có trách nhiệm
- Luôn cập nhật với bối cảnh AI/ML đang phát triển nhanh chóng

---

## Điểm chính rút ra

### Nguyên tắc chiến lược

1. **Bắt đầu với Use Cases:**
   Luôn bắt đầu bằng cách xác định các vấn đề và yêu cầu kinh doanh cụ thể trước khi chọn giải pháp AI/ML. Công nghệ nên giải quyết các vấn đề thực tế và cung cấp giá trị có thể đo lường, không được triển khai vì lợi ích của chính nó. Hiểu sâu vấn đề dẫn đến lựa chọn và triển khai giải pháp tốt hơn.

2. **Foundation Models mạnh mẽ:**
   Pre-trained foundation models có thể giải quyết nhiều vấn đề hiệu quả mà không cần training tùy chỉnh, tăng tốc đáng kể phát triển và giảm chi phí. Tận dụng các models này một cách thông minh có thể chuyển đổi timeline phát triển và cho phép đổi mới nhanh chóng.

3. **RAG là thiết yếu:**
   Đối với ứng dụng yêu cầu kiến thức cụ thể hoặc chuyên môn domain, kiến trúc RAG là cách tiếp cận tối ưu. Nó cung cấp độ chính xác, relevance và khả năng cập nhật cần thiết cho ứng dụng production mà không có sự phức tạp và chi phí của fine-tuning.

4. **MLOps quan trọng:**
   Thực hành MLOps đúng đắn rất quan trọng để duy trì ML models trong production. Không có MLOps mạnh mẽ, models có thể suy giảm theo thời gian, trở nên không đáng tin cậy và không đạt được giá trị kinh doanh mong đợi. MLOps không phải tùy chọn mà là thiết yếu cho hệ thống ML production.

5. **An toàn không thể bỏ qua:**
   Lọc nội dung và biện pháp an toàn phải được tích hợp từ giai đoạn thiết kế. Giải quyết an toàn như một suy nghĩ sau có thể dẫn đến vấn đề đáng kể, vấn đề tuân thủ và thiệt hại cho danh tiếng thương hiệu. An toàn là yêu cầu nền tảng, không phải nice-to-have.

6. **Học tập liên tục:**
   Bối cảnh AI/ML phát triển với tốc độ chưa từng có, đòi hỏi học tập, thử nghiệm và thích ứng liên tục. Luôn cập nhật với các models, kỹ thuật và best practices mới là thiết yếu cho thành công lâu dài trong lĩnh vực đang thay đổi nhanh chóng này.

---

## Hình ảnh sự kiện

*Thêm hình ảnh sự kiện của bạn tại đây*

---

> AI/ML/GenAI on AWS Workshop là giới thiệu toàn diện và thực tế về xây dựng ứng dụng AI trên AWS. Sự kết hợp điêu luyện giữa kiến thức lý thuyết, demo thực hành và ví dụ thực tế đã cung cấp nền tảng vững chắc cho làm việc với SageMaker và Bedrock. Những insights thu được từ workshop này đã trang bị cho tôi kiến thức và kỹ năng cần thiết để xây dựng ứng dụng AI/ML sẵn sàng cho production và đã truyền cảm hứng cho tôi tiếp tục khám phá thế giới trí tuệ nhân tạo đang phát triển nhanh chóng, thú vị. Trải nghiệm này đã định hình cơ bản hiểu biết của tôi về cách AI có thể được áp dụng thực tế để giải quyết các vấn đề thực tế.

