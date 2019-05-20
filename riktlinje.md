# Riktlinje för öppen källkod
De här riktlinjerna vänder sig till medarbetare inom it avdelningen.

## Det här handlar riktlinjerna om
Riktlinje för öppen källkod beskriver myndighetens förhållningssätt till öppen källkod och närliggande principer på en övergripande nivå och är styrande för it avdelningens domänstrategier, arkitekturriktlinjer och berörda processer.

### Det här är styrande i riktlinjerna
De styrande delarna i riktlinjen finns beskrivet i nedanstående angivna kapitel.
* Kapitel 3 visar myndighetens förhållningssätt till de i kapitel 2 beskrivna direktiv från Europeiska kommissionen och Sveriges regering.
* Avsnitt 3.1, 3.2 och 3.3 beskriver de styrande delarna kring produktval, supporttjänster och val av öppna projekt.
* Kapitel 5 och 6 beskriver styrande delar gällande hur myndighetens personal kan delta i öppna samarbeten och hur delning av källkod kan ske.
 
# 1 - Bakgrundsinformation
Öppen källkod kommer från den engelska termen Open Source som har rötterna i 50-talet där program- och maskinvara delades för att gemensamt utveckla tekniken och 1997 blev Open Source ett formellt begrepp.

Öppen källkod handlar till stor del om att källkod i form av funktionella program, fristående funktioner och script ska göras tillgängliga för andra att använda och förbättra, för att på så sätt driva utvecklingen framåt. Förutom detta handlar konceptet Öppen källkod om öppenhet i både arbetssätt och styrning vilket ofta realiseras med öppna gemenskapsprojekt (eng. "community") där vem som helst får ta del av utvecklingen, planer och själv komma med förslag och förbättringar.

 
# 2 - Styrande förutsättningar
**Europeiska kommissionen**

I Europeiska kommissionens publicerade dokument "Europeiska interoperabililtetsramen - Genomförandestrategi  finns styrande rekommendationer för hur medlemsstaterna ska bygga IT-tjänster. Rekommendationerna återkommer ofta till att både data och kod om möjligt ska göras tillgänglig för medborgarna och att medlemsstaterna helst ska återge förbättringar till de öppna projekten.

> **Rekommendation 2:**
> 
> Säkerställa lika villkor för programvara med öppen källkod och på ett aktivt och rättvist sätt överväga att använda programvara med öppen källkod, med beaktande av lösningens sammanlagda ägandekostnader.
> Användningen av teknik och produkter för programvara med öppen källkod kan bidra till minskade utvecklingskostnader, undvika inlåsning och möjliggöra snabb anpassning till bestämda verksamhetsbehov, eftersom utvecklarna hela tiden anpassar dem. Offentliga förvaltningar bör inte endast använda programvara med öppen källkod, utan när så är möjligt bidra till de berörda utvecklarna. Öppen källkod är en nyckelfaktor för den grundläggande EIF-principen om vidareutnyttjande.

Inom EU finns även en strategi för öppen källkod för kommissionens interna utvecklingsprojekt i syfte att stärka och styra användningen av programkod och mjukvara med öppen källkod. Se Open Source Software Strategy 

**Sveriges regering**

I regeringsdokumentet "Så enkelt som möjligt för så många som möjligt - från strategi till handling för e-förvaltning" finns nedanstående rekommendation.

_Den offentliga förvaltningens e-tjänster bör i så stor utsträckning som möjligt bygga på öppna standarder samt använda sig av programvara som bygger på öppen källkod och lösningar som stegvis frigör förvaltningen från beroendet av enskilda plattformar och lösningar._

 
# 3 - Användningar av lösningar med öppen källkod
Detta kapitel beskriver de styrande principerna för användande av lösningar baserade på öppen källkod inom myndigheten. Det generella förhållningssättet är att följa direktiven från Europeiska kommissionen och regering och därför alltid sträva efter användande av produkter med öppna och fria gränssnitt, baserade på öppna och icke-proprietära standarder. Detta i kombination med målet om öppenhet mot medborgare samt viljan om samverkan gör att öppna lösningar primärt ska väljas.
## 3.1 - Produktvalsprocessen
Vid anskaffning av nya produkter ska processen för produktval följas. Denna process ska följa ovanstående rekommendation om att öppna programvaror alltid ska övervägas förutsatt att ett öppet alternativ som uppfyller ställda krav finns tillgängligt samt att totalkostnaden inkl. implementering och ev. omställning är rimlig.

## 3.2 - Support och Enterprise-paketeringar
Ifall support och garanti om felrättningar på en öppen programvara krävs finns normalt nedanstående varianter.
Om behov av support för en viss produkt föreligger ska normalt sett alltid en Enterprise-paketering väljas. Detta eftersom de är väl testade, innehåller dokumentation och anpassade utbildningar samt att det i modellen ingår rättsligt skydd mot eventuellt patentintrång i den aktuella koden. Vid köp av enterprise-paketering ska det i första hand väljas leverantörer som arbetar enligt principen "community first" för att säkerställa att inga funktioner byggs exklusivt för enterprise-paketeringen vilket kan bidra till inlåsningseffekter.

**Enterprise-paketering**

En produkttillverkare som arbetar i ett eller flera communityprojekt och gör en egen paketering av projektets kod för att leverera den som en väl testad leverans, som ofta är certifierad ihop med andra tillverkares produkter. Betalning sker vanligtvis genom köp av supportprenumerationer.

**Supporterad communityrelease**

En leverantör med god kunskap kring en öppen lösning som erbjuder supporttjänster för den aktuella produkten. Leverantörens personal deltar ofta i communityn och kan på så sätt erbjuda både kunskap och möjlighet till felrättningar.

Vid köp av support på en communitybaserad produkt måste det i upphandlingsfasen säkerställas att supportgivaren dels har rätt kunskap men också möjlighet att utföra felrättningar i produkten och få dessa accepterade av communityn. Ett sätt att göra det är ställa krav på leverantörens deltagande i communityn, kräva redogörelse och insyn i historik av förbättringsförslag och kodbidrag i communityn.
## 3.3	- Välja rätt projekt
Det finns ett stort antal öppenkällkodsprojekt tillgängliga på Internet, vissa är väldigt aktiva med många medlemmar medan några är vilande eller består endast av ett fåtal personer.

Vid val av öppna community-projekt ska nedanstående checklista följas för att säkerställa ett bra och lämpligt val.
* Projektet ska vara publikt tillgängligt på Internet där källkod, felrapporter och förbättringsförslag kan läsas av vem som helst.
* Projektet ska vara öppet för bidrag av kod eller andra förbättringsförslag från vem som helst.
* Projektets kod ska av vem som helst kunna laddas ner, användas och förändras utan motprestation.
* Projektet ska vara aktivt, dvs. källkod och arbetsuppgifter uppdateras löpande.
* Projektets deltagare och de som aktivt bidrar med källkod bör inte enbart bestå av personal från ett och samma företag. Om så är fallet, verifiera att det aktuella företaget har en policy eller skrivelse som beskriver hur de arbetar med öppen källkod och säkerställer det öppna projektets framtid.
* Projektets bidragsgivare av källkod bör vara flera personer, undvik enmansprojekt.
* Projektet ska ha en kommitté eller motsvarande som granskar och godkänner kodbidrag för att säkerställa att skadlig kod inte kan föras in i projektet.
* Projektets källkod ska distribueras under någon av "Open Source Initiatives" godkända licensformer. https://opensource.org/licenses 

# 4 - Deltagande i öppna samarbeten
Myndigheten och dess personal får och bör aktivt delta i öppenkällkods-communityn genom att t.ex. rapportera problem, ge återkoppling, leverera förbättringsförslag och kodrättningar.

Ifall ett öppet projekt bedöms vara viktigt för den egna myndigheten men saknar avgörande funktionalitet kan anställd eller inhyrd personal tillåtas att på arbetstid bidra med kompetens och utvecklingsinsatser i projektet.
Genom att lämna ett kodbidrag till ett befintligt öppet projekt ärver den aktuella koden den licensmodell som projektet använder. 

Ifall omfattande eller strategiskt stöd ska ges till ett öppenkällkodsprojekt ska det godkännas av it avdelningens arkitekturstyrning.
# 5 - Skapande och delning av öppen källkod
I linje med rekommendationer från Europeiska kommissionen och regeringen ska offentlig verksamhet aktivt arbeta med öppenhet och att dela med sig av data, information och källkod där det är möjligt. Myndigheten ska därför aktivt arbeta med att öppna upp sina applikationer, egenutvecklade funktioner och lösningar för att där det är möjligt tillgängliggöras publikt.

Innan publicering ska materialets ägare först bedöma innehållets konfidentialitet och därefter beslutar och dokumenterar ansvarig IT-arkitekt publiceringen.

**Checklista inför publicering**
* Finns en beskrivning av underhållet för publiceringen 
* Materialet ska utifrån gällande informationsklassningsmodell och säkerhetsskydd vara lämpligt för publicering.
* Materialet ska vara av generell karaktär och får inte innehålla konfigurationsparametrar som är specifika för myndigheten.
* Koden får inte omfattas av en licensmodell som omöjliggör publicering.
* Koden ska vara helt skriven inom myndigheten, om tredjepartsprogramvara används i källkodform måste licensformerna vara kompatibla och ingå till fullo eller i enlighet med tredje partens krav.
* Kvalitén på publicerat innehåll ska vara hög och inte innehålla irrelevant information.
* Publicerat material får inte utsätta myndigheten för ökad risk eller på annat sätt påverka myndighetens anseende negativt.
* Licensform ska vara bestämd och vara godkänd av "Open Source Initiatives" som finns på https://opensource.org/licenses .
* Säkerhetsbedömning av kod ska göras och åtgärder ska vidtas för att säkra kvalité

# 6 - Planerad uppföljningsmetod
Uppföljning av riktlinjens efterlevnad samt uppdatering av innehåll och kontroll av dess aktualitet utförs av strategisk arkitekturstyrning på it avdelningen. Ändringar beslutas av it avdelningens ledningsgrupp.









