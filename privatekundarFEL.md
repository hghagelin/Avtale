---
Bruksvilkår for private kunder av de offentlige fellesløsningene
---

# 1. Generelle

## 1.1 Om Bruksvilkår

Dette bruksvilkåret gjelder for private virksomheter som skal ha tilgang til eller tilby et API som er regulert av en offentlig virksomhet eller ledd i offentlig myndighetsutøvelse.

Når virksomheten skal ha tilgang til et API for ren maskin til maskin kommunikasjon benyttes Maskinporten. Når en privatperson skal godkjenne datadeling ved hvert enkelt tilfelle benyttes ID-porten som et tillegg.

Virksomhet som skal gi tilgang til et API gjennom Maskinporten vil i det videre bli omtalt som «tilbyder av data» eller «tilbyder». Virksomhet som skal få tilgang til et API gjennom Maskinporten vil i det videre bli omtalt som «konsument av data» eller «konsument».

## 1.2 Om Maskinporten og ID-porten
Maskinporten er en løsning for å sikre korrekt tilgang til data i kommunikasjon mellom maskiner. Løsningen er i stor grad selvbetjent. Tilbyder av data kan definere hva konsument av data skal ha tilgang til, hvordan konsument kan bruke tilgangen, og hvem som kan bli konsument av det aktuelle API. Ved å legge til ID-porten i kommunikasjonen, kan privatpersoner autentisere seg og autorisere tilgang i enkelttilfeller. Det kan være når innbygger, enten påvegne av seg selv eller på vegne av andre, vil dele en offentlig etats data om seg selv med andre offentlige eller private virksomheter.

## 1.3 Finansiering
Maskinporten baserer seg på brukerfinansiering for API-tilbyder. Dette skjer i samsvar med gjeldende kostnadsmodell for Maskinporten som ligger på Samarbeidsportalen.

Autentisering med ID-porten blir fakturert i samsvar med kostnadsmodellen for ID-porten, der det er API-tilbyder som bærer kostnaden.

Kunden faktureres i EHF-format, og skal oppgi ett fakturamottak og referanse ved etablering. Kundens kostnader med integrasjon dekkes av kunden selv.

# 2. Kundens ansvar
## 2.1 Generelt
Tilbyder av data og konsument av data skal sørge for å ha det nødvendige grunnlag for samhandlingen mellom hverandre. Dette kan være lov-/forskriftshjemmel, avtale med offentlig virksomhet, pålegg i form av vedtak, etc. Digdir er ikke part i et slikt grunnlag.

I den grad samhandlingen omfatter behandling av personopplysninger, må rettigheter til behandling være dokumentert og eventuelle databehandleravtaler inngått. Når ID-porten brukes til deling av data som er basert på innbyggers samtykke, må systemene kunne dokumentere samtykke, samt at rettighetene som gjelder samtykke i personopplysningsloven må følges. Dette er utenfor Digdirs ansvar.

Tilbyder av data og konsument av data plikter å holde Digdir skadefri for forhold som gjelder kundenes manglende oppfyllelse av avtaler og regelverk.

Tilbyder av data og konsument av data plikter å holde rollestyringsmekanismer oppdatert, slik at kun bemyndigede ansatte i virksomheten får tilgang til selvbetjening.

Tilbyder av data og konsument av data skal håndtere sertifikat og nøkler på en måte som sikrer at uvedkommende ikke kan misbruke disse.

## 2.2 Kundens ansvar som API-tilbyder
Tilbyder av data skal ha rutiner for å administrere konsumenter som skal ha tilganger.

Tilbyder av data skal sikre at konsument som delegerer ansvaret for sin integrasjon til en underleverandør er informert om konsekvensene av delegeringen. For eksempel kan tilbyder sin avtale med konsument inneholde informasjon om at konsumenten kan delegere sin tilgang videre til en leverandør, men at ansvaret fortsatt ligger hos API-konsument.

## 2.3 Kundens ansvar som API-konsument
Konsument av data skal følge gode prinsipper for tilgangsstyring, slik at kun personell og systemer med tjenstlig behov har tilgang til token fra maskinporten og data utlevert fra tilbyder.

Konsument av data skal i samsvar med prinsipp om dataminimering sørge for at det ikke hentes ut eller lagres mer data enn nødvendig.

Konsument av data som bruker underleverandør for å få tilgang til API må sørge for å delegere tilgang til underleverandøren. Konsument og underleverandør må ha avtaler som regulerer forholdet mellom dem.

# 3. Digdirs ansvar
Digdir skal ha på plass rutiner og systemer som underbygger og i størst mulig grad sikrer at virksomhet som registreres som konsument er den virksomheten den utgir seg for. Digdir skal ha på plass systemer og rutiner som så langt som mulig sikrer at bare bemyndiget person i virksomhetene har mulighet til å gjøre endringer gjennom selvbetjeningsløsningen. Av hensyn til sikkerhet kan ikke Digdir manuelt gi tilganger.

For å sikre at API-definisjoner er tilstrekkelig unike skal Digdir tildele et API-prefiks til tilbydere og sørge for at dette er unikt innenfor Maskinporten. Digdir kan ved berettiget grunn til mistanke om misbruk eller etter varsel fra tilbyder av data fjerne en tilgang.

## 3.1 Selvbetjening
Maskinporten (med ID-porten) er basert på at kundene selv konfigurerer løsningen ved hjelp av selvbetjeningsfunksjonalitet. Av sikkerhets- og integritetshensyn har Digdir ikke anledning til å manuelt tildele tilganger til tilbyders API.

Selvbetjeningsfunksjonalitet er tilgjengelig både over API og som web-løsning på Samarbeidsportalen.

## 3.2 Logger
Selvbetjeningsløsningen logger endringer, aktivitet og hvem som utfører endringene.

Maskinporten og ID-porten logger utstedelser av token.

Digdir lagrer logger i 13 måneder.

## 3.3 Samarbeidsportalen
Samarbeidsportalen er den primære informasjons- og varslingskanalen fra Digitaliseringsdirektoratet om fellesløsningene. Vi forvalter og drifter Samarbeidsportalen. Du finner løsningsinformasjon, teknisk dokumentasjon og stegvis guide for hvordan ta i bruk de ulike fellesløsningene, statistikk for bruk og drift av fellesløsningene, status og driftsmeldinger, utviklingsplaner osv.

Kunder som godtar bruksvilkår, får tilgang til Min profil som gir tilgang til selvbetjening og vedlikehold av virksomhetsinformasjon i våre systemer.

Kunden har selv ansvar for å holde listen over kontaktpunkter i egen virksomhet og annen nødvendig informasjon om egne tjenester oppdatert i Min profil. Spesielt viktig er varslingspunkt for kundens tjenester, da dette varslingspunktet vil motta varsler fra Digitaliseringsdirektoratet ved kritiske og alvorlige hendelser.

## 3.4 Brukerråd
Brukerrådet skal diskutere status, endringsønsker og videreutviklingsprosjekter for fellesløsningene, samt annet av relevans for kundenes bruk av fellesløsningene. Mandat for brukerrådet for Digdirs digitale fellesløsninger er tilgjengelig på Samarbeidsportalen. Deltakelse i brukerrådet er åpen for alle kunder, men Digdir har mulighet til å begrense antall deltakere.

## 3.5 Styringsråd

Styringsrådet er et rådgivende organ for Digitaliseringsdirektoratet og skal særlig behandle viktige saker som gjelder fellesløsningene. Mandat for styringsrådet  er tilgjengelig på Samarbeidsportalen.

## 3.6 Produktråd

Ved behov kan styringsrådet og Digdir opprette produktråd for Digdirs produkter eller grupper av produkter. Produktrådene kan være permanente eller for en periode, og rapporterer til styringsrådet. Mandat for produktrådet er tilgjengelig på Samarbeidsportalen.

## 3.7 Brukerråd

Brukerrådet skal diskutere status, endringsønsker og videreutviklingsprosjekter for fellesløsningene, samt annet av relevans for kundenes bruk av fellesløsningene. Mandat for brukerrådet er tilgjengelig på samarbeidsportalen.

# 4. Tjenestenivå og vedlikehold
## 4.1 Tjenestenivå
Alle krav som er spesifisert i disse bruksvilkår for datadeling, skal følges opp slik at tjenester og ytelser blir levert med avtalt og tilfredsstillende kvalitetsnivå.

Digdir skal følge opp at autorisasjonstjenester levert for datadeling holder det tjenestenivå som fremgår av de til enhver tid gjeldende avtaler Digdir har med eksterne leverandører.

Måleperiode for alle tjenester og ytelser er månedlig (per kalendermåned).

## 4.2 Tilgjengelighet og responstid
Driftsperioden for ID-porten og Maskinporten er 24 timer/7 dager i uken/365 dager i året.

| Beskrivelse                                                       | Krav  |
| ----------------------------------------------------------------- | ------ |
| Tilgjengelighet til Maskinporten, ID-porten og selvbetjenings API |	99,90% |
| Responstid |	Mindre enn 1 sekund for 95 % av utsendelsene i gjennomsnitt |
| Ytelse |	720 000 tokenutstedelse i timen for tjenesten totalt |

## 4.3 Planlagt vedlikehold - vedlikeholdsvindu
Vedlikeholdsvindu er avtalt tid der tjenesten kan være utilgjengelig, og benyttes til vedlikehold av maskinvare, oppgraderinger, service med mer.

Digdirs vedlikeholdsvindu er natt til tirsdag. For nærmere informasjon om tidspunkt og antall, se spesielle bruksvilkår for den enkelte fellesløsning.

### 4.3.1 Varsling av planlagt vedlikehold
Digdir skal minimum 5 virkedager på forhånd varsle om bruk av vedlikeholdsvindu. Varsling skjer på Samarbeidsportalen.

Mindre endringer produksjonsettes fortløpende uten varsling.

# 5. Personopplysninger
Både konsument av data og tilbyder av data må ha behandlingsgrunnlag for personopplysninger i token (personopplysningsloven art. 6, jf § 1) og saklig og nødvendig behov for behandling av fødselsnummer (personopplysningsloven § 12).

Token blir ikke loggført av Digdir.

Med henvisning til personvernforordningen art. 28, punkt 3, jf personopplysningsloven § 1 angis følgende:

Dersom API/Scope tillater det, kan konsumenten bruke fødselsnummer for å minimere tilgangen til informasjon i APIet. Digdir vil være databehandler for fødselsnummer og eventuell annen informasjon i tokenet som sammen med fødselsnummer kan regnes som personopplysninger. Innhold i token blir loggført.
Digdir og alle personer som er autorisert til å behandle personopplysninger er underlagt taushetsplikt om alle forhold de får innsyn i ved å behandle personopplysninger i henhold til denne avtalen.
Digdir gjennomfører egnede tekniske og organisatoriske tiltak for å oppnå et sikkerhetsnivå som er egnet med hensyn til risikoenetter GDPR art 32.
Digdir bruker databehandlere for å oppfylle sine plikter etter disse vilkårene. Kunden gir generell tillatelse til at Digdir kan endre databehandlere. Eventuelle endringer skal varsles gjennom saamarbeidsportalen med tre måneders frist.
Digdir har rutiner for å oppfylle den registrertes rettigheter etter forordningen kap III.
Digdir bistår med oppfylling av plikter etter forordningen art 32-36.
Sletting og tilbakelevering er ikke aktuelt i dette tilfellet.
Ved bruk av Maskinporten med ID-porten vil følgende gjelde for autentisering av innbyggere:

Digdir er behandlingsansvarlig for behandling av personopplysninger i ID-porten i forbindelse med autentisering.

Ved autentisering lagrer og videreformidler Digdir sluttbrukers fødselsnummer, sikkerhetsnivå for gjennomført autentisering, sluttbrukers språkvalg og hvilken e-ID som ble benyttet for autentiseringen. Digitaliseringsdirektoratet lagrer opplysningene om autentisering i ett år.

Kunden er behandlingsansvarlig for opplysninger om autentiseringsoperasjoner som er utlevert fra ID-porten i forbindelse med autentisering av sluttbrukere.
