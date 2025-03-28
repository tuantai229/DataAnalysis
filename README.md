# Data Science & AI Analytics Portfolio

## Giới thiệu

Dự án phân tích dữ liệu toàn diện nhằm khám phá các xu hướng và thông tin chi tiết trong lĩnh vực Data Science, Machine Learning và AI. Dự án sử dụng các công cụ phân tích dữ liệu hiện đại trong Python để khám phá nhiều bộ dữ liệu khác nhau.

## Bộ dữ liệu hiện có

### 1. [Data Science Salaries](notebooks/ds_salaries/README.md)

Phân tích chi tiết về xu hướng lương trong lĩnh vực Data Science, bao gồm:
- Phân tích theo chức danh công việc
- Phân tích theo vị trí địa lý
- Phân tích theo kinh nghiệm và quy mô công ty

### 2. [City Population Density](notebooks/city_populations/README.md)

Phân tích về dân số và mật độ dân số của các thành phố trên toàn cầu, bao gồm:
- Xếp hạng thành phố theo dân số
- Thống kê về phân bố thành phố theo quốc gia
- Mối quan hệ giữa diện tích và dân số
- Phân tích mật độ dân số theo quốc gia

### 3. [Student Performance](notebooks/student_performance/README.md)

Phân tích về hiệu suất học tập của học sinh và các yếu tố ảnh hưởng, bao gồm:
- Phân tích điểm số theo các nhóm nhân khẩu học
- Tác động của trình độ học vấn của cha mẹ đến kết quả học tập
- Ảnh hưởng của hoàn cảnh kinh tế xã hội (qua bữa ăn) đến điểm số
- Hiệu quả của việc tham gia khóa chuẩn bị kiểm tra

## Cấu trúc dự án

```
DataAnalysis/
│
├── README.md                     # Tài liệu chính của dự án
├── requirements.txt              # Các thư viện Python cần thiết
├── .gitignore                    # Các file/thư mục được git bỏ qua
│
├── datasets/                     # Thư mục chứa tất cả bộ dữ liệu
│   ├── ds_salaries/              # Dữ liệu phân tích lương Data Science
│   ├── city_populations/         # Dữ liệu phân tích dân số thành phố
│   ├── student_performance/      # Dữ liệu hiệu suất học tập của học sinh
│   └── ...                       # Các bộ dữ liệu khác (sẽ thêm sau)
│
└── notebooks/                    # Jupyter notebooks cho phân tích khám phá
    ├── ds_salaries/              # Phân tích dữ liệu lương Data Science
    ├── city_populations/         # Phân tích dữ liệu dân số thành phố
    ├── student_performance/      # Phân tích hiệu suất học tập của học sinh
    └── ...                       # Các phân tích cho bộ dữ liệu khác
```

## Phát hiện chung từ các bộ dữ liệu

Một số phát hiện quan trọng từ phân tích dữ liệu bao gồm:

1. **Từ phân tích ds_salaries**:
   - Các vị trí liên quan đến AI, ML và Data Science có xu hướng được trả lương cao hơn.
   - Các vị trí quản lý thường có mức lương cao nhất.
   - Bắc Mỹ, đặc biệt là Hoa Kỳ, có mức lương trung bình cao nhất cho các vị trí Data Science.

2. **Từ phân tích city_population_density**:
   - Phân bố dân số thể hiện sự chênh lệch lớn giữa các thành phố.
   - Các quốc gia có dân số lớn như Ấn Độ và Trung Quốc có nhiều thành phố trong danh sách.
   - Mật độ dân số thay đổi đáng kể giữa các quốc gia, phản ánh sự khác biệt về mô hình đô thị hóa.

3. **Từ phân tích student_performance**:
   - Nền tảng gia đình và hoàn cảnh kinh tế xã hội có tác động đáng kể đến kết quả học tập.
   - Can thiệp giáo dục như khóa chuẩn bị kiểm tra có thể mang lại hiệu quả tích cực.
   - Kết quả học tập có mối tương quan chặt chẽ giữa các môn học, thể hiện năng lực học tập tổng thể của học sinh.

## Công nghệ sử dụng

- **Python**: Ngôn ngữ lập trình chính
- **Pandas & NumPy**: Xử lý và phân tích dữ liệu
- **Matplotlib & Seaborn**: Trực quan hóa dữ liệu cơ bản
- **Plotly**: Tạo biểu đồ tương tác
- **SciPy**: Phân tích thống kê
- **Jupyter Notebook**: Môi trường phát triển

## Cài đặt và sử dụng

1. Clone repository:
```bash
git clone https://github.com/tuantai229/DataAnalysis.git
cd DataAnalysis
```

2. Tạo và kích hoạt môi trường conda:
```bash
conda create -n data_analysis python=3.10
conda activate data_analysis
```

3. Cài đặt các thư viện cần thiết:
```bash
pip install -r requirements.txt
```

4. Đăng ký môi trường với Jupyter:
```bash
python -m ipykernel install --user --name=data_analysis
```

5. Chạy Jupyter Notebook:
```bash
jupyter notebook
```

6. Mở các notebook trong thư mục `notebooks/` để xem phân tích.

## Phát triển trong tương lai

Dự án sẽ tiếp tục phát triển với:
- Thêm các bộ dữ liệu mới về các lĩnh vực khác nhau của Data Science, AI và ML
- Phân tích chuyên sâu hơn về các lĩnh vực cụ thể như NLP, Computer Vision, v.v.
- Tạo các mô hình dự báo dựa trên dữ liệu đã phân tích
- Phát triển các biểu đồ và dashboard tương tác

## Đóng góp

Mọi đóng góp đều được hoan nghênh! Vui lòng tạo issue hoặc pull request nếu bạn muốn đóng góp vào dự án.

## Giấy phép

Dự án này được cấp phép theo giấy phép MIT.