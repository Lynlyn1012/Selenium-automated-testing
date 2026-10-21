# Selenium Automated Testing – Sauce Demo

## 1. Giới thiệu

Bài tập thực hành kiểm thử tự động website bằng Selenium WebDriver trên website Sauce Demo.

- Website: https://www.saucedemo.com/
- Công cụ: Python, Selenium WebDriver, Google Colab
- Trình duyệt: Chromium
- Môi trường thực thi: Google Colab

## 2. Mục tiêu

- Làm quen với Selenium WebDriver.
- Tự động hóa các thao tác trên website.
- Kiểm tra kết quả thực hiện và phát hiện lỗi.
- Ghi nhận kết quả kiểm thử cho từng test case.

## 3. Các test case

| Test Case | Nội dung | Kết quả |
|---|---|---|
| TC01 | Đăng nhập thành công | PASSED |
| TC02 | Đăng nhập với mật khẩu sai | PASSED |
| TC03 | Kiểm tra danh sách sản phẩm | PASSED |
| TC04 | Thêm sản phẩm vào giỏ hàng | PASSED |
| TC05 | Đăng xuất khỏi hệ thống | FAILED |

## 4. Kết quả kiểm thử

Đã thực hiện 5 test case trên Sauce Demo. Bốn test case đầu tiên đạt yêu cầu trong các lần chạy đã ghi nhận. Test case đăng xuất vẫn gặp lỗi TimeoutException khi chờ menu hoặc thao tác đăng xuất hoàn tất.

Kết quả được ghi nhận theo thực tế chạy thử; TC05 cần được kiểm tra và sửa lỗi thêm.


## 5. Kết luận

Bài tập giúp làm quen với Selenium WebDriver, cách tìm phần tử trên trang web, tự động hóa thao tác đăng nhập, kiểm tra sản phẩm và thêm sản phẩm vào giỏ hàng. Chức năng đăng xuất vẫn cần được khắc phục và kiểm thử lại trước khi hoàn thiện.
