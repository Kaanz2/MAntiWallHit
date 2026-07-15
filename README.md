# MAntiWallHit

MAntiWallHit, oyuncuların duvar veya örümcek ağı arkasından başka oyunculara hasar vermesini tespit etmek ve engellemek amacıyla geliştirilmiştir.

Plugin; saldıran oyuncunun görüş açısını, hedef oyuncunun hitbox’ını ve aradaki blokların gerçek çarpışma şekillerini kontrol eder. Hedefin vurulabilir bir bölümü açıktaysa normal vuruşa izin verir. Bütün geçerli vuruş yolları duvar veya örümcek ağı tarafından kapatılmışsa hasarı iptal eder ve yetkililere log gönderir.

Oyuncu belirlenen ihlal sınırına ulaştığında, config dosyasında ayarlanan ceza komutu konsol üzerinden otomatik olarak çalıştırılır.

## Özellikler

- Duvar arkasından vurmayı tespit eder.
- Örümcek ağı arkasından vurmayı engeller.
- Hedef hitbox’ını birden fazla noktadan kontrol eder.
- Slab, merdiven, çit, cam panel ve açık kapı gibi blokların gerçek çarpışma şekillerini hesaplar.
- Zıplama ve köşe vuruşlarında oluşabilecek false logları azaltır.
- Oyuncuların kısa süreli hareket geçmişini kontrol eder.
- Yüksek ping ve düşük TPS durumlarında kontrolleri geçici olarak durdurur.
- Teleport ve dünya değişimlerinden kaynaklanan false logları önler.
- Geçersiz vuruşlarda hasarı iptal eder.
- Yetkililere anlık tespit logları gönderir.
- İhlal sınırı ve sıfırlanma süresi ayarlanabilir.
- Uygulanacak ceza komutu tamamen değiştirilebilir.
- Bütün mesajlar ve renkler config üzerinden düzenlenebilir.
- Yetkililer uyarıları açıp kapatabilir.

## Komutlar

- `/mawh alerts` - WallHit uyarılarını açar veya kapatır.
- `/mawh reload` - Config ayarlarını yeniler.

## Yetkiler

- `mawh.alerts` - Tespit loglarını görme ve uyarıları açıp kapatma yetkisi.
- `mawh.reload` - Plugin ayarlarını yenileme yetkisi.
- `mawh.bypass` - WallHit kontrollerinden muaf olma yetkisi.

## Uyumluluk

- Paper 1.21.4
- Java 21 - 25

Hata bildirimi ve öneriler için Discord: **sindellz2**
