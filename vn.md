
[Source](https://12factor.net/ "Permalink to The Twelve-Factor App")

# The Twelve-Factor App

## Giới thiệu

Trong thời đại hiện đại, phần mềm thường được phát hành như một dịch vụ: được gọi là ứng dụng web hoặc phần mềm dịch vụ. 12 yếu tố là phương pháp để xây dựng các ứng dụng phần mềm dịch vụ:

* Sử dụng các định dạng **khai báo** để tự động hóa việc thiết lập, và để tiết kiệm thời gian, chi phí cho những nhà phát triển mới tham gia vào dự án.

* Có một **quy tắc rõ ràng** với hệ điều hành cơ bản, cung cấp khả năng di chuyển tối đa giữa các môi trường thực thi.

* Thích hợp cho việc triển khai trên nền tảng đám mây hiện đại, giảm thiểu sự phụ thuộc vào các máy chủ và quản trị hệ thống;

* **Giảm thiểu sự khác biệt** giữa việc thử nghiệm và sản phẩm, cho phép tiếp tục triển khai một cách linh hoạt nhất

* Và có thể **mở rộng** mà không cần thay đổi đáng kể  công cụ, kiến trúc hoặc phát triển thực tiễn.

Phương pháp 12 yếu tố có thể được áp dụng cho các ứng dụng được viết bằng bất kỳ ngôn ngữ lập trình nào và sử dụng bất kỳ kết hợp dịch vụ sao lưu nào (cơ sở dữ liệu, hàng đợi, bộ nhớ cache, v.v.).

## Tổng quan

Những người đóng góp cho tài liệu này đã trực tiếp tham gia vào việc phát triển và triển khai hàng trăm ứng dụng, và gián tiếp chứng kiến sự phát triển, vận hành và mở rộng hàng trăm nghìn ứng dụng thông qua công việc của chúng tôi trên nền tảng Heroku.

Tài liệu này tổng hợp tất cả các kinh ngh và quan sát của chúng tôi về một loạt các ứng dụng phần mềm như một dịch vụ trong thực tế. Đó là một sự triangulation về các phương pháp lý tưởng để phát triển ứng dụng, đặc biệt chú ý đến sự linh hoạt trong sự phát triển hữu cơ của ứng dụng theo thời gian, động lực của sự cộng tác giữa các nhà phát triển làm việc trên cơ sở mã ứng dụng và tránh chi phí phát sinh của phần mềm.

Mong muốn của chúng tôi là nâng cao nhận thức về một số vấn đề hệ thống mà chúng tôi đã thấy trong phát triển ứng dụng hiện đại, để cung cấp vốn từ vựng chung để thảo luận những vấn đề đó và cung cấp một loạt giải pháp khái niệm rộng cho những vấn đề kèm theo những thuật ngữ. Quy tắc này được lấy cảm hứng từ sách nói về Kiến trúc ứng dụng và tái cấu trúc ứng dụng doanh nghiệp của Martin Fowler.


[1]: http://www.heroku.com/
[2]: http://blog.heroku.com/archives/2011/6/28/the_new_heroku_4_erosion_resistance_explicit_contracts/
[3]: https://books.google.com/books/about/Patterns_of_enterprise_application_archi.html?id=FyWZt5DdvFkC
[4]: https://books.google.com/books/about/Refactoring.html?id=1MsETFPD3I0C

Nguồn: https://12factor.net/

  
