Bước 1: phân tích ngữ cảnh bussines context, bussines problem
- bussines context
  Công ty ABC là doanh nghiệp cung cấp dịch vụ đặt xe trực tuyến (CAB).
  Hiện tại, khách hàng có thể đặt xe thông qua:
    - Tổng đài.
    - Ứng dụng đơn giản hiện có.
  - Tuy nhiên, hệ thống hiện tại chưa đáp ứng tốt khi quy mô khách hàng và tài xế tăng lên. Việc phân công tài xế còn phụ thuộc nhiều vào thao tác thủ công, khách hàng khó theo dõi trạng thái chuyến đi và thông tin thanh toán chưa được quản lý tập trung.
  - Doanh nghiệp mong muốn xây dựng một nền tảng CAB mới có khả năng phục vụ số lượng lớn khách hàng     và tài xế, đồng thời có kiến trúc linh hoạt để có thể mở rộng thêm các tính năng và dịch vụ trongtương lai.

- bussines problem
ABC cần thay thế quy trình đặt xe và điều phối thủ công bằng một nền tảng CAB tập trung, có khả năng:
- Tự động hóa việc tìm kiếm và điều phối tài xế.
- Quản lý toàn bộ vòng đời của chuyến đi.
- Hỗ trợ tính cước và thanh toán.
- Cung cấp hệ thống thông báo cho khách hàng và tài xế.
- Hỗ trợ nhân viên vận hành theo dõi và xử lý các chuyến đi.
- Quản lý tập trung thông tin khách hàng, tài xế, phương tiện và giao dịch.
- Cung cấp báo cáo phục vụ quản lý và ra quyết định.
- Đảm bảo hệ thống hoạt động ổn định khi số lượng người dùng tăng cao.
- Có khả năng mở rộng thêm dịch vụ và tích hợp mới trong tương lai.

- khách hàng muốn giải quyết vấn đề gì
  Khách hàng muốn giải quyết các vấn đề chính sau:
1. **Giảm việc điều phối tài xế thủ công**
   - Tự động tìm tài xế phù hợp và gần khách hàng.
   - Tự động chuyển yêu cầu sang tài xế khác nếu tài xế được đề xuất từ chối hoặc không phản hồi.
2. **Cải thiện trải nghiệm đặt xe**
   - Khách hàng có thể đặt xe trực tuyến.
   - Khách hàng biết được trạng thái yêu cầu đặt xe.
   - Khách hàng có thể theo dõi tài xế và chuyến đi.
3. **Quản lý thanh toán tập trung**
   - Hỗ trợ thanh toán tiền mặt và thanh toán điện tử.
   - Tích hợp với nhà cung cấp thanh toán bên ngoài.
   - Không lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán.
4. **Cải thiện việc quản lý và vận hành**
   - Nhân viên có thể theo dõi các chuyến đang diễn ra.
   - Quản lý khách hàng, tài xế và phương tiện.
   - Xử lý các trường hợp chuyến bị lỗi hoặc phát sinh vấn đề.
5. **Cải thiện khả năng quản lý dữ liệu**
   - Quản lý tập trung lịch sử chuyến đi và giao dịch.
   - Cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế.
6. **Đảm bảo khả năng mở rộng**
   - Hệ thống có thể phục vụ số lượng lớn khách hàng và tài xế.
   - Có thể bổ sung dịch vụ, phương thức thanh toán và nhà cung cấp thông báo mới trong tương lai.
  
- ai sẽ sử dụng he thong
Hệ thống CAB có 3 nhóm người dùng chính:

| Nhóm người dùng | Đối tượng | Mục đích sử dụng |
|---|---|---|
| **Khách hàng** | Người có nhu cầu đặt xe | Đăng ký, đăng nhập, đặt xe, theo dõi chuyến, thanh toán, xem lịch sử và đánh giá tài xế. |
| **Tài xế** | Tài xế của ABC | Quản lý hồ sơ, phương tiện, trạng thái hoạt động, nhận chuyến và cập nhật trạng thái chuyến. |
| **Nhân viên vận hành** | Operations Staff / Operations Manager | Quản lý khách hàng, tài xế, phương tiện, theo dõi chuyến, xử lý sự cố và giám sát hoạt động. |

### Các bên liên quan hỗ trợ hệ thống

Ngoài 3 nhóm người dùng chính, hệ thống còn tương tác với:

- **Ban giám đốc:** Theo dõi báo cáo, doanh thu và hiệu quả hoạt động.
- **Finance / Accounting:** Theo dõi giao dịch, doanh thu và đối soát thanh toán.
- **System Administrator:** Quản trị tài khoản, hệ thống và phân quyền.
- **Payment Provider:** Xử lý thanh toán điện tử.
- **Notification Provider:** Cung cấp các kênh gửi thông báo như SMS, Email hoặc Push Notification.
- **IT / Development Team:** Xây dựng, triển khai và bảo trì hệ thống.
  

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
```
                    MA TRẬN MỨC ĐỘ ẢNH HƯỞNG STAKEHOLDER

                         MỨC ĐỘ QUAN TÂM
                   THẤP                 CAO
                     │                    │
                     │                    │
          ┌──────────┼────────────────────┐
          │          │                    │
          │   KEEP   │   MANAGE CLOSELY   │
          │ SATISFIED│                    │
          │          │ • Ban giám đốc     │
          │ • Finance│ • Operations       │
          │ • Security│   Manager         │
          │ • Compliance│                 │
  ẢNH     │          │                    │
  HƯỞNG ──┼──────────┼────────────────────┤
  CAO     │          │                    │
          │  MONITOR │   KEEP INFORMED    │
          │          │                    │
          │ • Payment│ • Customer         │
          │   Provider│ • Driver          │
          │ • Notification│ • Operations  │
          │   Provider│   Staff           │
          │          │ • Customer Support  │
          │          │ • IT/Development    │
          │          │   Team              │
          └──────────┼────────────────────┘
                     │
                     │
                    THẤP
```


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

Bước 4: scope, quản lý khách hàng, quản lý tài xế,..
những cái không thuộc scope: dùng al dự báo yêu cầu, tìm đường đi ngắn nhất, phải deal với khách hàng,....

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

Bước 7: Functional requirment 
| Mã | Tên Functional Requirement | Diễn giải |
|---|---|---|
| **FR01** | Đăng ký tài khoản | Hệ thống cho phép khách hàng đăng ký tài khoản bằng cách cung cấp các thông tin cần thiết. |
| **FR02** | Đăng nhập | Hệ thống cho phép khách hàng và tài xế đăng nhập bằng thông tin xác thực hợp lệ. |
| **FR03** | Cập nhật thông tin cá nhân | Hệ thống cho phép khách hàng cập nhật thông tin cá nhân của mình. |
| **FR04** | Nhập thông tin chuyến đi | Hệ thống cho phép khách hàng nhập điểm đón, điểm đến và lựa chọn loại xe/dịch vụ. |
| **FR05** | Tạo yêu cầu đặt chuyến | Hệ thống cho phép khách hàng gửi yêu cầu đặt chuyến sau khi thông tin chuyến hợp lệ. |
| **FR06** | Tìm tài xế phù hợp | Hệ thống tự động xác định các tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành. |
| **FR07** | Gửi yêu cầu đến tài xế | Hệ thống gửi thông tin chuyến đến tài xế phù hợp để tài xế chấp nhận hoặc từ chối chuyến. |
| **FR08** | Tìm tài xế tiếp theo | Khi tài xế từ chối hoặc không phản hồi, hệ thống tiếp tục tìm và gửi yêu cầu đến tài xế khác. |
| **FR09** | Thông báo không tìm được tài xế | Khi không tìm được tài xế phù hợp, hệ thống thông báo rõ ràng cho khách hàng. |
| **FR10** | Cập nhật vị trí tài xế | Hệ thống tiếp nhận và lưu thông tin vị trí hiện tại của tài xế. |
| **FR11** | Theo dõi vị trí tài xế | Hệ thống cho phép khách hàng theo dõi vị trí tài xế và thời gian dự kiến tài xế đến. |
| **FR12** | Cập nhật trạng thái chuyến | Hệ thống cho phép tài xế cập nhật trạng thái chuyến đi. |
| **FR13** | Tính cước chuyến đi | Hệ thống xác định số tiền khách hàng phải trả dựa trên loại dịch vụ và thông tin chuyến đi. |
| **FR14** | Thanh toán tiền mặt | Hệ thống cho phép ghi nhận và cập nhật trạng thái thanh toán bằng tiền mặt. |
| **FR15** | Thanh toán điện tử | Hệ thống tích hợp với nhà cung cấp thanh toán bên ngoài để xử lý giao dịch điện tử. |
| **FR16** | Xử lý thanh toán thất bại | Hệ thống thông báo cho khách hàng khi thanh toán thất bại và cho phép xử lý lại theo chính sách doanh nghiệp. |
| **FR17** | Gửi thông báo cho khách hàng | Hệ thống gửi thông báo về các sự kiện quan trọng của chuyến đi và thanh toán. |
| **FR18** | Gửi thông báo cho tài xế | Hệ thống gửi thông báo cho tài xế khi có chuyến mới hoặc thay đổi liên quan đến chuyến. |
| **FR19** | Xem lịch sử chuyến đi | Hệ thống cho phép khách hàng xem danh sách và thông tin các chuyến đã thực hiện. |
| **FR20** | Đánh giá tài xế | Hệ thống cho phép khách hàng đánh giá tài xế sau khi chuyến đi hoàn thành. |
| **FR21** | Quản lý hồ sơ tài xế | Hệ thống cho phép tạo, xem và cập nhật thông tin hồ sơ tài xế. |
| **FR22** | Quản lý phương tiện | Hệ thống cho phép quản lý thông tin phương tiện của tài xế. |
| **FR23** | Cập nhật trạng thái tài xế | Hệ thống cho phép tài xế chuyển trạng thái sẵn sàng hoặc không sẵn sàng nhận chuyến. |
| **FR24** | Quản lý khách hàng | Nhân viên vận hành có thể tra cứu và quản lý thông tin khách hàng theo quyền được cấp. |
| **FR25** | Quản lý tài xế | Nhân viên vận hành có thể tạo, cập nhật, xem và quản lý trạng thái tài xế. |
| **FR26** | Quản lý phương tiện | Nhân viên vận hành có thể xem và cập nhật thông tin phương tiện. |
| **FR27** | Theo dõi chuyến đang diễn ra | Nhân viên vận hành có thể xem danh sách và trạng thái các chuyến đang thực hiện. |
| **FR28** | Xử lý chuyến bất thường | Nhân viên vận hành có thể kiểm tra và xử lý các trường hợp chuyến bị lỗi hoặc phát sinh vấn đề. |
| **FR29** | Tra cứu giao dịch | Người có quyền có thể tra cứu lịch sử giao dịch và trạng thái thanh toán. |
| **FR30** | Phân quyền người dùng | Hệ thống phân quyền theo vai trò và kiểm tra quyền trước khi thực hiện các thao tác quản trị. |
| **FR31** | Xem báo cáo hoạt động | Hệ thống cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế. |
| **FR32** | Ghi nhận lịch sử thao tác | Hệ thống lưu vết các thao tác quan trọng để phục vụ kiểm tra và truy vết khi xảy ra sự cố. |

Bước 8: Bussines Rules và Exceptions
8.1. Business Rules

| Mã | Business Rule | Diễn giải |
|---|---|---|
| **BRL01** | Khách hàng phải đăng nhập | Khách hàng phải đăng nhập trước khi thực hiện các chức năng yêu cầu tài khoản như đặt xe, xem lịch sử chuyến và đánh giá tài xế. |
| **BRL02** | Tài xế phải ở trạng thái sẵn sàng | Chỉ những tài xế đang ở trạng thái sẵn sàng nhận chuyến mới được hệ thống đưa vào danh sách tìm kiếm tài xế. |
| **BRL03** | Tài xế phải phù hợp với chuyến | Tài xế được đề xuất phải đáp ứng các tiêu chí về vị trí, trạng thái hoạt động, loại phương tiện và các điều kiện vận hành khác. |
| **BRL04** | Tài xế có quyền chấp nhận hoặc từ chối chuyến | Khi nhận được yêu cầu chuyến, tài xế có thể chấp nhận hoặc từ chối yêu cầu. |
| **BRL05** | Tự động tìm tài xế tiếp theo | Nếu tài xế từ chối hoặc không phản hồi trong thời gian quy định, hệ thống phải tiếp tục tìm tài xế phù hợp khác. |
| **BRL06** | Một chuyến chỉ có một tài xế | Một yêu cầu đặt chuyến chỉ được gán cho một tài xế tại một thời điểm. |
| **BRL07** | Không tìm được tài xế | Nếu không còn tài xế phù hợp, hệ thống phải cập nhật trạng thái yêu cầu và thông báo cho khách hàng. |
| **BRL08** | Tài xế phải cập nhật trạng thái chuyến | Tài xế phải cập nhật trạng thái theo trình tự: đã đến điểm đón → đã đón khách → đang di chuyển → hoàn thành chuyến. |
| **BRL09** | Chỉ được hoàn thành chuyến hợp lệ | Chuyến chỉ được chuyển sang trạng thái hoàn thành khi tài xế đã thực hiện chuyến theo quy trình nghiệp vụ. |
| **BRL10** | Tính cước sau khi chuyến hoàn thành | Hệ thống xác định số tiền khách hàng phải trả dựa trên thông tin chuyến và chính sách tính cước của doanh nghiệp. |
| **BRL11** | Hỗ trợ nhiều phương thức thanh toán | Khách hàng có thể thanh toán bằng tiền mặt hoặc phương thức thanh toán điện tử được hệ thống hỗ trợ. |
| **BRL12** | Không lưu thông tin thanh toán nhạy cảm | Hệ thống CAB không lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán; việc xử lý được thực hiện thông qua Payment Provider. |
| **BRL13** | Xử lý thanh toán thất bại | Khi thanh toán điện tử thất bại, hệ thống phải ghi nhận trạng thái thất bại và thông báo cho khách hàng. |
| **BRL14** | Chỉ đánh giá sau khi hoàn thành chuyến | Khách hàng chỉ được đánh giá tài xế sau khi chuyến đi đã hoàn thành. |
| **BRL15** | Phân quyền quản trị | Nhân viên chỉ được thực hiện các chức năng phù hợp với quyền được cấp. |
| **BRL16** | Ghi nhận thao tác quan trọng | Các thao tác quản trị và thao tác quan trọng phải được ghi nhận để phục vụ kiểm tra và truy vết. |
| **BRL17** | Gửi thông báo theo sự kiện | Hệ thống phải gửi thông báo khi xảy ra các sự kiện quan trọng của chuyến đi và thanh toán. |
| **BRL18** | Không cho phép tài xế nhận nhiều chuyến xung đột | Tài xế đang thực hiện một chuyến không được đồng thời nhận một chuyến khác nếu hai chuyến có thời gian thực hiện bị trùng. |
| **BRL19** | Vị trí tài xế phục vụ điều phối | Thông tin vị trí tài xế được sử dụng để hỗ trợ tìm tài xế phù hợp và ước tính thời gian đến. |
| **BRL20** | Dữ liệu người dùng phải được bảo vệ | Thông tin cá nhân, thông tin phương tiện, dữ liệu vị trí và dữ liệu giao dịch phải được bảo vệ theo chính sách bảo mật của doanh nghiệp. |

---

8.2. Exceptions
| Mã | Exception | Điều kiện xảy ra | Cách xử lý |
|---|---|---|---|
| **EX01** | Không tìm được tài xế | Không có tài xế phù hợp hoặc tất cả tài xế đều từ chối/không phản hồi. | Hệ thống thông báo cho khách hàng rằng chưa tìm được tài xế và cập nhật trạng thái yêu cầu. |
| **EX02** | Tài xế từ chối chuyến | Tài xế nhận được yêu cầu nhưng chọn từ chối. | Hệ thống ghi nhận việc từ chối và tiếp tục tìm tài xế khác. |
| **EX03** | Tài xế không phản hồi | Tài xế không phản hồi trong thời gian quy định. | Hệ thống coi yêu cầu là hết thời gian phản hồi và chuyển sang tài xế khác. |
| **EX04** | Mất kết nối mạng của khách hàng | Khách hàng mất kết nối trong quá trình đặt hoặc theo dõi chuyến. | Hệ thống vẫn duy trì trạng thái chuyến ở phía server; ứng dụng cập nhật lại dữ liệu khi kết nối được khôi phục. |
| **EX05** | Mất kết nối mạng của tài xế | Tài xế mất kết nối trong quá trình thực hiện chuyến. | Hệ thống ghi nhận thời điểm mất kết nối và hiển thị trạng thái phù hợp cho nhân viên vận hành; xử lý tiếp theo theo chính sách doanh nghiệp. |
| **EX06** | Thanh toán điện tử thất bại | Payment Provider trả về kết quả giao dịch thất bại. | Hệ thống thông báo cho khách hàng và cho phép thực hiện lại thanh toán theo chính sách. |
| **EX07** | Payment Provider không phản hồi | Hệ thống không nhận được kết quả từ nhà cung cấp thanh toán. | Giao dịch được đưa vào trạng thái chờ xử lý/đối soát và không làm dừng chức năng đặt xe. |
| **EX08** | Notification Provider lỗi | Nhà cung cấp SMS, Email hoặc Push Notification không hoạt động. | Hệ thống ghi nhận lỗi, có thể thử lại hoặc chuyển sang kênh thông báo khác nếu được cấu hình. |
| **EX09** | Tài xế không cập nhật trạng thái | Tài xế không cập nhật trạng thái chuyến đúng thời điểm. | Hệ thống ghi nhận trạng thái hiện tại và cảnh báo/hiển thị cho nhân viên vận hành để xử lý. |
| **EX10** | Hủy chuyến | Khách hàng hoặc tài xế yêu cầu hủy chuyến theo điều kiện được phép. | Hệ thống kiểm tra chính sách hủy, cập nhật trạng thái chuyến và xử lý phí hủy nếu có. |
| **EX11** | Không thể xác định vị trí tài xế | GPS hoặc dịch vụ vị trí không cung cấp được vị trí hợp lệ. | Hệ thống thông báo trạng thái vị trí không khả dụng và cho phép vận hành tiếp tục xử lý theo chính sách. |
| **EX12** | Lỗi hệ thống | Một thành phần như thanh toán, thông báo hoặc dịch vụ tìm tài xế gặp lỗi. | Hệ thống cô lập lỗi, ghi log và đảm bảo các chức năng khác tiếp tục hoạt động nếu có thể. |
| **EX13** | Tài xế mất trạng thái sẵn sàng | Tài xế chuyển sang không sẵn sàng trong khi đang được tìm kiếm. | Hệ thống loại tài xế khỏi danh sách ứng viên và tìm tài xế khác. |
| **EX14** | Chuyến bị lỗi hoặc bất thường | Chuyến có trạng thái không hợp lệ hoặc phát sinh vấn đề trong quá trình thực hiện. | Hệ thống đánh dấu chuyến cần xử lý và cho phép nhân viên vận hành kiểm tra, can thiệp. |

---
8.3. Business Rules cần xác nhận với khách hàng
Một số quy tắc trong đề bài chưa được xác định cụ thể. BA cần làm rõ trước khi phát triển:
| Mã | Nội dung cần xác nhận | Câu hỏi cần làm rõ |
|---|---|---|
| **TBC01** | Thời gian tài xế phản hồi | Tài xế có bao nhiêu giây/phút để chấp nhận hoặc từ chối chuyến? |
| **TBC02** | Tiêu chí ưu tiên tài xế | Ưu tiên theo khoảng cách, thời gian đến, loại xe, rating hay tiêu chí nào khác? |
| **TBC03** | Phạm vi tìm tài xế | Hệ thống tìm tài xế trong bán kính bao nhiêu km? Có mở rộng bán kính nếu không tìm được không? |
| **TBC04** | Cách tính cước | Cước được tính theo quãng đường, thời gian, loại xe, giá cố định hay kết hợp nhiều yếu tố? |
| **TBC05** | Chính sách hủy chuyến | Ai được phép hủy? Có tính phí hủy không? Phí được tính như thế nào? |
| **TBC06** | Thanh toán thất bại | Khách hàng được phép thanh toán lại bao nhiêu lần và trong thời gian bao lâu? |
| **TBC07** | Mất kết nối mạng | Khi khách hàng hoặc tài xế mất mạng, hệ thống xử lý trạng thái chuyến như thế nào? |
| **TBC08** | Lưu trữ dữ liệu | Dữ liệu khách hàng, chuyến đi, vị trí và giao dịch được lưu trong bao lâu? |
| **TBC09** | Quy tắc đánh giá | Khách hàng được đánh giá trong bao lâu sau khi hoàn thành chuyến? Có được sửa/xóa đánh giá không? |
| **TBC10** | Quy tắc xử lý tài xế | Tài xế từ chối nhiều chuyến liên tiếp có bị giới hạn hoặc thay đổi trạng thái không? |

Bước 9: Mô hình hóa dữ liệu, xác định các thực thể, erd 

Bước 10: Xác định non functional requirment 
Bước 11: vẽ usecase, UC 
Bước 12: usecase đặc tả 


