---
layout: post
title:  Ubuntu' da Zend Framework 
---

Son zamanlarda Zend framework ile geliştirilen bir projeye dahil oldum. İçeriğinden bahsedeyim... Proje, erasmus öğrencilerine yönelik olmakla birlikte, bu sürecte öğrencilerin ihtiyacı olan her türlü bilgi ve belgeleri içeren kılavuz niteliği taşıyan sistem.
Bu proje, Php tabanlı Zend Framework kullanılarak geliştirilmektedir.( Zend framework ile ilgili merak ettiklerinize [buradan](http://framework.zend.com/) erişebilirsiniz. ) Ben sonradan dahil olduğum için ilk olarak kendi yerel makineme kurulum yaparak çalışmaya başladım :) Ubuntu ortamına framework kurulumunu şu şekilde gerçekleştirdim:

- Öncelikle [Zend Framework](http://www.zend.com/community/downloads/) sitesinden son versiyonunu indiriyoruz.

- /var/www/ dizini altına indirilen klasoru açıyoruz.

-  Aşagıdaki komutla erişim izinlerini düzenliyoruz.

  `# sudo chmod -R 0755  /var/www/ZendFramework-1.11.12/`

- Zend framework ve zf tool' larını sembolink link yardımı ile etkinleştirmeliyiz. 

 `# ln -s /var/www/ZendFramework-1.11.1/bin/zf.sh  /usr/bin/zf`

 Bu komuttan sonra /usr/bin/ dizini altına sembolik link oluşmalı.

- Php ayarlarının bulunduğu php.ini dosyasında Zend kütüphanelerine erişmek için ufak düzenleme yapmalıyız.

`# sudo vim /etc/php5/apache2/php.ini`

`;include_path = “.:/usr/share/php”;`

`include_path = “.:/usr/share/php :/var/www/ZendFramework-1.11.12/library”`

Comment içinde bulunan include_path satırını Zend kütüphanelerini alacak şekilde etkinleştiriyoruz.

- Apache serverı yeniden başlatalım

`#sudo /etc/init.d/apache2 restart`

- Artık komut satırından projemizi oluşturabiliriz.

`#zf create project   /var/www/may_project `






  
          







