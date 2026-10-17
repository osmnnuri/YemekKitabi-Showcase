<h1 align="center">Yemek Kitabı</h1>

<p align="center">
  Yemek tariflerini adı, malzemeleri ve görseliyle kaydettiğin Android uygulaması.
</p>

<p align="center">
  <a href="https://osmnnuri.github.io"><b>Ekran görüntüleri için siteme göz at</b></a>
</p>

---

## Proje hakkında

Yemek Kitabı, kullanıcının istediği yemek tariflerini not almasını sağlayan
temel bir Android uygulamasıdır. Her tarif adı, malzeme / tarif metni ve
galeriden seçilen bir görselle birlikte cihazda saklanır.

## Özellikler

| | |
|---|---|
| **Tarif ekleme** | Ad, malzeme / tarif metni ve galeriden görsel ile tarif kaydetme |
| **Tarif listesi** | Kaydedilen tarifler en yeniden eskiye listelenir |
| **Tarif görüntüleme** | Listeden seçilen tarif tüm ayrıntılarıyla açılır |
| **Silme** | Onay penceresiyle tarif silme |
| **İzin yönetimi** | Galeri izni istenir; reddedilirse kullanıcı bilgilendirilir |
| **Yerel kayıt** | Tarifler Room veritabanında yalnızca cihazda saklanır |

## Kullanılan teknolojiler

| Katman | Teknoloji |
|---|---|
| Dil | Kotlin |
| Arayüz | Activity, RecyclerView, ViewBinding |
| Yerel veri | Room (coroutines ile) |
| Görsel seçimi | Activity Result API (galeri + izin) |
| Geliştirme ortamı | Android Studio |

## Neden yaptım?

Room veritabanı, liste ekranları ve çalışma zamanı izinleri üzerinde pratik
yapmak için.

## Kaynak kod

Kaynak kod özel bir depoda tutuluyor; inceleme için talep üzerine paylaşılabilir.

## İletişim

**osmnnuri** · [Web sitesi](https://osmnnuri.github.io) · [GitHub](https://github.com/osmnnuri) · osmannuriyasar57@gmail.com
