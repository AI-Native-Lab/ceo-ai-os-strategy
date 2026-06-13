# CEO Operating System — BỘ 3 GÓI (Offer Ladder)
### Tài liệu master về cấu trúc sản phẩm & giá

> **Trạng thái:** v1 — 2026-06-06
> **Quan hệ file:** `starter_spec_v1.md` là deep-dive của gói Starter; file này là master toàn bộ thang 3 gói. Bản trình bày: `offer_packages.html`.
> Tên marketing của mỗi gói là **đề xuất, cần chốt**. Giá là **giả thuyết, cần chốt**.

---

## 0. Nguyên tắc định vị

- Không bán "tool" hay "agent" — bán **một hệ điều hành cho CEO**, đã lắp sẵn và tự chạy.
- Một **lane** xuyên suốt: giúp CEO *nhìn rõ – ưu tiên đúng – quyết nhanh – vận hành nhẹ*.
- Thang 3 gói = 3 tầng trưởng thành của giáo trình **AI-BOS**: cá nhân → công ty → tổ chức.
- Mỗi gói **đủ giá trị để đứng một mình**, nhưng cố tình chừa khoảng trống để kéo lên gói trên.

---

## 1. Bảng so sánh 3 gói

| Tiêu chí | **STARTER** | **PRO** *(gói chốt chính)* | **COMMAND CENTER** |
|---|---|---|---|
| Tên đề xuất | CEO Daily Command | CEO Operating System | Executive Command Center |
| Tầng AI-BOS | Explorer / Nền tảng | Operator / Architect | Leader / Hợp nhất |
| Giải quyết | **Email + Họp** (giờ của CEO) | + Nhìn rõ công ty, quyết định, giao việc, nhịp điều hành | + Governance, ROI, cả tổ chức AI-first |
| Mặt tiền | Daily Brief (Telegram) | Brief + Weekly/Monthly Review + KPI | Command Center toàn cảnh + roadmap |
| Cỗ máy / Module | Email, Họp | + KPI dashboard, hỗ trợ quyết định, delegation tracker, báo cáo tự động | + custom automation/agents, policy, ROI scorecard, team rollout |
| Tích hợp | Gmail + Calendar | + Slack/CRM/Sheets (1–2) | + tích hợp sâu theo hệ thống của họ |
| Hỗ trợ quyết định | — *(teaser)* | Hội đồng cố vấn AI + decision log | + pre-mortem, governance quyết định |
| Giao việc | nhắc cá nhân | Delegation tracker + follow-up tự động | + accountability toàn đội |
| Governance / ROI | — | — | Policy + audit + ROI scorecard |
| Training | 1 buổi | 2–3 buổi (+ EA/trợ lý) | Team rollout / train-the-trainer |
| Tối ưu | check-in tuần 1 | 30 ngày tối ưu | Retainer hàng tháng + consulting |
| Đối tượng | CEO cá nhân, solopreneur, SME nhỏ | **SME có team (sweet spot)** | DN lớn / founder muốn full system |
| Giá đề xuất | **25–35tr** | **60–80tr** | **120–180tr+ / custom** |
| Thời gian setup | ~vài ngày | 30–45 ngày | dự án dài + retainer |

---

## 2. STARTER (tóm tắt — chi tiết ở `starter_spec_v1.md`)

**Định vị:** "Dọn 2 ổ ngốn giờ lớn nhất của CEO — email và họp — gói gọn trong Telegram, tự chạy mỗi ngày."

**Mô hình:** 1 mặt tiền (Daily Brief) + 2 cỗ máy (Email: triage + draft + gửi; Họp: ghi âm → biên bản + to-do).

**Vai trò trong phễu:** entry / quick win — hạ rào, tạo WOW nhanh, mở đường lên Pro.

---

## 3. PRO — "CEO Operating System" *(gói chốt doanh số chính)*

**Định vị một dòng:**
> "Từ trợ lý cá nhân thành **hệ điều hành cả công ty**: CEO nhìn rõ mọi việc quan trọng, quyết nhanh hơn, và theo dõi được đội ngũ — mọi thứ về một chỗ."

**Starter dọn *giờ* của CEO. Pro cho CEO *quyền kiểm soát* công ty.**

### Giải quyết thêm gì (ngoài Email + Họp)
- **Visibility:** KPI snapshot, trạng thái theo phòng ban, cảnh báo khi lệch mục tiêu.
- **Prioritization toàn công ty:** không chỉ việc cá nhân, mà ưu tiên xuyên phòng ban.
- **Hỗ trợ quyết định:** "Hội đồng cố vấn AI" phản biện đa chiều (tài chính / khách hàng / rủi ro) + pre-mortem (Bài 6 AI-BOS).
- **Delegation:** giao việc, theo dõi owner/deadline/status, nhắc tự động.
- **Nhịp điều hành:** Weekly Review (gì chạy, gì kẹt, ai nợ việc) + Monthly review.

### Gồm gì (cụ thể)
- **Mọi thứ trong Starter**, cộng:
- **KPI dashboard** — kết nối Google Sheets / nguồn số liệu → đưa vào brief sáng + weekly review.
- **Weekly / Monthly Review** tự động đẩy Telegram.
- **Delegation tracker** — backend Notion/Sheets; giao việc từ Telegram, theo dõi + nhắc.
- **Decision support + decision log** có cấu trúc (lưu lịch sử quyết định).
- **Báo cáo điều hành tự động** (mẫu tuần/tháng) — Bài 10 AI-BOS.
- **1–2 tích hợp đội ngũ:** Slack *hoặc* CRM (HubSpot/Pipedrive) → digest.
- **Module tùy chọn** (chọn 1–2): Radar đối thủ (Bài 3), Trợ lý sales (Bài 9), Cỗ máy nội dung (Bài 5).
- **2–3 buổi training** cho CEO (+ tùy chọn 1 buổi cho EA/trợ lý).
- **30 ngày tối ưu.**

### Đối tượng
SME 10–100 người có đội ngũ — **sweet spot của cả chương trình**.

### Ranh giới (Pro KHÔNG bao gồm → lên Command Center)
Governance/policy cấp công ty, ROI scorecard, custom automation/agents tích hợp sâu, team rollout toàn tổ chức, consulting retainer dài hạn.

### Giá đề xuất
**60–80tr** — gói chốt doanh số chính. Đây là gói nên đẩy mạnh trong sprint 7 ngày.

---

## 4. COMMAND CENTER — "Executive Command Center" *(high-ticket)*

**Định vị một dòng:**
> "Không chỉ hệ điều hành cho CEO — mà đưa **cả tổ chức lên AI-first**: có governance, đo được ROI, và đồng hành tối ưu dài hạn."

### Giải quyết thêm gì (tầng Leader, Bài 16–20 AI-BOS)
- **Governance & an toàn AI:** AI Usage Policy + bộ audit (Bài 16).
- **Dẫn dắt con người:** kế hoạch truyền thông + giảm kháng cự nội bộ (Bài 17).
- **Pilot có KPI** cho phòng ban (Bài 18).
- **Đo ROI:** AI Scorecard + đo lường định kỳ (Bài 19).
- **Hợp nhất:** mọi cấu phần thành một Command Center vận hành thật + roadmap 6–12 tháng (Bài 20).

### Gồm gì (cụ thể)
- **Mọi thứ trong Pro**, cộng:
- **Full custom setup** theo doanh nghiệp (nhiều phòng ban, workflow riêng).
- **Custom automation / agents** — tích hợp sâu hệ thống của họ (API, Make/n8n, MCP).
- **Governance pack** — policy + audit + phân quyền.
- **ROI scorecard** + báo cáo hiệu quả định kỳ.
- **Team rollout / train-the-trainer** cho các phòng ban.
- **Tối ưu hàng tháng (retainer)** + **consulting/coaching** đi kèm.
- **Roadmap 6–12 tháng.**

### Đối tượng
DN lớn (persona A) hoặc founder muốn full system + đồng hành dài hạn.

### Vai trò chiến lược
Đây là **cầu nối với hệ sinh thái dài hạn** (training, cohort, consulting). Command Center biến một deal thành quan hệ retainer + nguồn case study cao cấp.

### Giá đề xuất
**120–180tr+** hoặc **custom** (dự án + retainer hàng tháng).

---

## 5. Thang nâng cấp & map với giáo trình AI-BOS

```
   Cá nhân           →        Công ty          →        Tổ chức
 ┌──────────┐          ┌──────────────┐          ┌────────────────────┐
 │ STARTER  │  ──────▶ │     PRO      │  ──────▶ │  COMMAND CENTER     │
 │ Explorer │          │ Operator/    │          │  Leader / Hợp nhất  │
 │ Email+Họp│          │ Architect    │          │  Governance+ROI     │
 └──────────┘          └──────────────┘          └────────────────────┘
   25–35tr               60–80tr                   120–180tr+ / custom
```

- **Khóa AI-BOS** dạy CEO *tự xây* (DIY, rẻ ~9.9tr). **CEO OS** *làm sẵn cho họ* (high-ticket). Hai sản phẩm cùng một phễu, bổ trợ nhau.
- Cơ chế kéo upsell nằm ngay trong sản phẩm: brief Starter tự nhắc thứ nó chưa làm (KPI, giao việc) → gợi Pro; Pro chạm trần đội ngũ/governance → gợi Command Center.

---

## 6. Khác biệt chống-ChatGPT (áp dụng cả 3 gói)

ChatGPT/Claude đã có scheduled task + đọc Gmail/Calendar. Cả dòng CEO OS **không bán ở tầng tính năng**, mà ở 5 chỗ chúng không cho:

1. Kênh **Telegram-native** (chúng chỉ báo trong app/email).
2. **Đóng vòng hành động** (connector ChatGPT phần lớn chỉ đọc).
3. **Done-for-you + tuned bởi chuyên gia** — khách không phải tự làm AI engineer.
4. **Trí nhớ công ty nối ngày** (chat ChatGPT bay hơi).
5. **An toàn dữ liệu** (bot riêng, có kiểm soát).

---

## 7. Kịch bản doanh số 7 ngày (300tr)

| Kịch bản | Cấu trúc | Tổng |
|---|---|---|
| Base (dễ nhất) | 5 × Pro @ 60tr | 300tr |
| Có đệm | 4 × Pro @ 60tr + 1 × Command Center @ 120tr | 360tr |
| Ít deal, nặng proof | 3 × Pro+ @ 100tr | 300tr |

- **Gate thật = pipeline ấm**, không phải offer. Cần ~15–25 contact ấm → ~8–12 buổi audit → 5 chốt.
- **Đòn bẩy chốt:** giá sáng lập (founding client) — số suất giới hạn, đổi testimonial + case study.
- **Entry point:** buổi "CEO Context Setup / Audit" 30 phút → chốt ngay trong buổi.
- **Pipeline ấm gợi ý:** học viên + người quan tâm chương trình CEO AI Coaching.

---

## 8. Câu hỏi cần chốt / next steps

1. **Giá cuối** từng gói + chính sách credit khi nâng cấp.
2. **Tên marketing** chính thức của 3 gói (đang để tên đề xuất).
3. Có cần **bản .docx/PDF sales** xuất từ bản HTML không?
4. Chốt **module mặc định** của Pro (radar / sales / content — chọn cái nào vào gói chuẩn).
5. Soạn **sales script + danh sách warm** để khởi động sprint 7 ngày.

---

*Tài liệu nội bộ — dự án CEO AI Coaching. Cập nhật khi scope/giá thay đổi.*
