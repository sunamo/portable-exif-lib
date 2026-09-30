---
schema_version: 3
type: library
file_count: 45
delete_recommendation_percent: 10
generated_date: 2026-09-30
generated_time: 16:08:45
github_origin: yes
github_source_url: https://github.com/igrali/portable-exif-lib
---

## Description

Fork knihovny `igrali/portable-exif-lib` pro čtení Exif metadat z JPEG souborů, která je sama upravenou verzí ExifLib od Simona McKenzieho z CodeProject.
Na větvi `claude` jsou vlastní úpravy (`ExifIds`, `ExifTag`, `JpegInfo`), přidaný wrapper `JpegExif.cs` nad `ExifReader` a projekt `ExifLib.standard.csproj` (netstandard2.0).
Repo dál obsahuje původní testovací appky `WP8TestApp` a `Win8TestApp` z upstreamu.

## Původ zdrojáků

Staženo z GitHubu: **ano** — [igrali/portable-exif-lib](https://github.com/igrali/portable-exif-lib)

- Zdroj určen podle: `gh api repos/sunamo/portable-exif-lib` vrací `fork: true` s rodičem `igrali/portable-exif-lib`; remote `origin` míří na fork `sunamo/portable-exif-lib`; historie začíná commity autora `igrali` (2013-04-02, "Initial EXIF lib"); README odkazuje na původní ExifLib (CodeProject, Simon McKenzie).
