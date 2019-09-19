---
layout: post
title: "Lesson 1 - Tạo project với Libgdx."
date: 2019-09-19 18:59:00 +0700
categories: [libgdx, game]
tags: [libgdx, game]
image: libgdx.png
---

## Sơ lược về Libgdx  
  Đây là bài đầu tiên trong series học lập trình game với **libgdx**. Nếu bạn chưa biết libgdx là gì thì -> [libgdx wiki](https://en.wikipedia.org/wiki/LibGDX)  
Về cơ bản thì libgdx là một framework để lập trình game, hỗ trợ _**đa nền tảng**_.  

{: .box-note}
**Note:** Để hiểu được series này yêu cầu bạn phải có kiến thức căn bản về ngôn ngữ lập trình java nên những vấn đề như cài đặt jdk về java tôi sẽ không nhắc lại nữa nếu có thì chỉ lướt qua.

## Tạo project  
  Đầu tiên để bắt đầu học tập về libgdx bạn cần biết cách tạo 1 project libgdx như thế nào.  
  Bạn download Libgdx-liftoff [tại đây](https://github.com/tommyettinger/gdx-liftoff/releases/tag/v1.9.9.0).  
  Xong! bạn chạy file jar đó. Để chạy được file vừa download yêu cầu máy tính của bạn phải đã cài java nếu chưa cài bạn có thể lên google tìm kiếm phần này.
  Chạy file trông sẽ như thế này
  ![Libgdx-liftoff](https://raw.githubusercontent.com/NoCodeBlog/NoCodeBlog.github.io/master/static/img/_posts/libgdx-liftoff.png)
 
 Tại đây bạn cần điền tên cho project của bạn tại dòng đầu tiên.  
 Dòng thứ hai là điền package.  
 Dòng thứ ba là điền tên class có chứa hàm main.  
 Dòng thứ tư là nơi bạn muốn lưu project.  
 Và ở dòng cuối cùng, bạn cần trỏ tới thư mục chứa sdk của bạn nếu bạn định lập trình cho nền tảng android.
 
 Ở phần bên dưới bạn tích chọn vào những nền tảng mà bạn định sử dụng. Android, ios và desktop .v.v.  
 
 Xong! bạn chọn Generate project
 ![Generate project](https://raw.githubusercontent.com/NoCodeBlog/NoCodeBlog.github.io/master/static/img/_posts/libgdx-liftoff-lesson1.png)

 Bạn sẽ thấy tiến trình generate rất nhanh. Chọn Exit application vậy là bạn đã tạo xong một project libgdx với libgdx-liftoff.
 
 Tôi sẽ hướng dẫn bạn import project này vào android studio trong bài tiếp theo.
 
 {: .box-note}
**Note:** Chắc bạn sẽ thắc mắc tại sao tôi không dùng Libgdx trên trang chủ badlogic.com mà lại dùng libgdx-liftoff?  
Đơn giản vì libgdx-liftoff tốt hơn :))). Và Libgdx trên trang chủ mà bạn download về chỉ làm việc được với phiên bản java 8, và nó có khá nhiều vấn đề.

[Click vào đây để đến bài tiếp theo Lesson 2](#)

 
