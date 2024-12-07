# **Dự án Phân tích Dữ liệu Điểm thi THPT Quốc Gia (2022–2024)**

---

## 👥 **Thành viên nhóm**
Dự án được thực hiện bởi nhóm **BabyShark 🦈**:
- **Bùi Hải Đăng** - 23020356 - *(Trưởng nhóm)*
- **Vũ Nguyên Đan** - 23020351
- **Muộn Quốc Khánh Linh** - 23020393

---

## 📖 **Tổng quan dự án**
Dự án phân tích điểm thi Trung học Phổ thông Quốc gia tại Việt Nam trong các năm 2022, 2023 và 2024 nhằm:
- Tìm hiểu **xu hướng điểm thi** theo thời gian.
- Phân tích **mối tương quan giữa các môn học và khối thi**.
- Đưa ra các **đề xuất cải thiện chất lượng giáo dục** trên toàn quốc.

---

## 💡 **Lý do thực hiện**
- **Kỳ thi THPT Quốc gia** đóng vai trò quan trọng trong hệ thống giáo dục, quyết định con đường đại học của học sinh.
- **Phân tích dữ liệu điểm thi** mang lại:
  - **Nhìn nhận toàn diện**: Về xu hướng điểm số qua từng năm, từng khu vực.
  - **Hỗ trợ định hướng**: Giúp học sinh xác định khối thi phù hợp với năng lực.
  - **Cải thiện giáo dục**: Gợi ý các phương án nâng cao chất lượng giảng dạy.

---

## 🎯 **Mục tiêu dự án**
1. **Phân tích xu hướng**:
   - Số lượng thí sinh và điểm trung bình qua 3 năm (2022–2024).
   - Phổ điểm của từng môn thi và từng khối thi.
2. **Khám phá mối liên hệ**:
   - Giữa điểm thi các môn học.
   - Giữa điểm thi các khối và vùng miền.
3. **Kiểm tra giả thuyết**:
   - Ví dụ: "Càng giỏi Toán thì càng giỏi Vật lý."
4. **Đề xuất cải thiện**:
   - Tăng cường hỗ trợ giáo dục ở khu vực khó khăn.
   - Xây dựng phương án nâng cao chất lượng dạy học.

---

## 📂 **Dữ liệu sử dụng**
- **Nguồn dữ liệu**:
  - [Dữ liệu năm 2022](https://github.com/anhdung98/diem_thi_2022)
  - [Dữ liệu năm 2023](https://github.com/anhdung98/diem_thi_2023)
  - [Dữ liệu năm 2024](https://github.com/anhdung98/diem_thi_2024)
- **Nội dung**: Dữ liệu thô gồm điểm thi từng môn, khối thi, tỉnh/thành và năm thi.
- **Quy mô**: Hơn 3 triệu dòng dữ liệu.

---

## 📋 **Các bước thực hiện**
### 1️⃣ **Xử lý dữ liệu**
- Lọc và loại bỏ dữ liệu không hợp lệ.
- Kiểm tra và xử lý điểm bất thường.
- Tạo thêm cột:
  - **Tên tỉnh/thành**, **khối thi**, **năm thi**.
  - Tổng điểm các khối (A00, D01,...).

### 2️⃣ **Phân tích dữ liệu**
- **Tổng quan**:
  - Xu hướng số lượng thí sinh và điểm trung bình qua từng năm.
  - So sánh số lượng thí sinh theo vùng miền, tỉnh/thành.
- **Môn học**:
  - Điểm trung bình và phổ điểm từng môn thi.
- **Khối thi**:
  - So sánh phổ điểm và tỷ lệ chênh lệch giữa các khối thi.
- **Vùng miền**:
  - So sánh điểm trung bình, độ lệch chuẩn giữa các tỉnh.

### 3️⃣ **Kiểm tra giả thuyết**
- Phân tích tương quan giữa các môn học.
- Kiểm tra chênh lệch điểm giữa các khu vực:
  - Ví dụ: "Miền Bắc có điểm khối A00 cao hơn miền Nam."

### 4️⃣ **Trực quan hóa**
- Biểu đồ tăng trưởng số lượng thí sinh qua các năm.
- Phổ điểm từng môn và khối thi.
- Bản đồ nhiệt so sánh điểm giữa các tỉnh.

---

## 🛠️ **Công Nghệ Sử Dụng**
- **Ngôn ngữ lập trình**: Python
- **Thư viện chính**:
  - **Xử lý dữ liệu**: Pandas, NumPy
  - **Trực quan hóa**: Matplotlib, Seaborn
  - **Phân tích nâng cao**: Scikit-learn

---

## 🏆 **Kết quả dự án**
- **Xu hướng nổi bật**:
  - Điểm trung bình các môn như Sinh học, Địa lý có cải thiện nhẹ.
  - Ngoại ngữ tiếp tục là môn có điểm trung bình thấp nhất.
- **Sự chênh lệch vùng miền**:
  - Đồng bằng Sông Hồng và Đông Nam Bộ: Điểm trung bình cao nhất.
  - Tây Nguyên và miền núi phía Bắc: Cần nhiều hỗ trợ giáo dục hơn.
- **Đề xuất**:
  - Đầu tư vào giáo dục vùng khó khăn.
  - Cải thiện phương pháp giảng dạy môn Ngoại ngữ.

  ***Và còn nhiều điều nữa, vui lòng đọc file báo cáo phân tích dữ liệu để biết thêm chi tiết.***

---

## 📬 **Liên hệ**
Nếu bạn có bất kỳ câu hỏi hoặc góp ý nào, hãy liên hệ qua email của chúng tôi.
