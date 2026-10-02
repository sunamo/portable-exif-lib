---
schema_version: 7
type: library
file_count: 45
avg_lines_per_file: 151
move_to_legacy_percent: 10
generated_date: 2026-10-01
generated_time: 16:40:31
github_source_url: https://github.com/igrali/portable-exif-lib
last_build_ok: no
last_build_date: 2026-10-02
last_tests_run_date: n/a
covered_lines: n/a
total_lines: 3831
---

## Description

Fork knihovny `igrali/portable-exif-lib` pro čtení Exif metadat z JPEG souborů, která je sama upravenou verzí ExifLib od Simona McKenzieho z CodeProject.
Na větvi `claude` jsou vlastní úpravy (`ExifIds`, `ExifTag`, `JpegInfo`), přidaný wrapper `JpegExif.cs` nad `ExifReader` a projekt `ExifLib.standard.csproj` (netstandard2.0).
Repo dál obsahuje původní testovací appky `WP8TestApp` a `Win8TestApp` z upstreamu.

## Původ zdrojáků

Staženo z GitHubu: **ano** — [igrali/portable-exif-lib](https://github.com/igrali/portable-exif-lib)

- Zdroj určen podle: `gh api repos/sunamo/portable-exif-lib` vrací `fork: true` s rodičem `igrali/portable-exif-lib`; remote `origin` míří na fork `sunamo/portable-exif-lib`; historie začíná commity autora `igrali` (2013-04-02, "Initial EXIF lib"); README odkazuje na původní ExifLib (CodeProject, Simon McKenzie).

## Doporučení přesunu do legacy

Doporučení přesunu do sunamocz-legacy.visualstudio.com: **10 %** — nepřesouvat bez rozmyslu — použitelná knihovna EXIF, jen s vazbou na cizí původ

- 45 souborů reálného kódu knihovny, fork `igrali/portable-exif-lib` (původ známý, dá se získat znovu).
- Není dostupná jako balíček z package manageru, proto se drží zdroják; mazání by mělo smysl až po nahrazení PackageReference.

## Vazby na moje repa

- Submoduly: žádné
- ProjectReference / PackageReference: žádné
