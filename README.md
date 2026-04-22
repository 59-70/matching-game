# Refleks Ustası - Saga Pro

Oyuncuların hız, algı ve odaklanma sınırlarını test eden; minimalist ve modern tasarıma sahip, tarayıcı tabanlı bir refleks oyunu. Tamamen dış kütüphane kullanılmadan (Vanilla) geliştirilmiştir.

# Özellikler

* **Üç Farklı Zorluk Kategorisi:**
   **Renkler:** Renk algısını test eden temel mod.
   **Sayılar:** Hızlı matematiksel karar verme ve sayı tanıma.
   **Şekiller:** Geometrik karmaşa içinde doğruyu bulma.
* **Dinamik Oyun Motoru:** İlerledikçe büyüyen ızgara sistemi (2x2, 3x3, 4x4) ve oyuncuyu şaşırtan "Tersine Mantık" (Reverse) bölümleri.
* **İlerleme ve Kayıt Sistemi:** Tarayıcının `Local Storage` özelliği kullanılarak oyuncunun geçtiği bölümler ve kazandığı yıldızlar tarayıcıda kalıcı olarak saklanır.
* **Modern Kullanıcı Arayüzü (UI):** CSS ile hazırlanmış cam efekti (Glassmorphism), neon vurgular, akıcı animasyonlar ve cihaz boyutuna duyarlı (responsive) tasarım.
* **Süre ve Hedef Yönetimi:** Ana menüden ayarlanabilen dinamik süre ve saniye/skor oranına dayalı yıldız sistemi.

# Kullanılan Teknolojiler

* **HTML5:** Sayfa iskeleti ve oyun ızgarası.
* **CSS3:** Animasyonlar (`@keyframes`), Grid/Flexbox yapıları, dinamik renk değişkenleri (`:root`).
* **Vanilla JavaScript:** Oyun döngüsü (Game Loop), veri yönetimi (Array shuffling, DOM manipülasyonu), zamanlayıcı kontrolleri ve LocalStorage entegrasyonu. (Hiçbir harici kütüphane kullanılmamıştır).

# Kurulum ve Çalıştırma

Proje herhangi bir sunucu veya derleyici gerektirmez. Doğrudan tarayıcıda çalışacak şekilde tasarlanmıştır.

1. Depoyu bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/kullanici-adin/color-matching-game.git](https://github.com/kullanici-adin/color-matching-game.git)
