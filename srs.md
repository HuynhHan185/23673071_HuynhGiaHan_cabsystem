ngôn ngữ markdown 
Bước 1: phân tích ngữ cảnh bussines context, bussines problem
- bussines context
  Công ty ABC là doanh nghiệp cung cấp dịch vụ đặt xe trực tuyến (CAB).
  Hiện tại, khách hàng có thể đặt xe thông qua: Tổng đài, Ứng dụng đơn giản hiện có.
  Tuy nhiên, hệ thống hiện tại chưa đáp ứng tốt khi quy mô khách hàng và tài xế tăng lên.
- bussines problem
  ABC cần thay thế quy trình đặt xe và điều phối thủ công bằng một nền tảng CAB tập trung, có khả năng tự động hóa việc tìm tài xế, quản lý toàn bộ vòng đời chuyến đi, thanh toán, thông báo và hỗ trợ vận hành ở quy mô lớn.
- khách hàng muốn giải quyết vấn đề gì
  
- ai sẽ sử dụng he thong
  

Bước 2: xác định stakeholder trong hệ thống, những bên liên quan trong hệ thống
- lập bảng: 
cot1: những stake nào
cot2: vai trò của nó là
-duới vẽ ma trận, mức ảnh hưởng của các vai trò trong hệ thống

lập bảng
| STT | Stakeholder | Vai trò |
|-----|-------------|---------|
| 1 | Ban giám đốc | Định hướng mục tiêu, phê duyệt ngân sách và phạm vi dự án |
| 2 | Operations Manager | Quản lý vận hành, điều phối tài xế và giám sát chuyến |
| 3 | Operations Staff | Quản lý khách hàng, tài xế, phương tiện và chuyến đi |
| 4 | Customer | Đặt xe, theo dõi chuyến, thanh toán và đánh giá tài xế |
| 5 | Driver | Nhận chuyến, thực hiện chuyến và cập nhật trạng thái |
| 6 | Finance / Accounting | Quản lý doanh thu, thanh toán và đối soát |
| 7 | System Administrator | Quản trị tài khoản, phân quyền và cấu hình hệ thống |
| 8 | Payment Provider | Xử lý thanh toán điện tử |
| 9 | Notification Provider | Gửi thông báo SMS, Email, Push Notification |
| 10 | IT / Development Team | Xây dựng, triển khai và bảo trì hệ thống |
| 11 | Security / Compliance | Kiểm soát bảo mật và tuân thủ |
| 12 | Customer Support | Hỗ trợ khách hàng và xử lý khiếu nại |

ma trận
                         MỨC ĐỘ ẢNH HƯỞNG
                              CAO
                               │
                               │
          KEEP SATISFIED      │       MANAGE CLOSELY
                               │
          ┌────────────────────┼──────────────────────────┐
          │                    │                          │
          │ • Finance          │ • Ban giám đốc           │
          │ • Accounting       │ • Operations Manager     │
          │ • Security         │ • Business/Product Owner │
          │ • Compliance       │                          │
          │                    │                          │
          ├────────────────────┼──────────────────────────┤
          │                    │                          │
          │ • Payment Provider │ • Customer               │
          │ • Notification     │ • Driver                 │
          │   Provider         │ • Operations Staff        │
          │                    │ • Customer Support        │
          │                    │ • IT/Development Team     │
          │                    │                          │
          └────────────────────┼──────────────────────────┘
                               │
                              THẤP
                               │
                               └──────────────────────────────
                                  THẤP          CAO
                                     MỨC ĐỘ QUAN TÂM

Bước 3: bussines goal
bg01: hỗ trợ thanh toán
- thanh toán tiền mặt, chuyển khoản
bg02: cho phép tìm tài xế tự động


