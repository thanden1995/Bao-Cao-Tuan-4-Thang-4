#Add 2 card mạng trên máy Ubuntu Server, cấu hình cho 2 card mạng.
##Mục Lục:
###[1. Add card mạng trên máy Ubuntu Server](#add)
###[2. Cấu hình cho card mạng](#cauhinh)
###[3. Lời cảm ơn](#camon)

<a name="add"></a>
#1. Add card mạng trên máy Ubuntu:

**Bước 1:** Chuột phải vào máy ảo chọn Settings...

<img src="http://imgur.com/oIdDcIx.png">

**Bước 2:** Chọn Add... sau đó chọn Network Adapter rồi chọn Next.

<img src="http://imgur.com/3xZWD5W.png">

**Bước 3:** Chọn Custom:Specific virtual network rồi chọn Finish.

<img src="http://imgur.com/5LMUMMH.png">

**Bước 4:** Nhấn OK để hoàn tất việc Add card mạng.

<img src="http://imgur.com/lamGwNq.png">

**Bước 5:**	Làm như trên để add thêm một card mạng khác.

<a name="cauhinh" ></a>
#2. Cấu hình cho card mạng:

**Bước 1:** Khởi động lại máy Ubuntu Server để nhận card mạng.

**Bước 2:** Trong giao diện làm việc của Ubuntu Server, kiểm tra xem có bao nhiêu card mạng bằng lệnh `#ifconfig -a|grep eth`

**Bước 3:** Kiểm tra xem card mạng đã cấu hình hay chưa bằng lệnh `#ifconfig`

**Bước 4:** Cấu hình card mạng bằng câu lệnh `vi /etc/network/interfaces`

<img src="http://imgur.com/ZVEIZRD.png">

**Bước 5:** Restart lại card mạng bằng lệnh 

`ifdown -a`
`ifup -a`

**Bước 6:** Kiểm tra lại card mạng đã cấu hình bằng lệnh `ip a`

<img src="http://imgur.com/alnJ9D6.png">

<a name="camon"></a>
#3. Lời cảm ơn:
Bài viết còn nhiều thiếu sót mong nhận được ý kiến đóng góp của mọi người.

Chân thành cảm ơn bạn đã dành thời gian đọc bài viết này.
