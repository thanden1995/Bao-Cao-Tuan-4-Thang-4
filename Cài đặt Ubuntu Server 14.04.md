#Hướng dẫn cài đặt Ubuntu server 14.04 trên máy ảo vmware
##Mục lục
###[1. Giới thiệu về Ubuntu server] (#gioithieu)
###[2. Cài đặt Ubuntu server 14.04](#caidat)
###[3. Tổng kết] (#tongket)

<a name="gioithieu"></a>
#1. Giới thiệu về Ubuntu server:
<ul>
<li>Ubuntu là một hệ điều hành mã nguồn mở, hoàn toàn miễn phí.</li>
<li>Hệ điều hành này được sử dụng phổ biến và ưa chuộng vì tính bảo mật cao, nhanh, nhẹ, có giao diện đẹp, thân thiện, dễ sử dụng, kho phần mềm ứng dụng rất phong phú đáp ứng được hầu hết yêu cầu của người dùng.</li>
<li>Hàng năm, Ubuntu phát hành hai phiên bản vào tháng tư (xx.04)  và tháng 10 (xx.10) (xx là 2 số cuối của năm phát hành, ví dụ bản phát hành tháng 10 năm 2010 là 10.10, tháng tư là 10.04).</li>
<li>Hệ điều hành Ubuntu là sự lựa chọn tuyệt vời cho máy tính của bạn. Bạn không cần phải bỏ ra một số tiền lớn hoặc vi phạm bản quyền để mua hoặc dùng lậu Windows mà vẫn có thể làm mọi việc với chiếc máy tính của mình, không phải lo lắng về virus...</li>
</ul>

<a name="caidat"></a>
#2. Cài đặt Ubuntu Server 14.04:

**Bước 1:** Chọn ngôn ngữ sử dụng rồi nhấn Enter.

<img src="http://imgur.com/BOxbvLV.png">

**Bước 2:** Chọn Install Ubuntu Server.

<img src="http://imgur.com/ni4N8YE.png">

**Bước 3:** Chọn ngôn ngữ sử dụng cho quá trình cài đặt rồi nhấn Enter.

<img src="http://imgur.com/EsKlC6m.png">

**Bước 4:** Chọn khu vực của máy ảo.

<img src="http://imgur.com/FhcQqb3.png">

**Bước 5:** Ở đây hiển thị thông báo khu vực của bạn không tương thích với ngôn ngữ trên. Bạn cần trọn lại ngôn ngữ bằng cách thủ công.

<img src="http://imgur.com/S7Ax4Jy.png">

**Bước 6:** Chọn No

<img src="http://imgur.com/5cZMpYp.png">

**Bước 7:** Chọn khu vực cho bàn phím sử dụng nhấn Enter

<img src="http://imgur.com/r1jMAt8.png">

**Bước 8:** Chọn Keyboard Layout cho máy ảo rồi ấn Enter

<img src="http://imgur.com/g12vWef.png">

**Bước 9:** Chọn Continue để cấu hình mạng.

<img src="http://imgur.com/uDhSNDv.png">

**Bước 10:** Chọn Configure network manually để cấu hình mạng thủ công. Ngoài ra bạn có thể chọn thử lại cấu hình mạng tự động hoặc tự động cấu hình mạng với DHCP nếu bạn đang sử dụng DHCP.

<img src="http://imgur.com/4ORIKX4.png">

**Bước 11:** Nhập địa chỉ IP

<img src="http://imgur.com/rZ4A46I.png">

**Bước 12:** Nhập subnet mask cho card mạng

<img src="http://imgur.com/GO7IbIH.png">

**Bước 13:** Nhập địa chỉ gateway

<img src="http://imgur.com/jArdix8.png">

**Bước 14:** Nhập tên đầy đủ cho người dùng sử dụng máy ảo.

<img src="http://imgur.com/uxQXaJU.png">

**Bước 15:** Nhập tài khoản cho người dùng đó

<img src="http://imgur.com/5O2z4hX.png">

**Bước 16:** Nhập mật khẩu cho tài khoản đó

<img src="http://imgur.com/5jrnBuk.png">

**Bước 17:** Gõ lại mật khẩu

<img src="http://imgur.com/mPjsXUR.png">

**Bước 18:** Cửa sổ hiển thị xác nhận mã hóa thư mục home của bạn. Ở đây tôi chọn No vì không cần thiết.

<img src="http://imgur.com/KBEvUwV.png">

**Bước 19:** Chọn Yes để xác nhận múi giờ đã chính xác.

<img src="http://imgur.com/ZYYxsEs.png">

**Bước 20:** Chọn kiểu phân vùng ổ đĩa. Có các lựa chọn như sau:
<ul>
<li>Guided - use entire disk: Tự động phân vùng.</li>
<li>Guided - use entire disk and with set up LVM: Tự động phân vùng với LVM</li>
<li>Guided - use entire disk and with set encrypted up LVM: Tự động phân vùng và mã hóa LVM.</li>
<li>Manual: Phân vùng bằng tay.</li>
</ul>

<img src="http://imgur.com/pqP9rKW.png">

**Bước 21:** Nếu máy ảo bạn cài đặt sử dụng proxy bạn có thể nhập proxy vào đây. Hoặc nếu không thì để trống chọn Continue.

<img src="http://imgur.com/VLfHiVY.png">

**Bước 22:** Chọn No automatic update để hệ thống không tự động cập nhật các gói tin upgrade.

<img src="http://imgur.com/DQbkRZi.png">

**Bước 23:** Chọn phần mềm cài đặt bằng phím "space" sau đó chọn Continue

<img src="http://imgur.com/2yxNkQN.png">

**Bước 24:** Ở đây hiển thị cài đặt GRUB boot loader. Chọn Yes.

<img src="http://imgur.com/gI91YbF.png">
 
**Bước 25:** Hoàn thành cài đặt. Chọn Continue.

<img src="http://imgur.com/3dOh791.png">

<a name="tongket"></a>
#3. Tổng kết:

Bài viết là những giới thiệu căn bản về ubuntu và cách cài đặt Ubuntu Server 14.04.
Bài viết còn nhiều thiếu sót mong rằng sẽ nhận được ý kiến đóng góp từ mọi người.

Cảm ơn bạn đã dành thời gian cho bài viết của tôi.
Mọi thông tin liên hệ gửi về địa chỉ email thanden1995@gmail.com
