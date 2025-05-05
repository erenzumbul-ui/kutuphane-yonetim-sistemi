# Kütüphane Yönetim Sistemi

> Bu programı kütüphanedeki sistemi yönetmek için geliştirdim. Kitap ekleyebiliyor, üye ekleyebiliyor, kitapları üyelere ödünç verebiliyor iade alabiliyoruz. Ayrıca oluşturduğumuz tüm kitapları ve üyeleri görüntüleyebiliyoruz.

Ödünç olarak verdiğimiz tüm kitapları "Ödünç İşlemleri Görüntüle" bölümünden görüntüleyebiliriz.

Özellikle bulmak istediğimiz kitapları "Kitap Ara" kısmından ID, ISBN, Ad, Yazar gibi seçeneklere göre arayarak bulabiliriz.

Özellikle bulmak istediğimiz üyeleri "Üye Ara" kısmından ID, Ad, Soyad, Telefon, Email gibi seçeneklere göre arayarak bulabiliriz. 

Eklediğimiz üyeleri ve kitapları silebiliriz. 

Programın görünüşü bu şekildedir: 

![image](https://github.com/user-attachments/assets/09de6a90-b1c6-41ec-9185-d7a8a2ab49a4)

# ★ Kütüphane Yönetim Sistemi -> Kitap ekleme

Ekleyeceğimiz kitaba ISBN belirleyerek kitabın adı ve yazarını giriyor ve kitabı oluşturuyoruz.

![image](https://github.com/user-attachments/assets/a29c0768-6c5f-4b99-988d-0e05ed5cfc03)

# ★ Kütüphane Yönetim Sistemi -> Üye Ekleme

Üye eklemek için ekleyeceğimiz üyenin adını, soyadını, telefon numarasını ve mailini yazıyor ve Kaydet butonuna basıyoruz.

![image](https://github.com/user-attachments/assets/26c0bf64-dbe4-4221-a853-ed86cd932903)

# ★ Kütüphane Yönetim Sistemi -> Kitap Ödünç Ver

Kitap ödünç vermek için kitap ID'sini ve Üye ID'sini yazıyoruz.

![image](https://github.com/user-attachments/assets/516250fa-79d5-494d-81bf-0fad4ba2d21a)

# ★ Kütüphane Yönetim Sistemi -> Kitap İade Al

İade edilecek kitabın ID'sini yazıyoruz ve işlem yap butonuna basıyoruz.

![image](https://github.com/user-attachments/assets/bb29da2d-66f1-4565-99ab-0ef4980342e9)

# ★ Kütüphane Yönetim Sistemi -> Kitapları Görüntüle

Kitapları görüntüle butonuna bastıktan sonra daha önce eklediğimiz kitapları görüntüleyebiliyoruz.

![image](https://github.com/user-attachments/assets/3b220349-bc3d-4e7f-b051-3f45a5fffe25)

# ★ Kütüphane Yönetim Sistemi -> Üyeleri Görüntüle

Daha önce eklediğimiz üyeleri Üyeleri Görüntüle butonuna basarak görüntüleyebiliyoruz.

![image](https://github.com/user-attachments/assets/aa883c29-65cb-4671-ade9-dbf51dab6494)


# ★ Kütüphane Yönetim Sistemi -> Kitap Ara

ID, ISBN, Ad ve Yazar kriterlerine göre kitap arama yapabiliyoruz.

![image](https://github.com/user-attachments/assets/40399165-0fcc-43d0-9c6a-aa31a3530734)

# ★ Kütüphane Yönetim Sistemi -> Üye Ara

ID, Ad, Soyad, Telefon ve Email kriterlerine göre üye arama yapabiliyoruz.

![image](https://github.com/user-attachments/assets/9d0dc688-edc5-4771-8efd-07b92a2ebd89)

# ★ Kütüphane Yönetim Sistemi -> Kitap Sil

Silinecek kitap ID'sini yazarak kitap silebiliyoruz.

![image](https://github.com/user-attachments/assets/cbef28fa-8133-464d-8023-1d30dadc8489)

# ★ Kütüphane Yönetim Sistemi -> Üye Sil

Silinecek üye idsini yazarak üye silebiliyoruz.

![image](https://github.com/user-attachments/assets/f1e6f121-1491-4fc8-bf15-4f0b551141cc)

# ★ Veriler Kaydediliyor mu?

Evet uygulamada tüm veriler kodun çalıştığı dosyaya data.json dosyası olarak, işlem yapıldıkça anlık olarak kaydediliyor.

# ★ Uygulama nasıl kurulur?

1) Visual studio code programını kurup eklentiler kısmından Python eklentisini kuruyoruz.
2) Sonrasında projeyi indiriyoruz ve kullanmak istediğimiz herhangi biryere rar'dan çıkartıyoruz.
3) kutuphane.py dosyasını Visual Studio Code ile açıyoruz.
4) Sağ üstte çalıştır tuşuna basıyor ve uygulamamızı çalıştırıyoruz.
