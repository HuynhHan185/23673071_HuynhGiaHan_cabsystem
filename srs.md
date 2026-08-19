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



Bước 3: bussines goals
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

Bước 4: bóp scope, quản lý khách hàng, quản lý tài xế,..
những cái không thuộc scope: dùng al dự báo yêu cầu, tìm đường đi ngắn nhất, phải deal với khách hàng

Bước 5: Gặp khách hàng, chuyển đổi yêu cầu -> thành bussines requirment
| Mã | Tên Business Requirement | Diễn giải |
|---|---|---|
| **BR01** | **Cho phép đặt chuyến** | Hệ thống cho phép khách hàng nhập điểm đón, điểm đến, lựa chọn loại xe/dịch vụ và gửi yêu cầu đặt chuyến. |
| **BR02** | **Tìm tài xế tự động** | Hệ thống tự động tìm tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành được doanh nghiệp quy định. |
| **BR03** | **Theo dõi chuyến đi** | Khách hàng có khả năng theo dõi chuyến đi trong suốt quá trình di chuyển, bao gồm trạng thái chuyến và thông tin liên quan đến tài xế. |
| **BR04** | **Hỗ trợ thanh toán** | Hệ thống hỗ trợ khách hàng thanh toán bằng tiền mặt hoặc phương thức thanh toán điện tử thông qua nhà cung cấp thanh toán bên ngoài. |
| **BR05** | **Tính cước chuyến đi** | Hệ thống xác định số tiền khách hàng phải thanh toán dựa trên loại dịch vụ và thông tin của chuyến đi theo chính sách tính cước của doanh nghiệp. |
| **BR06** | **Quản lý tài khoản khách hàng** | Hệ thống cho phép khách hàng đăng ký, đăng nhập và cập nhật thông tin cá nhân. |
| **BR07** | **Quản lý tài xế** | Hệ thống cho phép quản lý hồ sơ tài xế, thông tin phương tiện và trạng thái hoạt động của tài xế. |
| **BR08** | **Nhận và xử lý chuyến** | Hệ thống cho phép tài xế nhận hoặc từ chối chuyến; nếu tài xế không nhận hoặc không phản hồi, hệ thống tiếp tục tìm tài xế khác. |
| **BR09** | **Cập nhật trạng thái chuyến** | Hệ thống cho phép tài xế cập nhật các trạng thái như đã đến điểm đón, đã đón khách, đang di chuyển và hoàn thành chuyến. |
| **BR10** | **Quản lý vị trí tài xế** | Hệ thống lưu và cập nhật thông tin vị trí của tài xế để hỗ trợ tìm tài xế phù hợp và dự kiến thời gian tài xế đến. |
| **BR11** | **Thông báo chuyến đi** | Hệ thống gửi thông báo cho khách hàng và tài xế khi xảy ra các sự kiện quan trọng trong chuyến đi. |
| **BR12** | **Quản lý lịch sử chuyến đi** | Hệ thống cho phép khách hàng xem lịch sử các chuyến đã thực hiện và thông tin liên quan. |
| **BR13** | **Đánh giá tài xế** | Hệ thống cho phép khách hàng đánh giá tài xế sau khi chuyến đi hoàn thành. |
| **BR14** | **Quản lý vận hành** | Hệ thống cung cấp giao diện cho nhân viên vận hành quản lý khách hàng, tài xế, phương tiện và theo dõi các chuyến đang diễn ra. |
| **BR15** | **Xử lý chuyến bất thường** | Hệ thống hỗ trợ nhân viên vận hành kiểm tra và xử lý các trường hợp chuyến bị lỗi hoặc phát sinh vấn đề. |
| **BR16** | **Quản lý giao dịch** | Hệ thống cho phép tra cứu thông tin giao dịch và hỗ trợ đối soát thanh toán. |
| **BR17** | **Phân quyền người dùng** | Hệ thống kiểm soát quyền truy cập theo vai trò, đảm bảo các thao tác nhạy cảm chỉ được thực hiện bởi người có quyền. |
| **BR18** | **Báo cáo hoạt động** | Hệ thống cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế. |
| **BR19** | **Bảo vệ dữ liệu** | Hệ thống bảo vệ thông tin cá nhân, thông tin phương tiện, dữ liệu vị trí và dữ liệu giao dịch. |
| **BR20** | **Ghi nhận lịch sử thao tác** | Hệ thống lưu vết các thao tác quan trọng để phục vụ kiểm tra, truy vết và xử lý sự cố. |
| **BR21** | **Xử lý thanh toán thất bại** | Khi thanh toán điện tử thất bại, hệ thống thông báo cho khách hàng và cho phép xử lý lại theo chính sách doanh nghiệp. |
| **BR22** | **Xử lý không tìm được tài xế** | Nếu không tìm được tài xế phù hợp, hệ thống thông báo rõ ràng cho khách hàng và cập nhật trạng thái yêu cầu. |
| **BR23** | **Khả năng mở rộng hệ thống** | Hệ thống có khả năng mở rộng khi số lượng khách hàng, tài xế và chuyến đi tăng cao. |
| **BR24** | **Hỗ trợ mở rộng dịch vụ** | Hệ thống cho phép bổ sung loại dịch vụ, phương thức thanh toán và nhà cung cấp mới mà hạn chế thay đổi hệ thống hiện tại. |

Bước 6: Bussines process
dùng công cụ mermaid 


