# Arduino-RGB-LED-Kontrol-Projesi
 Bu Proje, Arduino platformu üzerinde çalışan bir RGB LED kontrol projesini gerçekleştirmektedir. Ayrıca, bir SSD1306 OLED ekran modülü kullanılarak RGB LED'lerin renk değerlerini ekranda göstermektedir

## Gereksinimler

- Arduino UNO veya benzeri bir kart
- RGB LED
- 3 adet buton yada Membran (3) Butonlu
- SSD1306 OLED ekran
- 3 adet TIP31C Mosfet 
- Arduino IDE veya uyumlu bir programlama ortamı

## Devre Şeması

![Schematic_RGB LED_2024-01-15 (2)](https://github.com/recepuysal/Arduino-RGB-LED-Kontrol-Projesi/assets/148240525/3f8cd0fd-b04d-4e1e-b8ef-43ee995550cb)


## Kütüphaneler

Projeyi çalıştırmak için aşağıdaki kütüphanelere ihtiyaç vardır. Arduino IDE Kütüphane Yöneticisi'nden yükleyebilirsiniz.

- `Wire.h`
- `Adafruit_GFX.h`
- `Adafruit_SSD1306.h`

## Kurulum

1. Arduino IDE'yi açın.
2. Gerekli kütüphaneleri yükleyin.
3. Arduino kartınıza bağlayın.
4. Kodu Arduino kartınıza yükleyin.

## Pin Bağlantıları

- Kırmızı LED: D10
- Yeşil LED: D9
- Mavi LED: D11
- Kırmızı Buton: D5
- Yeşil Buton: D3
- Mavi Buton: D4
- OLED Reset: -1
- OLED SDA: A4
- OLED SCL: A5

## Kullanım
![WhatsApp Image 2024-01-15 at 15 29 11](https://github.com/recepuysal/Arduino-RGB-LED-Kontrol-Projesi/assets/148240525/2a4911da-e065-4c80-932a-7d27cef4ac72)
![WhatsApp Image 2024-01-15 at 15 28 49](https://github.com/recepuysal/Arduino-RGB-LED-Kontrol-Projesi/assets/148240525/e0f91e9d-ba4a-4fb5-b2a3-db932bd1078e)

Projeyi yükledikten sonra kırmızı, yeşil ve mavi butonlar aracılığıyla RGB LED'lerin renklerini kontrol edebilir ve OLED ekranında güncel renk değerlerini takip edebilirsiniz.

## Lisans

Bu proje açık kaynaklıdır ve MIT Lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına göz atabilirsiniz.
