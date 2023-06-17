
# 📌 Lời chào (Vietnamese Version)

**RDP Github Actions** phiên bản hình ảnh ***Windows*** gốc bởi **Github, Azure, Google Cloud Platform.** Vui lòng không sao chép và chỉnh sửa repo này.

**Vps Github Actions này được tạo bởi Rinne, vui lòng không sao chép và chỉnh sửa repo này.**

* **Phiên bản gốc: 
https://github.com/Rinne-Audio-Support-for-User/Debug-with-RDP-Tieng-Viet**

## 😺 Giới thiệu về Windows 2019, 2022, Ubuntu for Fansub Beta

**🥰 Windows, Ubuntu Github Actions Fansub Edition Beta là phiên bản RDP Windows, Ubuntu được cài sẵn các ứng dụng phần mềm và cài đặt sẵn tương thích cho các Fansub được thử nghiệm trước khi đưa vào bản chính thức của repo
(repo này không phải do Github tạo ra và không tuân thủ đúng chính sách điều khoản nên vui lòng không sử dung nó để đào coin.)**

**VPS này duy trì hoạt động trong bao lâu?**<br>

* **Vps** này vẫn hoạt động trong tối đa 6 giờ.<br>

**Cấu hình của VPS?**

* **Cấu hình mặc định của vps là:**
* ***RAM:*** 7GB (CHÍNH XÁC LÀ 6.8GB) cho Ubuntu, Windows
* ***BỘ NHỚ:*** 255GB cho Windows
* ***BỘ NHỚ:*** Còn lại (?) cho Ubuntu

## 🪟 Cách dùng file Windows Server 2019 - Microsoft Remote Desktop

Fork trang này về (nút trên cùng bên phải), Vào trang web [Ngrok](https://dashboard.ngrok.com/get-started/your-authtoken)
Đăng nhập bằng ***GitHub*** sau đó sao chép mã Token, quay lại repo này và vào Actions, chọn **Windows Server 2019** và nhấn "Run Workflow" nhập theo yêu cầu ở actions.

+ Sau khi nhấn "Run" xong, hãy load lại trang và vào cái ***Github Actions*** đang chạy, chờ vài phút bạn sẽ thấy **ip** và **username,** **mật khẩu**

# Kết nối với VPS Windows 2019

**Cách kết nối?**<br>
+ **Khi IP vps hiện ra, bỏ "tcp://" trong IP và kết nối bằng những phần mềm sau:**<br>

+ 🪟 **Windows:** Remote Desktop Connection (.exe, .msi) 

+ 🐧 **Hệ điều hành Linux**: Remmina Remote Desktop (.deb)

+ **🍎 Hệ điều hành Mac OS (Unix Like):** Microsoft Remote Desktop

+ **💚 Hệ điều hành Android (Linux Kernel):** RD CILENT (.apk)

+ **🍎 Hệ điều hành iOS (Unix Like)**: RD Cilent, Microsoft Remote Desktop (ipa)

# 🍔 Cách dùng file Ubuntu - Windows 2022 (Chrome Remote Desktop)

+ Vào Actions, chọn Ubuntu 20.04 hoặc Ubuntu 22.04

+ Đối với Windows, chọn Windows 2022

+ Nhấn "run workflow" và chép mã Debian Linux từ [Chrome Remote Desktop](https://remotedesktop.google.com/headless)

+ Đối với Windows, chép Windows Powershell (nếu chọn VPS Windows) từ [Chrome Remote Desktop](https://remotedesktop.google.com/headless)

+ Lưu ý là mã chứ không phải link

+ Dán mã đó vào phần "run workflow"

+ Tuỳ chọn: Bạn có thể vào trang web [Chocolatey Store](https://community.chocolatey.org/packages) để tìm kiếm các gói phần mềm muốn cài sẵn vào RDP, nếu gói bạn đang tìm khả dụng ở Chocolatey, hãy sao chép tên đằng sau "choco install" của mỗi gói vào file code pgnguoidung.ps1

+ Không được thoát tab Chrome Remote Desktop trong lúc chạy.
Phần mật khẩu và pin các bạn hãy nhập tuỳ ý nhé!
Sau đấy hãy nhấn run và chờ một lúc thôi nha
Sau khi chạy xong, bạn sẽ có một vps mới ở Chrome Remote Desktop, hãy kết nối và kết nối bằng PIN bạn đã nhập
Trong [Chrome Remote Desktop](https://remotedesktop.google.com/access)

+ **Windows 2022:** Sau khi chạy xong bạn sẽ thấy ngay giao diện Windows trước mắt, không tắt tab Github nếu không muốn bị hỏng VPS

+ **Ubuntu:** Sau khi chạy xong bạn sẽ cần chọn "Ubuntu" nếu được hỏi, vậy là xong rồi, chúc các bạn thành công!

## Thành quả đây!!!

**• Windows Server 2022 DataCenter:**

![Win22](https://github.com/Rinne-Audio-Support-for-User/Rdp-cho-fansub-beta/raw/main/received_1038569573789810.webp?raw=true)

**• Ubuntu 20.04:**

![Ubuntu](https://github.com/Rinne-Audio-Support-for-User/Rdp-cho-fansub-beta/raw/main/received_789599522797031.webp?raw=true)

**• Ubuntu 22.04:**

![Ubuntu22](https://github.com/Rinne-Audio-Support-for-User/Rdp-cho-fansub-beta/raw/main/received_762784862186636.webp?raw=true)

**• Windows Server 2019 DataCenter:**

![WIN2019](https://github.com/Rinne-Audio-Support-for-User/Rdp-cho-fansub-beta/raw/main/received_914498423174069.webp?raw=true)

## Giấy phép



Bản thân nội dung của dự án này được cấp phép theo [Giấy phép chưa chuyển đổi Creative Commons Attribution 3.0](https://creativecommons.org/licenses/by/3.0/) và mã nguồn cơ bản




