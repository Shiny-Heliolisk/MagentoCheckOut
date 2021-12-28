# MagentoCheckOut<br>
I. Các bước pull code và chạy module<br>
B1: Mở terminal, chạy : cd /var/www/html/tên project/app/code<br>
B2: Chạy trong terminal: git clone https://github.com/Shiny-Heliolisk/MagentoCheckOut<br>
B3: chạy các lệnh trong terminal: bin/magento setup:upgrade && bin/magento setup:di:compile && bin/magento c:c && bin/magento s:s:d -f<br>
B4: Hoàn thành.<br>
<br>
II.Đề bài<br>
1.	Thêm một step trang checkout để khách hàng nhập thông tin ngày giao hàng và note<br>
Ngày giao hàng require<br>
Admin có thể xem + sửa thông tin ngày giao hàng và note ở backend ( Order detail )<br>
2.	Dùng code để trường Company là required<br>
