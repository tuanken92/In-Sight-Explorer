
***
Mục tiêu: phát hiện lọ tiêu có nắp hay không
Ý tưởng: khi có nắp thì dòng chữ bên dưới có màu nhạt
-> thay đổi mức xám
***

1. Tìm obj hộp tiêu bằng tìm đường tròn

2. Khoanh vùng obj bằng Edge_Magnitude_Filter
tìm hiểu tại mục Filter Image Filter Tool - Settings Tab
Filters dark and light features; outputs an image where edges are represented as light pixels. This operation accounts for diagonally oriented edges, and is slower than the "Gradient Full" Operation.

Note: This operation enables the Kernel Rows and Kernel Columns parameters. The kernel must be constructed from odd integer values.


2. Binary
4. Đếm pixel sáng