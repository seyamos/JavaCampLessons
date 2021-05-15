# JavaCampLessons

# Game Management Project (Gun4 Odev3)

Bir oyun yazmak istiyorsunuz. Bu yazılım için backend kodlarını JAVA ile geliştirmeyi planlıyoruz.
Yeni üye, satış ve kampanya yönetimi yapılması isteniyor. 
(Nesnelere ait özellikleri istediğiniz gibi verebilirsiniz. Burada amaç yazdığınız kodun kalitesidir. Ödevde gereksinimleri tam anlamadığınız durum benim için önemli değil, kendinize göre mantık geliştirebilirsiniz. Dediğim gibi kod kalitesiyle ilgileniyoruz.

Gereksinimler:

1. Oyuncuların sisteme kayıt olabileceği, bilgilerini güncelleyebileceği, kayıtlarını silebileceği bir ortamı simule ediniz. Müşteri bilgilerinin doğruluğunu e-devlet       sistemlerini kullanarak doğrulama yapmak istiyoruz. (E-devlet sistemlerinde doğrulama TcNo, Ad, Soyad, DoğumYılı bilgileriyle yapılır. Bunu yapacak servisi simule etmeniz yeterlidir.)

2. Oyun satışı yapılabilecek satış ortamını simule ediniz.( Yapılan satışlar oyuncu ile ilişkilendirilmelidir. Oyuncunun parametre olarak metotta olmasını kastediyorum.)

3. Sisteme yeni kampanya girişi, kampanyanın silinmesi ve güncellenmesi imkanlarını simule ediniz.

4. Satışlarda kampanya entegrasyonunu simule ediniz.


# Coffee Customer Management (Gun4 Odev2)
Kahve dükkanları için müşteri kaydetme & Mernis (Kimlik Doğrulama) entegrasyonu

Mernis Entegrasyonu:
- Projeye sağ tıkla new -> other -> web şeklinde arat -> web service client
- Service definition için link (sonunda wsdl parametresi geçilmeli) : https://tckimlik.nvi.gov.tr/Service/KPSPublic.asmx?wsdl
- Finish deyince eklenecek.

projemizi javaSE-15 ile compile ediyorsak eklenen servis hata verecektir. Bunun için
projeye sağ tıklayıp
properties -> Java Compiler -> Use compliance from.. tikini kaldırıp -> 1.8 'i seçilmeli.


# Gun3 Odev
Kodlama.io projesini yazdığınızı düşünelim.

User, Instructor, Student nesnelerini modelleyiniz. (Class-Inheritance)

UserManager, InstructorManager, StudentManager için sistemde olabilecek operasyonları tahminleyip modelleyiniz. (Class-Inheritance-Method)

Kural -- Sadece gördüğümüz konulardan yararlanmalısınız.

# Gun2 Odev
Kodlama.io sitesine gidiniz.

Özellik nesnesi olarak tanımladığımızı düşündüğünüz iki örnek veriniz.

Bunlara ait class, contructor yapılarını oluşturup diziye ekleyip listeleyiniz.

İş sınıfı olarak tanımladığımızı düşündüğünüz bir class oluşturunuz. En az iki metot yazınız.
