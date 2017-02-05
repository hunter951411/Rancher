
##1. Tổng quan về Rancher
Rancher là một nền tảng phần mềm mã nguồn mở mà thực hiện một cơ sở hạ tầng được xây dựng cho mục đích chạy container trên production. Các Docker container, như là một khối lượng công việc ứng dụng càng ngày phổ biến, tạo ra các yêu cầu mới trong các dịch vụ cơ sở hạ tầng như hệ thống mạng, lưu trữ, cân bằng tải, an ninh, phát hiện dịch vụ và quản lý tài nguyên.

##2. Tính toán tài nguyên
Rancher trong tính toán tài nguyên thô từ bất kì public hay private cloud dưới dạng các máy chủ Linux. Mỗi máy chủ Linux có thể là một máy ảo hay một máy vật lý. Rancher không yêu cầu nhiều hơn CPU, bộ nhớ, không gian ổ đĩa lưu trữ cục bộ hay kết nối mạng từ các máy chủ. Từ góc nhìn của Rancher, một máy ảo từ một nhà cung cấp dịch vụ cloud và một máy chủ bare metal server được coi là như nhau.

##3. Các tính năng chính
Các tính năng chính của Rancher bao gồm
<ul>
<li>1. Mạng Cross-host. Rancher tạo một phần mềm định nghĩa mạng cho mỗi môi trường, cho phép kết nối an toàn giữa các container thông qua các host và các cloud</li>
<li>2. Cân bằng tải Container. Rancher cung cấp đầy đủ, dịch vụ cân bằng tải elastic để phân tán giao thông giữa các container hay các dịch vụ. Dịch vụ cân bằng tải làm việc thông quan nhiều cloud</li>
<li>3. Dịch vụ lưu trữ khăng khít. Rancher hỗ trợ dịch vụ orchestrating Persistent Storage cho Docker, làm cho nó có thể cho phép các nhà phát triển triển khai lưu trữ đáng tin cậy kết hợp với các ứng dụng trong container. tính năng mới được xây dựng trên Docker 1.9 khả năng kết nối volume, làm cho nó dễ dàng hơn cho các nhà phát triển để chạy các ứng dụng đòi hỏi phải có cơ sở dữ liệu trạng thái và lưu trữ liên tục.</li>
<li>4. Phát hiện dịch vụ: Rancher thực hiện một chức năng phát hiện dịch vụ dựa trên DNS được phân phối với việc kiểm tra trạng thái tích hợp cho phép container để tự động đăng ký như các dịch vụ cũng như các dịch vụ để tự động phát hiện nhau qua mạng/</li>
<li>5. Nâng cấp dịch vụ: Rancher làm cho nó dễ dàng cho người dùng nâng cấp các dịch vụ container hiện có, bằng cách nhân bản dịch vụ và chuyển hướng các yêu cầu dịch vụ. Điều này làm cho nó có thể được đảm bảo đối với các dịch vụ cũ còn phục thuộc trước khi chuyển sang các dịch vụ mới được nâng cấp.</li>
<li>6. Quản lý tài nguyên: Rancher hỗ trợ Docker machine: một công cụ mạnh mẽ để trích lập dự phòng máy chủ trực tiếp từ các nhà cung cấp cloud. Rancher sau đó giám sát tài nguyên máy chủ và quản lý triển khai container.</li>
<li>7. Multi-tenancy và quản lý user: Rancher được thiết kế cho nhiều người dùng và cho phép tổ chức để cộng tác trong suốt vòng đời ứng dụng. Bằng cách kết nối với các dịch vụ đã tồn tại, Rancher cho phép những người dùng tạo phát triển riêng biệt, kiểm tra và môi trường sản phẩm và mời các đồng nghiệp của họ để quản lý tài nguyên và ứng dụng.</li>
<li>8. Nhiều phương tiện Orchestration. Rancher hỗ trợ khả năng cho phép người dùng được chọn mặc định Cattle, Kubernetes hay Docker Swarm như một cố máy quản lý dàn nhạc cho container của họ trong khi tạo ra môi trường. Điều này sẽ cho phép người dùng lựa chọn </li>
</ul>
