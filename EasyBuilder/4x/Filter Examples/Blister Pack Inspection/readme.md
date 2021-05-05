***
Mục tiêu: phát hiện vỉ thuốc có cạnh bị móp, biến dạng
Ý tưởng: kiểm tra các cạnh của vị thuốc, nếu bt sẽ là 1 dải màu đen,
khi biến dạng, ánh sáng chiếu vào các điểm biến dạng sẽ làm thay đổi màu sắc
-> thay đổi số lượng blob
***


1. Tìm obj to (vỉ thuốc) bằng close filter -> check close filter
tìm hiểu tại mục Filter Image Filter Tool - Settings Tab
Filters out dark features smaller than the Filter Size; outputs an image with a slightly increased overall brightness level.
Note: This operation enables the Kernel Rows and Kernel Columns parameters. The kernel must be constructed from odd integer values.

2. Tại 4 cạnh của obj, đếm số blob black, thresh tìm blob manual theo từng cạnh

Nếu ok -> số lượng blob tại mỗi cạnh bằng 1