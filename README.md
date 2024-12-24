# Kütüphane Yönetim Sistemi

Bu proje, basit bir kütüphane yönetim sistemini gerçekleştiren bir Python uygulamasıdır. Kullanıcılar, kitap ekleyebilir, silebilir ve güncelleyebilir. Ayrıca, veritabanını sıfırlama işlemi de yapılabilmektedir.

## Özellikler:
1. **Kullanıcı Girişi**: Uygulama, sadece "admin" kullanıcı adı ve "1234" şifresiyle giriş yapılmasını sağlar.
2. **Kitap Ekleme**: Kullanıcılar, yeni kitaplar ekleyebilir. Kitap adı, yazar ve tür bilgileri girilebilir.
3. **Kitap Silme**: Var olan kitaplar, kullanıcı tarafından silinebilir.
4. **Kitap Güncelleme**: Kitap bilgileri, kullanıcı tarafından güncellenebilir.
5. **Veritabanı Sıfırlama**: Veritabanını sıfırlayarak tüm kitap ve tür bilgilerini silebilirsiniz.

## Kullanım Adımları:

### 1. Uygulamanın Başlatılması
Uygulama başlatıldığında, ilk olarak bir giriş ekranı gösterilecektir. Bu ekran üzerinden **Kullanıcı Adı** ve **Şifre** bilgilerini girerek sisteme giriş yapabilirsiniz. Varsayılan kullanıcı adı `admin` ve şifre `1234`'tür.

### 2. Kitap Ekleme
Giriş yaptıktan sonra, kitap eklemek için "Kitap Ekle" butonuna tıklayın. Yeni kitap için:
- Kitap Adı,
- Yazar,
- Tür seçimi yaparak "Kaydet" butonuna tıklayın.

Kitap türleri, veritabanında önceden tanımlanmış olan kategorilerden seçilebilir. Bu türler:
- **Roman**
- **Çocuk Kitapları**
- **Dünya Klasikleri**
- **Yardımcı Kaynaklar**
- **Bilişim**

### 3. Kitap Silme
Bir kitabı silmek için, "Kitap Sil" butonuna tıklayın ve silmek istediğiniz kitabın adını girin. Kitap, veritabanından silinecektir.

### 4. Kitap Güncelleme
Mevcut bir kitabın bilgilerini güncellemek için "Kitap Güncelle" butonuna tıklayın. Güncellemek için:
- Eski Kitap Adı,
- Yeni Kitap Adı,
- Yeni Yazar,
- Yeni Tür seçeneklerini girin.

Bu sayede kitap bilgileriniz güncellenmiş olacaktır.

### 5. Veritabanı Sıfırlama
Tüm kitaplar ve türler veritabanından silinmek istenirse, "Veritabanı Sıfırla" butonuna tıklayabilirsiniz. Bu işlem onay alarak yapılır.

## Veritabanı:
Proje, SQLite veritabanını kullanarak kitap ve tür bilgilerini saklar. Başlangıçta aşağıdaki tablolar oluşturulmuştur:
- **genres**: Kitap türlerini saklayan tablo.
- **books**: Kitapların bilgilerini saklayan tablo (kitap adı, yazar, tür).

## Gereksinimler:
- Python 3.x
- Tkinter (GUI için)
- SQLite (Veritabanı için)

## Kurulum:
1. Python'un yüklü olduğundan emin olun.
2. Uygulama dosyasını indirin.
3. Tkinter ve SQLite kütüphaneleri Python'un varsayılan kütüphaneleri arasında bulunduğu için ek bir yükleme yapmanız gerekmez.

## Uygulamanın Çalıştırılması:
Uygulamayı çalıştırmak için terminal veya komut istemcisine aşağıdaki komutu yazabilirsiniz:
```bash
python kütüphane_yönetim_sistemi.py
```

## Katkı:
Bu projeye katkı sağlamak isterseniz, pull request yapabilirsiniz. Yardımcı olmak için [giriş yapın](#) ve özellikler ekleyin!

---

Bu sistem, küçük bir kütüphane yönetimi için basit bir örnek olup, daha geniş ölçekli projelere dönüştürülebilir.
