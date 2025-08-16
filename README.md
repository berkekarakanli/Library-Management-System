# 📚 Kütüphane Yönetim Sistemi

Bu proje, Python aracılığıyla geliştirilmiş basit bir **Kütüphane Yönetim Sistemi** örneğidir.  
Amaç, görevli ve öğrenciler için kitap ekleme, çıkarma, ödünç alma ve teslim etme işlemlerini konsol tabanlı bir uygulama üzerinden gerçekleştirmektir.

---

## 🚀 Özellikler
- 📖 Kitap ekleme (Basılı kitap veya E-Kitap)  
- ❌ Kitap çıkarma  
- 📋 Kitapları listeleme  
- 📥 Kitap ödünç alma (tarih girişli)  
- 📤 Kitap teslim etme (gecikme durumunda ceza hesaplama)  
- 🔑 Görevli ve öğrenci için ayrı giriş menüleri  

---

## 🛠️ Kullanılan Teknolojiler
- **Python 3**  
- `datetime` modülü (tarih işlemleri için)  
- `abc` modülü (soyut sınıf kullanımı için)  

---

## 📂 Dosya Yapısı
```
kutuphane-yonetim-sistemi/
│── kutuphane.py   # Ana uygulama dosyası
│── README.md      # Proje açıklamaları
```

---

## ▶️ Çalıştırma
1. Depoyu bilgisayarına klonla:  
   ```bash
   git clone https://github.com/kullaniciadi/Kutuphane-Yonetim-Sistem.git
   ```
2. Proje klasörüne gir:  
   ```bash
   cd Kutuphane-Yonetim-Sistem
   ```
3. Programı çalıştır:  
   ```bash
   python kutuphane.py
   ```

---

## 👤 Kullanıcı Rolleri
- **Görevli**: Kitap ekleme, çıkarma, görüntüleme işlemleri yapabilir.  
  > Şifre: `görevli123`  

- **Öğrenci**: Kitap ödünç alabilir, teslim edebilir, kitap listesini görebilir.  

---

## 📌 Notlar
- Ödünç alınan kitaplar **14 gün içinde teslim edilmezse** günlük ceza uygulanır.  
- Ceza oranı varsayılan olarak **1.0 TL/gün**’dür.  

---

## 📜 Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.  
Dilediğiniz gibi kullanabilir ve geliştirebilirsiniz.
