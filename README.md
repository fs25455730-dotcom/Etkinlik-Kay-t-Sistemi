# Etkinlik-Kayit-Sistemi

# 🎟️ ProEvent — Etkinlik Kayıt Sistemi

Modern etkinlik organizasyonları için geliştirilmiş kapsamlı bir kayıt ve bilet yönetim sistemi.

---

# 📌 Proje Tanıtımı

**ProEvent**, etkinlik oluşturma, katılımcı yönetimi, bilet üretimi ve raporlama işlemlerini tek bir platform üzerinden gerçekleştirmek amacıyla geliştirilmiş masaüstü tabanlı bir etkinlik kayıt sistemidir.

Bu proje sayesinde organizasyon süreçleri dijital ortama taşınarak:

* Katılımcı kayıtları kolaylaştırılır
* Etkinlik kapasitesi kontrol edilir
* Otomatik bilet sistemi sağlanır
* Yönetim işlemleri merkezi hale getirilir
* Raporlama süreçleri hızlandırılır

---

# 🚀 Projenin Amacı

Bu sistemin temel amacı:

✅ Etkinlik yönetimini kolaylaştırmak

✅ Katılımcı kayıtlarını düzenlemek

✅ Bilet süreçlerini otomatikleştirmek

✅ Yönetici kontrolünü artırmak

✅ Kullanıcı dostu bir deneyim sunmaktır


---

# 🛠️ Kullanılan Teknolojiler

| Teknoloji | Açıklama                           |
| --------- | ---------------------------------- |
| Python    | Ana programlama dili               |
| PyQt5     | Grafik kullanıcı arayüzü           |
| UUID      | Benzersiz bilet numarası üretimi   |
| OOP       | Nesne yönelimli programlama yapısı |

---

# 🧠 Yazılım Mimarisi

Sistem nesne yönelimli programlama (OOP) prensipleri kullanılarak geliştirilmiştir.

Kod yapısı modüler şekilde hazırlanmıştır ve 3 temel sınıftan oluşmaktadır.

---

# 👤 Katilimci Sınıfı

Katılımcı bilgilerinin tutulduğu yapıdır.

## Tutulan Bilgiler

* Katılımcı ID
* Ad Soyad
* E-posta adresi

## Görevleri

* Katılımcı oluşturma
* Bilgi güncelleme
* E-posta erişimi
* Kullanıcı bilgilerini yönetme

## Kullanılan Metotlar

```python
get_ad()
get_email()
bilgileri_guncelle()
```

---

# 🎉 Etkinlik Sınıfı

Etkinliklerin oluşturulmasını ve yönetimini sağlar.

## Tutulan Bilgiler

* Etkinlik adı
* Tarih bilgisi
* Katılımcı kapasitesi
* Katılımcı listesi

## Temel Özellikler

✅ Katılımcı ekleme

✅ Katılımcı çıkarma

✅ Kapasite kontrolü

✅ Doluluk takibi

✅ Etkinlik raporlama


## Kullanılan Metotlar

```python
katilimci_ekle()
katilimci_cikar()
katilimci_raporu()
```

---

# 🎫 Bilet Sınıfı

Katılımcı ile etkinliği birbirine bağlayan sistem bileşenidir.

Her bilet için otomatik olarak benzersiz bir UUID oluşturulur.

## Özellikler

* Benzersiz bilet numarası üretimi
* Bilet oluşturma
* Bilet iptal işlemleri

## Kullanılan Metotlar

```python
bilet_olustur()
bilet_iptal()
```

---

# 🖥️ Grafik Kullanıcı Arayüzü (GUI)

Sistem arayüzü **PyQt5** kullanılarak geliştirilmiştir.

Kullanıcı dostu ve modern bir tasarım hedeflenmiştir.

---

# 📊 Dashboard

Ana kontrol panelidir.

Kullanıcı sisteme giriş yaptığında ilk olarak bu ekran görüntülenir.

## Gösterilen Bilgiler

* Toplam etkinlik sayısı
* Toplam kayıt sayısı
* Toplam bilet sayısı
* Aktif etkinliklerin doluluk oranı

## Özellikleri

✅ KPI kartları

✅ Etkinlik durum tabloları

✅ Gerçek zamanlı doluluk bilgisi

---

# ➕ Etkinlik Ekle Modülü

Yeni etkinliklerin oluşturulduğu ekrandır.

## Girilen Bilgiler

* Etkinlik adı
* Tarih
* Kontenjan bilgisi

## Sağlanan Avantajlar

* Hızlı etkinlik oluşturma
* Tarih doğrulama
* Kapasite belirleme

---

# 🧾 Kayıt Yönetimi

Katılımcı kayıt işlemleri bu bölümden gerçekleştirilir.

## Yapılabilen İşlemler

✅ Etkinlik seçimi

✅ Katılımcı ekleme

✅ E-posta doğrulama

✅ Kapasite kontrolü

---

# 🎟️ Bilet Yönetimi

Sistemde oluşturulan tüm biletler bu bölümde görüntülenir.

## Özellikler

* Bilet listeleme
* Detay görüntüleme
* Görsel bilet ekranı
* UUID bazlı bilet sistemi

---

# 📈 Raporlama Sistemi

Etkinlik analizlerinin görüntülendiği modüldür.

## Sunulan Veriler

* Doluluk oranı
* Katılımcı listesi
* İlerleme çubukları
* Etkinlik istatistikleri

---

# 🔐 Admin Paneli

Yönetici işlemleri için özel olarak tasarlanmış güvenli bölümdür.

## Güvenlik Özellikleri

* Şifre koruması
* Yetki kontrolü

```text
Varsayılan Şifre: 123
```

## Yönetici İşlemleri

✅ Etkinlik silme

✅ Katılımcı kaydı iptali

✅ Sistem loglarını görüntüleme

✅ İşlem geçmişi takibi

---

# 🔒 Güvenlik ve Yazılım Yaklaşımı

Projede veri güvenliği için çeşitli yazılım prensipleri uygulanmıştır.

## Kullanılan Yaklaşımlar

* Encapsulation (Kapsülleme)
* Private değişken kullanımı
* Modüler kod yapısı
* Nesne yönelimli programlama

---

# 📌 Sistem Avantajları

✅ Kullanıcı dostu arayüz

✅ Kolay yönetim paneli

✅ Hızlı kayıt sistemi

✅ Otomatik bilet üretimi

✅ Etkinlik kapasite kontrolü

✅ Detaylı raporlama sistemi

✅ Güvenli yönetici paneli

---

# 📷 Uygulama Özeti

ProEvent sistemi;

🎯 Etkinlik yönetimini kolaylaştırır

🎯 Kayıt süreçlerini hızlandırır

🎯 Organizasyon takibini merkezileştirir

🎯 Modern bir kullanıcı deneyimi sunar

---

# 🏁 Sonuç

ProEvent, etkinlik yönetim süreçlerini dijitalleştirmek amacıyla geliştirilmiş modern bir masaüstü uygulamasıdır.

Nesne yönelimli programlama yaklaşımı sayesinde:

* Düzenli
* Ölçeklenebilir
* Güvenli
* Kullanıcı dostu

bir yapı sunmaktadır.

Bu proje hem yazılım mimarisi hem de kullanıcı deneyimi açısından gerçek bir etkinlik yönetim sistemi altyapısı sağlamaktadır.
