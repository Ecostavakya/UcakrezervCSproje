Uçak Rezervasyon Uygulaması
Bu uygulama, basit bir uçak rezervasyon sistemini simüle eden bir C# konsol uygulamasıdır.
 Kullanıcılar, uçakları ekleyebilir, lokasyonları yönetebilir, uçuşlar oluşturabilir ve rezervasyon yapabilirler.

Kullanım
Programı başlatmak için uygulama çalıştırıldığında, kullanıcılara aşağıdaki seçenekleri içeren bir menü sunulur:

Uçak Ekle: Yeni bir uçak ekleyerek uçak bilgilerini kaydedin.
Lokasyon Ekle: Yeni bir lokasyon ekleyerek havaalanı bilgilerini kaydedin.
Uçuş Ekle: Kalkış ve varış lokasyonları arasında bir uçuş oluşturun.
Rezervasyon Yap: Bir uçuş için rezervasyon yapın, müşteri bilgilerini ekleyin.
Çıkış: Uygulamadan çıkış yapın.
Uçak Ekleme
Uçak eklerken, uçak modeli, marka, seri numarası ve koltuk kapasitesi gibi bilgileri girebilirsiniz.

Lokasyon Ekleme
Yeni bir havaalanı eklerken, ülke, şehir, havaalanı adı ve havaalanının aktif olup olmadığı bilgisini girebilirsiniz.

Uçuş Ekleme
Kalkış ve varış lokasyonlarını, uçuş saati ve kullanılacak uçak modelini belirleyerek yeni bir uçuş ekleyebilirsiniz.

Rezervasyon Yapma
Rezervasyon yaparken, ad, soyad, yaş gibi müşteri bilgilerini girmeniz ve rezervasyon yapmak istediğiniz uçuşun saati ile ilgili bilgileri vermeniz gerekmektedir.
 Eğer uçuş dolu değilse, rezervasyon tamamlanır; aksi takdirde, uçak dolu uyarısı alırsınız.

Dosya Kaydetme
Eklenen uçaklar, lokasyonlar, uçuşlar ve rezervasyonlar JSON formatında dosyalara kaydedilir.
 Bu sayede program her çalıştığında önceki verileri korur ve kullanıcılar daha önce eklenen bilgileri görebilir.

Renk Kodlama
Farklı işlemleri belirtmek için konsol renk kodları kullanılmıştır. Örneğin, uçak eklerken mavi, lokasyon eklerken mor renk kullanılmıştır.
 Renk kodları, kullanıcıların hangi işlemi gerçekleştirdiğini daha kolay ayırt etmelerine yardımcı olur.

Dikkat Edilmesi Gereken Noktalar
Uygulama, kullanıcının girdiği bilgileri doğru bir şekilde işlemek için gerekli doğrulama kontrollerini içermektedir.
Uçuş eklerken, var olan uçak modellerinin kontrol edilmesi ve varsa kullanılması sağlanmaktadır.
Uçuş saati ve uçak modeli gibi bilgiler, daha önce eklenen verilerle uyumlu olmalıdır.
Rezervasyon yaparken, uçuşun dolu olup olmadığı kontrol edilmektedir.
