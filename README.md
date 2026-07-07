# YAMA Museum Guide

YAMA Museum Guide, müzeleri kişisel fotoğraflar, kısa anlatılar ve güvenilir bağlantılarla düzenlemek için hazırlanmış statik web reposudur.

## Yeni dosya yapısı

Fotoğraflar artık müzelerin kendi klasörlerinde tutulur:

```text
museums/
  turkey/
    istanbul-arkeoloji/
      index.html
      photo01.jpg
      photo02.jpg
    antalya-muzesi/
    anadolu-medeniyetleri/
    turk-islam-eserleri/
  germany/
    munich/
      residenz/
      museum-fuenf-kontinente/
      ns-dokumentationszentrum/
      staatliche-muenzsammlung/
      kunstareal/
    berlin/
      pergamon/
```

## Fotoğraf ekleme

1. İlgili müzenin klasörüne girin.  
2. `Add file` → `Upload files` seçin.  
3. Fotoğrafı yükleyin.  
4. Dosya adını şu sistemle verin:

```text
photo01.jpg
photo02.jpg
photo03.jpg
```

Ana kart fotoğrafı genellikle `photo01.jpg` dosyasıdır.

## Ana sayfa hero görseli

Ana sayfanın büyük üst görseli hâlâ burada durur:

```text
assets/museum-hero.jpg
```
