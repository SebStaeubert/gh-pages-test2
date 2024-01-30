# gh-pages-test
Markdown Cheat Sheet, z.B. https://oddmuse.org/wiki/Markdown_Cheat_Sheet

## Beispiele
HITO
  * Homepage: https://www.hitontology.eu/ bzw.
  * github: https://github.com/hitontology/hitontology.eu
BaseTRACE
  * Homepage:
  * github: https://github.com/medizininformatik-initiative/BaseTRACE

## Notizen
  * Es gibt Tools, die Markdown in HTML wandeln, z.B. markdown
  * Pages aktivieren und konfigurieren ![image](https://github.com/SebStaeubert/gh-pages-test/assets/11329281/e5058c54-a347-4549-b781-756771b6714d)
  * Standard-Ordner /(root) oder /docs
    * Anpassungen über eigene Activity
  * "Github Action" -> Pages -> yml-Datei wird erstellt, die dann weiter angepasst werden kann![image](https://github.com/SebStaeubert/gh-pages-test/assets/11329281/d6cfd187-a8fe-4afc-b632-01a5a754c22b)
  * _config.yml mit Parametern, falls Markdown (Dialekt) nicht korrekt dargestellt wird, z.B. GFM
  * Index bzw. Readme wird durch Pages-Build nach interner Priorisierung: index.html, index.md, Readme.md
  * relative Link auf .md Dateien funktionieren auch -> werden durch entspr. HTML-Dateien beim Build ersetzt
  * R-Doku
    * man kann in R konfigurieren -> ist aber nur halb-cool, da generierte Dateien
    * github-Action, die aus dem R-Code dann dynamisch .rd-Dateien erzeugt und daraus md oder html macht...
  * Themes sind möglich: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll
    *  Der Link taucht nur beim Default Pages... auf
    *  Theme wird in _config.yml definiert und ist darüber auch im Custom Workflow (github actions) verfügbar
    *  Konrads Empfehlung: hyde


## Beispiele Markdown
Links:
  * Link mit Markdown: [MII Homepage](https://www.medizininformatik-initiative.de/)
  * Link mit HTML: <a href="https://www.medizininformatik-initiative.de">MII Homepage</a>
