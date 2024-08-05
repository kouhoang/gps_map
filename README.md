# Ứng Dụng Bản Đồ

Ứng dụng Android này sử dụng Google Maps và Fused Location Provider để hiển thị vị trí hiện tại của người dùng trên bản đồ và vẽ một đường polyline tới một vị trí cố định. Ứng dụng cũng tính toán và hiển thị khoảng cách giữa vị trí hiện tại và vị trí cố định.

## Tính Năng

- Hiển thị vị trí hiện tại của người dùng trên Google Maps.
- Hiển thị một vị trí cố định trên bản đồ.
- Vẽ một đường polyline giữa vị trí hiện tại và vị trí cố định.
- Tính toán và hiển thị khoảng cách giữa hai vị trí khi đường polyline được nhấp.
- Điều chỉnh góc nhìn của camera để bao gồm cả hai vị trí với khoảng cách đệm.

## Yêu Cầu

- Android Studio
- Google Maps API Key
- Fused Location Provider API

## Cài Đặt

1. **Clone Repository:**

    ```bash
    git clone https://github.com/kouhoang/gps_map.git
    ```

2. **Cấu Hình API Key**

    Thay thế `api_key` trong tệp `AndroidManifest.xml` bằng Google Maps API Key của bạn.

3. **Cài Đặt Các Phụ Thuộc**

    Mở dự án trong Android Studio và đồng bộ hóa các phụ thuộc bằng cách nhấp vào "Sync Now" nếu có yêu cầu.

4. **Chạy Ứng Dụng**

    Kết nối thiết bị Android hoặc khởi chạy trình giả lập và chạy ứng dụng từ Android Studio.

## Ghi Chú

- Đảm bảo rằng bạn đã cấp quyền truy cập vị trí cho ứng dụng khi chạy lần đầu tiên.
- Nếu gặp sự cố với API Key, hãy kiểm tra cấu hình và quyền truy cập của bạn trên Google Cloud Console.

