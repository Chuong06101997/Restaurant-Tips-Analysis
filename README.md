# Restaurant-Tips-Analysis

## Giới thiệu dự án
Dự án này nhằm phân tích hành vi tip của khách hàng tại một nhà hàng dựa trên dữ liệu lịch sử các hóa đơn. Qua đó, giúp hiểu rõ các yếu tố ảnh hưởng đến tiền tip như thời gian, ngày trong tuần, giới tính, thói quen hút thuốc, v.v.

## Nguồn sử dụng
- Nguồn dữ liệu:
  Tips Dataset on GitHub <https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv>
- Mô tả dữ liệu:
  Dữ liệu bao gồm các thông tin sau:
  id => Mã số dòng dữ liệu
  total_bill => 	Tổng giá trị hóa đơn (USD)
  tip => Tiền tip mà khách để lại (USD)
  sex => 	Giới tính khách hàng (Male / Female)
  smoker => Khách có hút thuốc không (Yes / No)
  day => Ngày trong tuần (Thur, Fri, Sat, Sun)
  time => Thời điểm ăn (Lunch / Dinner)
  size => Số lượng người trong bàn ăn
- Cách truy cập hoặc tải dữ liệu:
 ```
  import pandas as pd
  df = pd.read_csv('https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv')
```

  


