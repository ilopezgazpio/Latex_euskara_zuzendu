# Latex_euskara_zuzendu
Latex proiektu baten euskara linuxen zuzentzeko pausoak

Ikergazte hori:

latex proiektu baten euskara zuzentzailea pasatzeko kode guztia Microsoft officera / Libre Officera edo bestelako kksoft officera kopiatzea bada zure irtenbidea, metodo interesgarriago bat azaltzeko natorkizu gaurkoan.

## Aurrekariak
- Linux sistema eragilean 
- Latex proiektu polit bat, adibidez Ikergazte kongresura egin beharreko aportazioa

Lehenbizi tresna hauek instalatu beharko ditugu:

1. aspell
2. dictionaries-common
3. aspell-eu

Gogoratu ere latexen euskaraz idazteko ondokoak beharko dituzula (edo ez *):

1. texlive-lang-french
2. texlive-latex-extra (*)
3. texlive-publishers (*)

## Hizkuntza zuzenketa

Iriki terminala eta exekutatu
```
aspell -c *.tex --mode=tex -l eu -d eu
```

Azalpena
```
  -c|check <file>     spellchecks a file
  -l,--lang=<str>     language code
  -d,--master=<str>   base name of the main dictionary to use
```

## Gauza gehiago
Latexeko komando bereziak gehitzeko

```--add-tex-command=<list>```

Erabilgarri ditugun hiztegi guztiak azaltzen dira ondokoarekin, hemen, *eu* hiztegiak agertu beharko luke

```aspell dicts``` 

