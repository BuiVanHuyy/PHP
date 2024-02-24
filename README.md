# Giới thiệu về ngôn ngữ PHP

### Overview
PHP (viết tắt của Hypertext Preprocessor) là một ngôn ngữ lập trình (scripting languages) mã nguồn mở được sử dụng rộng rãi cho việt phát triển website. PHP có thể nhúng trực tiếp HTML và điều này giúp tạo ra các trang web động dễ dàng

*Ví dụ*

```php
<!DOCTYPE html>
<html>
    <head>
        <title>Example</title>
    </head>
    <body>

        <?php
            echo "Hi, I'm a PHP script!";
        ?>

    </body>
</html>
```
PHP khác với Javascript là PHP được executed trên server, generating HTML sau đó gửi về client. Browser sẽ chạy đoạn HTML đó nhưng client sẽ không biết được logic trong đoạn code đó là gì
### What PHP can do?
PHP là một ngôn ngữ lập trình server-side bạn có thể làm được nhiều thứ với PHP như là: thu thập dữ liệu từ form data, generate dynamic page content, or send and receive cookies, và nhiều hơn thế nữa

**There are 3 main areas where PHP scripts are used**

- Server-side scripting: Đây là tác dụng chủ yếu của PHP 

- Command line scripting: Bạn có thể tạo một script PHP và chạy mà không cần server hoặc browser. Bạn chỉ cần một trình biên dịch PHP (PHP parser)

- Writing desktop applications

Với PHP bạn có thể tự do chọn hệ điều hành máy chủ (operating system). Bạn cũng có thể chọn lập trình hướng thủ tục (Procedural programming) hoặc lập trình hướng đối tượng (Object-oriented programming) hoặc cả hai.
