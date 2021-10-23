# Microservice Sample

[.NET Tutorial - Your First Microservice](https://dotnet.microsoft.com/learn/aspnet/microservice-tutorial/intro)

[.NET Tutorial - Deploy a microservice to Azure](https://dotnet.microsoft.com/learn/aspnet/deploy-microservice-tutorial/intro)

You might also be interested in...

[Microsoft Learn for Microservices](https://docs.microsoft.com/en-us/learn/paths/create-microservices-with-dotnet/?WT.mc_id=dotnet-35129-website)

[Microservices architecture](https://dotnet.microsoft.com/learn/aspnet/microservices-architecture)

[.NET Docker docs](https://docs.microsoft.com/en-us/dotnet/core/docker/introduction?WT.mc_id=dotnet-35129-website)

[.NET Microservices Sample Reference Application](https://github.com/dotnet-architecture/eShopOnContainers)

# Microservices
## Ưu điểm của Microservices

- Microservices là modules triển khai độc lập, khép kín.
- Chi phí mở rộng tương đối ít hơn so với kiến ​​trúc nguyên khối.
- Microservices là các dịch vụ có thể quản lý độc lập. Nó có thể kích hoạt ngày càng nhiều dịch vụ khi có nhu cầu. Nó giảm thiểu tác động đến dịch vụ hiện có.
- Có thể thay đổi hoặc nâng cấp từng dịch vụ riêng lẻ chứ không phải nâng cấp trong toàn bộ ứng dụng.
- Microservices cho phép chúng tôi phát triển một ứng dụng hữu cơ (một ứng dụng sau này sẽ nâng cấp bằng cách thêm nhiều chức năng hoặc mô-đun hơn).
- Nó cho phép công nghệ phát trực tuyến sự kiện cho phép tích hợp dễ dàng so với truyền thông xen kẽ nặng nề.
- Microservices tuân theo nguyên tắc trách nhiệm duy nhất.
- Dịch vụ yêu cầu có thể được triển khai trên nhiều máy chủ để nâng cao hiệu suất.
- Ít phụ thuộc và dễ kiểm tra.
- Mở rộng quy mô động.
- Chu kỳ phát hành nhanh hơn.

## Nhược điểm của Microservices

- Microservices có tất cả các phức tạp liên quan của hệ thống phân tán.
- Khả năng bị lỗi cao hơn trong quá trình giao tiếp giữa các dịch vụ khác nhau.
- Khó quản lý một số lượng lớn các dịch vụ.
- Nhà phát triển cần giải quyết vấn đề, chẳng hạn như độ trễ mạng và cân bằng tải.
- Thử nghiệm phức tạp trên môi trường phân tán.

## Sự khác biệt giữa Kiến trúc Microservices (MSA) và Kiến trúc Hướng dịch vụ (SOA)

| Kiến trúc dựa trên dịch vụ vi mô (MSA) | Kiến trúc hướng dịch vụ (SOA) |
| ----------- | ----------- |
| Microservices sử dụng các giao thức nhẹ như REST và HTTP , v.v. | SOA hỗ trợ các giao thức đa tin nhắn |
| Nó tập trung vào việc phân tách . | 	Nó tập trung vào khả năng tái sử dụng dịch vụ ứng dụng . |
| Nó sử dụng một hệ thống nhắn tin đơn giản để liên lạc. | Nó sử dụng Bus dịch vụ doanh nghiệp (ESB) để giao tiếp. |
| Microservices tuân theo cách tiếp cận kiến ​​trúc ” chia sẻ càng ít càng tốt “. | SOA tuân theo cách tiếp cận ” chia sẻ kiến ​​trúc càng nhiều càng tốt “. |
| Microservices có khả năng chịu lỗi tốt hơn nhiều so với SOA. | SOA không tốt hơn về khả năng chịu lỗi so với MSA. |
| Mỗi microservice có một cơ sở dữ liệu độc lập . | Dịch vụ SOA chia sẻ toàn bộ dữ liệu lưu trữ. |
| MSA đã sử dụng cơ sở dữ liệu quan hệ hiện đại . | SOA đã sử dụng cơ sở dữ liệu quan hệ truyền thống . |
| MSA cố gắng giảm thiểu việc chia sẻ thông qua ngữ cảnh bị ràng buộc (sự kết hợp của các thành phần và dữ liệu của nó như một đơn vị duy nhất với sự phụ thuộc tối thiểu). | SOA tăng cường chia sẻ thành phần. |
| Nó phù hợp hơn với hệ thống dựa trên web nhỏ hơn và được chia nhỏ hơn . | Nó tốt hơn cho một môi trường ứng dụng kinh doanh lớn và phức tạp . |
