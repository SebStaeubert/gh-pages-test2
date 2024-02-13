# gh-pages-test
 * Markdown Cheat Sheet, z.B. https://oddmuse.org/wiki/Markdown_Cheat_Sheet, oder [markdown.land ](https://markdown.land/markdown-code-block).
 * [Markdown highlighted Notes](https://github.com/orgs/community/discussions/16925)

## Beispiele
HITO (KH)
  * Homepage: https://www.hitontology.eu/ bzw.
  * github: https://github.com/hitontology/hitontology.eu
BaseTRACE (KH, BS)
  * Homepage:
  * github: https://github.com/medizininformatik-initiative/BaseTRACE
DQ-Summary-Reports (CD)
  * https://imise.github.io/DQ-Summary-Reports/

## Notizen
  * Es gibt Tools, die Markdown in HTML wandeln, z.B. markdown
  * Pages aktivieren und konfigurieren ![image](https://github.com/SebStaeubert/gh-pages-test/assets/11329281/e5058c54-a347-4549-b781-756771b6714d)
  * Standard-Ordner /(root) oder /docs
    * Anpassungen über eigene Activity
  * "Github Action" -> Pages -> yml-Datei wird erstellt, die dann weiter angepasst werden kann![image](https://github.com/SebStaeubert/gh-pages-test/assets/11329281/d6cfd187-a8fe-4afc-b632-01a5a754c22b)
  * _config.yml mit Parametern, falls Markdown (Dialekt) nicht korrekt dargestellt wird, z.B. GFM
  * Index bzw. Readme wird durch Pages-Build nach interner Priorisierung: index.html, index.md, Readme.md
  * relative Link auf .md Dateien funktionieren auch -> werden durch entspr. HTML-Dateien beim Build ersetzt
### R-Doku
  * man kann in R konfigurieren -> ist aber nur halb-cool, da generierte Dateien
  * github-Action, die aus dem R-Code dann dynamisch .rd-Dateien erzeugt und daraus md oder html macht...
### Themes
  * [Adding a theme to your GitHub Pages site using Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)
    * Der Link taucht nur beim Default Pages... auf
  * [GitHub Pages Supported Themes](https://pages.github.com/themes/), z.B. [Leap day](https://github.com/pages-themes/leap-day)
  * Theme wird in _config.yml definiert und ist darüber auch im Custom Workflow (github actions) verfügbar
  * Konrads Empfehlung für ein Theme mit Navigation: [hyde](https://github.com/poole/hyde)
  * [Ein Design zur GitHub Pages-Website mit Jekyll hinzufügen](https://docs.github.com/de/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll#adding-a-jekyll-theme-in-your-sites-_configyml-file)


## Beispiele Markdown / Sandbox
Links:
  * Link mit Markdown: [MII Homepage](https://www.medizininformatik-initiative.de/)
  * Link mit HTML: <a href="https://www.medizininformatik-initiative.de">MII Homepage</a>
