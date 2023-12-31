---
date: 2023-12-02
title: Hướng dẫn cách cài đặt Jekyll làm công cụ tạo trang web tĩnh (SSG)
aliases:
  - Hướng dẫn cách cài đặt Jekyll làm công cụ tạo trang web tĩnh (SSG)
description: description goes here
tags:
  - jekyll
  - jamstack
  - github pages
categories:
  - Hướng dẫn
authors:
  - thinh-vu
---

## Giới thiệu

!!! abstract "Jekyll là gì?"
	[Jekyll](https://jekyllrb.com/) là một công cụ tạo trang web tĩnh (Static Site Generator, viết tắt SSG) viết bằng ngôn ngữ lập trình [Ruby](https://www.ruby-lang.org/en/) bởi Tom Preston-Werner. Jekyll được phân phối dạng mã nguồn mở theo giấy phép MIT.

## Sử dụng Jekyll ở đâu?

> Tùy chọn cài đặt Jekyll nếu bạn muốn preview trang trên máy tính cục bộ (localhost), nếu không cài trên máy sẽ khó và mất thời gian hơn chút khi tùy biến trang web. Tuy nhiên, nếu không cài m đẩy mã nguồn lên Github page vẫn có thể hiển thị website bình thường.

## Cài đặt Jekyll

*Bạn có thể tham khảo hướng dẫn chính thức bằng tiếng Anh: [tại đây](https://jekyllrb.com/docs/installation/windows/)*

- Chi tiết các bước cài đặt như sau:

    - Tải [Ruby Installer](https://rubyinstaller.org/downloads/) cho máy tính của bạn, tôi sẽ minh hoạ với máy tính Windows trong hướng dẫn này.
    - Mặc định chọn `ridk install` ở bước cài đặt cuối cùng của Wizard
    - Trong terminal/command prompt chạy sau khi kết thúc trình cài đặt (Wizard), nhập `3` cho tùy chọn tương ứng `MSYS2 and MINGW development tool chain`[![demo](https://learn-anything.online/assets/images/Pasted%20image%2020231110213146.png)](https://learn-anything.online/assets/images/Pasted%20image%2020231110213146.png)
    - Mở cửa sổ mới cho Terminal/command prompt, chạy lệnh `gem install jekyll bundler`[![](https://learn-anything.online/assets/images/Pasted%20image%2020231110213006.png)](https://learn-anything.online/assets/images/Pasted%20image%2020231110213006.png)
    - Cập nhật phiên bản mới theo hướng dẫn nếu cần. Ví dụ `gem update --system 3.4.22`[![](https://learn-anything.online/assets/images/Pasted%20image%2020231110213041.png)](https://learn-anything.online/assets/images/Pasted%20image%2020231110213041.png)
    - Kiểm tra phiên bản `jekyll -v`

Như vậy là bạn đã thực hiện cài đặt thành công Jekyll trên máy tính của mình để phục vụ cho việc xem trước các thay đổi với trang web và tùy biến một cách tiện lợi.