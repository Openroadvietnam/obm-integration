# Tích hợp Openroad và OBM

## Tổng quan OBM và Openroad
### OBM

[OBM](http://www.obm.org) là một nền tảng nhắn tin và cộng tác hữu ích không chỉ cho một vài người dùng mà còn cho số lượng lớn người dùng với sự hỗ trợ mạnh mẽ cho các thiết bị di động.

### Openroad

[OpenRoad](http://openroad.vn/) là một phần mềm nguồn mở được phát triển dựa trên [Joinup](https://joinup.ec.europa.eu/), một nền tảng cộng tác và chia sẻ các công nghệ mở nói chung và các ứng dụng nguồn mở nói riêng dành cho khu vực cộng đồng chính phủ Châu Âu.

Xem thêm thông tin: [dự án Openroad](https://github.com/Openroadvietnam/openroad).

## Tại sao phải tích hợp Openroad và OBM?

Openroad chưa có một nền tảng nhắn tin (thư điện tử) cho người dùng. Người dùng Openroad cần sử dụng thư điện tử để trao đổi thông tin trong hoạt động chia sẻ các công nghệ mở và các ứng dụng nguồn mở.

## Sử dụng Single Sign-On

Thiết lập cơ chế [single sign-on](http://en.wikipedia.org/wiki/Single_sign-on) cho phép người dùng Openroad sử dụng hệ thống thư điện tử (OBM) mà chỉ cần đăng nhập hệ thống duy nhất 1 lần.

## Mô đun tích hợp Openroad và OBM
### Mô đun tích hợp trên Openroad

Openroad sử dụng mô đun [CAS client](https://drupal.org/project/cas_services) để kết nối với hệ thống sử dụng Single Sing-On.

### Mô đun tích hợp trên OBM

OBM sử dụng mô đun [CAS client](http://code.google.com/p/rc-cas-plugin/) để kết nối với hệ thống sử dụng Single Sing-On.

## Tài liệu

Tài liệu hướng dẫn cài đặt và tích hợp Openroad - OBM được đặt trong thư mục [docs](docs).

## Kênh thông tin

* IRC: #openroad on irc.freenode.net
* Mailing list: http://lists.openroad.vn/mailman/listinfo/

## Giấy phép sử dụng

Openroad và module tích hợp do nhóm phát triển Openroad và module giữ quyền tác giả, được phân phối kèm theo giấy phép GNU GPL v2.0. Nguyên văn giấy phép sử dụng có thể được xem trong file [LICENSE](LICENSE).
