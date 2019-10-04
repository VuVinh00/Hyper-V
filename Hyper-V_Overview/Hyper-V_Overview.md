## Role and technology description

Hyper-V role cho phép ta tạo và quản lí môi trường máy tính ảo hóa bằng cách sử dụng công nghệ ảo hóa đc xây dựng sẵn trong Windows Server. Cài đặt Hyper-V để cài các thành phần cần thiết và các công cụ quản lý. Các thành phần cần thiết bao gồm : Windows hypervisor, Hyper-V Virtual Machine Management Service, the virtualization WMI provider và các thành phần ảo hóa như virtual machine bus ( VMbus ), virtualization service provider ( VSP ) và virtual infrastructure driver ( VID )

Công nghệ Hyper-V ảo hóa phần cứng và cung cấp môi trường mà ta có thể chạy nhiều hệ điều hành khác nhau trên 1 máy vật lý

## Features

- **Automatic VM Activation**: Cho phép máy ảo được active mà không cần phải quản lý khóa sản phẩm ( **product keys** ) cho mỗi máy ảo.

- **Back up and restore**: Tìm hiểu về các lựa chọn back up và quy trình restore một máy ảo

- **Checkpoints and snapshots**: Virtual machine checkpoints ( hay trước đây gọi là virtual machine snapshots ) dùng để capture lại trạng thái, dữ liệu và cấu hình phần cứng của máy ảo đang chạy

- **Dynamic Memory**: Giúp củng cố tài nguyên và cải thiện độ tin cậy khi khởi động lại máy ảo.

  Windows đòi hỏi nhiều bộ nhớ trong quá trình startup hơn khi đang chạy bình thường. Nếu ta gắn thêm bộ nhớ thì sẽ không thể lấy lại bộ nhớ sau khi máy ảo khởi động. Ở Windows Server 2012, **Dynamic Memory** giới thiệu một thiết lập bộ nhớ tối thiểu, cho phép Hyper-V lấy lại bộ nhớ không sử dụng từ máy ảo

  Nếu một máy ảo có bộ nhớ nhỏ hơn với bộ nhớ khởi động của nó và khi máy ảo khởi động lại. Hyper-V cần thêm bộ nhớ để restart máy ảo. Có thể do trạng thái của máy ảo, Hyper-V không thể luôn có bộ nhớ bổ sung. Điều này có thể khiến máy ảo khởi động thất bại. Tính năng Smart Paging được sử dụng để thu hẹp giữa bộ nhớ tối thiểu và bộ nhớ khởi động, cho phép máy ảo khởi động lại tin cậy hơn.
  
- **Export and import**: Tim hiểu về các lựa chọn export và import trong Hyper-V cho phép di chuyển máy ảo qua host khác

- **Hyper-V Replica**: 
