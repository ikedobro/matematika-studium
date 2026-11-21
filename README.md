# Plán studia: matematika a olympiáda

Česky psané lekce ve stylu programované výuky. Každá lekce: definice, úlohy po malých krocích, skryté nápovědy a řešení, na konci opakování ze starších lekcí. Lekce 1, 2, 8, 9, 11 a 12 končí skutečnou úlohou Matematické olympiády.

Začátek je `index.html` (plán po týdnech, odkazy na lekce). Kartičky do aplikace Anki: `anki_kartky.txt`.

## Sestavení

```
quarto render        # výstup do _site/
quarto preview       # místní náhled
```

Na GitHubu: Settings, Pages, Source = GitHub Actions. Po každém pushi do `main` workflow `.github/workflows/pages.yml` stránky sestaví a nasadí.

## Zdroje a práva

Zadání úloh označených „Zdroj“ pocházejí z archivu Matematické olympiády (matematickaolympiada.cz) a patří jejich autorům. Hinty, kroky a řešení jsou vlastní. Licence vlastního textu: zatím nezvolena.

Řešení lekcí 8, 9, 11 a 12 nejsou porovnána s oficiálními řešeními.
