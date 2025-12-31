# TikiNow

Dự án phân tích dữ liệu cho TikiNow, tập trung vào chuẩn bị dữ liệu và tạo dashboard báo cáo.

## Mô tả

Dự án này sử dụng Python và Jupyter Notebook để xử lý và phân tích dữ liệu. Bao gồm các bước chuẩn bị dữ liệu từ file thô, tạo ra dữ liệu sạch, và xây dựng dashboard với Power BI.

## Cài đặt

1. Clone repository này.
2. Tạo virtual environment:
   ```
   python -m venv .venv
   ```
3. Kích hoạt virtual environment:
   - Windows: `.venv\Scripts\activate`
   - Linux/Mac: `source .venv/bin/activate`
4. Cài đặt dependencies:
   ```
   pip install -r requirements.txt
   ```

## Sử dụng

1. Mở Jupyter Notebook:
   ```
   jupyter notebook
   ```
2. Chạy file `data_preparation.ipynb` để chuẩn bị dữ liệu.
3. Xem dashboard trong thư mục `dashboard/` với file Power BI (.pbix) và các hình ảnh phân tích.

## Cấu trúc dự án

- `data_preparation.ipynb`: Notebook chuẩn bị và phân tích dữ liệu.
- `requirements.txt`: Danh sách dependencies Python.
- `dashboard/`: Chứa dashboard Power BI và hình ảnh phân tích.
- `data/`: Thư mục dữ liệu.
  - `raw/`: Dữ liệu thô.
  - `clean/`: Dữ liệu đã xử lý.

## Tác giả

[Nguyen Ngoc Phuong Vy]
