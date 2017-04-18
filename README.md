# universitetsparken.dk
Siden er lavet i [Jekyll](http://jekyllrb.com/) og hosted på [Github Pages](https://pages.github.com/). Det er gratis og relativt let at vedligeholde.

For at opdatere sitet er der herunder nævnt et par af de vigtigste punkter. Hvis der skal laves større ændringer anbefales det at lave en lokal kopi (med [git](https://git-scm.com/) og [jekyll](http://jekyllrb.com/)) og så uploade det efterfølgende. Vejledning til [installation på en Windows computer](https://labs.sverrirs.com/jekyll/).

## Statiske sider
Siderne Kontakt, Nyttig information mm. kan rettes direkte - de er skrevet i [Markdown](https://en.wikipedia.org/wiki/Markdown)  
Markdown formatet, kan sammenlignes med en simpel form for HTML. Måden du formatere teksten på, kan du læse om i [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).


## Referater
Referater (i pdf-format) uploades til dokumenter/referater/ i formatet:
`YYYY.MM.DD-Dokumentnavn.pdf`


## Nyheder
Nyheder oprettes i mappen _post og navngives efter følgende skabelon:
`YYYY-MM-DD-overskrift-paa-siden.md`

**BEMÆRK**: Filerne oprettes med .md som fil-endelse.

## Markdown lynkursus

Markdown kode kan se ud som følger:
```
# Overskrift, niveau 1
## Overskrift, niveau 2
### Overskrift, niveau 3

Almindelig tekst
Mere tekst

Tekst i nyt afsnit (bemærk ekstra linieskift)

[Beskrivelse af link](http://adressentilsiden.dk)

* Punktopstilling, punkt 1
* Punktopstilling, punkt 2
* Punktopstilling, punkt 3

1. Punktopstilling, punkt 1
2. Punktopstilling, punkt 2
3. Punktopstilling, punkt 3

Men læs lidt mere om det før du retter alt for meget ;-)

```
Når det bliver oversat ser det ud som følger:


# Overskrift, niveau 1
## Overskrift, niveau 2
### Overskrift, niveau 3

Almindelig tekst
Mere tekst

Tekst i nyt afsnit (bemærk ekstra linieskift)

[Beskrivelse af link](http://adressentilsiden.dk)

* Punktopstilling, punkt 1
* Punktopstilling, punkt 2
* Punktopstilling, punkt 3

1. Punktopstilling, punkt 1
2. Punktopstilling, punkt 2
3. Punktopstilling, punkt 3

Men læs lidt mere om det før du retter alt for meget ;-)