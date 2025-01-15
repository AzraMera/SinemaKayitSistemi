Proje Yapısı
BaseEntity (Temel Sınıf):

Tüm sınıfların ortak özelliklerini tutar. ID ve isim gibi özelliklere sahiptir.
IKayit Interface:

Bu interface, nesnelerin kaydedilmesi için kaydet() metodunu zorunlu kılar.
Musteri Sınıfı:

Müşteri bilgilerini tutar ve JSON dosyasına kaydetme işlemi gerçekleştirir.
Film Sınıfı:

Film bilgilerini tutar ve bir salon için film bilgilerini gösterir.
Salon Sınıfı:

Salon bilgilerini tutar, filme ekleme ve müşteri ekleme işlemleri yapılabilir. Ayrıca salon bilgilerini JSON dosyasına kaydeder.

Kullanım
Yeni Müşteri Ekleme:

Menüdeki "1" seçeneğini seçerek yeni bir müşteri ekleyebilirsiniz.
Müşteri ID'si, ismi ve email bilgilerini girerek müşteri kaydını yapabilirsiniz.
Yeni Film Ekleme:

Menüdeki "2" seçeneğini seçerek yeni bir film ekleyebilirsiniz.
Film adı, süresi ve türü gibi bilgileri girerek film kaydını yapabilirsiniz.
Yeni Salon Ekleme:

Menüdeki "3" seçeneğini seçerek yeni bir salon ekleyebilirsiniz.
Salon ID'si ve ismi girilerek salon kaydını yapabilirsiniz.
Çıkış Yapma:

Menüdeki "4" seçeneğini seçerek programdan çıkabilirsiniz.



Lisans
Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasını inceleyebilirsiniz.
