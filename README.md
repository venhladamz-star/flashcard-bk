<div align="center">

# 🗂️ Flashcard

### Học từ vựng & ngữ pháp tiếng Anh — nhẹ, nhanh, không cần cài đặt

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-venhladamz--star.github.io-5b8def?style=for-the-badge)](https://venhladamz-star.github.io/flashcard-bk/)
[![Made with](https://img.shields.io/badge/Made_with-Vanilla_JS-f7df1e?style=flat-square&logo=javascript&logoColor=black)](#)
[![Backend](https://img.shields.io/badge/Backend-Firebase-ffca28?style=flat-square&logo=firebase&logoColor=black)](#)
[![No Build](https://img.shields.io/badge/Build_step-none-3fb87f?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-Personal_Project-8b95a7?style=flat-square)](#)

**[🚀 Dùng thử ngay](https://venhladamz-star.github.io/flashcard-bk/)**

</div>

<br>

Một ứng dụng học tiếng Anh chạy **hoàn toàn trong trình duyệt** — không app store, không cài đặt, không build step. Mở link là học được ngay, trên điện thoại, tablet hay máy tính đều có giao diện tối ưu riêng.

<br>

## 📚 Mục lục

- [Tính năng](#-tính-năng)
- [Công nghệ](#️-công-nghệ)
- [Chạy thử](#-chạy-thử)
- [Cấu trúc dự án](#-cấu-trúc-dự-án)

<br>

## ✨ Tính năng

### 📖 Học từ vựng
Tạo bộ thẻ bằng cách dán danh sách (định dạng Tab: `Từ · Nghĩa · Phát âm · Loại từ`), học kiểu lật thẻ 3D, nghe phát âm bằng giọng máy hoặc file mp3. Trạng thái *đã thuộc / chưa thuộc* được theo dõi cho từng từ và có thể xem lại gộp từ mọi bộ thẻ.

### ✏️ Kiểm tra (Quiz)
Trắc nghiệm hoặc tự luận, ngẫu nhiên cả chiều hỏi (Anh → Việt / Việt → Anh) lẫn kiểu trả lời. Tự động chấm điểm và cập nhật trạng thái ghi nhớ.

### 🎮 7 mini-game

<div align="center">

| Game | Cách chơi |
|:---:|:---|
| 🧩 **Nối từ** | Lật ô, ghép từ tiếng Anh với nghĩa tiếng Việt |
| 🎯 **Đoán từ** | Kiểu Hangman — đoán từng chữ cái, có gợi ý |
| 🔤 **Sắp xếp chữ** | Xếp lại chữ cái bị xáo trộn cho đúng từ, có gợi ý |
| ⚡ **Đua thời gian** | Chọn nhanh nghĩa đúng trước khi hết giờ, ăn combo điểm |
| 🌧️ **Từ rơi** | Gõ nghĩa trước khi từ rơi chạm đáy màn hình, có gợi ý |
| 📝 **Điền chỗ trống** | Chọn từ đúng để hoàn thành câu |
| 🎡 **Vòng quay** | Quay ngẫu nhiên 1 từ, trả lời để ghi điểm |

</div>

> 💡 3 game khó đoán nhất (Đoán từ, Sắp xếp chữ, Từ rơi) có nút **Gợi ý** dùng không giới hạn, không trừ điểm.

Mỗi game chơi được với bộ thẻ riêng, bộ Tham khảo công khai, hoặc toàn bộ từ đã thuộc — điểm cao nhất tự lưu và đồng bộ cloud.

### 📐 Ngữ pháp
Bài viết Markdown do Admin biên soạn (tiêu đề, bảng, code, blockquote...), người dùng thường chỉ xem — Admin đăng/sửa/xoá trực tiếp trên web, không cần công cụ ngoài.

### 🌐 Tham khảo
Kho bộ từ vựng công khai do Admin đăng, ai cũng học/quiz/chơi game được ngay mà không cần tự nhập liệu.

### ☁️ Đồng bộ & đa thiết bị

- 🔐 Đăng nhập Google — dữ liệu tự động đồng bộ qua Firebase, dùng được trên nhiều máy
- 📴 Hoạt động cả khi chưa đăng nhập (lưu local), tự gộp dữ liệu khi đăng nhập sau
- 📱 Giao diện tự thích ứng theo thiết bị: tabbar dưới cho điện thoại · sidebar cho tablet/laptop
- 🌗 Chế độ sáng / tối

<br>

## 🛠️ Công nghệ

<div align="center">

| | |
|---|---|
| **Frontend** | Vanilla JavaScript (ES Modules) — không framework |
| **Backend** | [Firebase](https://firebase.google.com/) — Authentication + Firestore (realtime sync) |
| **Build step** | Không có — 1 file `index.html` duy nhất, mở là chạy |
| **Hosting** | GitHub Pages |

</div>

<br>

## 🚀 Chạy thử

```bash
git clone https://github.com/venhladamz-star/flashcard-bk.git
cd flashcard-bk
npx serve .        # hoặc mở thẳng index.html bằng trình duyệt
```

Hoặc đơn giản nhất — **[mở bản đang chạy tại đây](https://venhladamz-star.github.io/flashcard-bk/)**, không cần clone gì cả.

> Các tính năng cần đăng nhập/đồng bộ cloud (Tham khảo, Ngữ pháp, tài khoản) dùng project Firebase riêng của tác giả.

<br>

## 📁 Cấu trúc dự án

```
flashcard-bk/
└── index.html   ← toàn bộ app: HTML + CSS + JavaScript
```

Không có `node_modules`, không có bước build — mọi thứ nằm trong một file để dễ tải, dễ chỉnh sửa, dễ deploy.

<br>

<div align="center">

Dự án cá nhân, phục vụ mục đích học tập 🎓

</div>
