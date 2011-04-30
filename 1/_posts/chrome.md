---
layout: post
title: Ubuntu'da Google Chrome Kurulumu
---

Google Chrome, Firefox'un yerini alamaz ama ikinci bir tarayıcıya ihtiyaç
duyulduğunda Chrome tercih edebilebilir.Uç birimi açıp verilen komutlar doğrultusunda kurabiliriz.

		sudo gedit /etc/apt/sources.list
				
Aşağıdaki satırı kaynak listesinin sonuna ekle :

		# Ubuntu Chromium
		# sudo apt-key adv --recv-keys --keyserver keyserver.ubuntu.com 4E5E17B5
		# sudo apt-get install chromium-browser
		deb http://ppa.launchpad.net/chromium-daily/ppa/ubuntu karmic main
		deb-src http://ppa.launchpad.net/chromium-daily/ppa/ubuntu karmic main
		
Sistem Ubuntu 9.10 ise satırlar yukarıdaki gibi kalsın. 
Değilse “karmic” kısmını uygun şekilde düzenle. Kaydet ve kapat.

İlgili GPG anahtarını almak için gerekli komut :

		sudo apt-key adv --recv-keys --keyserver keyserver.ubuntu.com 4E5E17B5
		
Anahtarı aldıktan sonra kaynak listesini güncelle :

		sudo apt-get update
		
Son adım olarak Chrome’u kurmak için gerekli komut :

		sudo apt-get install chromium-browser
