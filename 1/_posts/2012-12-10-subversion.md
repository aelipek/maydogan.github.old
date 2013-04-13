---
layout: post
title:  Subversion 
---

**S**ub**V**ersio**N** (SVN), açık kaynak kodlu özgür bir versiyon takip sistemidir. Şu an github üzerinde kullandığımız **git** sistemi gibi düşünebiliriz.
Her ikisi de fonksiyonellik açısından birbirine benziyor olsa da kullanım açısından biraz farklılıkları vardır. Şimdi linux ortamında svn kurulumunu ve ufak çaplı kullanımını anlatacağım.

- ubuntu makineye SVN kurulumu,

` # sudo apt-get install subversion`

- subversion araçlarını da kurmak isterseniz,

` # sudo apt-get install subversion subversion-helper-scripts subversion-tools`

- repository oluşturma,

` # svnadmin create "home/svn/test" `

home/svn/ dizini altında svn test reposunu oluşturduk. Repomuza baktığımızda svn dosyalarının oluştuğunu görebiliriz.

- repoya yerel klasor eklemek, 

`# svn import folder_name "home/svn/test"`  

- kontrol edelim,

`# svn checkout "/home/svn/test/folder_name"` 

- repoda bulunan bütün dizin ve dosyaları ekleme,

`# svn add * `

- repoda bulunan test dosyasını ekleme,

`# svn add test `

- repoda bulunan test dosyasını silip bunu commitleme,

`# svn delete "home/svn/test"`

`# svn -m "deleting test folder" delete "home/svn/test"` 

- repodaki log mesajlarını gösterme,

`# svn log "home/svn/test"`

- dosya birleştirme eylemi,

`svn merge "foo" "bar" "home/svn/test"`

- son olarak proje üzerinde yapılan değişiklikleri commit etmek,

`svn commit -m "mesajın içeriği burada" "değişiklik yapılan repo"`

Temel olarak SVN komutları yukarıdaki gibidir. Ayrıntıları için [bu](http://www.addedbytes.com/cheat-sheets/subversion-cheat-sheet/) cheatsheet işinize yarayacaktır. Kolay gelsin.. :)



 
 

   







