# Tra cứu đơn hàng

Static mobile-first site for GitHub Pages. Data is stored in `data/orders.json`.

## Deploy
1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, `app.js`, and `data/orders.json`.
3. Settings → Pages → Deploy from branch → `main` / root.
4. Open the generated GitHub Pages URL.

## Bổ sung mã vận đơn / phí ship
Trong `data/orders.json`, mỗi record có:
- `tracking`: mã vận đơn
- `shippingFee`: phí ship (số nguyên, đơn vị VND)

Đang để trống/null để chờ cập nhật.

> Lưu ý: GitHub Pages là public. Nếu đây là dữ liệu khách hàng thật, toàn bộ JSON có thể được người khác tải xuống. Khi cần bảo mật, nên chuyển phần tra cứu sang backend/API.
