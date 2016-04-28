#Tìm hiểu về VMWare Workstation
##Mục lục
###[1. Giới thiệu về vmware workstation](#1)
###[1.1 Khái niệm VMWare Workstation](#1.1)
###[1.2 Các chức năng của VMWare WorkStation](#1.2)
###[1.3 Ưu điểm và nhược điểm của VMWare WorkStation] (#1.3)
###[2. Hướng dẫn cài đặt máy ảo và network trong VMWare WorkStation](#2)
###[2.1 Hướng dẫn cài đặt máy ảo](#2.1)
###[2.2 Hướng dẫn cài đặt network](#2.2)
###[3. Cài đặt hệ điều hành Window Server 2012 trên máy ảo] (#3)
###[4. Tổng kết](#4)

<a name="1"></a>
#1. Giới thiệu về vmware workstation

<a name="1.1"></a>
##1.1. Khái niệm về VMWare WorkStation:

VMware Workstation là một phần mềm ảo hóa desktop mạnh mẽ dành cho các nhà phát triển/kiểm tra phần mềm và các chuyên gia IT cần chạ y nhiều HĐH một lúc trên một máy PC. Người dùng có thể chạ y các HĐH Windows, Linux, Netware hay Solaris x86 trên các máy ảo di động mà không cần phải khởi động lại hay phân vùng ổ cứng.
VMware Workstation họat động bằng cách cho phép nhiều HĐH và các ứng dụng của chúng chạy đồng thời trên một máy duy nhất. Các HĐH và ứng dụng này được tách ra vào trong các máy ảo. Những máy ảo này cùng tồn tại trên một ph ần cứng duy nhất. Các layer ảo của VMware sẽ kết n ối các ph ần cứng vật lý với các máy ảo, do đó mỗi máy ảo sẽ có CPU, bộ nhớ, các ổ đĩa, thiết b ị nhập/xuất riêng.

<a name="1.2"></a>
##1.2. Các chức năng của VMWare WorkStation:

<ul>
<li>Giúp một máy tính có thể chạy song song trên nhiều hệ điều hành</li>
<li>Giúp khai thác công suất tối đa của máy tính</li>
<li>Tăng tính linh hoạt khi nâng cấp phần cứng</li>
</ul>

<a name="1.3"></a>
##1.3. Ưu điểm và nhược điểm của VMWare WorkStation:

*Ưu điểm:
<ul>
<li>Giữa các máy ảo có tính bảo mật cao vì độc lập với nhau</li>
<li>Giảm chi phí cho người dùng</li>
<li>Có thể cài đặt và sử dụng một chương trình lạ từ internet mà không sợ ảnh hưởng đến máy tính vật lí vì nếu có thể cũng chỉ hỏng máy ảo được tạo bên trong</li>
<li>Bảo vệ được tài nguyên trên máy vật lí vì máy ảo có các thiết bị ảo hỗ trợ</li>
</ul>
*Nhược điểm:
<ul>
<li>Tất cả các máy ảo đều nằm trên cùng một máy vật lí vì vậy nếu máy vật lí bị kẻ gian chiếm quyền sử dụng thì toàn bộ máy ảo cũng sẽ đều bị kẻ gian kiểm soát</li>
<li>Việc tất cả máy ảo nằm trên cùng một máy tính vật lí cũng làm cho các máy ảo sẽ bị ảnh hưởng đồng loạt khi máy vật lí mắc những trục trặc về kĩ thuật hoặc bị hỏng</li>
<li>Yêu cầu máy tính vật lí chứa các máy ảo phải có cấu hình phần cứng mạnh </li>
</ul>

<a name="2"></a>
#2. Hướng dẫn cài đặt máy ảo và network trong VMWare WorkStation:

<a name="2.1"></a>
##2.1. Hướng dẫn cài đặt máy ảo:

**Bước 1:** Trên giao điện phần mềm VMWare WorkStation, vào File chọn New Virtual Machine...

<img src="http://imgur.com/yhhTvy1">

**Bước 2:** Chọn Custom rồi chọn Next

<img src="http://imgur.com/Vkj3oOq">

**Bước 3:** Chọn Next

<img src="http://imgur.com/tWiGE6s">

**Bước 4:** Chọn I will install the operating system later rồi chọn Next

<img src="http://imgur.com/tWiGE6s">

**Bước 5:** Chọn hệ điều hành mà bạn có thể sẽ cài đặt trên máy ảo rồi chọn Next

<img src="http://imgur.com/5nRehRd">

**Bước 6:** Đặt tên cho máy ảo. Sau đó, chọn thư mục lưu trữ máy ảo rồi chọn Next.

<img src="http://imgur.com/sIfMJNO">

**Bước 7:** Chọn loại firmware rồi chọn Next

<img src="http://imgur.com/IHNvuPi">

**Bước 8:** Chọn số lượng vi xử lí, nhân vi xử lí của máy ảo rồi chọn Next

<img src="http://imgur.com/tB52K8v">

**Bước 9:** Chọn dung lượng bộ nhớ RAM của máy ảo rồi chọn Next

<img src="http://imgur.com/PmTKGbj">

**Bước 10:** Chọn Use network address translation(NAT) rồi chọn Next

<img src="http://imgur.com/FjSYaLe">

**Bước 11:** Chọn Next

<img src="http://imgur.com/jg887aE">

**Bước 12:** Chọn Next

<img src="http://imgur.com/iV8xPqR">

**Bước 13:** Chọn Create a new virtual disk rồi chọn Next

<img src="http://imgur.com/hvUPYsR">

**Bước 14:** Chọn dung lượng bộ nhớ đĩa rồi chọn Next

<img src="http://imgur.com/Nl8bKEw">

**Bước 15:** Browse file ổ đĩa tới thư mục bạn mong muốn rồi chọn Next. Nên để chung với thư mục tạo máy ảo ban đầu.

<img src="http://imgur.com/lD7TsyP">

**Bước 16:** Chọn Customize Hardware

<img src="http://imgur.com/WXhwUzd">

**Bước 17:** Vào New CD/DVD chọn use ISO image file và browse file iso của hệ điều hành bạn sẽ cài đặt vào đây

<img src="http://imgur.com/D1QQH0Q">

**Bước 18:** Chọn Network Adapter. Chọn Custom và trỏ tới card mạng bạn muốn cắm cho máy. Thông thường để ở card mạng NAT. Sau đó, chọn Close.

<img src="http://imgur.com/wt860gS">

**Bước 19:** Chọn Finish.

<img src="http://imgur.com/2q0Hxlj">

**Bước 20:** Bạn có thể chọn Power on this Virtual Machine để bắt đầu cài máy hoặc chọn Edit để điều chỉnh lại một số cài đặt cho phù hợp.

<img src="http://imgur.com/kWnVb1B">

<a name="2.2"></a>
##2.2. Hướng dẫn cài đặt network:

**Bước 1:** Chọn Edit rồi chọn Virtual Network Editor

<img src="http://imgur.com/B78DnKj">

**Bước 2:** VMWare WorkStation sẽ hiển thị bảng Virtual Network Editor. Với mặc định là 3 card mạng chính mang vai trò card NAT, card bridged và card host.

<img src="http://imgur.com/MpEPzis">

**Bước 3:** Trên card NAT, bạn cần phải điều chỉnh các thông số về dải mạng, subnet. Chọn NAT Settings... để cài đặt nâng cao

<img src="http://imgur.com/KhXkhHM">

**Bước 4:** Trong NAT Settings, bạn điều chỉnh lại Gateway IP cho phù hợp rồi nhấn OK để hoàn tất cài đặt.

<img src="http://imgur.com/lVuH8AG">

**Bước 5:** Trên card Bridgedbanj có để điều chỉnh thông qua Automatic Bridging Settings.

<img src="http://imgur.com/cpC2mVf">

**Bước 6:** Ngoài ra, bạn có thể add hoặc remove card mạng bằng cách chọn Add Network... hoặc Remove Network. Sau khi hoàn tất mọi cài đặt cho mạng bạn ấn OK hoặc Apply để áp dụng cho toàn bộ các máy ảo.

<img src="http://imgur.com/dfY0nM3">

<a name="3"></a>
#3. Cài đặt hệ điều hành Window Server 2012 trên máy ảo

Như đã đề cập ở trên cách bạn tạo một máy ảo, tôi đã tạo và đưa file iso của WindowsServer 2012 vào máy ảo để cài đặt. Sau khi tạo thành công môi trường cho máy ảo, khởi động máy ảo lên bằng Power on this Virtual Machine. Để cài đặt WindowsServer 2012 có các bước sau:

**Bước 1:** Chọn ngôn ngữ sử dụng, loại bàn phím rồi chọn Next.

<img src="http://imgur.com/QZvXMdS">

**Bước 2:** Chọn Install now.

<img src="http://imgur.com/b1f7hIS">

**Bước 3:** Nhập key cho WindowsServer 2012 rồi chọn Next. Để biết key cho WindowsServer 2012 bạn có thể truy cập vào [Key WindowsServer 2012](http://thegioitinhoc.vn/khuyen-mai-ban-quyen-phan-mem/206800-share-key-windows-server-2012-r2-build-9600-cap-nhat-hang-ngay.html)

<img src="http://imgur.com/e92EE37">

**Bước 4:** Chọn Server with a GUI rồi chọn Next.

<img src="http://imgur.com/Tme0BL4">

**Bước 5:** Chọn I accept the license terms rồi chọn Next.

<img src="http://imgur.com/8GbCUV7">

**Bước 6:** Chọn Custom:Install Windows only.

<img src="http://imgur.com/E5z8alb">

**Bước 7:** Tạo các phân vùng ổ đĩa rồi chọn Next.

<img src="http://imgur.com/OhngbS5">

**Bước 8:** Đợi Windows cài đặt.

<img src="http://imgur.com/m1jrO1z">

**Bước 9:** Chờ vài giây hoặc bấm Restart now để khởi động lại máy

<img src="http://imgur.com/ht3CG1d">

**Bước 10:** Nhập administrator password rồi confirm. Sau đó chọn Finish.

<img src="http://imgur.com/uwOGcaU">

**Bước 11:** Nhấn tổ hợp phím Ctrl+Alt+Ins

<img src="http://imgur.com/yYM1jrH">

**Bước 12:** Đăng nhập bằng tài khoản administrator vừa nhập password.

<img src="http://imgur.com/lAmcDPg">

**Bước 13:** Cài đặt địa chỉ IP và DNS cho máy ảo. Đến đây là hoàn tất việc cài đặt hệ điều hành WindowsServer 2012.

<img src="http://imgur.com/4GhnMYI">

<a name="4"></a>
#4. Tổng kết:
Bài viết này tôi muốn làm rõ một số nội dung chính cơ bản về VMWare WorkStation và giới thiệu cách cài đặt sử dụng máy ảo và card mạng. Mong rằng mọi người thông qua bài viết có được cái nhìn tổng quan về phần mềm VMWare WorkStation.
Bài viết vẫn còn nhiều thiếu sót. Tôi mong nhân được ý kiến đóng góp bổ sung!

Email: thanden1995@gmail.com

Xin cảm ơn!
