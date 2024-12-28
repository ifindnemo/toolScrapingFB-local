# Hướng dẫn chi tiết:
## Bước 1: 
- Tải source code về máy.
- `pip install -r requirements.txt` để cài các thư viện cần thiết.
## Bước 2:
- Chuẩn bị website: [demo-yumyum-scraping-tool](https://github.com/ifindnemo/demo-yumyum-scraping-tool) (Nếu tải rồi thì bỏ qua)
- Chuẩn bị trước 1 file cookies.pkl để tự động đăng nhập vào acc facebook để cào (dùng acc clone xuất ra cookie thôi nha). Source code xuất ra cookies: cookies.ipynb
- Trong file server.py, chỉnh các biến PASSWORD_SECRET (Pass để thực hiện việc cào, tránh cho người lạ dùng), MONGO_URI (URI trên MongoDB).
- Ở đây mình để sẵn database tên là 'KPW', bạn có thể tùy chỉnh theo ý thích.
## Bước 3:
- Chạy server.py. Host website (Open with Live server)
- Điền thông tin vào các ô trên website, và Start để cào :3
- Chờ đến khi cào xong sẽ in ra kết quả trên website
# Mọi bug liên hệ discord nemodev, hoặc [Toàn Nguyễn](https://www.facebook.com/toannguyen.8640/).
