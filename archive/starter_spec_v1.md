# CEO Operating System — GÓI STARTER
### Đặc tả sản phẩm & Offer (bản canonical)

> **Trạng thái:** v1 — đã chốt scope ngày 2026-06-06
> **Thuộc:** dòng sản phẩm CEO OS (done-for-you), nhánh của dự án CEO AI Coaching
> **Mục đích file:** nguồn sự thật (source of truth) để bán + giao + iterate gói Starter. Bản .docx/PDF sales sẽ xuất ra từ file này khi cần.

---

## 0. Định vị một dòng

> **"Dọn sạch 2 ổ ngốn giờ lớn nhất của CEO — email và họp — gói gọn trong Telegram, tự chạy mỗi ngày, được chỉnh riêng cho công ty bạn."**

Không bán "AI tool". Bán **một hệ điều hành cá nhân cho CEO**, đã lắp sẵn và tự chạy.

---

## 1. Starter giải quyết gì

Đúng **2 vấn đề** — và đó là hai chỗ data nói thời gian CEO chảy vào nhiều nhất:

| Ổ ngốn giờ | Mức độ (theo data) | Nỗi đau hằng ngày |
|---|---|---|
| **Họp** | ~72% thời gian CEO | File ghi âm không ai bóc; biên bản & việc sau họp rơi rụng |
| **Email** | ~24% thời gian CEO | Hộp thư quá tải; không rõ email nào quan trọng; việc tồn đọng |

*Nguồn số liệu: HBR "How CEOs Manage Time" (Porter & Nohria); tham chiếu giáo trình AI-BOS v2.2.*

Chốt ở đúng 2 vấn đề để gói **mỏng, dễ giao, dễ nhớ, dễ bán** — và để chừa khoảng trống nâng cấp lên Pro.

---

## 2. Mô hình sản phẩm: 1 mặt tiền + 2 cỗ máy

Starter = **một mặt tiền (Daily Brief)** đứng trên **hai cỗ máy (Email, Họp)**.

```
            ┌─────────────────────────────┐
            │   DAILY BRIEF (Telegram)     │  ← mặt tiền: nơi 2 cỗ máy gặp nhau
            │   sáng mỗi ngày, 1 màn hình  │     + lịch + việc cần quyết
            └──────────────┬──────────────┘
                  ┌────────┴────────┐
        ┌─────────▼────────┐ ┌──────▼───────────┐
        │  CỖ MÁY EMAIL    │ │   CỖ MÁY HỌP     │
        │  triage + draft  │ │  ghi âm→biên bản  │
        │  + gửi           │ │  + to-do          │
        └──────────────────┘ └───────────────────┘
```

### 2.1 Daily Brief — mặt tiền

- **Đẩy chủ động** vào Telegram mỗi sáng (giờ CEO chọn, mặc định 07:00).
- Một màn hình, đọc 20–30 giây, gồm:
  - 🎯 Top 3 ưu tiên hôm nay
  - 📅 Lịch & chuẩn bị họp (việc cần để mắt trước mỗi cuộc)
  - ⚠️ Cần để mắt (email quan trọng chưa trả lời, việc đang chệch)
  - ✅ Cần bạn quyết hôm nay (kèm gợi ý)
  - 💡 Nếu chỉ làm 1 việc
- **Lệnh on-demand:** `/today` (xem lại brief), `/focus` (việc nên làm tiếp).

### 2.2 Cỗ máy Email

- **Triage:** brief sáng tự lọc "email quan trọng / cần trả lời gấp".
- **Draft + gửi (đóng vòng):** forward 1 email vào bot → nhận bản nháp trả lời → chạm **Gửi** → hệ thống gửi qua Gmail của CEO.
- **Bonus (đi kèm free):** forward *bất kỳ thứ gì* — kể cả file đính kèm (hợp đồng, PDF, số liệu) → tóm tắt + điểm rủi ro. *(Không quảng bá như vấn đề thứ 3 — chỉ là năng lực ngầm của cỗ máy email.)*

### 2.3 Cỗ máy Họp

- **Trước họp:** agenda + bối cảnh nằm sẵn trong brief sáng.
- **Sau họp (WOW chính):** forward file ghi âm/transcript vào bot → nhận **biên bản + bảng to-do** (ai làm gì, hạn nào) ngay trong Telegram.
- Chạm "nhắc tôi" trên một mục → mục đó xuất hiện lại trong brief hôm sau (trí nhớ nối ngày).

---

## 3. Trải nghiệm WOW (mẫu)

**Brief sáng:**

```
☀️ CEO Brief — Thứ Hai 07:00

🎯 3 ưu tiên hôm nay
1. Chốt proposal khách ABC (hạn 17:00)
2. Duyệt kế hoạch tuyển 2 vị trí sales
3. Phản hồi đối tác X về hợp tác Q3

📅 Lịch & chuẩn bị
• 10:00 Sales review — pipeline tuần trước +12%, hỏi An về deal D đang kẹt
• 14:30 Họp vận hành — 2 việc tồn tuần trước chưa đóng

⚠️ Cần để mắt
• Email CFO (2 ngày chưa trả lời) — ngân sách marketing
• Dự án Atlas trễ 2 ngày

✅ Cần bạn quyết hôm nay
• Duyệt ngân sách proposal ABC trước 11:00  [gợi ý: duyệt, ~80tr hợp lý]

💡 Nếu chỉ làm 1 việc: chốt ABC trước trưa → mở khóa 2 việc phụ thuộc.
```

**Biên bản họp (sau khi forward ghi âm):**

```
📝 Biên bản — Họp vận hành, 14:30 Thứ Hai

Quyết định:
• Dời ra mắt tính năng Y sang 20/06
• Tăng ngân sách ads tháng này thêm 15tr

Việc cần làm:
1. [An] Cập nhật timeline dự án Atlas — hạn 08/06
2. [Linh] Gửi báo giá lại cho khách ABC — hạn hôm nay
3. [Sếp] Duyệt ngân sách ads — hạn 07/06

Theo dõi tiếp: deal D đang kẹt khâu pháp lý.
```

---

## 4. Vì sao KHÔNG phải "giống ChatGPT/Claude"

ChatGPT/Claude nay đã có scheduled task + đọc Gmail/Calendar. Nên Starter **không bán ở tầng tính năng** — bán ở 5 chỗ chúng không cho:

1. **Kênh Telegram-native** — chúng báo trong app của chúng / email, *không* đẩy thẳng ra Telegram nơi CEO sống.
2. **Đóng vòng hành động** — nút gửi reply / nhắc / tạo việc; connector của ChatGPT phần lớn *chỉ đọc*.
3. **Done-for-you + tuned bởi chuyên gia** — CEO không phải tự cắm connector, viết prompt, bảo trì. Có người chịu trách nhiệm nó chạy đúng.
4. **Trí nhớ công ty nối ngày** — nhớ quyết định/việc treo, học từ phản hồi; chat của ChatGPT bay hơi.
5. **An toàn dữ liệu** — bot riêng, quyền kiểm soát, thay vì dán email công ty vào AI công cộng.

**Câu trả lời mẫu khi khách hỏi "sao không xài ChatGPT?":**
> "ChatGPT là cái máy. Tôi cài cho anh *hệ thống đã lắp sẵn và tự chạy* — nối vào email, lịch của anh; chỉnh theo đúng công ty anh; mỗi sáng tự đẩy về Telegram; nhớ quyết định và việc đang treo. Anh trả tiền để *không phải tự làm AI engineer* — và để có người chịu trách nhiệm nó chạy đúng."

---

## 5. Onboarding: "CEO Context Setup" (làm WOW thành thật)

Buổi 30 phút (cũng là entry/diagnostic để bán). Nạp 4 nhóm thông tin vào "context profile":

1. **3 mục tiêu / ưu tiên hiện tại** của CEO
2. **Người chủ chốt** (team, đối tác hay nhắc tới)
3. **Các quyết định đang treo**
4. **Việc CEO muốn thôi tốn thời gian**

→ Brief sáng đầu tiên đã cá nhân hóa. *Mẹo cohort đầu:* brief ngày 1 soạn tay để chắc chắn WOW, rồi mới để hệ thống tự chạy.

---

## 6. Ranh giới Starter ↔ Pro (giữ khoảng trống upsell)

**Quy tắc một dòng:** chạm vào *dữ liệu/đội ngũ công ty* hoặc *tự dựng tool/automation* → đó là **Pro**, không phải Starter.

| Trong STARTER (lane cá nhân hằng ngày) | KHÔNG ở Starter → lên PRO |
|---|---|
| Daily Brief (email + lịch + quyết định) | KPI snapshot / dashboard số liệu kinh doanh |
| Cỗ máy Email (triage + draft + gửi) | Theo dõi giao việc & đội ngũ (delegation tracker) |
| Cỗ máy Họp (biên bản + to-do) | Weekly/monthly review system |
| Forward tài liệu → tóm tắt/rủi ro (ngầm) | Tích hợp Slack / CRM / Sheets |
| Trí nhớ nối ngày | Phản biện quyết định `/quyetdinh` (teaser) |
| | Radar đối thủ, cỗ máy nội dung, báo cáo điều hành tự động |
| | Nhân viên AI theo phòng (Projects), Skills, dây chuyền tự chạy |

*Cơ chế kéo upsell:* brief tự nhắc khéo thứ nó chưa làm — vd `📊 KPI tuần: chưa kết nối → nâng Pro`.

---

## 7. Đường nâng cấp (map với giáo trình AI-BOS)

5 tầng L1→L5 / 4 chặng của khóa AI-BOS = 3 tier sản phẩm:

| Chặng khóa | Cấu phần | Tier sản phẩm |
|---|---|---|
| Explorer / Nền tảng (L1–L2, Bài 1–5, 8) | việc cá nhân hằng ngày của CEO | **STARTER** (done-for-you) |
| Operator / Architect (L3–L4, Bài 6–15) | điều hành + tự vận hành công ty | **PRO** |
| Leader (L4–L5, Bài 16–20) | governance, đội ngũ, ROI, hợp nhất | **COMMAND CENTER** |

Khóa dạy CEO **tự xây** (DIY, rẻ); CEO OS **làm sẵn cho họ** (high-ticket). Hai sản phẩm bổ trợ nhau trong cùng phễu.

---

## 8. Giao hàng & khả thi kỹ thuật

- **Khách "dùng được luôn"** vì Starter chỉ cần: 1 Telegram bot + OAuth Google (Gmail + Calendar) + 1 job tạo brief mỗi sáng.
- **Cohort đầu giao concierge (thủ công)** — đặc biệt khâu xử lý transcript họp; vừa giao được ngay, vừa học ra quy trình để productize sau. **Bán trước, tự động hóa sau.**
- **Lưu ý quyền Gmail:** vài CEO ngại cấp quyền ngày đầu → có sẵn biến thể nhẹ "Calendar + nhập tay ưu tiên", mở Gmail khi đã tin.
- *Chi tiết kỹ thuật (repo, VPS, skill agent) nằm ở luồng "AI Automation" riêng — không thuộc file này.*

---

## 9. Giá & vị trí trong phễu *(cần chốt con số)*

- **Vai trò:** entry / quick win — hạ rào cho người ngần ngừ, mở đường lên Pro.
- **Khoảng giá đề xuất:** 25–35 triệu (setup 30 ngày + 1 buổi training + onboarding).
- **Đòn bẩy chốt nhanh:** giá sáng lập (founding client) — số suất giới hạn, đổi lấy testimonial + case study.
- *Để chốt: con số giá cuối + có credit lên Pro hay không.*

---

## 10. Checklist bán & giao (rút gọn)

**Bán:**
- [ ] Liệt kê 15–25 CEO/founder ấm (gồm học viên/quan tâm coaching)
- [ ] Mời "CEO Context Setup" 30 phút (audit/diagnostic)
- [ ] Chốt ngay trong buổi bằng giá sáng lập

**Giao:**
- [ ] Tạo bot + kết nối Gmail/Calendar
- [ ] Nạp context profile từ buổi onboarding
- [ ] Brief ngày 1 soạn tay (đảm bảo WOW) → bật tự chạy
- [ ] Check-in tuần 1 chỉnh brief khớp 100%

---

## 11. Câu hỏi còn mở / next steps

1. Chốt **con số giá** Starter + chính sách credit lên Pro.
2. Chốt **tên gói** hiển thị với khách (vd "CEO Daily Command" hay giữ "CEO OS — Starter").
3. Có cần xuất **bản .docx/PDF sales one-pager** từ file này để gửi khách không?
4. Định nghĩa tiếp **gói Pro** (tầng Operator/Architect) để hoàn thiện thang giá.

---

*Tài liệu nội bộ — dự án CEO AI Coaching. Cập nhật khi scope thay đổi.*
