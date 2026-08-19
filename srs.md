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
<table>
  <tr>
    <th></th>
    <th style="text-align:center;">QUAN TÂM THẤP</th>
    <th style="text-align:center;">QUAN TÂM CAO</th>
  </tr>

  <tr>
    <th style="text-align:center; vertical-align:middle;">
      ẢNH HƯỞNG CAO
    </th>

    <td style="vertical-align:top;">
      <strong>KEEP SATISFIED</strong>
      <br><br>
      • Finance / Accounting
      <br>
      • Security / Compliance
    </td>

    <td style="vertical-align:top;">
      <strong>MANAGE CLOSELY</strong>
      <br><br>
      • Ban giám đốc
      <br>
      • Operations Manager
    </td>
  </tr>

  <tr>
    <th style="text-align:center; vertical-align:middle;">
      ẢNH HƯỞNG THẤP
    </th>

    <td style="vertical-align:top;">
      <strong>MONITOR</strong>
      <br><br>
      • Payment Provider
      <br>
      • Notification Provider
    </td>

    <td style="vertical-align:top;">
      <strong>KEEP INFORMED</strong>
      <br><br>
      • Customer
      <br>
      • Driver
      <br>
      • Operations Staff
      <br>
      • Customer Support
      <br>
      • IT / Development Team
    </td>
  </tr>
</table>

Bước 3: bussines goal
bg01: hỗ trợ thanh toán
- thanh toán tiền mặt, chuyển khoản
bg02: cho phép tìm tài xế tự động
# BƯỚC 3 – BUSINESS GOALS

| ID | Business Goal | Mô tả |
|---|---|---|
| **BG01** | **Hỗ trợ thanh toán** | Hỗ trợ khách hàng thanh toán bằng tiền mặt và phương thức thanh toán điện tử/chuyển khoản. |
| **BG02** | **Tự động tìm tài xế** | Cho phép hệ thống tự động tìm tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành. |
| **BG03** | **Tự động điều phối tài xế** | Tự động gửi yêu cầu đến tài xế phù hợp. Nếu tài xế từ chối hoặc không phản hồi, hệ thống tiếp tục tìm tài xế khác. |
| **BG04** | **Quản lý vòng đời chuyến đi** | Quản lý toàn bộ quá trình từ khi khách hàng đặt xe, tìm tài xế, nhận chuyến, đón khách, thực hiện chuyến đến khi hoàn thành hoặc hủy. |
| **BG05** | **Theo dõi chuyến đi** | Cho phép khách hàng và nhân viên vận hành theo dõi trạng thái chuyến và thông tin tài xế. |
| **BG06** | **Quản lý khách hàng, tài xế và phương tiện** | Quản lý tập trung thông tin khách hàng, hồ sơ tài xế, phương tiện, trạng thái hoạt động và vị trí tài xế. |
| **BG07** | **Tính cước và quản lý doanh thu** | Tự động xác định cước chuyến đi và cung cấp dữ liệu phục vụ quản lý doanh thu, giao dịch và đối soát. |
| **BG08** | **Hỗ trợ thông báo** | Gửi thông báo cho khách hàng và tài xế về các sự kiện quan trọng trong quá trình đặt và thực hiện chuyến. |
| **BG09** | **Hỗ trợ vận hành và báo cáo** | Cung cấp giao diện quản trị, giám sát chuyến đi và các báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế. |
| **BG10** | **Đảm bảo bảo mật và phân quyền** | Xác thực người dùng, kiểm soát quyền truy cập và bảo vệ dữ liệu cá nhân, phương tiện, vị trí và giao dịch. |
| **BG11** | **Đảm bảo khả năng mở rộng và ổn định** | Hệ thống có khả năng phục vụ số lượng lớn khách hàng, tài xế và duy trì hoạt động khi tải tăng cao. |
| **BG12** | **Hỗ trợ mở rộng trong tương lai** | Cho phép bổ sung dịch vụ mới, phương thức thanh toán, nhà cung cấp thông báo và thay đổi thành phần kỹ thuật mà không phải xây dựng lại toàn bộ hệ thống. |

