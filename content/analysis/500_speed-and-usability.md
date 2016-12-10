#Hastighet och användbarhet

Här nedanför är 4 st webbsiter analyserade ur ett hastighets- och användbarhetsperspektiv.

De sidor jag valt till analysen är valda dels på grund av att det är sidor som jag själv besöker eller har besökt, dels på grund av att det är lite olika stor målgrupper för respektive sida och dels för att det intryck jag fått är att några av dem har anställda som sköter administrationen/designen och andra sköts mer på ideel basis. Detta för att kunna se om där finns någon skillnad. Jag ville heller inte välja sidor som är för stora och därmed antingen har mycket anställd personal som gjort de förbättringar som går alternativt inte behöver bry sig lika mycket då de har ett väl förankrat varumärke som genererar trafik ändå.

Som metod för analysen har jag använt mig av [Google Insight](https://developers.google.com/speed/pagespeed/insights/) och av utvecklarvektygen (devtools) som är inbyggda i webbläsaren Firefox. Google Insight är ett automatiserat test som analyserar webbsidor och därefter ger rekomendationer för att optimera hastighet och användbarhet både på mobila och stationära enheter. Utvecklarverktygen i webbläsaren ger mätning av antalet resurser som laddas av sidan, sidans storlek samt laddningstid. Varje mätning har gjorts 3 gånger och sedan har ett genomsnitt tagits.

Rådatan till analysen finns i ett Google Spreadsheet som går att nå via denna [länk](https://docs.google.com/spreadsheets/d/1jmkSFQRl3EciOA_siclnT4U-PtDA41QdyhXKXHb8nuo/edit?usp=sharing).

###[Taffel.se](http://www.taffel.se)

En bloggportal för matintresserade och matbloggar.

[FIGURE src="image/analysis/taffel.png?area=0,20,0,20" class="w50 center"]

####Google Insight

Maxbetyg = 100

| Sida |Hastighet (mobil) | Användbarhet (mobil) | Förslagsöversikt (dator) |
|------|:----------------:|:--------------------:|:------------------------:|
| [Startsidan](http://www.taffel.se) | 49 | 99 | 39 |
| [Blogginlägg](http://www.taffel.se/blog/hannas-och-lisas-julkalender-lucka-9-natkompisar) | 48 | 99 | 46 |
| [Böcker](http://www.taffel.se/bocker) | 0 | 99 | 0 |

####Devtools

| Sida | Antal resurser | Storlek (kB) | Laddningstid (s) |
|------|:--------------:|:------------:|:----------------:|
| [Startsidan](http://www.taffel.se) | 195.67 | 11178.67 | 10.11 |
| [Blogginlägg](http://www.taffel.se/blog/hannas-och-lisas-julkalender-lucka-9-natkompisar) | 130.67 | 6026.67 | 7.96 |
| [Böcker](http://www.taffel.se/bocker) | 97.33 | 9383.00 | 6.03 |

####Reflektion

Användarmässigt får Taffel ett bra betyg. Den fungerar väl även på mindre skärmar. Förbättringsområden som finns är främst mot den stora mängd bilder som drar ner dess hastighet. Aktivering av cachning, komprimering och optimering av bilderna är det man borde fokusera på i huvudsak.


###[Tradevenue.se](http://www.tradevenue.se)

En portal för ekonomiintresserade med bloggar, forum och artiklar.

[FIGURE src="image/analysis/trade.png?area=0,20,0,20" class="w50 center"]

####Google Insight

Maxbetyg = 100

| Sida |Hastighet (mobil) | Användbarhet (mobil) | Förslagsöversikt (dator) |
|------|:----------------:|:--------------------:|:------------------------:|
| [Startsidan](http://www.tradevenue.se/) | 60 | 67 | 66 |
| [Blogginlägg](http://www.tradevenue.se/Investerarfysikern/trendf%C3%B6ljning-fallstudie-hundra%C3%A5rig-historik-och-svenska-alternativ) | 53 | 62 | 60 |
| [Portföljer](http://www.tradevenue.se/toplists) | 64 | 65 | 71 |

####Devtools

| Sida | Antal resurser | Storlek (kB) | Laddningstid (s) |
|------|:--------------:|:------------:|:----------------:|
| [Startsidan](http://www.tradevenue.se/) | 67.00 | 2461.00 | 2.74 |
| [Blogginlägg](http://www.tradevenue.se/Investerarfysikern/trendf%C3%B6ljning-fallstudie-hundra%C3%A5rig-historik-och-svenska-alternativ) | 63.00 | 3834.00 | 8.44 |
| [Portföljer](http://www.tradevenue.se/toplists) | 50.00 | 1868.00 | 1.99 |

####Reflektion

Tradevenue får inte toppbetyg i något. Den är förvisso ganska snabb redan från början men kan jobba med cachning och svarstiden från servern. Här ser vi även att det finns en del JavaScript och CSS som sidan måste vänta in innan den kan generera innehållet ovanför "the fold". Responsmässigt kan man arbeta med att göra tryckytorna vid bruk på mindre skärmar större.


###[Svenskorientering.se](http://www.svenskorientering.se)

Svenska orienteringsförbundets hemsida.

[FIGURE src="image/analysis/ori.png?area=0,20,0,20" class="w50 center"]

####Google Insight

Maxbetyg = 100

| Sida |Hastighet (mobil) | Användbarhet (mobil) | Förslagsöversikt (dator) |
|------|:----------------:|:--------------------:|:------------------------:|
| [Startsidan](http://www.svenskorientering.se) | 50 | 99 | 58 |
| [En nyhet](http://www.svenskorientering.se/Grenar/Orientering/Nyheter/alexanderssonochlysellmedistoromrostning) | 58 | 97 | 77 |
| [Börja med orientering](http://www.svenskorientering.se/Grenar/Orientering/Borjamedorientering/) | 58 | 99 | 76 |

####Devtools

| Sida | Antal resurser | Storlek (kB) | Laddningstid (s) |
|------|:--------------:|:------------:|:----------------:|
| [Startsidan](http://www.svenskorientering.se) | 59.00 | 2612.00 | 3.12 |
| [En nyhet](http://www.svenskorientering.se/Grenar/Orientering/Nyheter/alexanderssonochlysellmedistoromrostning) | 70.00 | 2536.00 | 4.24 |
| [Börja med orientering](http://www.svenskorientering.se/Grenar/Orientering/Borjamedorientering/) | 57.33 | 2117.00 | 3.68 |

####Reflektion

Också här behöver man arbeta med att ta bort JavaScript och CSS som blockerar rendering ovanför "the fold". Även optimering av bilder, aktivering av cachning och svarstider från servern behöver kolla över. Och till slut något som kan vara det enklaste, minifiera JavaScript, HTML och CSS.


###[Lidaloop.se](http://www.lidaloop.se)

Hemsidan för ett cykellopp strax utanför Stockholm.

[FIGURE src="image/analysis/lida.png?area=0,20,0,20" class="w50 center"]

####Google Insight

Maxbetyg = 100

| Sida |Hastighet (mobil) | Användbarhet (mobil) | Förslagsöversikt (dator) |
|------|:----------------:|:--------------------:|:------------------------:|
| [Startsidan](http://www.lidaloop.se) | 62 | 65 | 73 |
| [Inbjudan & PM](http://www.lidaloop.se/?p=448) | 65 | 66 | 78 |
| [Kontakt](http://www.lidaloop.se/?p=5) | 67 | 68 | 79 |

####Devtools

| Sida | Antal resurser | Storlek (kB) | Laddningstid (s) |
|------|:--------------:|:------------:|:----------------:|
| [Startsidan](http://www.lidaloop.se) | 95.67 | 4209.67 | 5.42 |
| [Inbjudan & PM](http://www.lidaloop.se/?p=448) | 52.00 | 1162.00 | 3.50 |
| [Kontakt](http://www.lidaloop.se/?p=5) | 49.00 | 1140.00 | 3.55 |

####Reflektion

Lida loop's sida har en hel del att förbättra. Cachning och få bort JavaScript och CSS som blockera ovanför "the fold" är en sak. En annan är att jobba med responsivitet och hur sidan visas på mindre skärmar. Man behöver både se över tryckytornas storlek samt teckensnittsstorlekar. Sen tillkommer saker från samtliga sidor ovan som optimering av bilder, förminskning av filer och aktivering av komprimering.


###Sammanfattning

Sammanfattningsvis får sidorna blandat resultat. De förbättringsområden som förekommer flest gånger är att jobba med cachning, optimera bilder, minifiera filer (JavaScript, HTML och CSS) och aktivera komprimering. Det som sticker ut allra mest och förekommer på samtliga sidor är att JavaScript och CSS hindrar rendering av sidan ovanför "the fold" tills de är inlästa.

Om man skulle rangordna sidorna från bäst till sämst skulle jag vilja se 2 olika kategorier. Hastighet och användbarhet.

Om vi rangordnar på hastighet får vi Svenska orienteringsförbundet i toppen följt av Lida loop och sen Tradevenue. Taffel kommer sist i denn aktegorin och av vad jag kan utläsa så beror detta på grund av sidans många bilder som tar stor plats. Om man här skulle jobba med kopmrimering, optimering och cachning av bilderna skulle man nog kunna komma på en bättre placering.

Användbarhetsmässigt om vi rangordnar så hamnar i stället Taffel i toppen. Sidan har bra layout och frungerar väl responsivt. Den följs av Svenska orienteringsförbundet och sedan av Lida loop och Tradevenue på sista plats.

När det kommer till gränsvärden att sträva mot i form av laddningstider är min uppfattning att 5 sekunder kan ses som ett maxtak. Här spelar dock hur webbsidan laddas in roll. Om jag måste vänte 5 sekunder innan jag ser skillnad på skärmen kommer jag att uppfatta sidan som långsam. Även om jag måste vänta 2 sekunder uppfattas den som långsam. Om sidan däremot börjar med att ladda det synliga innehållet och gör det snabbt och sedan laddar in resterande under tiden jag tar del av dess innehåll kan en längre laddtid var godkänd. Samtliga testade sidor uppfyller mina krav på laddtid. Att Taffel med en laddtid på uppåt 10 sekunder gör det har just med att det synliga innehållet laddas betydlig snabbare och allteftersom.


###Analysteam

Ovan analys är gjord av mig själv, Tobias Almroth som en del av kursmoment 05 i Designkursen.
