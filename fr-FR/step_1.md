Dans la mesure du possible, `rem` doit être utilisé pour indiquer la taille d'un élément dans une page web HTML.

En effet, `rem` utilise la taille par défaut spécifiée par le navigateur de l'utilisateur. `1rem` équivaut généralement à 16 px, mais un utilisateur peut décider de régler son `rem` sur une taille plus grande ou plus petite en fonction de ses besoins et de ses préférences.

Lorsque tu utilises `3rem` pour la taille, tu indiques que l'élément est trois fois plus grand que la taille par défaut.

--- code ---
---
language: CSS
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 2
---
.bigfont {
  font-size: 3rem;
}
--- /code ---

L'utilisation de `rem` est géniale car elle permet à ta page web d'être réactive aux besoins de ton utilisateur.
