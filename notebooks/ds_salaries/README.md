# Phân tích bộ dữ liệu Data Science Salaries

Bộ dữ liệu `ds_salaries.csv` chứa thông tin về mức lương của các chuyên gia trong lĩnh vực Data Science từ nhiều quốc gia, công ty và vị trí khác nhau.

## Các cột trong bộ dữ liệu:

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

## Các phân tích đã thực hiện:

### 1. Khám phá dữ liệu (`01_ds_salaries_exploration.ipynb`)
- Phân tích thống kê mô tả của dữ liệu
- Khám phá phân bố mức lương 
- Phân tích ban đầu về mối quan hệ giữa các biến
- Trực quan hóa các xu hướng chính trong dữ liệu

### 2. Phân tích theo chức danh công việc (`02_salary_by_job_title.ipynb`)
- Xếp hạng các chức danh công việc theo mức lương trung bình
- So sánh mức lương giữa các mức kinh nghiệm khác nhau cho cùng chức danh
- Phân tích khoảng cách thu nhập giữa các mức kinh nghiệm
- Tìm ra các chức danh có mức lương cao nhất/thấp nhất ở các nhóm cụ thể

### 3. Phân tích theo quốc gia và vị trí địa lý (`03_salary_by_geography.ipynb`)
- So sánh mức lương trung bình giữa các quốc gia
- Phân tích chênh lệch lương giữa nhân sự trong nước và nước ngoài
- Đánh giá tác động của quy mô công ty đến mức lương
- Phân tích dòng chảy nhân lực giữa các khu vực địa lý

## Phát hiện chính:

- Các vị trí liên quan đến AI, ML và Data Science có xu hướng được trả lương cao hơn.
- Các vị trí quản lý thường có mức lương cao nhất.
- Bắc Mỹ, đặc biệt là Hoa Kỳ, có mức lương trung bình cao nhất cho các vị trí Data Science.