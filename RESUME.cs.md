---
schema_version: 1
type: library
file_count: 43
delete_recommendation_percent: 10
generated_date: 2026-09-29
---

## Description

Fork knihovny `igrali/portable-exif-lib` pro čtení Exif metadat z JPEG souborů.
Na větvi `claude` jsou vlastní úpravy (`ExifIds`, `ExifTag`, `JpegInfo`) a přidaný
wrapper `JpegExif.cs` nad `ExifReader` pro projekt `ImageMagickTool`. Repo dál
obsahuje původní testovací appky `WP8TestApp` a `Win8TestApp` z upstreamu.
Slouží jako náhrada za dřív jen zkopírovaný zdroják bez vazby na package
manager.
