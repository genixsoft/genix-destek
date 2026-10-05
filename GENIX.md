# Genix Destek

Genixsoft Ltd. Şti. uzaktan destek programı. [RustDesk](https://github.com/rustdesk/rustdesk) 1.5.0 (AGPL-3.0) tabanlıdır; bu depo değiştirilmiş kaynak kodunun tamamıdır.

Değişiklikler:
- Sunucu: Genixsoft'un kendi RustDesk sunucusu (`libs/hbb_common/src/config.rs`).
- Ad/logo: "Genix Destek", Genixsoft simgeleri (`res/`, `flutter/assets/`, Windows kaynakları).
- Müşteri sürümü ayarları programın içinde (`src/common.rs` `GENIX_CUSTOM_CLIENT`): bağlantı müşteri "Kabul et" deyince açılır, ayarlar/kurulum gizli, Türkçe.
- Derleme: `.github/workflows/genix-windows.yml` (elle başlatılır, `GenixDestek.exe` üretir).
