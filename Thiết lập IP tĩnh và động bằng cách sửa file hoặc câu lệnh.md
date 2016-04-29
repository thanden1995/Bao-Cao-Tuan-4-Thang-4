# Thiết lập IP tĩnh và động bằng cách sửa file và câu lệnh.
##Mục Lục:
###[1. Gán IP tĩnh trên Ubuntu](#iptinh)
###[1.1. Đặt IP tĩnh tức thời](#tucthoi)
###[1.2. Đặt IP tĩnh bằng cách sửa file](#suafile)
###[2. Gán IP động trên Ubuntu](#ipdong)
###[3.Lời cảm ơn] (#camon)
<a name="iptinh"></a>
#1. Gán IP tĩnh trên Ubuntu:
<a name="tucthoi"></a>
##1.1. Đặt IP tĩnh tức thời:

**Bước 1:** Xem máy có bao nhiêu card mạng, gõ lệnh sau `# ifconfig -a | grep eth`

<img src="http://imgur.com/A7iq58U.png">

**Bước 2:** Kiểm tra xem các card mạng đã được cấu hình hay chưa gõ các lệnh sau `# ifconfig`

<img src="http://imgur.com/jh33KAX.png">

**Bước 3:** Cấu hình cho card mạng và kiểm tra, chúng ta dùng lệnh sau. Lệnh này sẽ có tác dụng ngay tức thì tuy nhiên cấu hình này không ghi vào file config nên sẽ mất khi khởi động lại máy tính

`# ifconfig ethX IP-address netmask subnet-mask`

<img src="http://imgur.com/HHPdzqT.png">

<a name="suafile"></a>
##1.2. Đặt IP tĩnh bằng cách sửa file:
**Bước 1:** Để đặt ip tĩnh bằng cách sửa file, ta sử dụng câu lệnh : `vi /etc/network/interfaces` và thiết lập IP, netmask, gateway,..:	

<img src="http://imgur.com/gWeUfHF.png">
	
**Bước 2:** Sau khi thiết lập ip cho card mạng, ta reboot máy và gõ lệnh `ip a` để kiểm tra.

<a name="ipdong"></a>
#2. Gán IP động trên Ubuntu:

Nếu muốn cấu hình card mạng nhận IP từ DHCP server, chúng ta gõ lệnh sau `vi /etc/network/interfaces` thay  các dòng lệnh bằng 
``` auto eth0
iface eth0 inet dhcp```

<img src="http://imgur.com/3boLPE3.png">

<a name="camon"></a>
#3. Lời cảm ơn:
Bài viết còn nhiều thiếu sót mong nhận được những ý kiến đóng góp từ mọi người.

Email: thanden1995@gmail.com

Chân thành cảm ơn bạn đã dành thời gian đọc bài viết này!
