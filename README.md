Veri Madenciliği dersi için basit bir veri analiz aracı

Bu projer katılımcılardan gerçek zamanlı olarak gelen metin yanıtlarını  analiz eden ve görselleştiren bir web uygulamasıdır. soru "Bugün nasılsın?" olmakla birlikte kullanıcılar istedikleri geri bildirimleri gönderebilir. Uygulama yanıtları anlık olarak duygu analizinden geçiri özetler ve canlı grafiklere yansıtır


#Gereksinimler
- Python 3.10+
- `pip`


Gerekli paketleri yüklemek için
pip install -r requirements.txt



#Uygulamayı Çalıştır
python app.py


Ardından tarayıcınızdan `http://localhost:5000` adresine gidin. Aynı adrese bağlanan tüm kullanıcılar yanıt gönderebilir ve panodaki istatistikler tüm istemcilerde eş zamanlı olarak güncellenir.

## Özellikler

- >Gerçek zamanlı duygu analizi> VADER algoritması ile yanıtların duygu skorları ve sınıflandırmaları hesaplanır.
- >Canlı görselleştirme> Chart.js tabanlı grafikler duygu dağılımını ve zaman içindeki değişimi sunar.
- >Özet istatistikler> Ortalama duygu skoru, toplam yanıt sayısı ve son gelen yanıt anlık olarak gösterilir.
- >Katılımcı listesi> Tüm gönderilen yanıtlar kolayca takip edilebilir.

Sunumlarda veya canlı etkinliklerde, yanıtlar geldikçe panonun otomatik güncellenmesini sağlayarak etkileşimli bir deneyim sunar.
