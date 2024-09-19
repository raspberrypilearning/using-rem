Waar mogelijk moet `rem` worden gebruikt om de grootte van een element op een HTML-webpagina aan te geven.

Dit komt omdat `rem` werkt met de standaardgrootte die de browser van de gebruiker heeft opgegeven. `1rem` komt normaal gesproken overeen met 16px, maar een gebruiker kan ervoor kiezen om de `rem` groter of kleiner in te stellen op basis van zijn/haar behoeften en voorkeuren.

Wanneer je `3rem` gebruikt voor de grootte, geef je aan dat het element drie keer zo groot is als de standaardgrootte.

## --- code ---

language: CSS
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 2
-------------------------------------------------------

.bigfont {
font-size: 3rem;
}
\--- /code ---

Het gebruik van `rem` is aan te raden omdat het ervoor zorgt dat jouw webpagina beter aansluit op de behoeften van je gebruiker.
