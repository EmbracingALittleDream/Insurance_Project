# Medical Insurance Cost Analysis

## Objective
Dự báo về số tiền bồi thường nhận được từ công ty bảo hiểm dựa vào các thuộc tính (biến) có sẵn.

Khám phá chiếc hộp đen của thuật toán hồi quy tuyến tính bội dưới góc nhin toán học.
## Dataset
- Source: https://www.kaggle.com/datasets/mirichoi0218/insurance?utm_source=chatgpt.com
- Number of rows/columns: 1338 quan trắc - 7 biến
- Variables description
 1. Tuổi (age): tuổi của người được bảo hiểm (Dữ liệu số)
 2. Giới tính (sex): giới tính của người được bảo hiểm (Dữ liệu phận loại: Nam, nữ)
 3. Body mass index (bmi): chỉ số bmi của người được bảo hiểm (Dữ liệu số)
 4. Số con (children): số con của người được bảo hiểm (Dữ liệu số)
 5. Hút thuốc (smoker): cho biết người được bảo hiểm có hút thuốc hay không (Dữ liệu phân loại: Có, Không)
 6. Khu vực (region): khu vực sinh sống của người được bảo hiểm (Dữ liệu phân loại: Đông Bắc, Tây Bắc, Đông Nam , Tây Nam)
 7. Chi phí bảo hiểm (charges): chi phí y tế mà công ty bảo hiểm chi trả cho người được bảo hiểm (Dữ liệu số)


## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis Process
1. Đọc dữ liệu
2. Trực quan hóa dữ liệu
3. Thống kê mô tả
4. Mã hóa các biến định tính
5. Chia dataset thành tập train và tập test
6. Tính các ước lượng cho hệ số hồi quy (estimated coefficients)
7. Tính ước lượng phương sai cho sai số
8. Tính các thống kê t (student) cho phép kiểm định
9. Tính hệ số xác định $R^2$
10. Tính hệ số $R^2$ hiệu chỉnh
11. Tính giá trị dự báo từ đường thẳng hồi quy ước lượng
12. Tính khoảng tin cậy 95% cho giá trị dự báo
13. Kiểm tra các giả định về sai số của mô hình

## Project Files
- report: [Markdown Report](final_Project_complete.ipynb)
- dataset: [insurance.csv](dataset/insurance.csv)
