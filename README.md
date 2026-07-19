Cách đẩy tốc độ chạy nhanh gấp nhiều lần:Bạn hãy tắt tool đi (Ctrl + C) rồi mở Command Prompt (cmd) lên, di chuyển vào thư mục tool và chạy lệnh tăng luồng + giảm thời gian chờ xuống.  Ví dụ lệnh chạy tối ưu:DOSpython proxy_scraper.py --threads 500 --timeout 4 --max-ms 3000
Giải thích lệnh:--threads 500: Tăng lên 500 luồng chạy cùng lúc (máy của bạn dư sức cân mức này).  --timeout 4: Quá 4 giây không kết nối được là bỏ qua luôn, không bắt tool phải đợi tận 10 giây.  --max-ms 3000: Chỉ lọc lấy những proxy có độ trễ (ping) dưới 3 giây để đảm bảo chất lượng.  





python proxy_scraper.py --threads 500 --timeout 4 --max-ms 3000
