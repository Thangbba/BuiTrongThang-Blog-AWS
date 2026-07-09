---
title: "Event 2"
date: 2026-07-09
weight: 2
chapter: false
pre: " <b> 4.3. </b> "
---


# FCJ Community Day - Knowledge Sharing Session

### Mục Đích Của Sự Kiện

- Hiểu rõ cách ứng dụng Điện toán đám mây (AWS), Container hóa (Docker) và Trí tuệ nhân tạo (Machine Learning, GraphRAG) vào các bài toán thực tế như bảo mật, làm game và quản lý dữ liệu.
- Tiếp cận góc nhìn thực tế về lộ trình phát triển sự nghiệp trong ngành IT, từ vị trí Helpdesk tiến lên Điện toán đám mây và DevOps.
- Học hỏi các phương pháp tối ưu hiệu suất làm việc nhóm và áp dụng công cụ số vào quy trình phát triển dự án công nghệ.
- Có thêm động lực rèn luyện tư duy thực chiến, tự xây dựng Lab, Portfolio cá nhân thay vì chỉ tập trung vào lý thuyết hay chứng chỉ.

### Danh Sách Diễn Giả

- **Bạn Lê Hoàng Gia Đại** - Sinh viên năm cuối Đại học HUTECH, thành viên AWS G3
- **Anh Nguyễn Quốc Bảo** - Diễn giả chuyên đề Cloud Multiplayer
- **Bạn Việt Phát** - Sinh viên ngành AI tại Đại học Công nghệ Swinburne
- **Anh Bảo Huỳnh** - Junior Cloud Native Developer tại Endava Vietnam & Founder ITea Lab
- **Anh Trương Huy Phước** - Diễn giả chuyên đề Kỹ năng mềm
- **Anh Trần Trung Vinh** - System Administrator tại Central Retail Group

### Nội Dung Nổi Bật

### 1. Diễn giả Lê Hoàng Gia Đại – AWS G3 Team (HUTECH University)

**Chủ đề:** *Machine Learning-based Network Intrusion Detection System (NIDS) on AWS (WAF + ML for Cyber Attack Detection)*
**Dịch:** *Hệ thống phát hiện xâm nhập mạng dựa trên Machine Learning trên AWS (Kết hợp WAF + ML để phát hiện tấn công mạng)*

Diễn giả Lê Hoàng Gia Đại đã mang đến giải pháp tối ưu bảo mật bằng cách kết hợp AWS WAF truyền thống (vốn dựa trên tập luật có sẵn và dễ bị bỏ qua bởi các cuộc tấn công Zero-day hoặc hành vi bất thường mới) với hệ thống NIDS sử dụng học máy. 

Nội dung chính tập trung vào quy trình xử lý dữ liệu từ bộ dữ liệu CSE-CIC-IDS2018, huấn luyện các mô hình như Random Forest, LightGBM, XGBoost để phát hiện các loại tấn công phức tạp (SQLi, XSS, DoS, Botnet...). Kiến trúc hệ thống được triển khai đồng bộ trên nền tảng đám mây AWS với các dịch vụ cốt lõi như VPC, EC2, ALB, S3, Kinesis Data Firehose, Lambda và Security Hub để giám sát và cảnh báo theo thời gian thực thông qua một Dashboard trực quan.

**Kết quả hoặc giá trị đạt được:**
Bài chia sẻ giúp em nhận thức được tầm quan trọng của việc kết hợp các giải pháp bảo mật chủ động (ML-based NIDS) bên cạnh các bức tường lửa truyền thống. Em học được quy trình chuẩn bị dữ liệu thực tế (xử lý mất cân bằng nhãn), cách đánh giá mô hình qua Confusion Matrix và kiến trúc vận hành tự động hóa trên hệ sinh thái AWS Cloud.

---

### 2. Diễn giả Nguyễn Quốc Bảo – Cloud Multiplayer Specialist

**Chủ đề:** *Multiplayer in the Cloud: Connecting Godot Clients with AWS WebSockets*
**Dịch:** *Chơi game đa người chơi trên Cloud: Kết nối các Client Godot bằng AWS WebSockets*

Anh Nguyễn Quốc Bảo đã phân tích chuyên sâu về kiến trúc mạng trong phát triển game đa người chơi, so sánh giữa các giao thức UDP/ENet, HTTP Polling và WebSocket. Chuyên đề tập trung vào giải pháp sử dụng WebSocket kết hợp với AWS để xây dựng hệ thống phòng chờ (Lobby), Chat và cơ chế ghép trận (Matchmaking) thời gian thực cho các tựa game dạng Turn-based.

Kiến trúc triển khai bao gồm API Gateway WebSocket làm cổng kết nối, xử lý các tuyến (routes) thông qua các hàm AWS Lambda không trạng thái (Stateless Lambda), ghi nhận và quản lý trạng thái trận đấu (finding_match, choice, result) trong cơ sở dữ liệu DynamoDB. Phía client được hiện thực hóa trực tiếp trên Game Engine Godot 4 bằng cách điều khiển vòng lặp mạng thông qua hàm `poll()` và xử lý gửi nhận dữ liệu dạng chuỗi JSON.

**Kết quả hoặc giá trị đạt được:**
Qua bài thuyết trình, em hiểu được cách thiết kế một hệ thống backend không máy chủ (Serverless) đáp ứng yêu cầu truyền thông hai chiều toàn phần (Full-duplex). Đồng thời, em cũng nhận diện được các thách thức thực tế như bài toán dọn dẹp kết nối rác (Stale Connections), chi phí quét dữ liệu DynamoDB và định hướng nâng cấp lên AWS GameLift khi cần máy chủ chuyên dụng (Dedicated Server) cho các game FPS/Racing đòi hỏi tần số đồng bộ cao.

---

### 3. Diễn giả Việt Phát – Swinburne University of Technology

**Chủ đề:** *GraphRAG: Build GraphRAG applications using Amazon Bedrock and Amazon Neptune*
**Dịch:** *GraphRAG: Xây dựng các ứng dụng GraphRAG sử dụng Amazon Bedrock và Amazon Neptune*

Bạn Việt Phát mang đến một góc nhìn tiên tiến về kỹ thuật RAG (Retrieval-Augmented Generation) - phương pháp bổ sung kiến thức bên ngoài vào Prompt để mô hình ngôn ngữ lớn (LLM) trả lời chính xác hơn. Diễn giả đã vạch rõ điểm hạn chế của RAG truyền thống khi gặp các câu hỏi dạng phức hợp, cần truy vấn qua nhiều thực thể (Multi-hop Reasoning).

Giải pháp được đưa ra là GraphRAG, tận dụng cấu trúc Đồ thị tri thức (Knowledge Graph) để lưu trữ tường minh các mối quan hệ thông qua các nút (Nodes) và cạnh (Edges). Bài viết chỉ ra 2 hướng triển khai trên AWS: Hướng quản lý hoàn toàn (Fully Managed Route) bằng cách kết hợp Amazon Bedrock Knowledge Bases với Amazon Neptune Analytics; và Hướng tùy biến (Custom Route) sử dụng LlamaIndex để trích xuất thực thể và lưu vào cơ sở dữ liệu đồ thị Amazon Neptune để thực hiện các câu lệnh truy vấn Cypher Query.

**Kết quả hoặc giá trị đạt được:**
Em hiểu sâu hơn về xu hướng phát triển mới của AI tạo sinh (GenAI), biết cách khắc phục điểm yếu "ảo tưởng" của LLM khi xử lý luồng thông tin phức tạp. Kiến thức về liên kết dữ liệu dạng đồ thị giúp em mở rộng tư duy thiết kế hệ thống quản trị tri thức thông minh cho doanh nghiệp.

---

### 4. Diễn giả Bảo Huỳnh – Endava Vietnam & ITea Lab

**Chủ đề:** *Docker – A containerization technology*
**Dịch:** *Docker – Công nghệ container hóa*

Diễn giả Bảo Huỳnh đã mang đến một bài chia sẻ thực tế và trực quan về ảo hóa và container hóa. Anh giải thích lý do vì sao kiến trúc máy ảo truyền thống (Virtual Machines) thường cồng kềnh, tiêu tốn nhiều tài nguyên do mỗi VM phải chạy một hệ điều hành khách (Guest OS) riêng biệt.

Docker xuất hiện như một giải pháp thay thế gọn nhẹ (Lightweight), cho phép đóng gói ứng dụng cùng tất cả các thư viện, cấu hình phụ thuộc vào trong một Package duy nhất. Các Container này chia sẻ chung nhân hệ điều hành của máy chủ (Host OS) giúp khởi động nhanh trong tích tắc (miliseconds), tiết kiệm bộ nhớ và đảm bảo tính nhất quán "chạy mượt mà ở mọi môi trường" từ máy local của lập trình viên cho đến Cloud. Bài trình bày cũng đi qua cấu trúc của một Dockerfile mẫu, cơ chế bộ đệm phân lớp (Image Layers Cache) và các tập lệnh CLI thông dụng để quản lý Container, Mạng (Network) và Khối lưu trữ (Volume).

**Kết quả hoặc giá trị đạt được:**
Em nắm vững bản chất cốt lõi của Docker và sự khác biệt giữa VM và Container. Từ đó, em biết cách ứng dụng Docker vào quy trình phát triển phần mềm, xây dựng kiến trúc Microservices và tích hợp vào các đường ống tự động hóa CI/CD một cách tối ưu.

---

### 5. Diễn giả Trương Huy Phước – Teamwork Expert

**Chủ đề:** *The Art of Effective Teamwork*
**Dịch:** *Nghệ thuật làm việc nhóm hiệu quả*

Anh Trương Huy Phước đã chia sẻ về các kỹ năng mềm cốt lõi để nâng cao hiệu suất làm việc tập thể. Nội dung nhấn mạnh rằng một nhóm làm việc hiệu quả không chỉ đơn thuần là gộp nhiều người lại, mà cần tuân thủ theo **4 Quy vàng (The 4 Golden Rules)**: Thiết lập mục tiêu rõ ràng và chung sức (Clear & Shared Goals); Sắp xếp đúng người, đúng việc (Right Person, Right Place); Giao tiếp cởi mở và lắng nghe tích cực (Open Communication & Active Listening); Nâng cao tinh thần trách nhiệm cá nhân (Personal Accountability).

Bên cạnh tư duy phối hợp, diễn giả còn giới thiệu các bộ công cụ số hóa giúp tối ưu hóa quy trình làm việc nhóm hiện đại, bao gồm công cụ quản lý tiến độ công việc (Trello, ClickUp), không gian làm việc tài liệu chung (Google Workspace) và hệ thống liên lạc nội bộ nhanh chóng (Slack, Discord).

**Kết quả hoặc giá trị đạt được:**
Em nhận thức rõ hơn về vai trò của từng cá nhân trong một tập thể và học được cách quản trị xung đột, phân chia công việc hợp lý. Việc áp dụng nhuần nhuyễn các công cụ như Trello hay Discord sẽ giúp em quản lý các dự án nhóm ở trường đại học chuyên nghiệp và hiệu quả hơn.

---

### 6. Diễn giả Trần Trung Vinh – Senior System Administrator tại Central Retail Group

**Chủ đề:** *From IT Helpdesk to Senior Sysadmin: A practical career journey*
**Dịch:** *Từ IT Helpdesk đến Senior Sysadmin: Hành trình sự nghiệp thực tế*

Anh Trần Trung Vinh mang đến một câu chuyện truyền cảm hứng thực tế dành cho các bạn sinh viên và lập trình viên trẻ. Xuất phát điểm từ vị trí IT Helpdesk không có nhiều lợi thế, anh đã tận dụng môi trường này để rèn luyện kỹ năng xử lý sự cố dưới áp lực cao, kỹ năng giao tiếp với người dùng cuối và hiểu cách vận hành cơ bản của hệ thống IT.

Bước ngoặt lớn đến khi anh quyết định đi sâu nghiên cứu hệ điều hành Linux, mạng máy tính (Networking) và tự xây dựng các môi trường Lab thực hành để tiến lên vị trí Sysadmin quản lý hạ tầng. Khi xu hướng công nghệ chuyển dịch, anh tiếp tục thực hiện cuộc cách mạng tư duy: chuyển từ hạ tầng vật lý (On-Premise) sang tư duy Điện toán đám mây (Cloud Mindset) với AWS, tự động hóa hạ tầng bằng mã lệnh (IaC - Terraform) và xây dựng văn hóa DevOps (CI/CD, Docker). Diễn giả cũng chia sẻ kinh nghiệm phỏng vấn thực tế tại Central Retail Group và nhắc nhở quy tắc sống còn của kỹ sư hệ thống: "Không bao giờ được kiểm thử trên môi trường Production".

**Kết quả hoặc giá trị đạt được:**
Bài chia sẻ giúp em định hình rõ ràng lộ trình phát triển bản thân. Em thấm thía lời khuyên của anh: hãy học sâu từ 1-2 công nghệ cốt lõi, tập trung xây dựng các sản phẩm/Lab thực tế để tạo Portfolio ấn tượng thay vì chạy theo số lượng chứng chỉ, và quan trọng nhất là "Điểm khởi đầu không quyết định tất cả - hành trình liên tục tiến về phía trước mới là câu trả lời".


