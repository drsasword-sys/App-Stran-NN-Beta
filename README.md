# App-StranNN CatGPT Beta

Repo public này chỉ dùng để phân phối bản cài đặt Windows của App-StranNN CatGPT Beta. Mã nguồn ứng dụng không được phát hành trong repo này.

## Tải bản beta

Mở trang [Releases](https://github.com/drsasword-sys/App-Stran-NN-Beta/releases) và chọn:

- `...-Setup.exe`: bộ cài Windows x64, khuyến nghị cho người dùng thông thường.
- `...-Portable.zip`: bản chạy trực tiếp, dành cho kiểm thử hoặc xử lý sự cố.
- `SHA256SUMS.txt`: mã kiểm tra tính toàn vẹn của hai file trên.

## Sử dụng lần đầu

1. Cài đặt và mở App-StranNN.
2. Vào **Tool 2 - Pipeline 3 bước** > **Nâng cao**.
3. Giữ **CatGPT Browser** làm provider và bấm **Mở đăng nhập**.
4. Đăng nhập trực tiếp vào ChatGPT trong cửa sổ Chromium. Không nhập mật khẩu ChatGPT vào App-StranNN.
5. Bấm **Kiểm tra gateway**, thử 1-2 chương trước khi chạy lô lớn.

Phiên đăng nhập được lưu cục bộ trên máy người dùng. Đây là automation thử nghiệm dựa trên ChatGPT Web, không phải OpenAI API chính thức; giao diện web hoặc bước xác minh thay đổi có thể làm tích hợp ngừng hoạt động.

## Lưu ý beta

- Chỉ hỗ trợ Windows x64.
- Chưa ký số; Windows SmartScreen có thể hiện cảnh báo nhà phát hành chưa xác định.
- Mỗi người dùng đăng nhập tài khoản ChatGPT của chính mình trên máy của họ.
- Không gửi mật khẩu, cookie hoặc thư mục profile trình duyệt cho người hỗ trợ.
- Giữ bản sao output quan trọng và chỉ xử lý nội dung bạn có quyền sử dụng.

Kiểm tra SHA-256 trong PowerShell:

```powershell
Get-FileHash .\App-StranNN-CatGPT-v8.2.0-beta.1-Windows-x64-Setup.exe -Algorithm SHA256
```
