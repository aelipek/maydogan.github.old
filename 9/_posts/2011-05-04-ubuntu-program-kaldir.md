---
layout : post
title : Ubuntu'da Program Kaldırmak
---

Ubuntu'da daha önce kurmuş olduğumuz programları  iki şekilde kaldırabilirsiniz.
Eğer grafik arayüzden kaldırmak istiyorsanız :

#### system -> administrator -> synaptic package manager

yolu izleyerek yukarıdaki quick search kısmına kaldırılacak program adını yazın.
Sıralananlardan kaldırmak istediğinizi seçin ve sağ tıklayın. Sağ tıklayınca
açılan pencerede mark for removal(kaldırmak için işaretle)' yi
seçin. Yapılandırma
paketlerini de  kaldıracaksanız mark for complete removal(tamamen kaldırmak için
işaretle yani tüm yapılandırma paketleri ile birlikte kaldırmak)'i seçin.
İkicisi olarak eğer konsoldan işlem yapmayı seviyorsanız :

	sudo apt-get remove program_adi

komutu ile kaldırabilirsiniz.Yapılandırma paketlerini de kaldırmak için :

	sudo apt-get purge

komutu yeterlidir...

