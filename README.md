
# 🎓 Điểm thi THPT 2025

Phân tích dữ liệu điểm thi tốt nghiệp THPT năm 2025.

📌 **Nguồn dữ liệu:**  
Báo Điện tử Chính phủ  
🔗 [https://baochinhphu.vn/8h-sang-16-7-tra-cuu-diem-thi-tot-nghiep-thpt-nam-2025-tren-cong-thong-tin-dien-tu-chinh-phu](https://baochinhphu.vn/8h-sang-16-7-tra-cuu-diem-thi-tot-nghiep-thpt-nam-2025-tren-cong-thong-tin-dien-tu-chinh-phu-102250715114537341.htm)

---

## 🧠 Mục tiêu

- Phân tích phân phối điểm của học sinh tốt nghiệp THPT năm 2025 theo từng **tổ hợp khối xét tuyển đại học** (A, B, C, D...).
- Làm sạch dữ liệu gốc từ file Excel.
- Tính toán điểm tổ hợp theo quy định của Bộ GD&ĐT.
- Trực quan hóa kết quả bằng biểu đồ barplot.

---

## 📂 Cấu trúc thư mục

```bash
├── thpt_2025.ipynb            # Notebook phân tích chính
├── 20250715-ketquathi-ct2006.xlsx
├── 20250715-ketquathi-ct2018a.xlsx
├── sources/
│   └── internal/
│       ├── Ban A/
│       ├── Ban B/
│       ├── Ban C/
│       └── Ban D/
```

---

## 📊 Demo biểu đồ phân phối điểm

Dưới đây là một số ví dụ biểu đồ đã xuất ra:

| Khối        | Biểu đồ phân phối điểm |
|-------------|------------------------|
| Ban A – A00 | <img src="sources/internal/Ban%20A/A00.png" width="600px"> |
| Ban B – B00 | <img src="sources/internal/Ban%20B/B00.png" width="600px"> |
| Ban C – C00 | <img src="sources/internal/Ban%20C/C00.png" width="600px"> |
| Ban D – D01 | <img src="sources/internal/Ban%20D/D01.png" width="600px"> |
(Thư mục `sources/internal/` chứa toàn bộ biểu đồ của tất cả tổ hợp đã xử lý.)

---

## 🛠 Công nghệ sử dụng

- Python 3.8+
- Pandas, Seaborn, Matplotlib
- Jupyter Notebook

---

## 📬 Liên hệ

Được thực hiện bởi `@tunguyenn99` Xóm Data.  
👉 Tham gia tại: [facebook.com/groups/xomdata](https://facebook.com/groups/xomdata)
