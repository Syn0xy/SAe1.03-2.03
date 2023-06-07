![](img/iuta.png)

# Rapport S2.03 I.S.R

## How to compile and run

**Compile**

* Format **HTML** :

```
pandoc --toc --toc-depth=2 --standalone report.md -o report.html -c css/pandoc.css --metadata title="Rapport S2.03 I.S.R"
```

* Format **PDF** :

```
pandoc --pdf-engine=wkhtmltopdf .\report.html -t latex -o .\report.pdf
```

**Run**

Double-click ``report.html`` or ``report.pdf`` to run.

## Help

Si vous êtes sur windows, vous ne pourrez surement pas convertir le fichier en pdf, il faut donc installer wkhtmltopdf avec
```
choco install wkhtmltopdf
```
Si vous ne possedez pas chocolatey, il faut l'installer grâce a cette commande sur un terminal en tant qu'administrateur:
```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## About

Cette archive contient :

* Les images et le css avec l'arborescence
* Le fichier ``readme.md`` non compilé
* Le fichier ``readme.html`` compilé
* Le fichier ``report.md`` non compilé
* Le fichier ``report.html`` compilé
* Le fichier ``report.pdf`` compilé

# Credits

* Questionnaire - Antoine DOMISSE
* Questionnaire, Markdown - Antoine POURTHIÉ
* Questionnaire, Virtual machine - Axel DUMON