# ds-netflix-analysis
Final project for Data Science course - Analyzing Netflix dataset.

Một mô tả ngắn gọn về dự án của bạn (ví dụ: "Dự án phân tích dữ liệu sử dụng Python và các thư viện khoa học dữ liệu phổ biến").

## Môi trường Phát triển

Dự án này sử dụng môi trường Conda có tên là `min_ds-env`.

### Cài đặt

Để thiết lập môi trường phát triển, hãy làm theo các bước sau:

1.  **Cài đặt Miniconda hoặc Anaconda:** Nếu bạn chưa có, hãy tải xuống và cài đặt [Miniconda](https://docs.conda.io/en/latest/miniconda.html) hoặc [Anaconda](https://www.anaconda.com/products/distribution).

2.  **Tạo môi trường từ file `environment.yml`:**
    Mở terminal (hoặc Anaconda Prompt trên Windows) và chạy lệnh sau trong thư mục chứa file `environment.yml`:

    ```bash
    conda env create -f environment.yml
    ```

3.  **Kích hoạt môi trường:**

    ```bash
    conda activate min_ds-env
    ```

### Các Thư viện Chính

Môi trường này bao gồm các thư viện phổ biến cho khoa học dữ liệu và phát triển Python, bao gồm:

* **Khoa học Dữ liệu & Phân tích:** `pandas`, `numpy`, `scikit-learn`, `scipy`, `statsmodels`
* **Trực quan hóa:** `matplotlib`, `seaborn`, `plotly`
* **Jupyter & Interactive:** `jupyterlab`, `notebook`, `ipykernel`, `ipywidgets`
* **Tiện ích & Khác:** `requests`, `beautifulsoup4`, `black` (code formatting), `selenium` (web automation)

### Cập nhật Môi trường

Nếu bạn thay đổi file `environment.yml`, hãy cập nhật môi trường bằng lệnh:

```bash
conda env update -f environment.yml --prune
```
### Cập nhật Môi trường
(Thêm hướng dẫn cách chạy code, ví dụ: "Chạy jupyter lab để mở các notebook phân tích.")

### Tác giả
[Tên của bạn]

### Giấy phép
(Thêm thông tin giấy phép nếu cần, ví dụ: MIT License)