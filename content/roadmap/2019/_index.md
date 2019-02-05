---
title: Altinn roadmap 2019
linktitle: 2019
description: Overordnet roadmap for videreutvikling av Altinn i 2019.
---

Overordnet roadmap for videreutvikling av Altinn i 2019.

!["Vei i Brønnøysund"](../vei-i-brønnøysund.png)

## Q1 - 2019

### Tilby bruker mulighet til å definere "mine favoritt-aktører" for å lette aktørvalg i pålogging
I dag får bruker med mange aktører presentert alle aktører hvor de mest brukte aktørene står øverst. Konseptet "mest brukte aktører" skal fjernes og i stedet vil det tilbys funksjonalitet for å legge til - og fjerne favorittaktører.

### Forbedre logging av tjenesteeiers bruk av løsningen
Det skal etableres bedre logging av tjenesteeiers bruk av løsningen. Dette omfatter bedre oversikt over bruken av blant annet melding-, skjema-, innsyn-, autorisasjon/lenke-, integrasjons- og varslingstjeneste

### Ny innlesing av Enhetsregisteret
Følgende skal utføres:

1. Tilpasning/utvidelse av [Enhetsregisteret](https://www.brreg.no/om-oss/oppgavene-vare/alle-registrene-vare/om-enhetsregisteret/) i Altinn
2. Full re-innlesing av Enhetsregisteret i Altinn

### Nasjonal tjeneste for dokumentasjonsbevis - NADOBE
Det skal etableres en [løsning](/docs/guides/nadobe/) for innhenting, visning og oppbevaring av dokumentasjonsbevis fra leverandør.
![NADOBE](https://www.lucidchart.com/publicSegments/view/f3ce06b1-22a8-4b29-9af4-13dbeb258c83/image.png?width=800)

### Konsolidering av brukere med D-nummer
Det skal etableres en løsning slik at bruker med [D-nummer](https://www.skatteetaten.no/person/utenlandsk/norsk-identitetsnummer/d-nummer/)
som har fått fødselsnummer skal kunne få tilgang til det som lå i innboks/arkiv på D-nummer samt kunne videreføre en skattedialog som ble startet på D-nummer.

### Erstatte /api/help med dokumentasjon på Altinndocs
/api/help i REST-APIet skal avvikles. I stedet skal dokumentasjon av REST-APIet legges ut på Altinn Docs. Dette vil blir tilrettelagt gjennom at det skal etableres en offentlig tilgjengelig OpenAPI 3.0-spesifikasjon som blir lagt til grunn for å generere dokumentasjon.

Målsetning med endringen er å oppnå enklere vedlikehold av dokumentasjon av REST-API


## Q2 - 2019

### Altinn skytjenester
Det skal etableres testmiljø i skyen for å kunne teste tjenester utviklet i Altinnstudio. Se nærmere informasjon om Altinnstudio under Q2 2019.

### Altinn Studio (aka Tjenester 3.0) - "minimum viable product" (MVP)
Det skal etableres en minimumsløsning slik at tjenesteutviklere kan utvikle og produksjonssette enkle tjenester.  
Altinn Studio utvikles smidig og endringer tilgjengeliggjøres fortløpende på https://altinn.studio frem mot MVP.

Både [koden](https://github.com/Altinn/altinn-studio) og [backlog for videreutvikling](https://github.com/Altinn/altinn-studio/issues) ligger åpent på GitHub,
og alle kan [opprette bugs, stille spørsmål eller komme med forslag til forbedringer](https://github.com/Altinn/altinn-studio/issues/new/choose).

Hva vi til enhver tid jobber med vises i oversikten over [milepæler](https://github.com/Altinn/altinn-studio/milestones?direction=asc&sort=due_date&state=open).


## Q3 - 2019

### "Proffversjon" av innboks
Som proffbruker av Altinn skal det kunne være mulig å tilpasse innboksen slik at den bedre ivaretar behovene, samt legger til rette
for at en skal kunne gjøre fleksible søk på tvers av aktører.