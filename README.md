## Họ và tên: Bùi Thế Thuật
## Mã sinh viên: 21020796

# Phần 1. Tìm hiểu các khái niệm

## Docker là gì? Docker compose là gì?

- **Docker:** Nền tảng phần mềm cho phép chúng ta dựng, kiểm thử và triển khai ứng dụng một cách nhanh chóng. Docker đóng gói phần mềm vào các đơn vị tiêu chuẩn hóa được gọi là container, nó bao gồm mọi thứ mà phần mềm cần để chạy, trong đó có thư viện, công cụ hệ thống, mã nguồn và thời gian chạy. Bằng cách sử dụng Docker, ta có thể nhanh chóng triển khai và thay đổi quy mô ứng dụng vào bất kỳ môi trường nào và biết chắc rằng mã nguồn của mình sẽ chạy được. Docker chạy theo các image trong file Dockerfile và có thể chạy trực tiếp container không cần file có trước.

- **Docker-compose:** Là một công cụ dùng để định nghĩa và chạy nhiều container trên ứng dụng Docker. Nó cho phép ta tạo 1 file cấu hình YAML, nơi mà ta sẽ định nghĩa các services trên ứng dụng của mình và định nghĩa tất cả các bước, các cấu hình cần thiết để xây dựng các image, up các container và liên kết chúng với nhau. Cuối cùng, một khi tất cả điều này được thực hiện, ta sẽ chỉ cần thiết lập tất cả với một lệnh duy nhất. Tóm lại, Docker compose giúp ta tự động tải các image, thiết lập cấu hình tốt hơn rất nhiều so với docker. Nó sẽ cần một file cấu hình docker-compose.yml để chạy theo các image và cấu hình trong đó.

## Linux, Unix, BSD, *nix là gì? macOS thuộc loại nào?

- **Linux, Unix, BSD, và *nix(Unix-like):** đều là các hệ điều hành thuộc dạng Unix-like, 
            có nghĩa là chúng được thiết kế hoặc phát triển dựa trên hệ điều hành Unix gốc. Dưới đây là mô tả 
            ngắn về mỗi loại:

  1. **Unix:** Unix là một hệ điều hành multitasking, multiuser được phát triển từ đầu những năm 1970 bởi Ken Thompson, Dennis Ritchie và nhóm nghiên cứu tại Bell Labs. Unix có ảnh hưởng lớn đối với nhiều hệ điều hành khác như Linux và BSD.

  2. **Linux:** Linux là một hệ điều hành mã nguồn mở được phát triển dựa trên ý tưởng và tiêu chí của Unix. Linux kernel là nền tảng cơ bản của hệ điều hành Linux, được phát triển bởi Linus Torvalds vào những năm 1990.

  3. **BSD (Berkeley Software Distribution):** BSD là một họ các hệ điều hành Unix-like phát triển từ Unix BSD được phát triển tại Đại học California, Berkeley.

  4. **\*nix (Unix-like):** Thuật ngữ "Unix-like" hay "*nix" thường được sử dụng để mô tả các hệ điều hành có các tính chất tương tự Unix, bao gồm cả Linux và BSD.

- **macOS:** macOS thuộc loại *nix vì nó sử dụng một số thành phần từ hệ điều hành BSD, đặc biệt là Darwin.

## Alpine và Ubuntu là gì?

- **Alpine Linux:** Alpine Linux là một hệ điều hành Linux nhẹ và có độ bảo mật cao. Nổi bật với kích thước hình ảnh nhỏ, Alpine thường được sử dụng cho các container Docker và các môi trường có hạn tài nguyên. Alpine sử dụng thư viện libc của musl, thay vì thư viện libc của GNU (glibc), điều này giúp giảm kích thước hệ thống.

- **Ubuntu:** Ubuntu là một hệ điều hành Linux phổ biến, được xây dựng trên nền tảng Debian. Ubuntu cung cấp một hệ thống đầy đủ chức năng và thân thiện với người dùng, phù hợp cho cả máy tính cá nhân và máy chủ. Được duy trì chặt chẽ, Ubuntu có thời kỳ hỗ trợ dài hạn, điều này làm cho nó trở thành lựa chọn phổ biến trong cả môi trường doanh nghiệp và cá nhân.

## VNC là gì?

- VNC là viết tắt của "Virtual Network Computing." Đây là một hệ thống chia sẻ màn hình chạy trên nhiều nền tảng, được tạo ra để điều khiển máy tính từ xa. Điều này có nghĩa là màn hình, bàn phím và chuột của một máy tính có thể được sử dụng từ xa bởi một người dùng từ một thiết bị phụ khác như họ đang ngồi trước máy tính đó.

- VNC hoạt động dựa trên mô hình client/server. Một thành phần máy chủ được cài đặt trên máy tính từ xa (máy tính bạn muốn điều khiển), và một trình xem VNC, hoặc client, được cài đặt trên thiết bị bạn muốn kiểm soát từ xa. Điều này có thể là một máy tính khác, một máy tính bảng hoặc điện thoại di động. Khi máy chủ và trình xem kết nối, máy chủ truyền một bản sao của màn hình máy tính từ xa đến trình xem.
  
- Không chỉ người dùng từ xa có thể nhìn thấy mọi thứ trên màn hình của máy tính từ xa, mà chương trình còn cho phép các lệnh từ bàn phím và chuột hoạt động trên máy tính từ xa, do đó người dùng kết nối có đầy đủ quyền kiểm soát (sau khi được cấp quyền từ máy tính từ xa).

- VNC được tạo ra tại Cambridge vào cuối những năm 1990 bởi những người sáng lập của RealVNC và đã được thương mại hóa vào năm 2002 khi công ty được thành lập.
