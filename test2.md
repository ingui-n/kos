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

Hypotéza slabých vazeb: pokud má osoba
X vazbu s osobami Y, Z, tak je větší šance,
že i mezi Y a Z existuje vazba.
- Sociální síť je tvořena skupinami, intenzivně (silně)
  propojenými uvnitř a slabě spojenými navenek.
- Rychlost a míra šíření v síti závisí na spojích mezi prvky sítě.
  Slabé vazby mnohonásobně zvyšují počet propojení; s jejich
  počtem roste rychlost šíření.
- Pokud skupina nemá dostatek slabých vazeb, nezíská
  informace ze vzdálenějších částí sociální sítě (tj. členové
  skupiny budou mít přístup jen k novinkám a názorům zevnitř
  vlastní skupiny).

### 20. Vysvětlete pojem bod zvratu ve vztahu k sociální dynamice, popište jeho zachycení v konkrétním modelu.

- Moment, kdy se chování jednotlivce nebo skupiny náhle změní v závislosti na chování ostatních
- Při jehož překročení se jednotlivec rozhodne přidat k určitému kolektivnímu chování

Bod zvratu (prahová hodnota, treshold)
- Moment, kdy se jedinec přidá k davovému chování
- Prahová hodnota je individuální a souvisí s užitkem (ziskem)
  z toho, že se jedinec chová/nechová stejně, jako okolí
  5 agentů se rozhoduje, zda nosit výstřední
  módní doplněk, například červenou
  čepičku
  a) Prahové hodnoty 1,1,1,2,2 (průměr
  1,4) …žádný agent si čepičku nevezme
  b) 0,1,2,2,2 (průměr 1,4) …první agent si
  čepičku vezme, to je důvod, aby si ji
  vzal druhý agent, což je důvod, aby si ji
  vzali i další tři agenti najednou
  c) 0,1,2,3,4 (průměr 2,5)
  Kolektivní akce je pravděpodobnější, když
  prahové hodnoty jsou nižší a variabilnější.

### 21. Vysvětlete rozdíl mezi šířením jednoduché nákazy a šířením komplexní nákazy (v síti).

#### Jednoduchá nákaza

- Jedinci se „nakazí“ už po jediném kontaktu s nakaženým sousedem
- Šíření je lineární – pravděpodobnost přenosu závisí jen na kontaktu mezi dvěma uzly
- Modely: SI, SIS, SIR

#### Komplexní nákaza

- K přenosu je potřeba opakovaný nebo souběžný vliv více sousedů
- Šíření je nelineární – jedinec změní stav (např. přijme inovaci), až když podíl nakažených sousedů splní prahovou podmínku

### 22. Vysvětlete pozici simulace mezi vědeckými metodami (např. tak, že uvedete rozdíl mezi indukcí, dedukcí a simulací).
Výpočetní modely vs. vědecké metody
- Indukce
    - Pracujeme přímo se zkoumaným systémem, který může být i
      obrovský
    - Odhalování nových vztahů z empirických dat – např. vyhodnocování
      dotazníků, výsledků měření,…
    - Závěry jsou jen popisné
- Dedukce
    - Pracujeme se zjednodušeným modelem světa
    - Odvozování a dokazování nových tvrzení z daných předpokladů a
      platných axiomů - např. hledání rovnovážného bodu ve hře pro dva
      hráče za předpokladu axiomu o racionálním výběru
    - Exaktní důkazy jsou možné jen při malém modelu
- Simulace
    - Používají se modely (jako v dedukci), ale neprovádí se dokazování
      platnosti tvrzení, nýbrž generování dat, která zkoumáme a
      popisujeme a která mají jiný charakter, než data sbíraná/měřená a
      zpracovávaná induktivně

### 23. Vysvětlete pojem model, uveďte hlavní kategorie modelů.
Model = výsledek procesu
modelování; zjednodušená
reprezentace objektů nebo
jevů/procesů reálného světa
Typy modelů
- Mentální – základ lidského vnímání světa a myšlení
- Fyzické – reálné objekty; měřítko (zvětšení/zmenšení)
- Matematické – rovnice vyjadřující stav světa
    - Popisné modely vystihují vztahy proměnných v časovém
      okamžiku (např. regresní modely), nic nevysvětlují
    - Dynamické (analytické) modely říkají, jak se mění hodnoty
      proměnných v čase (např. diferenciální rovnice, např. vztah
      mezi velikostí populace predátora a populace kořisti; vztah
      nabídka-poptávka); hledáme řešení (např. rovnovážnou situaci)
- Výpočetní (programy nebo matematické zápisy) model
  zkoumáme simulací (výpočtem – spuštění programu
  nebo řešení rovnic); nutný je dostatečný výpočetní
  výkon

### 24. Jmenujte základní kroky tvorby agentových simulačních modelů.
1. Návrh modelu
2. Implementace modelu
3. Verifikace a validace
4. Simulace a analýza
5. Sumarizace a sdílení výsledků
6. Reprodukce simulace

### 25. Vysvětlete, z čeho se skládá a k čemu se používá protokol ODD.
Standardní protokol pro formulování a popis agentových modelů
<img width="1123" height="622" alt="image" src="https://github.com/user-attachments/assets/1dd03dc6-a9b9-48a4-8583-57ea79128a94" />
<img width="1182" height="763" alt="image" src="https://github.com/user-attachments/assets/35211397-e209-4e36-8f5f-b456219b0e76" />

### 26. Vysvětlete, proč je třeba agentové modely kalibrovat a jak se to provádí.
Agentové modely popisují individuální chování agentů pomocí mnoha parametrů
Tyto parametry nejsou univerzální a musí odpovídat reálnému chování lidí v daném prostředí.
Je tedy třeba kalibrovat (= doplnit kvantitativní informace, nastavit parametry podle reality nebo historických dat, dat z dotazníků, statisticky zpracovaných měření,…)

### 27. Vysvětlete rozdíl mezi validací a verifikací agentového simulačního modelu.
Validace = ověření, zda model odpovídá chování reálného systému  
Verifikace = ověření, zda model dělá, co si myslíme, že by dělat měl

### 28. Popište, z jakých hledisek je model zkoumán při prověřování validity.
- Strukturální validita = zda vztahy v modelu odpovídají vztahům v reálném systému
- Prediktivní validita = zda chování modelu odpovídá chování reálného systému
    - Základní validita = chování modelu se základními parametry odpovídá systému
    - Retrodikce = použijeme-li historická data, model dává odpovídající výsledky pro daný časový interval
    - Rovnováha = pokud lze analyticky stanovit rovnovážný stav při určitých podmínkách, model jej musí produkovat
    - Mezní hodnoty parametrů = zda se model chová přijatelně při krajích (i když nereálných) hodnotách

### 29. Jmenujte aplikační oblasti, v nichž se uplatňují modely pohybu chodců (davu).
- Dopravní plánování a architektura – efektivnost dopravy, evakuační postupy pro různá prostředí
- Psychologie – ověřování hypotéz o chování lidí za různých situací
- Marketing – porozumění chování lidí – muzea, letiště, nákupní centra
- Vizuální efekty – věrohodné modely pro filmy, počítačové hry
- Informatika – umělá inteligence, algoritmy pro předchozí aplikace

### 30. Vysvětlete principy modelování pohybu chodců (davu).
- Agent reprezentuje typického chodce, který se řídí jednoduchými pravidly
- Chůzi chápeme jako aktivitu částečně
    - cílenou (chodec obvykle má cíl)
    - náhodnou (vyhýbání se, drobné změny směru a rychlosti)
- Prostor je dvourozměrný
- Podstatné je měřítko
    - Prostorové (rozměr chodce ve vztahu k rozměru mapy)
    - Časové (rychlost chodce ve vztahu k běhu simulace)

### 31. Jmenujte (nakreslete) typické struktury, které mohou být generovány pohybem chodců.

- Tvorba linií (laning) – chodci jdoucí opačnými směry spontánně vytvářejí oddělené pruhy pohybu, aby si usnadnili průchod
- Fronty (queue formation) – v místech s překážkami nebo úzkými průchody vznikají fronty díky postupnému přizpůsobování pohybu ostatním
- Stop-and-go vlny – v hustém davu se pohyb střídá mezi zastavením a rozchodem, podobně jako u dopravních kolon
- Zip-efekt (zipper merging) – při průchodu zúženým místem se chodci střídavě zařazují z obou směrů, čímž vzniká plynulejší proud
- Herding (efekt stáda) – tendence lidí sledovat ostatní, zejména v nejistých nebo krizových situacích
- Faster-is-slower efekt – snaha jednotlivců zrychlit vede paradoxně ke zpomalení celého proudu (např. při panice u východu)

### 32. Vysvětlete pojem základní diagram (ve vztahu k modelování pohybu chodců).
- Empirická zjišťování vztahu mezi hustotou davu a rychlostí, liší se pro různé prostory (chodník, náměstí, schodiště,…)
- Analogie: pohyb tekutin
- Možnost validace modelu!

### 33. Uveďte, podle jakých hledisek lze klasifikovat modelovací přístupy, použitelné v simulacích pohybu chodců.

- Mikroskopický model – zachycuje jednotlivé chodce s individuálními charakteristikami a trasami
- Makroskopický model – agregovaný pohled, popisuje proudění davu pomocí veličin jako hustota a rychlost
- Rozlišení proměnných – prostor, čas a rychlost mohou být diskrétní nebo spojité
- Deterministický model – další stav systému je jednoznačně určen předchozím stavem a akcemi
- Stochastický model – využívá pravděpodobnosti k překlenutí neznalosti detailních procesů
- Pravidlový model (rule-based) – agent se řídí souborem pravidel pro různé situace
- Model sil (force-based) – chování agenta je výsledkem působení sil z okolí (cíle, ostatní chodci, překážky)
- Vysoce věrné modely (high-fidelity) – snaha o realistické zobrazení chování i za cenu složitosti
- Málo věrné modely (low-fidelity) – chodec reprezentován zjednodušeně (např. částice), menší počet parametrů

### 34. Popište modelování pohybu chodců za využití buněčného automatu.

- Prostor – reprezentován jako diskrétní 2D mřížka
- Buňka – může obsahovat nejvýše jednoho chodce, překážku nebo být prázdná
- Čas – diskrétní kroky; všichni agenti se pohybují paralelně
- Konflikty – při snaze více chodců vstoupit do stejné buňky se rozhoduje podle pravidel nebo pravděpodobností
- Směr pohybu – určen podle stavu okolních buněk (blízkost cíle, vyhýbání se kolizím)
- Reprezentace – matice pravděpodobností přechodu do sousedních buněk
- Varianty modelu:
    - různé rychlosti a typy chodců
    - různé definice okolí buňky (4, 6, 8 sousedů)
    - možnost více chodců v jedné buňce (rozšířené verze)

### 35. Popište modelování pohybu chodců za využití modelu sociálních sil.

- Každý chodec je modelován jako částice, na kterou působí síly:
    - přitažlivá síla směrem k cíli
    - odpudivé síly od ostatních chodců a překážek
    - vlivy prostředí – světelné, zvukové signály, stres, sklon terénu
- Výsledné chování je dáno součtem všech působících sil
- Do výpočtu mohou vstupovat i další faktory:
    - omezené zorné pole
    - snaha šetřit energií
    - držení se ve skupině
- Výhody:
    - realistické trajektorie a interakce
    - spontánně vznikají jevy jako lanes nebo oscilace u zúžení
- Nevýhody:
    - výpočetně náročný
    - nutnost kalibrace parametrů (intenzity sil, doba reakce)
