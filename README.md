# Tez Tanıtım Sitesi — GitHub Pages

Bu klasör, **"Federe Öğrenme Kullanılarak Nesnelerin İnterneti (IoT) Verileri Analizi"** başlıklı tez çalışmasını akademik olmayan okurlara anlatmak için hazırlanmış statik bir GitHub Pages sitesidir.

## Yayına alma

1. GitHub'da yeni bir repo oluşturun. Önerilen ad: `kullanici-adiniz.github.io` veya `tez-tanitim`.
2. Bu klasördeki tüm dosyaları repoya yükleyin.
3. Repository > Settings > Pages bölümüne gidin.
4. Source: **Deploy from a branch** seçin.
5. Branch: `main`, folder: `/root` seçin ve kaydedin.
6. Birkaç dakika sonra site yayınlanır.

## Dosya yapısı

```text
.
├── index.html
├── README.md
├── _config.yml
├── .nojekyll
└── assets/
    └── tez.pdf
```

## Düzenlenecek alanlar

- `index.html` içindeki başlık, metrikler ve iletişim bilgileri.
- `assets/tez.pdf` dosyasını yayında göstermek istemiyorsanız silin ve `index.html` içindeki `Tez PDF` bağlantısını kaldırın.
- Kendi alan adınızı kullanacaksanız GitHub Pages ayarlarından custom domain tanımlayın.
