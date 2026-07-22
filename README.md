# hoc-code

Hành trình học **vibe coding** từ con số 0 — từ chỗ chưa biết file là gì đến khi
tự làm và đưa được sản phẩm lên internet.

Người học: **Ruby** ([@vsonmemo-rb](https://github.com/vsonmemo-rb)) — nền tảng kinh tế, không học lập trình.

---

## 🎯 Các sản phẩm trong repo

### 📊 [Dashboard Quảng cáo Facebook](dashboard-ads/)

Công cụ theo dõi và tối ưu chiến dịch quảng cáo. Đây là dự án chính, dùng được cho công việc thật.

**Tính năng**

- Kéo thả file CSV xuất từ Ads Manager
- 10 chỉ số: Chi phí · Doanh thu · ROAS · Purchase · CAC · Hiển thị · Click · CTR · CPC · CPM
- Xem theo 4 cấp: chiến dịch · nhóm quảng cáo · mẫu quảng cáo · ngày
- Tự chấm điểm theo ngưỡng: 🟢 Tốt · 🟠 Xem lại · 🔴 Cần tắt
- Biểu đồ xu hướng chi phí/doanh thu và ROAS theo ngày
- Phễu hành trình khách hàng 8 bước, tự chỉ ra khâu rơi rụng nhiều nhất
- So sánh kỳ này với kỳ trước, kèm mức tăng giảm
- Nhớ dữ liệu đã tải, mở lại không phải kéo file lần nữa

**Cách dùng**

1. Mở `dashboard-ads/index.html` bằng trình duyệt
2. Xuất báo cáo CSV từ Ads Manager
3. Kéo file thả vào dashboard
4. Đặt ngưỡng ROAS và CAC theo mục tiêu của bạn

**Lưu ý riêng tư:** file CSV chứa số liệu kinh doanh thật đã được chặn không đẩy
lên GitHub (xem `.gitignore`). Chỉ file mẫu `du-lieu-mau.csv` là dữ liệu giả.

---

### 🎓 [Trang chúc mừng tốt nghiệp](tot-nghiep/)

🔗 **[Xem trực tiếp](https://vsonmemo-rb.github.io/hoc-code/tot-nghiep/)**

Trang chúc mừng có màn tung mũ, pháo hoa, âm thanh tự tạo bằng code, đĩa nhạc quay,
thư mở giữa màn hình, và album ảnh vuốt được trên điện thoại.

---

### 💌 [Thiệp gửi 10 năm sau](thiep-10-nam/)

🔗 **[Xem trực tiếp](https://vsonmemo-rb.github.io/hoc-code/thiep-10-nam/)**

Phong bì mở ra bằng hiệu ứng 3D, mưa trái tim, album ảnh toàn màn hình kèm nhạc.

---

### 🧮 Bài tập nền tảng

| Thư mục | Nội dung |
|---|---|
| [buoi7/](buoi7/) | Máy tính lãi tiết kiệm — học biến & kiểu dữ liệu |
| [buoi8/](buoi8/) | Máy tính thuế TNCN lũy tiến — học if/else & vòng lặp |

---

## 🛠️ Công nghệ

Toàn bộ viết bằng **HTML · CSS · JavaScript thuần**, không cần cài đặt gì.
Mỗi sản phẩm là một file HTML duy nhất, mở bằng trình duyệt là chạy.

- **Chart.js** (qua CDN) — vẽ biểu đồ
- **localStorage** — lưu dữ liệu trong trình duyệt
- **Web Audio API** — tạo âm thanh bằng code, không cần file
- **GitHub Pages** — đưa sản phẩm lên internet

---

## 📚 Những gì đã học

| Chủ đề | Nội dung |
|---|---|
| Nền tảng | File & thư mục · VS Code · terminal |
| Web | HTML / CSS / JavaScript · frontend vs backend |
| Lập trình | Biến · kiểu dữ liệu · if/else · vòng lặp · hàm |
| Dữ liệu | Đọc CSV · localStorage · vòng đời dữ liệu |
| Công cụ | Git & GitHub · thư viện & CDN · API |
| Kỹ năng | Viết prompt · chia nhỏ yêu cầu · debug · kiểm thử |
| Phát hành | GitHub Pages · robots.txt · .gitignore |

---

## 🐛 Vài lỗi đáng nhớ đã tự tìm ra và sửa

| Lỗi | Nguyên nhân |
|---|---|
| Ảnh không hiện | Tên file có dấu cách |
| Chữ tiếng Việt bị vỡ | Font Caveat không hỗ trợ tiếng Việt |
| Video bung toàn màn hình trên iPhone | Thiếu thuộc tính `playsinline` |
| Pháo hoa không kêu trên điện thoại | iPhone chặn âm thanh tạo bằng code |
| Sửa rồi mà web không đổi | Bộ nhớ đệm (cache) |
| Phễu tô đỏ nhiều bước cùng lúc | Vừa duyệt vừa vẽ — phải tách hai lượt |
| CAC hiện $0 khi chưa có đơn | Thiếu xử lý trường hợp chia cho 0 |

---

*Repo này là nhật ký học tập. Code có thể chưa hoàn hảo, nhưng mỗi dòng đều được
hiểu và kiểm thử trước khi giữ lại.*
