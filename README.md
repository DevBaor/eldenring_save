# ⚔️ Elden Ring Savegame Copy Tool

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Game Compatibility](https://img.shields.io/badge/Game-Elden%20Ring-yellow.svg)](https://en.wikipedia.org/wiki/Elden_Ring)

Công cụ này cho phép người dùng dễ dàng sao chép dữ liệu nhân vật (character data) từ một tệp lưu trữ Elden Ring (`ER0000.sl2`) sang một tệp lưu trữ khác. Điều này rất hữu ích khi chuyển nhân vật giữa các tài khoản hoặc khôi phục nhân vật riêng lẻ.

## ✨ Tính năng chính

* **Sao chép nhân vật:** Chọn nhân vật từ Tệp Nguồn (**Source file**) và sao chép nó vào vị trí nhân vật mong muốn trong Tệp Đích (**Destination file**).
* **Giao diện trực quan:** Giao diện đơn giản, chỉ cần chọn tệp và nhân vật.

## 📥 Cách sử dụng

### 1. Vị trí tệp lưu trữ

Tệp lưu trữ chính của Elden Ring thường nằm ở:

`C:\Users\[Tên người dùng]\AppData\Roaming\EldenRing\[ID Người dùng]\ER0000.sl2`

### 2. Các bước sao chép nhân vật

1.  **Chạy ứng dụng:** Khởi động `Savegame Copy Tool.exe`.
<img width="559" height="622" alt="image" src="https://github.com/user-attachments/assets/f345d73e-909d-4b73-9394-6ff7f7a83fca" />

2.  **Chọn Tệp Nguồn (Source file):**
    * Nhấn nút **"Browse"** bên dưới **"Source file"**.
    * Chọn tệp lưu trữ Elden Ring chứa nhân vật bạn muốn **sao chép đi** (ví dụ: `ER0000.sl2` từ Tài khoản A).
3.  **Chọn Tệp Đích (Destination file):**
    * Nhấn nút **"Browse"** bên dưới **"Destination file"**.
    * Chọn tệp lưu trữ Elden Ring nơi bạn muốn **sao chép đến** (ví dụ: `ER0000.sl2` của Tài khoản B).
4.  **Chọn Nhân vật:**
    * Trong ô thả xuống **"Copy from"** (bên Nguồn), chọn nhân vật bạn muốn sao chép.
    * Trong ô thả xuống **"Copy to"** (bên Đích), chọn khe nhân vật (slot) bạn muốn ghi đè lên hoặc khe trống để dán nhân vật.
5.  **Thực hiện Sao chép:**
    * Nhấn vào nút **"Select Source and Destination file and characters"** (hoặc một nút thực thi tương tự sẽ xuất hiện sau khi chọn tệp) để hoàn tất quá trình sao chép.

> ⚠️ **Cảnh báo:** Hãy luôn **SAO LƯU (BACKUP)** tệp lưu trữ gốc (`ER0000.sl2`) trước khi sử dụng công cụ này để phòng trường hợp lỗi xảy ra.

## 🛠 Yêu cầu hệ thống

* Hệ điều hành: Windows (Dựa trên cấu trúc đường dẫn savegame của game).
* Game: Elden Ring.

## 🛑 Lưu ý và Miễn trừ trách nhiệm

* Việc chỉnh sửa tệp lưu trữ có thể vi phạm Điều khoản dịch vụ của game hoặc dẫn đến việc bị cấm nếu bạn sử dụng các tệp đã sao chép để tận dụng lỗi (exploits) trong môi trường trực tuyến. **Sử dụng công cụ này hoàn toàn do người dùng tự chịu rủi ro.**
* Công cụ này chỉ sao chép dữ liệu nhân vật; nó không kiểm soát bất kỳ cơ chế chống gian lận (anti-cheat) nào của game.
