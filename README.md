# exileapi Bot — bản phát hành

Repo này **chỉ chứa file phát hành** (AppImage). Mã nguồn: `nlttien/exileapi-rebuild` (riêng tư).

## Cài trên máy mới (Linux Nobara / Fedora)
1. Vào **Releases** → tải `exileapi-Bot-<commit>-x86_64.AppImage` mới nhất.
2. `chmod +x exileapi-Bot-*.AppImage` → bấm đúp (hoặc `./exileapi-Bot-*.AppImage`).
3. Lần đầu: tự cài gói thiếu (hỏi mật khẩu), thêm nhóm `input` (→ đăng xuất / đăng nhập lại rồi mở lại),
   tạo biểu tượng **exileapi Bot**, mở overlay.
4. Điều khiển: **F3** bật bot boss · **End** dừng khẩn cấp · web `http://127.0.0.1:8790` (nút *Cài đặt đánh*).

Code chép ra `~/.local/share/exileapi/`; dữ liệu `tools/data/` giữ nguyên khi mở bản mới.

## Làm tay
- TẮT game → vá PoeRedux: `camera` + `black-screen`.
- Game đúng bản **3.29.3** (khác bản → bot đọc sai bộ nhớ).
- Màn hình khác 1920×1080 → `python3 ~/.local/share/exileapi/tools/walk.py calib`.
- Bot mua: đăng nhập lại trang trade.

Kiểm tải đúng file: so `sha256sum` với file `.sha256` trong release.
