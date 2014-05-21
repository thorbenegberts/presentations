#Plentymarkets Workflow Refactoring



##So sieht's aus:
![.](PHPUndGWTLangsam.png)



##Was kann verbessert werden?


##Weniger "Trichter"
###... es sind Flaschenhälse, die uns bremsen
![.](LessFunnelsSmaller.png)


##Weniger "Hüte"
###... reduziert den Kommunikations-Overhead
![.](LessHatsSmaller.png)



##So könnte es gehen:
![.](PHPundGWTschnell.png)



##Pro & Contra


##Pro
---
####Verantwortung ist klar
- "End-to-End Responsibility"
- Alles aus <u>einer</u> Hand: Modell-Planung & UI-Entwurf
---
####Vieles wird einfacher
- Weniger Overhead für <u>Planung</u>
- Weniger Overhead für <u>Kommunikation</u>
- Schnelle <u>Entscheidungen</u></li>
- Weniger <u>Fehler</u> und <u>Missverständnisse</u> bei Planung, Entwicklung & Test
- Vereinfachung für QA & Support: <strike>"GWT oder PHP Bug?!"</strike> Feature XY Bug!


##Contra
---
####Einheitlichkeit der UI muss erhalten bleiben
- Ich liefere einen <u>Styleguide</u>
- Ich leiste gerne <u>Hilfe</u>
- Wichtig: <u>Pragmatisch</u> sein. Wir brauchen keine finalen Designs, sondern nur Mockups!
---
####Belastung der PHP-PLs
- Nicht jedes Projekt benötigt <u>wirklich</u> einen UI-Entwurf
- Arbeit mit Balsamiq Mockups ist leicht erlernt und effizient
- Ich stelle euch eine zusätzliche Widget-Library bereit!
---
####Verteilung der UI-Ressourcen
Hier liefere ich euch gleich eine Lösung :-)



#UI-Ressourcen verteilen


##Eine "maritime Metapher"
##(weil ich Ostfriese bin)


##Im Hafen:
###Kapitäne suchen Matrosen für ihr Schiff
![.]()


## Das ist ein "Push-System" ...


## Push-System =
![.](jB10Q4F.gif)
![.](traffic.gif)
![.](PMJYz8t.gif)
![.](wtf.gif)


##Noch mal im Hafen:
### Matrosen suchen sich ihre Schiffe selbst
![.]()


## ... das ist ein "Pull-System".


## Pull-System =
![.](DoughMade.gif)
![.](IceCreamSandwichesMade.gif)
![.](Vn6NGKh.gif)
![.](aWZpOj3_460sa.gif)


![.](thefuckyousay.gif)
##Was hat das mit plentymarkets zu tun?!


##Konkret das:
![.]()