# Time Series Forecasting Comparison
This repository contains time series forecasting experiments using financial and environmental datasets.
## Nội dung
- `LSTM.ipynb`: Notebook nghiên cứu và triển khai mô hình LSTM cho dự báo chuỗi thời gian.
- `ACB.csv`: Dữ liệu tài chính (giá cổ phiếu ACB).
- `air+quality/AirQualityUCI.csv`: Dữ liệu chất lượng không khí từ UCI.
## Yêu cầu
Sử dụng Python và cài đặt các thư viện trong `requirements.txt`:
```bash
pip install -r requirements.txt
```
## Cách chạy
1. Mở thư mục `KT` trong Jupyter Notebook hoặc JupyterLab.
2. Chạy lần lượt các cell trong `TimeSeries_Forecasting_Comparison.ipynb` để so sánh các mô hình.
3. Nếu cần tập trung vào LSTM, mở `LSTM.ipynb`.
## Ghi chú
- Notebook đã bao gồm các bước tiền xử lý, tạo đặc trưng trễ (lag features), chia tập train/test, huấn luyện và đánh giá mô hình.
- Dữ liệu môi trường có thể cần làm sạch thêm tùy thuộc vào mục đích sử dụng.
