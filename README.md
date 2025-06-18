# Barışalım mı? 💕

İnteraktif bir barışma sayfası. Aleyna Begüm Kasım için özel olarak tasarlanmış romantik bir web uygulaması.

## 🚀 Canlı Demo

Site GitHub Pages üzerinden otomatik olarak deploy edilmektedir: [Siteyi Görüntüle](https://[KULLANICI-ADI].github.io/[REPOSITORY-ADI])

## ✨ Özellikler

- 💖 İnteraktif "Evet/Hayır" butonları
- 🎭 Hayır butonuna her tıklamada farklı duygusal mesajlar
- 📈 Evet butonunun giderek büyümesi
- 🎉 Özel animasyonlar ve geçişler
- 📱 Mobil uyumlu tasarım
- 🌸 Romantik pembe tema

## 🛠️ Teknolojiler

- HTML5
- CSS3 (Flexbox, Animasyonlar)
- Vanilla JavaScript
- GitHub Pages (Otomatik Deploy)
- GitHub Actions

## 📂 Dosya Yapısı

```
├── index.html              # Ana HTML dosyası
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions workflow
└── README.md               # Bu dosya
```

## 🔄 Otomatik Deploy

Bu proje GitHub Actions kullanarak otomatik deploy edilir:

- `main` branch'e her push işleminde
- Pull request oluşturulduğunda (test amaçlı)
- Manuel tetikleme ile

## 💾 Yerel Geliştirme

1. Repository'yi klonlayın:
```bash
git clone https://github.com/[KULLANICI-ADI]/[REPOSITORY-ADI].git
```

2. Dosyayı bir web sunucusunda açın veya doğrudan tarayıcıda görüntüleyin:
```bash
# Basit HTTP sunucusu için (Python 3)
python -m http.server 8000

# Veya doğrudan dosyayı açın
start index.html
```

## 🚀 GitHub'a Yükleme ve GitHub Pages Kurulumu

1. **GitHub'da yeni repository oluşturun**
2. **Local repository'yi hazırlayın:**
```bash
git add .
git commit -m "İlk commit: Barışma sayfası eklendi"
git branch -M main
git remote add origin https://github.com/[KULLANICI-ADI]/[REPOSITORY-ADI].git
git push -u origin main
```

3. **GitHub Pages'i etkinleştirin:**
   - Repository ayarlarına gidin (Settings)
   - Sol menüden "Pages" seçin
   - Source olarak "GitHub Actions" seçin
   - Workflow otomatik çalışacak ve siteniz yayına girecek

## 📝 Kişiselleştirme

Farklı isimler için kullanmak isterseniz:
- `index.html` dosyasındaki `[Aleyna Begüm Kasım]` kısımlarını değiştirin
- Renk temasını CSS'den özelleştirebilirsiniz
- Mesajları `noPrompts` array'inden düzenleyebilirsiniz

## ❤️ Lisans

Bu proje kişisel kullanım için tasarlanmıştır. Sevgiyle yapılmıştır! 💕 