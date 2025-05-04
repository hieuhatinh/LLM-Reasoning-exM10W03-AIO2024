# Exercise M10W03 - Improving Reasoning Capability of LLMs with Reinforcement Learning - AIO2024

**LLM Reasoning (LLM Suy Luận)** là khả năng của các mô hình ngôn ngữ lớn trong việc mô phỏng quy trình tư duy logic và giải quyết vấn đề theo từng bước rõ ràng, từ việc trích xuất, liên kết các luận điểm đến diễn giải chi tiết trước khi đưa ra kết quả cuối cùng.

Thay vì chỉ sinh văn bản mạch lạc dựa trên dữ liệu đã học, LLM Reasoning đòi hỏi mô hình “suy nghĩ từng bước” để đưa ra lời giải chính xác và giải thích chi tiết quá trình tư duy, đồng thời cải thiện tính minh bạch và độ tin cậy trên các nhiệm vụ như giải toán trắc nghiệm, lập luận khoa học hay phân tích ngữ nghĩa.

Trong bài tập này, chúng ta sẽ tìm hiểu cách cài đặt quá trình huấn luyện nhằm tăng cường khả năng suy luận cho một mô hình ngôn ngữ lớn thông qua dữ liệu các câu hỏi toán học. Mục tiêu là xây dựng một mô hình ngôn ngữ lớn chuyên cho việc giải toán trắc nghiệm tiếng Việt, không những có thể đưa ra đáp án đúng mà còn trình bày được chuỗi suy nghĩ logic dẫn đến đáp án đó (dẫn đến việc cải thiện hiệu suất mô hình). Bài toán được định nghĩa với đầu vào và đầu ra như sau:<br>
- **Input:** Nội dung cụ thể của bài toán cần giải quyết. <br>
- **Output:** Lời phản hồi từ mô hình, bao gồm quá trình suy nghĩ và đáp án cho câu hỏi.<br>

 ![Pipeline](/readme_img/pipeline.png "AIO2024")