# TC Kimlik Numarası Doğrulama ve Üretme

Girilen bir T.C. Kimlik Numarasının resmi algoritmaya göre geçerli olup olmadığını kontrol eden, isteğe bağlı olarak geçerli formatta rastgele bir kimlik numarası üreten basit bir PHP uygulaması.

🔗 **GitHub:** https://github.com/eminenurserbess/tckimlik

## Amaç

T.C. Kimlik Numarası, belirli bir matematiksel algoritmaya (hane kontrolleri) göre üretilir. Bu proje, girilen bir numaranın bu algoritmaya uyup uymadığını kontrol eder ve test/deneme amaçlı geçerli formatta örnek numaralar üretir.

## Özellikler

- **Doğrulama** — girilen 11 haneli numaranın T.C. Kimlik No algoritmasına uygunluğunu kontrol eder:
  - 11 hane olmalı, ilk hane 0 olamaz
  - Tek sıradaki hanelerin toplamı × 7 − çift sıradaki hanelerin toplamı → mod 10 = 10. hane
  - İlk 10 hanenin toplamı → mod 10 = 11. hane
- **Üretme** — yukarıdaki kurallara uyan, geçerli formatta rastgele bir kimlik numarası oluşturur
- Tek sayfalık, sade arayüz

## Kullanılan Teknolojiler

<p>
  <img src="https://img.shields.io/badge/-PHP-777BB4?logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white" />
</p>


## Kullanım

1. "TC Kimlik Numarası Girin" kutusuna 11 haneli bir numara yaz, **Doğrula** butonuna bas → numaranın geçerli olup olmadığı ekrana yazdırılır.
2. **Üret** butonuna bas → algoritmaya uygun, rastgele bir örnek kimlik numarası üretilir.
