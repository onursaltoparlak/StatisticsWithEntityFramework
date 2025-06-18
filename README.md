# 🧮 İstatistik Dashboard Projesi

Bu proje, Entity Framework ve SQL sorgularını birlikte kullanarak geliştirilmiş dinamik bir **istatistiksel analiz dashboard** uygulamasıdır. Proje kapsamında; ürünler, siparişler, müşteriler ve kategorilere ait veriler kullanıcı arayüzünde görsel olarak sunulur.

## 🛠️ Kullanılan Teknolojiler

- C# (.NET Framework)
- Windows Forms
- Entity Framework (Database First)
- SQL Server
- LINQ & Raw SQL Queries

## 🎯 Uygulama Özellikleri

📌 Uygulama açıldığında aşağıdaki veriler otomatik olarak hesaplanır ve etiketlere yansıtılır:

- Toplam kategori, ürün, müşteri ve sipariş sayısı
- Ortalama ürün fiyatı ve toplam stok miktarı
- Belirli ürünler için stok & işlem hacmi hesaplama (örnek: Gazoz, Kola)
- Kategorilere göre stok analizi (örnek: Sebze, Meyve)
- Türkiye’den gelen sipariş sayısı (hem SQL hem EF ile)
- Son eklenen ürün ve kategorisinin bilgisi
- Farklı ülke sayısı (müşteri çeşitliliği)

## 📊 SQL & Entity Framework Karşılaştırmaları

Bazı analizler hem **doğrudan SQL sorgusu** hem de **Entity Framework LINQ** kullanılarak yapılmıştır. Bu, performans ve okunabilirlik açısından farkların gözlemlenmesini sağlar.

📸 Ekran Görüntüsü
![istatistikler](https://github.com/user-attachments/assets/fb8235b0-dd45-4c03-87e8-abe2e3784833)


🧪 Öğrenilenler
SQL ve EF performans karşılaştırması

LINQ ile karmaşık sorguların nasıl yazılacağı

SQL join yapısının EF tarafındaki karşılığı

Gerçek zamanlı dashboard tasarımı
