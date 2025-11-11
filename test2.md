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
- - nejkratší cesty - vzdálenost mezi uzly s nejmenším počtem hran, které tvoří cestu

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

#### Malý svět

- mezi libovolnými dvěma uzly existuje poměrně **krátká cesta** a zároveň mají uzly **tendenci vytvářet shluky**

#### Šest kroků separace

- přes méně jak 6 vazeb lze propojit 2 náhodně vybrané jedince

#### Erdősovo číslo

- vyjadřuje vzdálenost spolupráce
- každý člověk (který spolupracoval s Erdasem) má číslo 1, další 2, k + 1
- vztahuje se k fenoménu "Malého světa"

### 5. Vysvětlete, jaký význam má stupeň uzlu a rozdělení stupňů uzlů v komplexní síti.

#### Stupeň uzlu

- počet hran uzlu

#### Rozdělení stupňů uzlů

- pravděpodobnost, že náhodně vybraný uzel má stupeň _k_

### 6. Vysvětlete alespoň tři pojmy, související s hledáním nejkratších cest v síti.

- nejkratší cesta - cesta mezi dvěma uzly v síti, která minimalizuje určitou metriku
- lokální centralita - stupeň uzlu
- průměr sítě - diametr - nejdelší ze všech nejkratších cest
- blízkost -  průměrná vzdálenost uzlu od všech ostatní uzlů

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

#### Výpočetní modely

- Používají matematické a výpočetní metody pro simulaci sociálních systémů, predikci a hlubší pochopení sociální 
dynamiky a zákonitostí

### 12. Vysvětlete, co je cílem modelů vývoje kooperace.

- vysvětlit jak a proč se v populaci vytváří spolupráce
- zkoumají:
1. podmínky za nichž se spolupráce vyplatí - strategie
2. Mechanismy přenosu strategií – genetické i sociální - učení od úspěšných nebo od rodičů

### 13. Vysvětlete, v čem spočívá opakované vězňovo dilema.

- zkoumá, jak může mezi racionálními hráči vznikat a udržovat se spolupráce
- Hra probíhá ve více kolech, přičemž si hráči pamatují předchozí chování soupeře a mohou na něj reagovat
- Krátkodobě se vyplácí zrada
- Dlouhodobě se vyplácí spolupráce

### 14. Jmenujte strategie, které lze použít při opakovaném vězňově dilematu.

- ALL-C/ALL-D - vždy spolupracovat / vždy zradit
- RANDOM - náhodné
- TIT-FOR-TAT - půjčka za oplátku (oko za oko) - v první kole spolupracovat, potom opakovat předchozí tah protihráče
- TESTER - v prvním kole zradit, potom opakovat předchozí tah protihráče
- PAVLOV – opakovat minulou volbu, pokud přinesla 3 nebo 5 bodů

### 15. Popište, jaké vysvětlující faktory podle E.Rogerse působí při šíření inovací (tj. co přispívá k rychlejšímu či pomalejšímu šíření inovace).

- Inovace - její prospěšnost, srozumitelnost, kompatibilita, složitost použití, dostupnost
- Způsob komunikace - jakými cestami se lidé o inovaci dozvídají
- Čas - proces osvojování, rychlost šíření
- Sociální systém, osvojitelé (inovátoři, časní osvojitelé, časná většina, pozdní většina, opozdilci)

### 16. Popište, jaké skupiny osvojitelů inovací definoval E.Rogers a jakou křivkou je popsáno rozložení skupin osvojitelů v populaci.

- Inovátoři - rádi riskují a zkoušejí novinky jako první
- Raní osvojitelé - inovaci přijímají brzy a často ovlivňují ostatní
- Raní následovníci - přijímají inovaci po delší úvaze, až když vidí její přínosy
- Pozdní většina - inovaci přijímají až tehdy, když je široce rozšířená a ověřená
- Opozdilci - přijímají inovace jako poslední nebo vůbec

### 17. V přednášce bylo popsáno několik modelů šíření inovací či nákazy, jeden z modelů jmenujte a popište jeho princip.

#### SIS

- Jedinci se po určité době mohou vrátit zpět do původního stavu - ztrácejí inovaci nebo imunitu
- Po určité době I → S, takže proces může probíhat cyklicky
- Tento model odpovídá např. módním trendům nebo produktům, které se lidé po čase „odnaučí“ používat
- 2 skupiny:
1. S - náchylní k přijetí inovace
2. I - dočasní nositelé inovace

### 18. V přednášce bylo vysvětleno, jak lze modelovat sociální vliv na utváření a polarizaci názorů, jeden z modelů popište.

#### Model omezené důvěry

- Agenti jsou umístěni na mřížku a interagují se svými sousedy (sever, jih, východ, západ)
- Každý agent má názor vyjádřený číslem x1, x2, ...
- Agenti se navzájem ovlivní jen pokud je rozdíl mezi jejich názory menší než určité prahové číslo |x1 – x2| < d
- Pokud je rozdíl větší než d, interakce nenastane a názory se neovlivní

### 19. Vysvětlete pojem síla slabých vazeb ve vztahu ke komplexním sítím.

#### Slabé vazby
- Méně intenzivní nebo méně časté kontakty mezi jednotlivci či skupinami
- Propojují různé sociální skupiny a umožňují přenos informací
- Čím více slabých vazeb v síti existuje, tím rychleji a efektivněji se informace šíří mezi vzdálenými částmi sítě
- Nedostatek slabých vazeb vede k izolaci skupin

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