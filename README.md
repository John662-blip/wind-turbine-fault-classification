# 🌪️ Phân Loại Lỗi Tuabin Gió bằng SVM

## 📌 Giới thiệu

Dự án này sử dụng mô hình **Support Vector Machine (SVM)** để phân loại các lỗi xảy ra trong **tuabin gió**, dựa trên dữ liệu cảm biến dạng **chuỗi thời gian (time series)**.  
Mục tiêu là xây dựng một hệ thống cảnh báo sớm giúp phát hiện sự cố và phân loại lỗi để phục vụ bảo trì dự đoán.

---

## 🧠 Phương pháp

### ✅ 1. Tiền xử lý dữ liệu
- Thu thập dữ liệu cảm biến theo thời gian (rung động).
- Thực hiện các bước tiền xử lý:
  - Trích xuất đặc trưng (trên miền thời gian và miền tần sô)
  - chuẩn hóa 

### ⚙️ 2. Mô hình SVM
- Sử dụng RBF-SVM để phân loại nhiều lớp (hoạt động bình thường và các loại lỗi khác nhau).

### 📉 3. Đánh giá mô hình
- **Độ chính xác (Accuracy)** : 0.9821
- **Ma trận nhầm lẫn (Confusion Matrix)**
![image](https://github.com/user-attachments/assets/644358a1-c235-42a3-8b86-5444af534a92)


