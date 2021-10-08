## Zalozeni noveho projektu

1. Mas lokalny adresar (slozku) na pocitaci
2. Vytvorime z obycejneho adresare gitovy repozitar: prikaz git init
3. Vytvoreni verze (commitu)
   - "stage files": git add
   - "vytvoreni commitu": git commit -m "Popis verze"
   - "odeslani zmen na server": git push
4. Vytvoreni "vzdaleneho repozitare" na GitHubu: https://github.com/new
5. Spojeni "lokalniho a vzdaleneho repozitare":
```
git remote add origin git@github.com:tomas-mazak/alitest.git
git branch -M main
git push -u origin main
```

## Kazda dalsi zmena

1. zmenit soubor
2. git add soubor
3. git commit -m "Popis zmeny"
4. git push

## Nova vetev

1. vytvoreni pres VSCode anebo: git checkout -b nazev_vetve
2. zmeny ve vetvi klasicky git add/commit/push

!! Prvni push kazde vetve musi vypadat nasledovne: git push -u origin

## "Zamergeovani" vetve do main

1. Zmeny musi byt pushnuty do spravne vetve
2. V GitHubu: Pull Requests -> New Pull request -> Vybrat pozadovanou branch -> Create
3. Po schvaleni pull requestu kliknout Merge
4. Po uspesnem merge ve VSCode prepnout vetev na main a spustit: git pull

## Zkouška kolaborace 
1. musím naklonovat nový repozitař, který mi Tom poslal v gitHube
2. Zelené tlačítko code - zkopírovat SHH odkaz a vložit do VSCode ... nahoře - clone a vložit zkopírovaný odkaz 
3. Udělám změnu v dokumentu 
4. Add/Commit/Push - dolní lišta kolečko vedle MAIN pro Push a PUll - tím se projeví změny u mě i na GitHubu
5. Kolaborátor musí u sebe zadat Pull (nebo Push/Pull kolečko vedle main větvě v dolní liště)
