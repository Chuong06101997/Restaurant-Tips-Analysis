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
- Hành vi tip của người hút thuốc và không hút thuốc
    - Người hút thuốc có giá trị trung bình (mean: 3.01) và trung vị (median: 3.00) cao hơn một chút so với người không hút thuốc (mean: 2.99, median: 2.74).
    - Tuy nhiên, biểu đồ histogram cho thấy người không hút thuốc có tần suất tip cao hơn ở khoảng thấp (1.0–3.0).
 ![image](https://github.com/user-attachments/assets/df8eaa2a-f821-48ce-acc1-56e640e7de0e)
- So sánh theo giới tính
    - Khách hàng nam có tip trung bình cao hơn một chút so với nữ.
    - Phân phối giữa hai nhóm giới tính khá giống nhau, nhưng giá trị tip tối đa ở nam có phần cao hơn.
 ![image](https://github.com/user-attachments/assets/13b9b320-4459-4f86-993b-89ea9622fa92)
- Cuối tuần so với ngày thường
    - Tiền tip vào cuối tuần (Thứ Bảy & Chủ Nhật) thường cao hơn, với phân phối rộng hơn và giá trị trung vị lớn hơn.
    - Điều này cho thấy khách hàng có xu hướng tip hào phóng hơn vào cuối tuần.
 ![image](https://github.com/user-attachments/assets/65422ed7-8aaa-4b34-b939-3862b0a755c9)
 - Thời điểm bữa ăn (trưa so với tối)
    - Tiền tip vào buổi tối có giá trị trung bình và phân phối rộng hơn, cho thấy hành vi tip hào phóng hơn vào bữa tối.
 ![image](https://github.com/user-attachments/assets/2713a16e-ed74-4885-9e64-b4d888a6042a)
## Kết luận:
=> Tổng thể, phân tích cho thấy thời điểm dùng bữa và tình trạng hút thuốc là những yếu tố ảnh hưởng lớn nhất đến giá trị tiền tip.






