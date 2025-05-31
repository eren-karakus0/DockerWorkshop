# Katkıda Bulunma Rehberi

Bu Docker workshop projesine katkıda bulunmak istediğiniz için teşekkürler!

## 🔄 Katkı Süreci

1. Projeyi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)  
5. Pull Request oluşturun

## 📋 Geliştirme Ortamı

```bash
# Projeyi klonlayın
git clone https://github.com/eren-karakus0/docker-workshop.git
cd docker-workshop

# Docker ile çalıştırın
docker build -t getting-started .
docker run -dp 127.0.0.1:3000:3000 getting-started

🐛 Issue Raporlama

Issue template'ini kullanın
Detaylı açıklama yapın
Adımları tekrarlanabilir şekilde yazın
Mümkünse ekran görüntüsü ekleyin

💡 Özellik Önerileri

Yeni özellik önerilerinizi issue olarak açın
Mümkün olduğunca detaylı açıklayın
Use case'leri belirtin
