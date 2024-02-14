# IHA-Kiralama
UAV Rental Application with Python Django for Baykar HR Homework

![alt text](https://guryeli.com/ss.png)

```
Baykar
IHA Kiralama Projesi
Web Yazılım Uzmanı / Back-End Developer Vaka Çalışması
```

<h3>Kullanılan Teknolojiler</h3>
<b>1) Python</b><br>
<b>2) Django</b><br>
<b>3) Rest API</b><br>
<b>4) Datatable</b><br>
<b>5) jQuery</b><br>
<b>6) Ajax</b><br>
<b>7) Postgresql</b><br>
<b>8) Bootstrap 5</b>

<br><br>

<h3>Özellikler</h3>
<b>1) Üyelik ve Giriş Özelliği</b><br>
<b>2) Admin ve Kullanıcı Rolü</b><br>
<b>3) Adminler için IHA Ekleme, Düzenleme, Silme, Ajax Listeleme</b><br>
<b>4) Adminler için Kullanıcı Ekleme, Düzenleme, Silme, Ajax Listeleme</b><br>
<b>5) Adminler için IHA Kiralamarını Ajax ile Listeleme</b><br>
<b>6) Çeşitli IHA Özellikleri</b><br>
<b>7) Kullanıcılar için IHA Arama, Ajax Listeleme, Kiralama</b><br>
<b>8) Kullanıcılar için Kiralamalarını Arama, Ajax Listeleme, İptal Etme</b><br>
<b>9) IHAları tarih ve adet verisine göre müsaitlik durumu kontrol etme</b><br>
<b>11) Tüm datatable tablolarda arama, pagination, excel, print, pdf çıktı alma fonksiyonları</b><br>
<b>12) Birim testleri</b><br>
<b>13) İşlevsellikler için ekstra Django kütüphaneleri</b><br>

<h3>Kurulum</h3>

Gerekli bağımlılıkların yüklenmesi için bir sanal ortam oluşturun (virtualenv veya venv kullanarak).<br>
Projeyi klonlayın
```
git clone
```

Proje dizine gidin
```
cd myproject
```

Proje bağımlılıklarını yükleyin
```
pip install -r requirements.txt
```

setting.py dosyasında veritabanı bağlantısı ayarlarınızı yapın.
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql_psycopg2',
        'NAME': 'ihadb',  # PostgreSQL veritabanı adı
        'USER': 'postgres',  # PostgreSQL kullanıcı adı
        'PASSWORD': 'postgres',  # PostgreSQL şifre
        'HOST': 'localhost',  # Yerel PostgreSQL sunucusu
        'PORT': '5432',  # PostgreSQL port numarası
    }
}
```

Projeyi başlattığınızda veritabanı tabloları otomatik olarak oluşturulacaktır

İlk kullanıcı oluşturmak kayıt olup; PostgreSQL üzerinden yetkisini is_staff sütunundan yönetici olarak ayarlayabilirsiniz.
