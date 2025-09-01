# 📅 Toplantı Planlayıcı

Modern ve kullanıcı dostu bir toplantı planlama uygulaması. React, TypeScript ve Vite kullanılarak geliştirilmiştir.

## ✨ Özellikler

- **Toplantı Oluşturma**: Detaylı toplantı bilgileri ile yeni toplantılar oluşturun
- **Toplantı Düzenleme**: Mevcut toplantıları kolayca düzenleyin
- **Toplantı Silme**: Artık gerekli olmayan toplantıları silin
- **Akıllı Filtreleme**: Tümü, bugün, yaklaşan ve tamamlanan toplantıları filtreleyin
- **Arama**: Toplantı başlığı, açıklama, konum ve katılımcılarda arama yapın
- **Durum Takibi**: Toplantıların durumunu (yaklaşan, devam ediyor, tamamlandı) görün
- **Responsive Tasarım**: Mobil ve masaüstü cihazlarda mükemmel görünüm
- **Veri Kalıcılığı**: Local storage ile verileriniz tarayıcıda saklanır
- **Modern UI**: Gradient arka plan ve modern kart tasarımı

## 🚀 Kurulum

1. Projeyi klonlayın:
```bash
git clone <repository-url>
cd meeting-planner
```

2. Bağımlılıkları yükleyin:
```bash
npm install
```

3. Geliştirme sunucusunu başlatın:
```bash
npm run dev
```

4. Tarayıcınızda `http://localhost:3000` adresini açın.

## 🛠️ Geliştirme

### Build
```bash
npm run build
```

### Preview
```bash
npm run preview
```

## 📱 Kullanım

1. **Yeni Toplantı Oluşturma**: "Yeni Toplantı" butonuna tıklayın ve formu doldurun
2. **Toplantı Düzenleme**: Toplantı kartındaki "Düzenle" butonuna tıklayın
3. **Toplantı Silme**: Toplantı kartındaki "Sil" butonuna tıklayın
4. **Filtreleme**: Üst kısımdaki filtre butonlarını kullanın
5. **Arama**: Arama kutusuna anahtar kelimeler girin

## 🎨 Teknolojiler

- **React 18**: Modern React hooks ve functional components
- **TypeScript**: Tip güvenliği ve geliştirici deneyimi
- **Vite**: Hızlı geliştirme ve build süreci
- **Lucide React**: Modern ikonlar
- **CSS3**: Modern CSS özellikleri ve responsive tasarım

## 📁 Proje Yapısı

```
src/
├── components/          # React bileşenleri
│   ├── MeetingCard.tsx  # Toplantı kartı bileşeni
│   ├── MeetingForm.tsx  # Toplantı formu bileşeni
│   └── MeetingList.tsx  # Toplantı listesi bileşeni
├── hooks/               # Custom React hooks
│   └── useMeetings.ts   # Toplantı yönetimi hook'u
├── types/               # TypeScript tip tanımları
│   └── Meeting.ts       # Toplantı interface'i
├── App.tsx              # Ana uygulama bileşeni
├── main.tsx             # Uygulama giriş noktası
└── index.css            # Global stiller
```

## 🔧 Özelleştirme

- **Renkler**: `src/index.css` dosyasındaki CSS değişkenlerini düzenleyin
- **Validasyon**: `src/components/MeetingForm.tsx` dosyasındaki validasyon kurallarını değiştirin
- **Stil**: Bileşenlerdeki inline stilleri veya CSS sınıflarını özelleştirin

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.
