# Phân tích bộ dữ liệu Student Performance

Bộ dữ liệu `student_performance.csv` chứa thông tin về điểm số của học sinh trong ba môn học (toán, đọc, viết) cùng với các thông tin nhân khẩu học và hoàn cảnh gia đình.

## Các cột trong bộ dữ liệu:

- `gender`: Giới tính của học sinh
- `race/ethnicity`: Nhóm chủng tộc/dân tộc của học sinh
- `parental level of education`: Trình độ học vấn cao nhất của cha mẹ
- `lunch`: Loại bữa ăn trưa (standard hoặc free/reduced)
- `test preparation course`: Tham gia khóa chuẩn bị kiểm tra (completed hoặc none)
- `math score`: Điểm số môn toán
- `reading score`: Điểm số môn đọc
- `writing score`: Điểm số môn viết

## Các phân tích đã thực hiện:

### Phân tích toàn diện (`student_performance_analysis.ipynb`)
- Task 1: Xác định 10 học sinh có điểm toán và điểm đọc đều nằm trong Top 100
- Task 2: Liệt kê 20 học sinh có điểm viết cao nhất của mỗi nhóm dân tộc/chủng tộc
- Task 3: Thống kê số lượng học sinh của nhóm A theo trình độ học vấn của cha mẹ
- Task 4: Phân tích mối quan hệ giữa trình độ học vấn của cha mẹ và điểm số của học sinh
- Task 5: Đánh giá tác động của loại bữa ăn trưa đến điểm số trung bình
- Task 6: Xác định 10 học sinh có điểm toán cao nhất của mỗi nhóm dân tộc/chủng tộc
- Task 7: Phân tích hiệu quả của việc tham gia khóa chuẩn bị kiểm tra đối với điểm số

## Phát hiện chính:

- Mối tương quan giữa các môn học: Có mối tương quan mạnh giữa điểm số các môn học, đặc biệt giữa đọc và viết.
- Ảnh hưởng của yếu tố gia đình: Trình độ học vấn của cha mẹ có tác động tích cực đến điểm số của học sinh.
- Tác động của hoàn cảnh kinh tế: Học sinh có bữa ăn tiêu chuẩn thường có điểm số cao hơn.
- Hiệu quả của chuẩn bị kiểm tra: Việc tham gia khóa chuẩn bị kiểm tra giúp cải thiện đáng kể điểm số.
- Khác biệt giữa các nhóm dân tộc/chủng tộc: Có sự khác biệt về điểm số giữa các nhóm.