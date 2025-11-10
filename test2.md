## Test 2

### 1. Vysvětlete, co je komplexní síť, uveďte alespoň tři příklady takových sítí.

- rozsáhlý systém vzájemně propojených jednotek
- studuje struktury a vlastnosti sítí, interakce prvků, makrovzorce, projevy emergence atd
- příklady:

#### Sociální síť

- uzly: lidé
- hrany: sledující
- příklady: Facebook, Instagram

#### Internetová síť

- uzly: servery
- hrany: datová spojení

#### Dopravní síť

- uzly: zastávky
- hrany: trať

### 2. Vysvětlete alespoň tři důležité charakteristiky komplexních sítí.

- velikost - počet uzlů, nebo hran
- hustota - podíl počtu hran k maximálnímu možnému počtu hran
- topologické vlastnosti: 
- - stupeň uzlu - počet hran uzlu
- - shlukování - intenzita vzájemných spojů
- - nejkratší cesty - vzdálenost mezi uzly je nejmenší počet hran, které tvoří cesu

### 3. Popište, jak probíhal Milgramův experiment se zásilkami a jaké přinesl zjištění.

- Fenomém **malého světa** 
- měření vzdálenosti mezi lidmi
- vybral 2 adresáty
- požádal 160 náhodně vybraných osob z Kansasu a z Nebrasky, aby
  odeslali zásilky buď přímo adresátům (pokud je osobně znají), anebo
  někomu, kdo by adresáta pravděpodobně znát mohl
- 42 zásilek došlo přes 2 až 12 prostředníků (průměrně přes 5,5) => objevení fenoménu tzv. malého světa a 6 kroků 
odloučenosti
- experiment byl několikrát opakován na Facebooku i Twitteru

### 4. Vysvětlete pojmy malý svět, šest kroků separace, Erdősovo číslo.

> todo
#### Malý svět

- vazby mezi lidmi jsou tak rozsáhlé, že přes pár lidí lze znát všechny na světě

#### Šest kroků separace

- přes méně jak 6 vazeb lze najít kontakt na kohokoliv

#### Erdősovo číslo

- vyjadřuje vzdálenost spolupráce
- první člověk má číslo 0, další 1, k + 1

### 5. Vysvětlete, jaký význam má stupeň uzlu a rozdělení stupňů uzlů v komplexní síti.

#### Stupeň uzlu

- počet hran uzlu

#### Rozdělení stupňů uzlů

- pravděpodobnost, že náhodně vybraný uzel má stupeň _k_

### 6. Vysvětlete alespoň tři pojmy, související s hledáním nejkratších cest v síti.

> todo

### 7. Popište náhodný graf (Erdős-Rényiho model).

- Postup: je dáno **N** uzlů, náhodně vybíráme
  dvojice uzlů a s pravděpodobností **p** je propojíme (např. na základě
  výsledku hodu kostkou)
- Ze způsobu konstrukce grafu vyplývá,
  že všechny uzly mají přibližně stejný
  počet hran
- Náhodné grafy neodpovídají reálným
  komplexním sítím, ale z matematického
  hlediska jsou zajímavé
- např. se v nich projevuje **princip fázového přechodu**

### 8. Vysvětlete pojem obří komponenta v síti a popište proces (algoritmus) jejího utváření.

- komponenta, která obsahuje téměř všechny uzly sítě
- V každém kroku jsou dva náhodně vybrané uzly spojeny hranou
- Hrana mezi dvěma uzly existuje s pravděpodobností p
- Emergence: hrany spojující dvojice uzlů => řetězce => propojování komponent

### 9. Popište graf malého světa (Watts-Strogatzův model).

- 2 pravidla:
1. Pravidelné uspořádání – N vrcholů v kruhu, každý je spojen s K
   sousedy (K/2 na každé straně)
2. Proces náhodné změny hran – s pravděpodobností p každou
   hranu nahradíme jinou, náhodnou hranou

### 10. Popište bezškálovou síť (Barabási-Albertův model).

- Reprodukuje distribuci uzlů podle mocninného zákona
- 3 pravidla
1. Malý výchozí počet uzlů a hran
2. Přidávají se vrcholy, každý nově přidaný je spojen **k** hranami s
   již existujícími vrcholy
3. Dodržuje se preferenční připojování, tj. pravděpodobnost
   výběru vrcholu je přímo úměrná jeho aktuálnímu stupni (tím je
   dodržena mocninná distribuce stupňů uzlů)

### 11. Vysvětlete pojmy sociální fyzika a roli výpočetních modelů v této oblasti.

-  Člověk jako jednotka (atom, molekula, agent) v systému
- Přírodovědný pohled na sociální systémy a jevy
- - Pravděpodobnost a statistika
- - Zkoumání volebních preferencí, kriminality, nezaměstnanosti, sebevražednosti,…

> todo role výpočetních modelů

### 12. Vysvětlete, co je cílem modelů vývoje kooperace.

> todo

Vysvětlete, v čem spočívá opakované vězňovo dilema.
Jmenujte strategie, které lze použít při opakovaném vězňově dilematu.
Popište, jaké vysvětlující faktory podle E.Rogerse působí při šíření inovací (tj. co přispívá k rychlejšímu či
pomalejšímu šíření inovace).
Popište, jaké skupiny osvojitelů inovací definoval E.Rogers a jakou křivkou je popsáno rozložení skupin osvojitelů v
populaci.
V přednášce bylo popsáno několik modelů šíření inovací či nákazy, jeden z modelů jmenujte a popište jeho princip.
V přednášce bylo vysvětleno, jak lze modelovat sociální vliv na utváření a polarizaci názorů, jeden z modelů popište.
Vysvětlete pojem síla slabých vazeb ve vztahu ke komplexním sítím.
Vysvětlete pojem bod zvratu ve vztahu k sociální dynamice, popište jeho zachycení v konkrétním modelu.
Vysvětlete rozdíl mezi šířením jednoduché nákazy a šířením komplexní nákazy (v síti).
Vysvětlete pozici simulace mezi vědeckými metodami (např. tak, že uvedete rozdíl mezi indukcí, dedukcí a simulací).
Vysvětlete pojem model, uveďte hlavní kategorie modelů.
Jmenujte základní kroky tvorby agentových simulačních modelů.
Vysvětlete, z čeho se skládá a k čemu se používá protokol ODD.
Vysvětlete, proč je třeba agentové modely kalibrovat a jak se to provádí.
Vysvětlete rozdíl mezi validací a verifikací agentového simulačního modelu.
Popište, z jakých hledisek je model zkoumán při prověřování validity.
Jmenujte aplikační oblasti, v nichž se uplatňují modely pohybu chodců (davu).
Vysvětlete principy modelování pohybu chodců (davu).
Jmenujte (nakreslete) typické struktury, které mohou být generovány pohybem chodců.
Vysvětlete pojem základní diagram (ve vztahu k modelování pohybu chodců).
Uveďte, podle jakých hledisek lze klasifikovat modelovací přístupy, použitelné v simulacích pohybu chodců.
Popište modelování pohybu chodců za využití buněčného automatu.
Popište modelování pohybu chodců za využití modelu sociálních sil.