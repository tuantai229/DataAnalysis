# Phân tích bộ dữ liệu City Population Density

Bộ dữ liệu `city_population_density.csv` chứa thông tin về dân số, diện tích, và mật độ dân số của các thành phố lớn trên thế giới.

## Các cột trong bộ dữ liệu:

- `Rank`: Thứ hạng của thành phố theo mật độ dân số
- `City`: Tên thành phố
- `Population`: Dân số
- `Area KM2`: Diện tích tính theo kilômét vuông
- `Area M2`: Diện tích tính theo dặm vuông
- `Density KM2`: Mật độ dân số tính theo người/kilômét vuông
- `Density M2`: Mật độ dân số tính theo người/dặm vuông
- `Country`: Quốc gia của thành phố
- `Year`: Năm của dữ liệu

## Các phân tích đã thực hiện:

### Phân tích toàn diện (`city_population_analysis.ipynb`)
- Xếp hạng các thành phố theo dân số (lớn nhất và nhỏ nhất)
- Phân tích phân bố thành phố theo quốc gia
- Tìm ra các thành phố có cả dân số và diện tích lớn
- Thống kê mật độ dân số theo quốc gia
- Phân tích thành phố có dân số lớn nhất trong mỗi quốc gia

## Phát hiện chính:

- Phân bố dân số thể hiện sự chênh lệch lớn giữa các thành phố.
- Các quốc gia có dân số lớn như Ấn Độ và Trung Quốc có nhiều thành phố trong danh sách.
- Mật độ dân số thay đổi đáng kể giữa các quốc gia, phản ánh sự khác biệt về mô hình đô thị hóa.