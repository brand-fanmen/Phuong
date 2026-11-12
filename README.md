# Phòng Marketing Fanmen (AI Agents)

Đây là phòng marketing gồm 4 agent AI chạy trên Claude Code, phục vụ team Brand Fanmen.

## Cấu trúc
```
CLAUDE.md                     ← File thông tin tổng: thương hiệu, quy trình, quy ước pháp lý (agent nào cũng đọc)
phong-ban/
  truong-phong.md             ← Trưởng phòng: điều phối và vận hành (phiên chat chính đóng vai này)
.claude/agents/
  chien-luoc.md               ← Agent Chiến lược: định vị, chiến lược campaign
  nghien-cuu.md               ← Agent Nghiên cứu: thị trường, đối thủ, phân tích, báo cáo
  content.md                  ← Agent Content: content, kịch bản, brief KOL/PR/seeding
brand/
  ho-so-thuong-hieu.md        ← Hồ sơ thương hiệu, persona, đối thủ
  bai-hoc-campaign.md         ← Bài học từ các campaign (bắt đầu từ campaign 19/11)
  quy-dinh-phap-ly.md         ← Chi tiết quy định quảng cáo mỹ phẩm và nguồn
templates/                    ← Mẫu plan, brief campaign, báo cáo nghiên cứu, brief nội dung
output/                       ← Kết quả công việc, mỗi việc một thư mục
```

## Cách sử dụng
1. Mở Claude Code trong thư mục này. Claude sẽ tự đọc `CLAUDE.md` và đóng vai Trưởng phòng.
2. Gõ yêu cầu, ví dụ: *"Lên chiến lược campaign Tết 2027 cho dòng nước hoa, ngân sách 800 triệu"*.
3. Trưởng phòng hỏi lại **3 câu** → bạn trả lời.
4. Trưởng phòng gửi **plan** → bạn trả lời **"Duyệt"** hoặc **"Không duyệt"** kèm góp ý.
5. Trưởng phòng giao việc cho các agent, tổng hợp kết quả, rồi lưu vào `output/`.

Muốn gọi trực tiếp một agent, bạn có thể nói: *"Dùng agent nghien-cuu để…"*.

## Chỉnh sửa
Tất cả đều là file `.md` thuần, mở bằng bất kỳ trình soạn thảo nào để sửa.
- Đổi cách làm việc của một agent: sửa file của agent đó.
- Đổi thông tin thương hiệu hoặc quy trình chung: sửa `CLAUDE.md` hoặc các file trong `brand/`.
- Phần đầu (giữa hai dòng `---`) của các file trong `.claude/agents/` là cấu hình kỹ thuật. Chỉ nên sửa dòng `description`.

## Việc nên làm tiếp
Điền các mục `[CẦN BỔ SUNG]` trong `brand/ho-so-thuong-hieu.md`:
- sứ mệnh và giá trị cốt lõi;
- danh mục sản phẩm, giá, công dụng đã công bố;
- logo, màu, font.
