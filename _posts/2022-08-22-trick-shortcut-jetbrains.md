---
layout: post
title:  "[Tips] Phím tắt hữu ích khi sử dụng jetbrains ides"
date:   2022-08-20 05:47:04 +0700
categories: Life
tags:
  - Tips
  - Other
hide_thumbnail: true
image: /assets/img/posts/2022-08-22-trick-shortcut-jetbrains/jb_beam.svg
---
{% capture markdown %}
#### 1. Alt + Enter (⌥↑⏎)
#### 2. Alt + F7 (⌥↑F7)
#### 3. Cmd + b (⌘b)
#### 4. Cmd + e (⌘e)
#### 5. Cmd + shift + enter (⇧⌘⏎)
#### 6. Alt + up/down (⌥↑ / ⌥↓) 
#### 6. Alt + up/down (⌥↑ / ⌥↓) 
#### 7. Cmd 1 (⌘1)
#### 8. F2
#### 9. Ctrl + t (⌃t)
#### 10. Cmd + shift + a (⇧⌘a)
#### 11. Ctrl + g (⌃g)

{: .hide-from-excerpt}

{% endcapture %}
{% assign text = markdown | markdownify %}

{% include toc.html html=text %}
#### 1. Alt + Enter (⌥↑⏎)

Hiển thị đề xuất code theo ngữ cảnh. Thường được sử dụng khi phát hiện lỗi trong code.

<img src="/assets/img/posts/2022-08-22-trick-shortcut-jetbrains/alt_enter.gif" alt="alt_enter" width="400"/>

#### 2. Alt + F7 (⌥↑F7)

Tìm xem hàm hay biến được sử dụng ở những đâu trong project.

<img src="/assets/img/posts/2022-08-22-trick-shortcut-jetbrains/alt_enter.gif" alt="alt_f7" width="400"/>

#### 3. Cmd + b (⌘b)

Tìm đến nơi khai báo của phần tử được chọn.

<img src="/assets/img/posts/2022-08-22-trick-shortcut-jetbrains/alt_f7.gif" alt="cmd_b" width="400"/>

#### 4. Cmd + e (⌘e)

Mở danh sách những tệp được mở gần nhất

<img src="/assets/img/posts/2022-08-22-trick-shortcut-jetbrains/alt_f7.gif" alt="cmd_e" width="400"/>

#### 5. Cmd + shift + enter (⇧⌘⏎)

Xuống dòng và tự hoàn thành cú pháp hiện tại, ví dụ như dùng với vòng for, if. (Xem ví dụ để hiểu hơn)

<img src="/assets/img/posts/2022-08-22-trick-shortcut-jetbrains/cmd_shift_enter.gif" alt="cmd_shift_enter" width="400"/>

#### 6. Alt + up/down (⌥↑ / ⌥↓) 

Tự động mở rộng bôi đen từ vị trí con trỏ. Ngày xưa mình toàn dùng ⌥➝ rồi đi bôi đen từ cuối từ. Từ lúc biết toàn xài cái này :kissing_closed_eyes::kissing_closed_eyes:

<img src="/assets/img/posts/2022-08-22-trick-shortcut-jetbrains/alt_up.gif" alt="alt_up" width="400"/>

#### 7. Cmd 1 (⌘1)

Không cần dùng chuột mà bạn vẫn có thể select file bên cửa sổ project, bao tiện :sunglasses::sunglasses: <br>
P/s: nhấn ESC để quay lại màn editor nhé :laughing::laughing:

<img src="/assets/img/posts/2022-08-22-trick-shortcut-jetbrains/cmd-1.gif" alt="cmd_1" width="400"/>

#### 8. F2

Nhảy tới những phần bị lỗi ở file hiện tại.

<img src="/assets/img/posts/2022-08-22-trick-shortcut-jetbrains/f2.gif" alt="f2" width="400"/>

#### 9. Ctrl + t (⌃t)

Hiểu đơn giản là để refactor phần tử được chọn. Đơn giản như rename chẳng hạn :grin::grin:

<img src="/assets/img/posts/2022-08-22-trick-shortcut-jetbrains/ctrlT.gif" alt="ctrl_t" width="400"/>

#### 10. Cmd + shift + a (⇧⌘a)

Bạn có tìm đủ thể loại hổ lốn tạp phí lù, tất cả các action của ide đều có trong đây.

<img src="/assets/img/posts/2022-08-22-trick-shortcut-jetbrains/cmd_shift_a.gif" alt="cmd_shift_a" width="400"/>

#### 11. Ctrl + g (⌃g)

Select phần tử giống phần tử đang được bôi đen. (⌃⌘g là chọn tất cả)

<img src="/assets/img/posts/2022-08-22-trick-shortcut-jetbrains/ctrlG.gif" alt="ctrl_g" width="400"/>

Đây là một vài phím tắt mình hay dùng khi code. Vẫn còn nữa nhưng list hết ra thì nhiều quá. <br>
Ngoài ra các bạn có thể tự custom shortcut theo sở thích của mình nhé :D

Nguồn tham khảo:
- https://www.jetbrains.com/help/idea/reference-keymap-mac-default.html
- https://blog.jetbrains.com/idea/2020/03/top-15-intellij-idea-shortcuts/#%E2%8C%83T_or_ShiftCtrlAltT



