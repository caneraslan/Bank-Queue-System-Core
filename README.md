# Bank Queue System Core 🏦

**Bank-Queue-System-Core**, bir banka veya finansal kuruluşun müşteri trafiğini yönetmek için tasarlanmış, yüksek performanslı ve mantıksal bir kuyruk yönetimi (Queue Management) motorudur. Bu proje, nesne yönelimli programlama (OOP) prensipleri ve verimli veri yapıları kullanılarak inşa edilmiştir.

---

## ✨ Öne Çıkan Özellikler

* **Dinamik Kuyruk Yapısı:** Müşterilerin işlem türlerine (Bireysel, Kurumsal, Gişe vb.) göre farklı kuyruklara otomatik dağıtılması.
* **Akıllı Öncelik Sistemi:** VIP müşteriler, yaşlılar veya engelli bireyler için özelleştirilebilir öncelik (Priority) algoritmaları.
* **Gişe (Counter) Yönetimi:** Boşa çıkan gişelerin, merkezi kuyruktan sıradaki en uygun müşteriyi çağırma mantığı.
* **Gelişmiş Veri Yapıları:** Performans kaybını önlemek amacıyla optimize edilmiş `Queue` ve `Linked List` yapıları üzerine kurgulanmıştır.

---

## 🛠️ Teknik Altyapı ve Prensipler

Bu proje, bir kullanıcı arayüzünden ziyade sistemin "beyni" olan mantık katmanına odaklanır:

* **Object-Oriented Programming (OOP):** Kapsülleme (Encapsulation) ve Kalıtım (Inheritance) prensipleri ile sürdürülebilir kod yapısı.
* **Separation of Concerns:** İş mantığı (Business Logic), veri modellerinden (Data Models) tamamen ayrıştırılmıştır.
* **Scalability:** Sistem, kolayca yeni gişe tipleri veya işlem kategorileri eklenebilecek şekilde genişletilebilir mimariye sahiptir.

---

## 📂 Proje Yapısı

Proje temel olarak şu çekirdek sınıflar üzerine kuruludur:

- `Customer`: Müşteri kimlik ve öncelik bilgilerini taşır.
- `Ticket`: Oluşturulan sıra numarası ve zaman damgası yönetimini yapar.
- `QueueManager`: Kuyruğun ana kontrol ünitesidir; ekleme, çıkarma ve önceliklendirme işlemlerini yürütür.
- `ServiceCounter`: Gişelerin durumunu ve müşteri kabul mantığını yönetir.

---

## 🚀 Kullanım Alanları

Bu "Logic Core", şu tür sistemlere entegre edilmek üzere tasarlanmıştır:
- Banka ve Vergi Dairesi Kioskları
- Hastane ve Poliklinik Sıra Sistemleri
- Müşteri Hizmetleri Operasyon Merkezleri

---

## 📫 İletişim

Caner ASLAN - [caneraslanm@gmail.com](mailto:caneraslanm@gmail.com)
