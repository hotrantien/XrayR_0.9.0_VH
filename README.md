# XrayR 0.9.0 Tiếng Việt

Đây là phiên bản XrayR 0.9.0 đã được dịch sang tiếng Việt.

## Cài đặt

Để cài đặt, hãy chạy lệnh sau trong terminal:

```bash
wget -N https://raw.githubusercontent.com/hotrantien/XrayR_0.9.0_VH/main/install.sh && bash install.sh
```
```
nano /etc/XrayR/config.yml
```
Dòng PanelType : Tên kiểu web (ví dụ V2board, SSpanel,… chữ đầu viết hoa)

Dòng ApiHost : Địa chỉ web muốn liên kết (ví dụ https://domain.com/)

Dòng ApiKey : key của web (lấy trên web admin / cấu hình hệ thống / máy chủ chìa khóa giao tiếp) (phần này các bạn qua và tự đặt APIKey trên V2board admin nhé!)

Dòng NodeID : ID server (lấy trên web admin / Quản lý nút / tên ID nút)

Dòng certdomain : IP của server muốn đưa lên web

Thêm dòng DisableSniffing: true giữa 2 dòng ControllerConfig: và ListenIP: 0.0.0.0 để fix lỗi zalo
