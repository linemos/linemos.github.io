---
layout: post
title: "Ansiktsgjennkjenning og fotball"
---

I Danmark har fotballklubben Brøndby IF innført ansiktsgjenkjenning for å identifisere og utestenge uønskede tilskuere på sine hjemmekamper. Datatilsynet har godkjent bruken av overvåkning hos den private aktøren. 

Dette er ikke et innlegg om fotball.

Fotballklubbens bruk av ansiktsgjennkjenning bruker 150 punkter i bildet for å søke etter en match i deres interne bilderegister over folk med karantene 
(altså er utestengt for en periode for regelbrudd). Informasjonen skal slettes etter kampens slutt. Hvorfor det i det heletatt lagres er uvisst. 
Hvis funksjonen er tommel opp eller ned for å slippe tilskuere inn eller sperre dem ute fra stadion trenger ingen persondata å lagres. 
Flyten burde være:

```
if personHasQuaranteene(imageData):
    doNotOpenGate()
else:
    openGate()
```

Ingen lagring av bildedata eller annen persondata er nødvendig i denne flyten.
At det er i henhold til GDPR kan jeg ikke forstå. For å få godkjenning til å innhente disse persondataene (les: ansiktsbildet) skal det være nødvendig for driften av bedriften.
En fotballklubb kan fint operere uten denne teknologien og informasjonen - det er ca alle andre fotballklubber i verden beviset på.

At all prosessering og lagring gjøres visstnok på klubbens egne servere og ikke i skya gjør ikke praksisen mer eller mindre ok. Det er faktisk ikke relevant.

Kameraovervåkning settes i dag opp utenfor inngangsdørene til folk rundt om i Norge. For å blant annet varsle om potensielle kriminelle. 
De lærer om våre vaner, nabolag og omgangskrets. Det skal gjøre oss tryggere. Dataene sendes (i de fleste tilfellene) til leverandørens sky for å prosessere og analysere. 
Det vil si - data om alle som står foran utgangsdøra sendes til selskapets sky. Vi som ringer på disse dørene har ikke godkjent dette.

Som ellers i samfunnet er vi nødt til å stole på at de private aktørene både behandler dataene våre og sletter dem slik de lover. 
Det er ikke diskusjonen her nå.
En fotballklubb får tilltatelse til å lagre persondata om sine mangetusen tilskuere for å håndheve utestengelsen av et tosifra antall personer. 
Hjemme installerer vi lovlige overvåkningssystemer for å få varsler om folk som ikke ser ut som de som vanligvis pleier besøke ytterdøra vår.
Ansiktsgjenkjenning er på vei inn det internasjonale samfunnet (flyselskaper, sosiale medier, overvåkningskameraer...) både via telefonene våre og ute på gata. 
Det påvirker oss i Norge også. På internett er landegrenser og deres lovverk ganske flytende. Vi reiser mer utenlands. 
Norske bedrifter og privatpersoner blir påvirka og inspirert av det som skjer ellers i verden. 
Har vi kontroll når ansiktsgjenkjenninga begynner å nærme seg våre gater?
