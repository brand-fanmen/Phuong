# PLAN THỰC HIỆN — Bản đồ đối thủ local brand mỹ phẩm nam tại Việt Nam

**Ngày:** 12/11/2026 · **Người yêu cầu:** Team Brand · **Thư mục lưu:** `output/2026-11-12_ban-do-doi-thu-local-brand-nam/`
**Trạng thái:** ĐÃ DUYỆT (12/11/2026)

## 1. Hiểu yêu cầu
- **Yêu cầu:** Lập danh sách các local brand Việt về mỹ phẩm/chăm sóc cá nhân nam cạnh tranh trực tiếp với Fanmen, kèm phân tích để làm đầu vào định vị Fanmen.
- **Thông tin đã làm rõ (từ 3 câu hỏi):**
  1. Mục đích: bản đồ đối thủ để định vị Fanmen (phân khúc giá, định vị, kênh bán, điểm mạnh/yếu).
  2. Phạm vi: chỉ local brand Việt cạnh tranh trực tiếp (Rhys Man, Nerman…).
  3. Ngành hàng: tất cả ngành hàng Fanmen đang bán, mọi kênh.
- **Mục tiêu:** Branding (tìm khoảng trống định vị); phụ: Doanh số (đối thủ thắng ở ngành hàng/kênh nào).
- **Tiêu chí hoàn thành:** Danh sách ~8–15 local brand, đủ cột thông tin, dữ kiện có nguồn, có bản đồ định vị và nhận định khoảng trống cho Fanmen.

## 2. Đầu ra sẽ bàn giao
| # | Đầu ra | Định dạng | File |
|---|---|---|---|
| 1 | Danh sách và hồ sơ từng đối thủ | Bảng Markdown | `01-nghien-cuu.md` |
| 2 | Bản đồ định vị, ma trận ngành hàng × đối thủ, khoảng trống cho Fanmen | Markdown | `02-chien-luoc.md` |
| 3 | Tổng hợp | Markdown | `TONG-HOP.md` |

## 3. Các bước và phân công
| Bước | Agent | Việc cụ thể | Đầu vào | Đầu ra |
|---|---|---|---|---|
| 1 | Nghiên cứu | Lập danh sách và hồ sơ đối thủ, có nguồn | CLAUDE.md, brand/ | `01-nghien-cuu.md` |
| 2 | Chiến lược | Bản đồ định vị, 2–3 khoảng trống định vị | Kết quả bước 1 | `02-chien-luoc.md` |
| 3 | Trưởng phòng | Tổng hợp, kiểm duyệt | Tất cả | `TONG-HOP.md` |

*Tuần tự. Không cần agent Content.*

## 4. Cần người dùng cung cấp thêm (không bắt buộc)
- Danh sách đối thủ team đã biết ngoài Rhys Man, Nerman.
- Bảng giá Fanmen hiện tại.

## 5. Giả định và rủi ro
- **Giả định:** "Local brand" = thương hiệu do công ty Việt sở hữu (kể cả OEM/gia công nước ngoài). Giá lấy theo niêm yết công khai trên sàn/website tại 11/2026.
- **Rủi ro:** Không có dữ liệu doanh số/thị phần chính thức; lượt bán, follower chỉ là tín hiệu tham khảo. Thương hiệu nhỏ ít thông tin.
- **Pháp lý:** Tài liệu chỉ dùng nội bộ, không đưa so sánh với đối thủ vào quảng cáo (CLAUDE.md mục 5.1, điều 4).
