# Dấu Son — Ảnh và video kỷ niệm

Web tạo ảnh và video kỷ niệm (sinh nhật, kỷ niệm ngày cưới, đám cưới, ngày yêu nhau) từ ảnh và thông tin người dùng nhập. Có 6 concept: Phim nhựa, Lịch bloc, Báo xưa, Polaroid, Son đỏ, Tạp chí.

Toàn bộ chạy trong trình duyệt (HTML + Canvas + MediaRecorder), không cần server. Ảnh người dùng không bị tải lên đâu cả.

## Chạy thử trên máy

Mở thẳng file `index.html` bằng Chrome hoặc Edge là dùng được.

## Đưa lên GitHub Pages

1. Tạo repo mới trên GitHub, ví dụ `dau-son`.
2. Upload 3 file: `index.html`, `README.md`, `.nojekyll`.
3. Vào **Settings → Pages**, phần **Source** chọn **Deploy from a branch**, branch `main`, thư mục `/ (root)`, bấm **Save**.
4. Đợi 1–2 phút, web sẽ chạy tại `https://<tên-tài-khoản>.github.io/dau-son/`.

## Trình duyệt hỗ trợ

- Ảnh PNG: mọi trình duyệt hiện đại.
- Video: Chrome, Edge (ra MP4 hoặc WebM tùy phiên bản), Safari 14.1+ (MP4). Firefox ra WebM.
- Khi xuất video cần giữ tab mở, vì video được dựng theo thời gian thực.
