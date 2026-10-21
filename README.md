# Portfolio & CV Website — Trần Hải Quân

Trang web CV cá nhân & Portfolio kỹ thuật số của **Trần Hải Quân (Robotics AI Engineer & Researcher)**, được xây dựng dựa trên ý tưởng thiết kế của `ngtoanrob.github.io` (Start Bootstrap Resume template) và nâng cấp với bộ nhận diện kỹ thuật chuyên nghiệp **Vin Robotics Navy Theme** (`#0B2C5B`, `#1877F2`, `#F5F7FA`).

---

## 🌟 Điểm nổi bật
- **Bố cục chuẩn mực:** Thanh điều hướng cố định bên trái (Sidebar Navigation) với ảnh đại diện, menu cuộn mượt (ScrollSpy) và tự động co giãn tương thích hoàn hảo trên Mobile/Tablet/Desktop.
- **Tích hợp toàn diện thông tin:**
  - **About:** Thông tin liên hệ, tóm tắt định hướng nghiên cứu, nút tải trực tiếp file `Tran_Hai_Quan_CV.pdf`.
  - **Experience (Kinh nghiệm thực tập Vin Robotics):** Báo cáo chi tiết quá trình nghiên cứu, triển khai mô hình học tăng cường/học bắt chước (ACT + CVAE) trên robot 16 bậc tự do OpenArm, tối ưu hóa suy luận thời gian thực với NVIDIA TensorRT FP16 (24.6ms / 40.6Hz), độ chính xác 87.5%.
  - **Featured Projects:** OpenArm ACT Training, GreenBin AI (4-Tier Multimodal Vision Routing), PIEUPIEU Review Care (RAG + xlm-roberta ONNX), E-Commerce Customer Sentiment Analyzer, Track 3 HITL Guardrails.
  - **Skills & Tools:** Phân loại rõ ràng chuyên môn sâu (Embodied AI, Model Optimization, Hybrid RAG, Full-Stack AI) cùng hệ thống biểu tượng SVG chất lượng cao (Iconify & FontAwesome).
  - **Research & Technical Report:** Trích xuất chuyên sâu báo cáo khoa học với công thức toán học KaTeX render sắc nét và bảng so sánh Vision Backbones (ResNet-18, ResNet-50, EfficientNet, DINOv2).
  - **Education & Awards:** Đại học Thăng Long (GPA 3.5/4.0), Olympic AI 2026, Kaggle Landmark Transformer.

---

## 📁 Cấu trúc thư mục

```
tran-hai-quan-cv-portfolio/
├── index.html                   # Trang chủ portfolio chính
├── README.md                    # Hướng dẫn sử dụng & triển khai
└── assets/
    ├── css/
    │   └── styles.css           # Bảng màu Vin Robotics Navy & Custom UI
    ├── js/
    │   └── scripts.js           # ScrollSpy, KaTeX auto-render & mobile toggle
    ├── img/
    │   └── avatar.jpg           # Ảnh chân dung đại diện
    └── pdf/
        └── Tran_Hai_Quan_CV.pdf # Bản mềm CV để nhà tuyển dụng tải về
```

---

## 🚀 Hướng dẫn chạy thử nghiệm tại máy cục bộ (Local Preview)

Mở terminal trong thư mục này và gõ:

```bash
python3 -m http.server 8080
```

Sau đó mở trình duyệt và truy cập: [http://localhost:8080](http://localhost:8080)

---

## 🌐 Hướng dẫn Đưa lên GitHub Pages (Miễn phí vĩnh viễn)

Tương tự như trang `ngtoanrob.github.io` của mentor Nguyễn Toàn, bạn có thể triển khai thành tên miền cá nhân `https://pieupieu16.github.io`:

1. Truy cập [GitHub](https://github.com/new) và tạo một Repository mới có tên chính xác là:
   ```
   pieupieu16.github.io
   ```
   *(Để chế độ Public)*

2. Trong thư mục `tran-hai-quan-cv-portfolio`, thực hiện đẩy toàn bộ code lên:
   ```bash
   git init
   git add .
   git commit -m "feat: initial commit for Tran Hai Quan portfolio website"
   git branch -M main
   git remote add origin https://github.com/pieupieu16/pieupieu16.github.io.git
   git push -u origin main
   ```

3. Sau 1-2 phút, trang web của bạn sẽ chính thức hoạt động tại địa chỉ:
   👉 **`https://pieupieu16.github.io`**
