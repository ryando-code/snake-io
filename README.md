# Snake.io style (JavaScript + HTML5 Canvas)

Trò chơi snake.io chạy trực tiếp trên trình duyệt bằng JavaScript thuần và HTML5 Canvas. Không cần PyScript hay CDN ngoài.

## Chơi thử (local)
- Mở terminal tại thư mục repo và chạy: `python -m http.server`
- Mở trình duyệt: http://localhost:8000
- Trong Codespaces: mở cổng 8000 ở chế độ Public để truy cập bên ngoài.

## Điều khiển
- Chuột để lái (nhấn `M` để chuyển sang phím mũi tên trái/phải).
- Space: tăng tốc (boost).
- `P`: tạm dừng.
- `R`: chơi lại.

## Deploy GitHub Pages
1. Merge nhánh thay đổi vào `main`.
2. Vào Settings → Pages của repository.
3. Build and deployment → Source: chọn "Deploy from a branch".
4. Branch: `main`, Folder: `/ (root)` → Save.
5. Đợi 30–120 giây, mở: `https://ryando-code.github.io/snake-io/`.

## Ghi chú
- Mặc định canvas tự scale theo DPI để hình ảnh sắc nét.
- Không phụ thuộc mạng/CDN nên chạy offline được khi mở qua HTTP (không khuyến nghị mở trực tiếp file bằng `file://`).