# Tesi in LaTeX

Un punto di partenza per la scrittura di una tesi in LaTeX aderente alle
specifiche del DISI.

## Uso

Clicca su "Use this template" per creare una nuova tesi basata su questo
modello. Poi, clicca su Actions per accedere alle funzioni di CI/CD. Se vuoi
che la tua tesi venga autonomamente ripubblicata in PDF ogni volta che `main`
viene aggiornata, sotto "Settings"/"Pages"/"Build and deployment" imposta
"Source" a "GitHub Actions".

## CI/CD

Ogni volta che aggiungi un _commit_ su una PR aperta verso `main`, viene
controllata la correta compilazione di `tesi/tesi.tex`. Ogni volta che `main`
subisce modifiche, il risultato della compilazione viene pubblicato su
`https://<nome-utente>.github.io/<nome-repository>/tesi.pdf`.
