# MEN STYLE – Size Finder

Website tư vấn size quần áo nam, chạy trực tiếp trên trình duyệt bằng HTML, CSS và JavaScript.

## Chạy thử trên máy
Mở file `index.html` bằng trình duyệt.

## Đưa website lên GitHub Pages

1. Đăng nhập GitHub và tạo một repository mới (ví dụ: `men-style-size-finder`).
2. Giải nén ZIP này.
3. Tải **các file bên trong thư mục** lên repository, bảo đảm `index.html` nằm ở thư mục gốc.
4. Vào **Settings → Pages**.
5. Trong **Build and deployment**, chọn **Deploy from a branch**.
6. Chọn branch `main`, thư mục `/(root)`, rồi nhấn **Save**.
7. Đợi GitHub Pages triển khai xong. Địa chỉ website sẽ có dạng:
   `https://TEN-GITHUB.github.io/men-style-size-finder/`

Nếu repository của bạn có tên `<TEN-GITHUB>.github.io`, địa chỉ thường là:
`https://TEN-GITHUB.github.io/`

## Cấu trúc gói

- `index.html` – toàn bộ website, không cần cài thư viện hay build.
- `.nojekyll` – yêu cầu GitHub Pages không xử lý thư mục bằng Jekyll.
- `README.md` – hướng dẫn triển khai.

## Lưu ý

Đây là website tĩnh, hiện không cần backend, cơ sở dữ liệu hay API. Mọi tính toán tư vấn size được thực hiện trong trình duyệt của người truy cập.
