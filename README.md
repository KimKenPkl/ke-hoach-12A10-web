# Kế hoạch học tập 12A10 — Web theo dõi từng em (public)

🌐 Web public: **https://kimkenpkl.github.io/ke-hoach-12A10-web/**

Mỗi em 1 thẻ: chân dung điểm số 6 Lần KTĐK, **mục tiêu Lần 7**, việc cần làm theo môn (tích ✔ theo dõi tiến độ, lưu trên máy), copy kế hoạch gửi Zalo.

## Phân nhóm (sau Lần 6)

- **TOP** (9): TB ≥ 20 — nâng trần, mục tiêu 22+
- **GIỮA** (16): TB 17–20 — sửa môn yếu nhất
- **NGUY CƠ** (7): TB < 17 — phụ đạo gốc Toán + Sinh
- **MỚI** (1): Nguyễn Trịnh Bảo Ngọc — kèm riêng, thi bù

## File trong repo

- `index.html` — web tĩnh (không backend, mở offline vẫn chạy).
- `scores.js` — điểm L1–L6 (dùng chung với web báo điểm).
- `plans.js` — kế hoạch 33 em (sinh từ file Excel kế hoạch, không chứa SĐT).
- `danhba-private.js` — **LOCAL ONLY** (SĐT ba/mẹ, đã gitignore, không push).
- `.nojekyll` — cấu hình GitHub Pages.

## Cập nhật khi có điểm Lần 7

1. Bổ sung điểm vào file Excel → sinh lại `scores.js`/`plans.js` (hoặc nhắn tôi làm).
2. Tôi sẽ mở thêm phần **nhập điểm Lần 7** để đối chiếu mục tiêu (hiện chưa thi nên web chưa có phần này).
3. `git add scores.js plans.js index.html && git commit -m "cap nhat Lan 7" && git push` — web tự cập nhật sau ~1 phút.
