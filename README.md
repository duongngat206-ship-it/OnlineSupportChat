
# Online Support Chat System

## 1. Giới thiệu

Dự án xây dựng hệ thống chat hỗ trợ trực tuyến giữa khách hàng và nhân viên tư vấn.

Hệ thống sử dụng SignalR để trao đổi tin nhắn thời gian thực, RabbitMQ để truyền sự kiện và Worker Service để xử lý, lưu lịch sử hội thoại.

## 2. Công nghệ sử dụng

- C#: Ngôn ngữ lập trình
- .NET 10: Nền tảng phát triển
- ASP.NET Core Minimal API: REST API
- SignalR: Chat thời gian thực
- RabbitMQ: Message Broker
- PostgreSQL: Database
- Docker: Đóng gói và triển khai
- Git/GitHub: Quản lý mã nguồn

## 3. Cấu trúc dự án

- Chat.Api: API và SignalR Hub
- History.Worker: Xử lý sự kiện và lưu lịch sử
- Customer.Client: Ứng dụng khách hàng
- Agent.Client: Ứng dụng nhân viên tư vấn

## 4. Tiến độ thực hiện

- Tuần 1: Khởi tạo dự án và GitHub
- Tuần 2: Xây dựng REST API
- Tuần 3: Triển khai SignalR
- Tuần 4: Tích hợp RabbitMQ
- Tuần 5: Xây dựng History Worker
- Tuần 6: Docker và tích hợp hệ thống
- Tuần 7: Kiểm thử và hoàn thiện báo cáo

## 5. Trạng thái

Đang trong giai đoạn khởi tạo dự án.
