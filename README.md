# Upplýsingar
* Keyra skal verkefnið með 'npm run dev'.
* 'npm run lint' til að keyra stylelint á Sass.
## Skipulag
### css og scss
* Allar html srár vísa í eina css ská (styles.css).
* styles.scss inniheldur aðallega bara @import, og sú skrá er þýdd yfir í styles.css.
* common.scss inniheldur stíla sem allar html skrár hafa sameiginlegt.
* config.scss inniheldur stillingar (breytur, föll, o.s.frv.). 
* Aðrar scss skrár innihalda stíla fyrir hverja html skrá (t.d. index.scss inniheldur stíla fyrir index.html).
* Allar scss skrár verða í /styles möppunni.
### html
* Allar html skrár, nema index.html, verða í /pages möppunni.