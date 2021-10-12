# Upplýsingar
* Keyra skal verkefnið með 'npm run dev'.
* 'npm run lint' til að keyra stylelint á Sass.
## Skipulag
### css og scss
* Allar HTML srár vísa í eina css ská (styles.css).
* styles.scss inniheldur aðallega bara @import, og sú skrá er þýdd yfir í styles.css.
* common.scss inniheldur stíla sem allar html skrár hafa sameiginlegt.
* config.scss inniheldur stillingar (breytur, föll, o.s.frv.). 
* Aðrar scss skrár verða fyrir hverja html skrá.
* Allar scss skrár verða í /styles möppunni.
### html
* Allar html skrár, nema index.html, verða í /pages möppunni.