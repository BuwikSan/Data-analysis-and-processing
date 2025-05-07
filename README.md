# UJEP-MSW
## Mathematical software projects
Z prvu jde o repozitář zaměřený na upload

## závěrečné práce pro matematický software
Jde o 3 Úlohy kde pomocí několika python knihoven pro práci 
s pokročilejší matematikou, matematickou analýzou a pro vytváření grafů.
Projekt je psán pomocí různých paradigmat, a to převážně pomocí OOP a místy funkcionálně.

### Úloha 1 - SIR Model (systém diferenciálních rovnic)
Zde programuji Suceptible Infected Recovered (SIR) Model
Používám zde stejně jako v úloze 2 knihovnu scipy pro řešení soustavy diferenciálních rovnic
pomocí finálního řešení, které je zároveň závislé na pár vstupních parametrech závislých na nemoci kterou simuluji, 
črtám grafy detailně popisující průběh dané nemoci.

### Úloha 2 Lotka-Volterra Model (systém diferenciálních rovnic)
Pomocí stejné python knihovny simuluji průběh populace lovné zvěři a predátorů (i více) a pro zajímavé a názorné grafy,
které zobrazují různé možné chování populací využívám vstupní podmínky generované generativní umělou inteligencí.

### Úloha 3 Simulace Portfolia Aktiv (Monte Carlo Model)
zde simuluji výslednou hodnotu aktiv s libovolnou počáteční investicí a libovolným uplynulým časem 
pomocí stovek či tisíců nezávislých simulací a následně vykresluji několik grafů zobrazující (doplň)



# UJEP-MSW
## Mathematical Software Projects
Z prvu jde o repozitář zaměřený na upload

## závěrečné práce pro matematický software
Tento notebook obsahuje implementaci tří matematických modelů pro závěrečnou práci z předmětu matematický software. 
Využívá různé pokročilé knihovny jako numpy, scipy, matplotlib a seaborn pro matematickou analýzu a vizualizaci dat.

### Úloha 1 - SIR Model (systém diferenciálních rovnic)
Implementace Susceptible-Infected-Recovered (SIR) modelu pro simulaci šíření infekčních nemocí v populaci. Model používá soustavu diferenciálních rovnic řešenou pomocí knihovny scipy.integrate. 

* Analyzuje průběh epidemie pomocí parametru R0 (základní reprodukční číslo) pro různé nemoci
* Vizualizuje změny v počtu náchylných, nakažených a uzdravených jedinců v čase
* Identifikuje vrchol epidemie a její konec
* Zobrazuje finální statistiku poměru uzdravených a nikdy nenakažených pomocí koláčových grafů

### Úloha 2 - Lotka-Volterra Model (systém diferenciálních rovnic)
Implementace Lotka-Volterra modelu (predátor-kořist) pomocí diferenciálních rovnic. Model simuluje dynamiku populace kořisti a predátorů v ekosystému.

* Základní model se dvěma druhy (kořist a predátor)
* Rozšířený model se třemi druhy (kořist, predátor a vrcholový predátor)
* Různé parametry modelu generované generativní umělou inteligencí pro vytvoření zajímavých a názorných průběhů populací
* Sledování dynamické rovnováhy a cyklických změn v ekosystému

### Úloha 3 - Simulace Portfolia Aktiv (Monte Carlo Model)
Implementace Monte Carlo simulace pro finanční portfolio pomocí náhodných procesů.

* Simulace vývoje různých typů aktiv (akcie, dluhopisy, zlato, nemovitosti) s různou mírou výnosu a volatility
* Provedení tisíců nezávislých simulací pro statistické vyhodnocení možných výsledků investice
* Vizualizace distribuce konečných hodnot pomocí histogramů a pásem spolehlivosti (5% a 95% kvantily)
* Porovnání průměrných výnosů jednotlivých aktiv a celkového portfolia
* Analýza vlivu diverzifikace na celkové riziko a výnos portfolia
