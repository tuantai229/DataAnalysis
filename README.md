# Data Science & AI Analytics Portfolio

## Giới thiệu

Đây là portfolio phân tích dữ liệu toàn diện nhằm khám phá các xu hướng và thông tin chi tiết trong lĩnh vực Data Science, Machine Learning và AI. Dự án sử dụng các công cụ phân tích dữ liệu hiện đại trong Python để khám phá nhiều bộ dữ liệu khác nhau.

## Bộ dữ liệu hiện có

### 1. Data Science Salaries

Phân tích chi tiết về xu hướng lương trong lĩnh vực Data Science, bao gồm:
- Phân tích theo chức danh công việc
- Phân tích theo vị trí địa lý
- Phân tích theo kinh nghiệm và quy mô công ty

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
│   │   └── ds_salaries.csv       # File dữ liệu gốc
│   └── ...                       # Các bộ dữ liệu khác (sẽ thêm sau)
│
└── notebooks/                    # Jupyter notebooks cho phân tích khám phá
    ├── ds_salaries/              # Phân tích dữ liệu lương Data Science
    │   ├── 01_ds_salaries_exploration.ipynb      # Khám phá dữ liệu
    │   ├── 02_salary_by_job_title.ipynb          # Phân tích theo chức danh
    │   └── 03_salary_by_geography.ipynb          # Phân tích theo quốc gia/vị trí
    └── ...                       # Các phân tích cho bộ dữ liệu khác (sẽ thêm sau)
```

## Phân tích bộ dữ liệu ds_salaries

Bộ dữ liệu `ds_salaries.csv` chứa thông tin về mức lương của các chuyên gia trong lĩnh vực Data Science từ nhiều quốc gia, công ty và vị trí khác nhau.

### Các cột trong bộ dữ liệu:

- `work_year`: Năm làm việc
- `experience_level`: Mức kinh nghiệm (EN=Entry-level, MI=Mid-level, SE=Senior, EX=Executive)
- `employment_type`: Loại hình làm việc (FT=Full-time, PT=Part-time, CT=Contract, FL=Freelance)
- `job_title`: Chức danh công việc
- `salary`: Mức lương (trong đơn vị tiền tệ gốc)
- `salary_currency`: Đơn vị tiền tệ của mức lương
- `salary_in_usd`: Mức lương quy đổi sang USD
- `employee_residence`: Quốc gia cư trú của nhân viên
- `remote_ratio`: Tỷ lệ làm việc từ xa (0=Tại văn phòng, 50=Hybrid, 100=Remote)
- `company_location`: Quốc gia của công ty
- `company_size`: Quy mô công ty (S=Small, M=Medium, L=Large)

### Các phân tích đã thực hiện:

#### 1. Khám phá dữ liệu (`01_ds_salaries_exploration.ipynb`)
- Phân tích thống kê mô tả của dữ liệu
- Khám phá phân bố mức lương 
- Phân tích ban đầu về mối quan hệ giữa các biến
- Trực quan hóa các xu hướng chính trong dữ liệu

#### 2. Phân tích theo chức danh công việc (`02_salary_by_job_title.ipynb`)
- Xếp hạng các chức danh công việc theo mức lương trung bình
- So sánh mức lương giữa các mức kinh nghiệm khác nhau cho cùng chức danh
- Phân tích khoảng cách thu nhập giữa các mức kinh nghiệm
- Tìm ra các chức danh có mức lương cao nhất/thấp nhất ở các nhóm cụ thể

#### 3. Phân tích theo quốc gia và vị trí địa lý (`03_salary_by_geography.ipynb`)
- So sánh mức lương trung bình giữa các quốc gia
- Phân tích chênh lệch lương giữa nhân sự trong nước và nước ngoài
- Đánh giá tác động của quy mô công ty đến mức lương
- Phân tích dòng chảy nhân lực giữa các khu vực địa lý

## Phát hiện chính

Một số phát hiện quan trọng từ phân tích dữ liệu bao gồm:

1. **Theo chức danh công việc**:
   - Các vị trí liên quan đến AI, ML và Data Science có xu hướng được trả lương cao hơn.
   - Các vị trí quản lý (như Director, VP) thường có mức lương cao nhất.
   - Một số chức danh có sự chênh lệch lớn về mức lương giữa các mức kinh nghiệm.

2. **Theo địa lý**:
   - Bắc Mỹ, đặc biệt là Hoa Kỳ, có mức lương trung bình cao nhất cho các vị trí Data Science.
   - Có sự khác biệt đáng kể về mức lương giữa các khu vực địa lý.
   - Quy mô công ty tỷ lệ thuận với mức lương ở hầu hết các quốc gia.

3. **Theo kinh nghiệm và quy mô công ty**:
   - Mức lương tăng theo cấp bậc kinh nghiệm trong hầu hết các trường hợp.
   - Các công ty lớn thường trả lương cao hơn cho cùng một vị trí và mức kinh nghiệm.
   - Tỷ lệ làm việc từ xa có ảnh hưởng đến mức lương ở một số quốc gia.

## Công nghệ sử dụng

- **Python**: Ngôn ngữ lập trình chính
- **Pandas & NumPy**: Xử lý và phân tích dữ liệu
- **Matplotlib & Seaborn**: Trực quan hóa dữ liệu cơ bản
- **Plotly**: Tạo biểu đồ tương tác
- **SciPy**: Phân tích thống kê
- **Jupyter Notebook**: Môi trường phát triển

## Cài đặt và sử dụng

1. Clone repository:
```
git clone https://github.com/username/data-science-portfolio.git
cd data-science-portfolio
```

2. Tạo và kích hoạt môi trường conda:
```
conda create -n data_analysis python=3.10
conda activate data_analysis
```

3. Cài đặt các thư viện cần thiết:
```
pip install -r requirements.txt
```

4. Đăng ký môi trường với Jupyter:
```
python -m ipykernel install --user --name=data_analysis
```

5. Chạy Jupyter Notebook:
```
jupyter notebook
```

6. Mở các notebook trong thư mục `notebooks/` để xem phân tích.

## Phát triển trong tương lai

Dự án sẽ tiếp tục phát triển với:
- Thêm các bộ dữ liệu mới về các lĩnh vực khác nhau của Data Science, AI và ML
- Phân tích chuyên sâu hơn về các lĩnh vực cụ thể như NLP, Computer Vision, v.v.
- Tạo các mô hình dự báo dựa trên dữ liệu đã phân tích
- Phát triển các biểu đồ và dashboard tương tác
- Phân tích các xu hướng theo thời gian khi có dữ liệu mới

## Đóng góp

Mọi đóng góp đều được hoan nghênh! Vui lòng tạo issue hoặc pull request nếu bạn muốn đóng góp vào dự án.

## Giấy phép

Dự án này được cấp phép theo giấy phép MIT.