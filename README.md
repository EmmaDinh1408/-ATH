# -ATH: Thuật Toán Phân Loại Machine Learning

## Thông tin môn học

- **Tên môn:** Machine Learning
- **Mã môn:** CO2004
- **Học kỳ:** II
- **Năm học:** 2025-2026
- **Trường:** Đại học Bách Khoa, ĐHQG-HCM

---

## Mô tả dự án

Đồ án tổng hợp của chúng em tập trung vào việc triển khai và so sánh 3 thuật toán phân loại (classification) phổ biến trong Machine Learning:

### 1. Naive Bayes
Thuật toán phân loại dựa trên xác suất có điều kiện, sử dụng định lý Bayes với giả định các đặc trưng độc lập với nhau.

### 2. Random Forest
Thuật toán học tổ hợp (ensemble learning) xây dựng nhiều cây quyết định và kết hợp kết quả từ các cây để đưa ra dự đoán cuối cùng.

### 3. Support Vector Machine (SVM)
Thuật toán tìm siêu phẳng tối ưu để phân tách các lớp dữ liệu trong không gian nhiều chiều.

---

## Cấu trúc thư mục

```
-ATH/
├── CODE/
│   ├── Naive_Bayes.ipynb          # Triển khai thuật toán Naive Bayes
│   ├── Random_Forest.ipynb       # Triển khai thuật toán Random Forest
│   └── Support_Vector_Machine.ipynb  # Triển khai thuật toán SVM
├── BÁO_CÁO.docx                  # Báo cáo tổng hợp
├── Naive Bayes.docx              # Báo cáo chi tiết Naive Bayes
├── Random Forest.docx            # Báo cáo chi tiết Random Forest
├── Nhiệm vụ.docx                 # File nhiệm vụ bài tập
└── README.md                     # File này
```

---

## Yêu cầu môi trường

Để chạy các notebook, cần cài đặt:

- Python 3.8+
- Jupyter Notebook
- Các thư viện:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

Cài đặt qua pip:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

---

## Cách chạy code

1. Mở Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Di chuyển đến thư mục `CODE/`

3. Mở file notebook mong muốn:
   - `Naive_Bayes.ipynb`
   - `Random_Forest.ipynb`
   - `Support_Vector_Machine.ipynb`

4. Chạy từng cell theo thứ tự để xem kết quả

---

## Kết quả mong đợi

Mỗi notebook sẽ trình bày:
- Giới thiệu về thuật toán
- Triển khai code
- Đánh giá hiệu suất (accuracy, precision, recall, F1-score)
- So sánh giữa các thuật toán

---

## Tài liệu tham khảo

- Scikit-learn Documentation: https://scikit-learn.org/
- Machine Learning with Python: https://www.python-course.eu/machine_learning.php