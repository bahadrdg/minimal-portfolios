# Kişisel Portföy Sitesi

Bu proje, Vue 3, TypeScript ve Vite kullanılarak geliştirilmiş modern bir kişisel portföy web sitesidir. Tailwind CSS ile stillendirilmiş ve tamamen responsive tasarıma sahiptir.

## Özellikler

- Modern ve temiz kullanıcı arayüzü
- Responsive tasarım (mobil, tablet ve masaüstü uyumlu)
- Bölümler:
  - Hakkımda
  - Neler Yapıyorum
  - Öne Çıkan Projeler
  - İş Deneyimi
  - İletişim
- Vue 3 Composition API kullanımı
- TypeScript ile tip güvenliği
- Tailwind CSS ile modern stil

## Kurulum

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyin:

```bash
# Repoyu klonlayın
git clone https://github.com/bahadrdg/minimal-portfolios.git

# Proje dizinine gidin
cd REPO_ADINIZ

# Bağımlılıkları yükleyin
npm install

# Geliştirme sunucusunu başlatın
npm run dev
```

## Kullanılan Teknolojiler

- Vue 3
- TypeScript
- Vite
- Tailwind CSS

## Derleme ve Dağıtım

Projeyi üretim için derlemek için:

```bash
npm run build
```

Derlenen dosyalar `dist` klasöründe oluşturulacaktır.

Derlenen projeyi önizlemek için:

```bash
npm run preview
```

## Proje Yapısı

```
src/
├── assets/        # Statik varlıklar (resimler, fontlar vb.)
├── components/    # Vue bileşenleri
│   ├── Header.vue
│   ├── WhoAmI.vue
│   ├── WhatIDo.vue
│   ├── FeaturesProjects.vue
│   ├── WorkExperience.vue
│   ├── ContactHere.vue
│   └── Footer.vue
├── App.vue        # Ana uygulama bileşeni
├── main.ts        # Uygulama giriş noktası
└── style.css      # Global stiller
```

## Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.
