---
layout: post
title: ağ çeşitleri
---
İnternetin bizim için önemini hepimiz biliyoruz. Hemen herkesin hayatında büyük bir yere sahip olan internet o kadar
çok yaygınlaştı ki, hayatımızı onsuz yaşayamaz olduk. *Bilgisayar'a Giriş* dersinde de öğrendiğimiz üzere internetin çalışma hızını ve şeklini **ağ çeşitleri** başlığında  anlatacak olursak;

###Ağ Bağlantısı Nedir?
Ağ bağlantısı kavramına iki pencereden bakmalıyız. Ağ bağlantısı denildiğinde
ilk düşünülmesi gereken internettir. Ağ bağlantısı kavramına bu yönden
baktığımızda şöyle açıklayabiliriz: Ağ bağlantısı, bilgisayarımızın internete
kablolu ya da kablosuz bir şekilde ulaşabilmesini sağlayan sistemler bütünüdür.
Diğer bir yandan bakıldığında ise ağ bağlantısı, birden fazla sayıdaki
bilgisayarınmkablolu ya da kablosuz bir şekilde birbiri ile veri
alışverişinin yanında ortak donanım birimlerini kullanabilmelerini
sağlayan sistemler bütünüdür.
    Ağ bağlantısı denildiğinde akla gelecek terimlerin başında *sunucu*
ve *kullanıcı* kavramları gelmektedir.

###Sunucu ve Kullanıcı Kavramları
Ağ bağlantısı teknolojileri ilk geliştirildikleri zamanlarda, bir ana bilgisayar ve bu bilgisayardan hem donanımsal hem de
yazılımsal olarak çok düşük özelliklere sahip olan
kullanıcı bilgisayarları(terminaller) vardı. Terminal denilen bu bilgisayarlar aynı zamanda ana bilgisayarın işlemcisini ve
sabit diskini kullanıyorlardı. Ana bilgisayarın arızalanması sırasında bütün ağ
elemanları devre dışı kalırken, aynı zamanda onarımlarının maliyeti de çok
yüksek oluyordu. Böylesi büyük bir sorunu ortadan kaldırmak isteyen geliştiriciler
kullanıcı(istemci)/sunucu adı verilen bir ağ modeli ortaya koydular. Bu modelde her
bilgisayar kendi kendine çalışabiliyorken yine ağa bağlanabilmek için sunucu adı verilen bir ana bilgisayara ihtiyaç
duymaktadırlar. Kullanıcı olarak adlandırılan  birimleri, basitçe, kendinden
başka bir bilgisayardan yardım isteyen birim olarak tanımlayabiliriz.

Ağ bağlantıları kurulurken kapsadığı alana dikkat edecek olursak, 3 tip ağ
çeşidi bulunmaktadır:

- Yerel Alan Ağları(LAN)
- Metropolitan Ağlar(MAN)
- Geniş Alan Ağları (WAN)

###Yerel Alan Ağları
İsminden de anlaşılabileceği gibi yerel alan ağları, bir yerleşke ya da
kuruluşta kullanılan dışarıya kapalı ağlardır.
Bilgisayarlar arası mesafenin 1 kilometreyi geçmediği bu ağ çeşidi genellikle
internete bağlanabilmek ya da basit uygulamaların ortak kullanımı için
kullanılır.

###Metropolitan Ağlar
Yerel alan ağlarının biraz daha gelişmiş hali olan bu ağ tipi genellikle
üniversitelerin yerleşmelerinde ve büyük iş yerlerinde kullanılmaktadır.

###Geniş Alan Ağları
Yerel alan ağlarının birleşiminden oluşan bir ağ çeşidi olan geniş alan
ağlarında yönlendirici ve çoklayıcı gibi donanım birimlerinin bulunmaktadır.

Ağ bağlantıları kurulurken bilgisayarların birbirine bağlanış şeklini göz
önünde bulundurduğumuzda, iki ana başlık olan LAN ve WAN topolojileri akla
gelmelidir.

###LAN Topolojileri
Yerel alan ağlarından kullanılan 3 tip topoloji bulunmaktadır:

- Ortak Topoloji(BUS)
- Halka Topoloji(Ring)
- Yıldız Topoloji(Star)

###Ortak Yol Topoloji(BUS)
Bu topoloji çeşidinde tüm terminaller (bilgisayarlar) düz bir çizgi halinde
sıralanmışlardır. İletilen bilgiyi tüm terminaller görüyor olmasına
karşılık, her bilgisayar kendine ait olan bilgiyi alır. Hattaki veri akışı çift yönlü olduğu için veri çakışması olabileceği düşünülmüş
ve protokollerin bunu engellemek amaçlı kullanılmasına olanak sağlanmıştır. Bus
topolojisi kurulurken koaksiyel kablo kullanılır. Her bir bilgisayar ağa
T-konektörler ile bağlanır.
Avantajları;

- Kablo yapısı güvenlidir.
- Yeni bir istasyon eklemek çok kolaydır.
- Merkez birime ihtiyaç duyulmaz.

Dezavantajları;

- Ağda en fazla 30 bilgisayar bulunabilir.
- Ağın uzunluğu ince koaksiyelde 185, kalın koaksiyelde 500 metreden fazla olamaz.
- Bir istasyon arızalandığında tüm ağ devre dışı kalır. Bu yüzden arıza tespiti
  zordur.
  
###Halka Topoloji(Ring)
Bu ağ çeşidinde tüm bilgisayarlar bir halkanın elemanları konumundadırlar. Ağa
düşen her bilgiyi BUS topolojisinde de olduğu gibi tüm bilgisayarlar görür fakat
bilginin adresi ile kendi adresi uyum gösteren bilgisayara iletilir. Eğer bilgi
hiçbir bilgisayar tarafından alınmamış ise devre dışı kalır.

Avantajları;

- Kablo yapısı güvenlidir.
- Yeni bir istasyon eklemek çok kolaydır.
- Merkez birime ihtiyaç duyulmaz.

Dezavantajları;

- Maliyet bakımından diğer ağlardan biraz daha pahallıdır.
- İletişim hızları kablolama sisteminize bağlıdır.
- Hem ağın yayıldığı tüm alan hem de bilgisayarlar arası
mesafe sınırlıdır.
- Sistemin hızı devreye eklenen her elemanla biraz daha azalır.

###Yıldız Topoloji(Star)
Bu ağ çeşidinde merkezde bir sunucu bilgisayar bulunur ve tüm kullanıcı
bilgisayarlar bu sunucuya bağlıdır.Bu sistemde, gönderilecek veri ilk önce merkezi birime gönderilir. Bu merkezi
birim de ağın düzenini sağlayacak şekilde bu veriyi hedef bilgisayarlara iletir.
Genel olarak bu merkezi birime HUB ya da SWITCH (anahtar) denilmektedir.
Kullanılan ağ kartına göre hızının değişebildiği bu ağda, merkez ile istasyonlar
arasındaki mesafe en fazla 100 metre olabilir.
Merkezdeki birimin üzerindeki ışıkların yanıp yanmaması durumuna bakılarak
arızalı istasyonun bulunabilmesi tüm ağın güvenliğini sağlamaktadır.

Avantajları;

- İstasyonların arızalanması ağı etkilemez.
- Ağa yeni bir istasyon eklemek çok kolaydır.
- Ağ yönetimi kolaydır.
- Kullanılan ağ elemanına göre ağın hızı artırılabilir.

Dezavantajları;

- Merkezde oluşacak arıza tüm ağın devre dışı kalmasına neden olabilir.
- Her bir istasyon için ayrı bir koaksiyel kablo kullanılacağından maliyet
  yüksek, kablo kirliliği çoktur.

![1](http://maydogan.me/file/topoloji.jpg)

###WAN Topolojileri
WAN topolojisinde başlıca iki tip topoloji vardır:

- Ağaç Topolojisi
- Örgü Topolojisi

###Ağaç Topoloji
Hiyerarşik topoloji olarak da bilinen ağaç topolojisinde, ağacın merkezinde bir
bilgisayar bulunurken tüm sorumluluklar bu bilgisayara aittir. Bu
sistemlerde dallanma arttıkça görevi en az olan bilgisayara doğru bir geçiş
gözlenmektedir.

###Örgü Topoloji
Mesh Topoloji de denilen örgü topolojisinde ağ yapısı incelendiğinde belirli bir
düzen görülmemektedir. Her bilgisayar kendine en yakın olan bilgisayara
bağlanmaktadır.

![1](http://maydogan.me/file/topoloji1.jpg)
