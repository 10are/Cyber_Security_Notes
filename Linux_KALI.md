

## Linux Nedir?
Linux, en çok bilinen ve en çok kullanılan açık kaynak kodlu işletim sistemidir. 
Diğer işletim sistemlerinden farklı olarak Linux açık kaynak kodlu bir yapıya sahiptir.
Bu da işletim sistemini kullanan kişinin bilgisayarın arka planında dönen neredeyse her şeyden haberi
olabileceği, işletim sistemini kendince düzenleyebileceği ve geliştirebileceği anlamına geliyor.

## Neden Linux KALI
BackTrack yaratıcıları tarafından 2013 yılında oluşturulmuş Kali, Linux işletim sisteminin siber güvenlik için yaratılmış olan güvenlik kontrol işletim sistemidir. Debian tabanlı Linux dağıtımı olan Kali Linux, çoğunlukla test ortamları için kullanılmaktadır. Penetration Testler'ların ve Siber Güvenlik Uzmanlarının yanısıra yazılım geliştiricilerin de sıkça kullandığı Kali Linux için özel olan farklı kategoriler ve araçlar (toollar) bulunmaktadır. Kali Linux için özelleştirilmiş kategoriler ve araçların arasında ise:

- Information Gathering,

- Forensics,

- Reporting Tools,

- Web Applications,

- Wireless Attacks,

- Vulnerability Analysis,

- Password Tools,

- Reverse Engineering,

- Stress Testing'i bulabilirsiniz

# Linux Komutları
Linux Shell Terminal
Terminali basitçe bir programdır. Kullanıcıların girdiği komutları alır ve işlem yapması için işletim sistemine verir. Komutların sonuçlarını ve çıktısını kendi üzerinde gösterir. Yani, işletim sistemi ile kullanıcı arasındaki ana köprüdür. Linux dağıtıcıları bir GUI(Graphical User Interface – Grafiksel Arayüz) ile gelir


- ### PWD
Terminali ilk açtığımız zaman, giriş yapmış olduğunuz kullanıcının home dosyasında başlar. Eğer hangi dosyanın içinde olduğumuzu bilmek istiyorsak `pwd ` komutunu yazarız. Bu komutun çıktısı bize roottan başlayarak tam hangi klasörde olduğumuzu gösterir. Root Linux bir sistemin temelidir. Root, eğik bir çizgi ile gösterilir(/).

- ### Ls

 ` ls ` komutu, bulunduğunuz dizindeki hangi dosyaların olduğunu bilmek için kullanılır.  `Ls-a ` komutunu kullanarak ta tüm gizli dosyaları görebilirsiniz.


- ### Cd 
 ` cd `, bir dizine gitmek için kullanılan komuttur. Örneğin, Home klasöründeyseniz ve Downloads klasörüne gitmek istiyorsanız, ` cd Dowloads ` yazabilirsiniz. Unutmayın   ki bu komut büyük / küçük harfe duyarlıdır ve klasörün adını tam olarak olduğu gibi yazmanız gerekir. Bulunduğunuz klasörden geri dönmek veya bir üst klasöre çıkmak   istiyorsanız ` cd... ` komutu kullanılır.
 
 - ### Mkdir & Rmdir
` mkdir ` komutu, bir klasör veya dizin oluşturmanız gerektiğinde kullanılır. Örneğin “ TEST” adlı bir dizin yapmak istiyorsanız “mkdir TEST” komutunu yazabilirsiniz.  ` rmdir ` bir dizini silmek için kullanılan komuttur. Ancak, rmdir yalnızca boş bir dizini silmek için kullanılabilir. İçi dolu bir klasörü silmek istiyorsanız komutu ` rm -r klsörünadı ` şeklinde kullanmanız gerekir.

- ### Touch
 ` touch ` komutu bir dosya yaratmak için kullanılır. Bu dosya herhangi bir şey olabilir. Örneğin bir zip dosyası ya da txt dosyasını aynı komutla yaratabilirsiniz.

- ### Man & -Help
Bir komutun nasıl kullanılacağını ve hakkında daha fazla bilgi edinmek için man komutu kullanılır. Örneğin, ` man touch ` touch komutunun manuel sayfalarını gösterir. Bir komutu yazıp arkasına “–help” eklersek, yine manual çıktısı ile aynı sonuca ulaşırız.

- ### Cp

 ` cp ` komutu, komut satırı üzerinden kopyalama yapmak için kullanılır. İki argüman alır; ilki kopyalanacak dosyanın konumu, ikincisi kopyalanacak yerdir.

- ### Mv
` mv ` komutu, dosyaları komut satırı yoluyla taşımak için kullanılır. Bir dosyayı yeniden adlandırmak için mv komutunu da kullanabiliriz. Örneğin az önce kopyaladığımız “copytest.txt” d0syasının ismini “newcopytest.txt” olarak değiştirmek istiyoruz. “mv copytest.txt newcopytest.txt” komutu ile bu işlemi gerçekleştirebiliriz.

- ### Nano & Vi

nano ve vi, Linux komut satırı üzerinde hali hazırda yüklü olan metin düzenleyicilerdir. Nano, renkli anahtar kelimeleri gösteren ve dillerin çoğunu tanıyan iyi bir metin editörüdür. Vi, nano’dan daha basittir. Bu komutla yeni bir dosya oluşturabilir veya bu düzenleyiciyi kullanarak dosyayı değiştirebilirsiniz

- ###  Sudo

Sudo, Linux komut satırında yaygın olarak kullanılan bir komuttur. Sudo, “SuperUserDo” kelimesinden gelir. Bu komutu yapılacak bir işlemde kök ayrıcalıkları kullanmak istersek veya idari bir yapıyla erişim gerekiyorsa kullanabiliriz. Örneğin “sudo su” komutunu kullanarak sistemde admin yetkisi ile işlem yapmaya başlayabiliriz.


# KAYNAKLAR
- http://whylinuxisbetter.net/tr/

- https://diyhacking.com/linux-commands-for-beginners/

- https://shiftdelete.net/temel-linux-komutlari-47991

- https://wiki.ubuntu-tr.net/index.php?title=Temel_Linux_komutlar%C4%B1












