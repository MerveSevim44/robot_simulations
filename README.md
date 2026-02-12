# Fleet Manager – Multi-Robot Simulation (MATLAB App Designer)

Bu proje, aynı ortamda görev yapan birden fazla mobil robotun **yol planlama, çakışma yönetimi ve deadlock çözümü** süreçlerini simüle etmek amacıyla geliştirilmiştir. Uygulama **MATLAB App Designer** kullanılarak grafiksel arayüzlü (GUI) bir simülasyon aracı olarak tasarlanmıştır.

## Proje Özeti

Mobil robotların aynı harita üzerinde güvenli ve verimli şekilde hareket etmesi, depo otomasyonu ve otonom sistemlerde önemli bir problemdir. Bu projede:

* Çoklu robotların aynı harita üzerinde hareketi
* Global yol planlama algoritmaları
* Çakışma ve deadlock yönetimi
* Simülasyon ve performans analizi

tek bir uygulama içerisinde gerçekleştirilmiştir.

Sistem, kullanıcıya harita türünü, robot sayısını ve planlayıcı algoritmayı seçme imkânı sunar ve simülasyonu gerçek zamanlı olarak gösterir. 

---

## Özellikler

Uygulama aşağıdaki temel özellikleri içerir:

* Rastgele harita üretimi
* Dar koridor senaryoları
* Çok robotlu simülasyon
* Yol planlama algoritmaları
* Çakışma tespiti
* Deadlock tespiti ve çözümü
* Robot hız analizi

---

## Kullanılan Teknolojiler

* MATLAB
* MATLAB App Designer
* Robotics System Toolbox
* Binary Occupancy Grid
* Diferansiyel sürüş modeli

---

## Yol Planlama Algoritmaları

Projede üç farklı global planlayıcı kullanılmıştır:

* A*
* PRM (Probabilistic Roadmap)
* Theta*

Bu algoritmalar aynı senaryoda karşılaştırmalı olarak çalıştırılabilmektedir. 

---

## Harita Türleri

Sistem iki farklı harita üretim modu içerir:

1. **Random Map**

   * Rastgele engeller
   * Farklı geometrik şekiller
   * Karmaşık senaryolar

2. **Dar Koridor**

   * Deadlock senaryolarını test etmek için tasarlanmıştır
   * Karşılıklı geçiş durumları

Bu haritalar çok robotlu planlama algoritmalarını zorlayacak şekilde oluşturulmuştur. 

---

## Deadlock Tespiti

Sistem deadlock durumlarını:

* Wait-for graph
* Circular wait tespiti
* Uzun süreli takılma analizi

yöntemleri ile algılar ve çözüm üretir. 

---

## Simülasyon Analizi

Simülasyonlar aşağıdaki kriterlerle değerlendirilir:

* Başarı oranı
* Simülasyon süresi
* Çakışma sayısı
* Deadlock sayısı 

---

## Robot Modeli

Robotlar diferansiyel sürüş modeline göre simüle edilmiştir:

* Doğrusal hız
* Açısal hız
* Tekerlek hızları

Simülasyon sırasında bu değerler analiz edilmiştir. 

---

## Projeyi Çalıştırma

1. MATLAB açılır
2. Proje klasörü açılır
3. App Designer dosyası (`.mlapp`) çalıştırılır
4. Harita ve robot sayısı seçilir
5. Simülasyon başlatılır

---

## Amaç

Bu proje aşağıdaki amaçlar için geliştirilmiştir:

* Çok robotlu sistemleri anlamak
* Yol planlama algoritmalarını karşılaştırmak
* Deadlock problemini incelemek
* Robot kinematiğini analiz etmek

---

## Gelecek Çalışmalar

* Dinamik engellerin eklenmesi
* Daha gelişmiş deadlock çözüm stratejileri
* Gerçek robot entegrasyonu 

---

## Lisans

Eğitim amaçlı kullanım.
