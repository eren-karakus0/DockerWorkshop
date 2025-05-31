Docker Workshop - Getting Started App

Bu proje Docker resmi workshop'unu takip ederek oluşturulmuş bir Todo uygulamasıdır.

## 🚀 Hızlı Başlangıç

### Docker ile Çalıştırma
```bash
# Docker Hub'dan image çekme
docker pull knkchn/getting-started

# Container başlatma
docker run -dp 127.0.0.1:3000:3000 knkchn/docker-workshop
Tarayıcınızda http://localhost:3000 adresini ziyaret edin.
Yerel Geliştirme
bash# Repository'yi klonlama
git clone https://github.com/eren-karakus0/DockerWorkshop.git
cd docker-workshop

# Docker ile build etme
docker build -t getting-started .

# Container çalıştırma
docker run -dp 127.0.0.1:3000:3000 getting-started
🛠️ Teknolojiler

Docker & Docker Compose
Node.js
HTML/CSS/JavaScript
SQLite/MySQL

📚 Workshop Adımları
Bu proje Docker resmi workshop'unun 8 adımını takip eder:

✅ Containerize the application
✅ Update the application
✅ Share the image on Docker Hub
✅ Persist the database using volumes
✅ Bind mounts for live development
✅ Multi-container setup with MySQL
✅ Use Docker Compose
✅ Image building best practices

🤝 Katkıda Bulunma
CONTRIBUTING.md dosyasını inceleyin.
📄 Lisans
Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için LICENSE dosyasını inceleyin.
🙏 Teşekkürler
Docker resmi dokümantasyonu ve community'sine teşekkürler.
