# Docker Workshop - Getting Started App

Bu proje Docker resmi workshop'unu takip ederek oluşturulmuş bir Todo uygulamasıdır.

## 🚀 Hızlı Başlangıç

### Docker ile Çalıştırma
```bash
# Docker Hub'dan image çekme
docker pull KULLANICI-ADINIZ/docker-workshop

# Container başlatma
docker run -dp 127.0.0.1:3000:3000 KULLANICI-ADINIZ/docker-workshop
