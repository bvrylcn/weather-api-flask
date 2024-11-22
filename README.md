
# Hava Durumu API Uygulaması

Bu proje, bir şehir adı girildiğinde OpenWeatherMap API'sini kullanarak o şehir için hava durumu bilgilerini döndüren basit bir Flask uygulamasıdır.

## Kullanılan Teknolojiler
- Python
- Flask
- OpenWeatherMap API

## Kurulum

1. Python 3 ve `pip` kurulu olmalıdır.
2. Gerekli paketleri yükleyin:
   ```bash
   pip install -r requirements.txt
   ```

3. OpenWeatherMap API'den bir API anahtarı alın ve `app.py` dosyasındaki `API_KEY` değişkenine ekleyin.

4. Flask uygulamasını başlatın:
   ```bash
   python app.py
   ```

5. Uygulamayı tarayıcınızda çalıştırın:
   ```
   http://127.0.0.1:5000/weather?city=Ankara
   ```

## Örnek Çıktı
```json
{
  "city": "Ankara",
  "temperature": 12.34,
  "description": "clear sky",
  "humidity": 50,
  "wind_speed": 3.4
}
```

