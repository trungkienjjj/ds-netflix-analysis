# Phân Tích Chiến Lược Nội Dung & Hệ Thống Gợi Ý trên Netflix

Đồ án cuối kỳ môn **CSC17104 – Lập trình cho Khoa học Dữ liệu**

## Giới thiệu

Dự án này phân tích bộ dữ liệu **Netflix Movies and TV Shows** (hơn 8,800 bộ phim và chương trình) để giải quyết hai mục tiêu chính:

1. **Phân tích chiến lược (Business Intelligence)**: Khám phá xu hướng sản xuất theo quốc gia, đối tượng khán giả (Rating) và tính mùa vụ trong thời điểm phát hành
2. **Ứng dụng kỹ thuật (Machine Learning)**: Xây dựng hệ thống gợi ý phim (Recommendation System) dựa trên nội dung để cá nhân hóa trải nghiệm người dùng

### Quy trình thực hiện

1. **Data Collection**: Thu thập và tìm hiểu dữ liệu
2. **Data Exploration**: Khám phá dữ liệu
3. **Preprocessing**: Làm sạch dữ liệu (xử lý missing values, chuẩn hóa ngày tháng, tách chuỗi)
4. **Data Analysis (EDA)**: Trực quan hóa để trả lời các câu hỏi chiến lược
5. **Machine Learning**: Xây dựng Content-Based Recommendation System sử dụng TF-IDF
6. **Project Summary**: Tóm tắt dự án

## Cài đặt môi trường

### Yêu cầu

- Python 3.10
- Conda (Miniconda hoặc Anaconda)

### Các bước cài đặt

1. **Cài đặt Miniconda hoặc Anaconda** (nếu chưa có):
   - Tải [Miniconda](https://docs.conda.io/en/latest/miniconda.html) hoặc [Anaconda](https://www.anaconda.com/products/distribution)

2. **Tạo môi trường từ file `environment.yml`**:
   ```bash
   conda env create -f environment.yml
   ```

3. **Kích hoạt môi trường**:
   ```bash
   conda activate recsys_env
   ```

### Các thư viện chính

- **Phân tích dữ liệu**: `pandas`, `numpy`, `scipy`
- **Machine Learning**: `scikit-learn`
- **Trực quan hóa**: `matplotlib`, `seaborn`, `wordcloud`
- **Notebook**: `ipykernel`, `ipywidgets`

## Cách chạy code

1. **Kích hoạt môi trường**:
   ```bash
   conda activate recsys_env
   ```

2. **Mở Jupyter Notebook hoặc Jupyter Lab**:
   ```bash
   jupyter notebook
   ```
   hoặc
   ```bash
   jupyter lab
   ```

3. **Mở các file notebook và bấm run all** 


## Thành viên nhóm

1. Nguyễn Trần Trung Kiên - 23122038 (Leader)
2. Vũ Nguyễn Trung Hiếu - 23122028

**Khoa Công nghệ Thông tin - ĐH KHTN, ĐHQG-HCM**