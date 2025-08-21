# Snake.io style (PyScript + HTML5 Canvas)

Trò chơi snake.io chạy trực tiếp trên trình duyệt bằng PyScript (Python trong WebAssembly) và HTML5 Canvas. Không cần build.

## Chơi thử (local)
- Mở terminal tại thư mục repo và chạy: `python -m http.server`
- Mở trình duyệt: http://localhost:8000
- Nếu mở file trực tiếp bằng `file://` có thể không chạy do CSP/CORS của trình duyệt.

## Điều khiển
- Chuột để lái (nhấn `M` để chuyển sang phím mũi tên trái/phải).
- Space: tăng tốc (boost).
- `P`: tạm dừng.
- `R`: chơi lại.

## Deploy GitHub Pages
1. Merge PR này vào nhánh mặc định (main).
2. Vào Settings → Pages.
3. "Build and deployment" → Source: chọn "Deploy from a branch".
4. Branch: `main`, Folder: `/ (root)`. Bấm Save.
5. Đợi vài chục giây, vào: `https://ryando-code.github.io/snake-io/`.

> Lưu ý: PyScript tải từ CDN `https://pyscript.net/` nên cần Internet để chạy.

## Tùy chọn
- Nếu muốn deploy qua GitHub Actions, tạo workflow để build (không cần cho dự án tĩnh này).
- Có thể thêm `.nojekyll` nếu bạn có thư mục bắt đầu bằng `_` để tránh bị Jekyll bỏ qua (không bắt buộc ở đây).