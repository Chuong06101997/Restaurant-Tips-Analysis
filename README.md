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
- Smoker vs. Non-Smoker Tipping Behavior
    - Smokers have slightly higher mean (3.01) and median (3.00) tip values than non-smokers (mean: 2.99, median: 2.74).
    - However, non-smokers show a higher frequency of tipping in the lower range (1.0–3.0), as seen in the histogram.
  ![image](https://github.com/user-attachments/assets/df8eaa2a-f821-48ce-acc1-56e640e7de0e)




