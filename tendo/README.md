# Tendo – koncept nového e-shopu

Statický frontend (HTML + CSS + vanilla JS, bez buildu) pro tendo.cz, vizuálně inspirovaný patike.ch – stejný designový jazyk jako předchozí koncepty (tmavý rám, zaoblené plochy, plovoucí pill menu, obří „ghost“ nápisy, carousel s flakony, pozadí se přebarvuje podle vůně).

**Jde o neoficiální návrh** – stránka má trvalý pruh „KONCEPT“, vodoznak a `noindex`.

## Co umí
- **Kompletní katalog** – 92 vůní Yodeyma Paris (dámské, pánské, unisex) s výběrem objemu 15 / 50 / 100 ml a cenou podle objemu.
- Carousel z fotokaret (průhledné flakony nejdou spolehlivě vyříznout).

## Spuštění lokálně
```bash
cd tendo && python3 -m http.server 8000
```

## Nasazení
Settings → Pages → Source: **GitHub Actions**, pak Actions → Run workflow. Kořenový `index.html` přesměruje do `tendo/`.

## Co ještě chybí do ostrého provozu
- Platby, sklad a objednávky v reálném čase – ceny jsou snímek z 20. 11. 2026, objednávka zatím odchází e-mailem (mailto).
