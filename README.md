# Etkinlik-Kayit-Sistemi

ProEvent: Etkinlik Kayıt Sistemi Teknik Dokümantasyon ve Kullanıcı Rehberi

Proje Hakkında
ProEvent, etkinlik organizasyonlarının dijital ortamda yönetilmesini sağlayan bir etkinlik kayıt sistemidir. Sistem sayesinde etkinlik oluşturma, katılımcı kaydı alma, bilet üretme ve raporlama işlemleri kolayca gerçekleştirilebilir.

Uygulama iki ana bölümden oluşmaktadır:

Backend (arka plan sistemi) Grafik Kullanıcı Arayüzü (GUI) 2. Kullanılan Teknolojiler Teknoloji Amaç Python Ana programlama dili PyQt5 Grafik kullanıcı arayüzü UUID Benzersiz bilet numarası üretimi OOP (Nesne Yönelimli Programlama) Sistem mimarisi 3. Sistem Mimarisi

Sistemin çekirdeği üç temel sınıftan oluşmaktadır.

3.1 Katilimci Sınıfı

Katılımcıların sisteme kayıt edilmesini ve bilgilerinin yönetilmesini sağlar.

Tutulan Bilgiler ID Ad Soyad E-posta Temel Metotlar Metot Görev get_ad() Katılımcı adını döndürür get_email() E-posta bilgisini döndürür bilgileri_guncelle() Katılımcı bilgilerini günceller 3.2 Etkinlik Sınıfı

Etkinliklerin oluşturulmasını ve yönetilmesini sağlar.

Tutulan Bilgiler Etkinlik adı Tarih Kapasite Katılımcı listesi Temel Özellikler Kapasite kontrolü Katılımcı ekleme Katılımcı çıkarma Doluluk takibi Temel Metotlar Metot Görev katilimci_ekle() Yeni katılımcı ekler katilimci_cikar() Katılımcıyı siler katilimci_raporu() Katılımcı listesini raporlar 3.3 Bilet Sınıfı

Katılımcı ile etkinliği birbirine bağlayan yapıdır.

Özellikler UUID tabanlı benzersiz bilet numarası üretir Bilet oluşturma Bilet iptali Temel Metotlar Metot Görev bilet_olustur() Yeni bilet oluşturur bilet_iptal() Mevcut bileti iptal eder 4. Grafik Kullanıcı Arayüzü (GUI)

Arayüz PyQt5 kullanılarak geliştirilmiştir.

Sistem toplamda 6 temel modülden oluşmaktadır.

4.1 Dashboard

Sistemin genel durumunu özetleyen ana ekrandır.

Gösterilen Bilgiler Toplam etkinlik sayısı Toplam kayıt sayısı Toplam bilet sayısı Aktif etkinliklerin doluluk oranı Özellikler KPI kartları Durum tabloları Doluluk takibi 4.2 Etkinlik Ekle

Yeni etkinlik oluşturma ekranıdır.

Girilen Bilgiler Etkinlik adı Tarih Kontenjan Özellikler Hızlı etkinlik oluşturma Tarih doğrulama Kapasite belirleme 4.3 Kayıt Yönetimi

Katılımcı kayıt işlemlerinin yapıldığı bölümdür.

Özellikler Etkinlik seçimi Katılımcı ekleme E-posta doğrulama Kapasite kontrolü 4.4 Biletler

Sistemde oluşturulan tüm biletleri listeler.

Özellikler Bilet listeleme Bilet detay görüntüleme Görsel bilet ekranı 4.5 Rapor Modülü

Etkinlik analizlerinin görüntülendiği bölümdür.

Gösterilen Bilgiler Doluluk oranı Katılımcı listesi İlerleme çubuğu Etkinlik istatistikleri 4.6 Admin Paneli

Yönetici işlemlerinin yapıldığı güvenli alandır.

Güvenlik Şifre koruması Varsayılan şifre: 123 Yapılabilen İşlemler Etkinlik silme Katılımcı kaydı iptali Sistem loglarını görüntüleme 5. Sistem Özellikleri Güvenlik Özellikleri Kapsülleme (Encapsulation) Gizli değişken kullanımı Yönetici paneli koruması Kullanıcı Deneyimi Basit arayüz Hızlı işlem akışı Görsel raporlama Veri Yönetimi Benzersiz bilet sistemi Katılımcı takibi Etkinlik kapasite kontrolü 6. Sonuç

ProEvent sistemi, etkinlik organizasyon süreçlerini dijitalleştirerek kayıt, biletleme ve raporlama işlemlerini merkezi bir yapı üzerinden yönetmeyi amaçlamaktadır.

Nesne yönelimli programlama prensipleri kullanılarak geliştirilen sistem; ölçeklenebilir, düzenli ve kullanıcı dostu bir yapı sunmaktadır.
