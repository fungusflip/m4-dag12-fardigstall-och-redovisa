# Kafé Kardemumma

En webbplats för det påhittade kaféet Kafé Kardemumma i Stockholm. Sidan har en startsida med meny och "Om oss", och en sida för att boka bord. Byggd i Modul 4 (HTML och CSS) på UI/UX & Frontendutveckling, Lexicon IT-Proffs.

**Live:** https://fungusflip.github.io/m4-dag12-fardigstall-och-redovisa/

## Tekniker

- Semantisk HTML5 (header, nav, main, section, article, footer)
- CSS3 med Flexbox (header, meny, footer) och Grid (menykorten, "Om oss")
- CSS-variabler i `css/variables.css` för färger, typografi och avstånd
- Responsiv design, mobile first, med brytpunkter vid 600 px och 900 px
- Tillgängligt formulär med kopplade etiketter, fältgrupper och synlig fokusmarkering
- Git och GitHub, publicerad med GitHub Pages

## Filstruktur

```
index.html        startsida: hero, meny, om oss
kontakt.html      boka bord (formulär)
css/
  variables.css   färger, typsnitt, avstånd
  base.css        reset, body, rubriker, länkar
  layout.css      header, footer, grid, brytpunkter
  components.css  knapp, kort, hero, formulär
images/           illustrationer (svg)
```

Filerna länkas i den ordningen: variabler först, sedan grund, layout och komponenter.

## Vad jag lärt mig

- Variabler på ett ställe gör att ett färgbyte slår igenom överallt.
- Grid för helheten, Flexbox inuti.
- Börja med mobilen och bygg ut med `min-width`.
- Små commits med tydliga meddelanden gör det lätt att hitta tillbaka.
- Kontrast och fokus behöver kollas även på hover och tangentbord.
