# Cài đặt Typora trên hệ điều hành Ubuntu

Sưu tầm: Thi Minh Nhựt - Email: thiminhnhut@gmail.com

Thời gian: Ngày 28 tháng 01 năm 2017

## Hướng dẫn tham khảo:

[T for Linux](https://typora.io/#linux) trên trang [Typora](https://typora.io/).

## Cách thực hiện:

* Phần hướng dẫn bên dưới đã được thực hiện thành công trên hệ điều hành Ubuntu 16.04.

* Mở cửa sổ Terminal và lần lượt thực hiện các lệnh sau (có yêu cầu nhập password khi cài đặt):
		
		sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys BA300B7755AFCFAE
		
		sudo add-apt-repository 'deb https://typora.io ./linux/'
		
		sudo apt-get update
		
		sudo apt-get install typora
		
* Sau khi cài đặt thành công, tìm và mở ứng dụng `Typora` để sử dụng:
	
	+ Nhấn phím `Window` và gõ `Typora` được kết quả tìm kiếm như hình dưới:

	![](https://raw.githubusercontent.com/thinhutubt/thinhutubt.github.io/master/typora/images/Typora-Ubuntu1604.png)
	
	+ Lần đầu tiên mở `Typora` được giao diện như hình dưới:
	
	![](https://raw.githubusercontent.com/thinhutubt/thinhutubt.github.io/master/typora/images/Open-Typora.png)
