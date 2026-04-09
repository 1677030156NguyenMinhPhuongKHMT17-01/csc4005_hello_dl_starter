# Báo cáo Thực hành Lab 0

**1. Thiết lập môi trường:**
- Tôi đã tạo môi trường ảo bằng Conda với tên `csc4005-dl` sử dụng Python 3.10.
- Kích hoạt môi trường và tiến hành cài đặt các thư viện cần thiết từ file `requirements.txt` bằng công cụ pip.

**2. Các bước chạy kiểm tra:**
- Đã thực thi script `check_env.py` để kiểm tra sự sẵn sàng của môi trường và các thư viện cốt lõi.
- Đã chạy thành công pipeline mẫu với lệnh `run_smoke_test.py`. Quá trình chạy hoàn tất và đã sinh ra đầy đủ các file theo yêu cầu: logs, checkpoint model và biểu đồ loss curve.

**3. Vấn đề gặp phải và cách xử lý:**
- **Vấn đề:** Gặp lỗi `CondaError: Run 'conda init' before 'conda activate'` khi cố gắng kích hoạt môi trường `csc4005-dl` trên PowerShell.
- **Cách xử lý:** Đã khắc phục bằng cách chạy lệnh `conda init powershell`, sau đó khởi động lại Terminal. Việc kích hoạt môi trường sau đó đã diễn ra bình thường.
