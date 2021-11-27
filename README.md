Mọi người đẩy bài tập lên git:
vì làm site giống nhau nên mọi người đặt tên file html/css theo cú pháp [tên file]_[tên riêng] viết liền không dấu: VD index_thai.html, index_thai.css
Cách để đẩy lên git bằng terminal trong VS code:
b1: chọn Terminal -> new terminal
b2: gõ lần lượt các lệnh sau:
1. git init
2. git add .
3. git commit -m "điền message vào trong dấu nháy kép này"
4. git branch -M main
5. git remote add origin https://github.com/thainh92/semester2-template.git
6. git push -u origin main
