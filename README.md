# Vectory Path

Vectory Path, stratejik bir yol oluşturma oyunudur. Oyuncular, başlangıç noktasından bitiş noktasına ulaşmak için bir yol oluştururken, rakibin hareketlerini engellemeye çalışırlar.

## Özellikler

- Online ve robot modları
- Farklı zorluk seviyeleri
- Seviye sistemi
- Gerçek zamanlı çok oyunculu
- Responsive tasarım

## Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/YOUR_USERNAME/vectory-path.git
```

2. Firebase konfigürasyonu:
- `firebase-config.js.example` dosyasını `firebase-config.js` olarak kopyalayın
- Firebase Console'dan kendi projenizin konfigürasyon bilgilerini alın
- `firebase-config.js` dosyasındaki değerleri kendi bilgilerinizle güncelleyin

3. Projeyi bir web sunucusunda çalıştırın

## Oyun Kuralları

- Başlangıç noktasından (yeşil) bitiş noktasına (kırmızı) ulaşmaya çalışın
- Sadece komşu noktalar arasında hareket edebilirsiniz
- X ile işaretli noktalar engeldir
- 🔒 ile işaretli noktalar kilitlidir
- Rakibin hareketlerini engelleyerek kazanabilirsiniz

## Seviye Sistemi

- Her 5 online galibiyet seviye atlatır
- Her 5 online mağlubiyet seviye düşürür
- Seviye sistemi sadece online oyunlarda geçerlidir

## Lisans

MIT 
