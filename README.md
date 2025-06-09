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
## Mục tiêu phân tích:
  - So sánh người hút thuốc vs không hút
  - So sánh ngày cuối tuần vs ngày thường
  - So sánh nam vs nữ
  - So sánh bữa trưa vs bữa tối
So sánh các thống kê (max, min, mean, median) của tiền tip theo các yếu tố như người có hút thuốc, giới tính, thời gian dùng bữa, v.v."

## Kết quả chính:
- Dinner có xu hướng tip cao hơn lunch
- Cuối tuần (thứ Bảy và Chủ Nhật) thường có tip cao hơn so với các ngày thường
- Người không hút thuốc tip nhiều hơn người hút thuốc, với mức tip trung bình và trung vị đều cao hơn.
- Tip trung bình và trung vị của nam và nữ không chênh lệch quá nhiều, nhưng nam có phân phối trải rộng hơn
  


