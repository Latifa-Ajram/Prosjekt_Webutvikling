~ DATA1200 FINAL ASSIGNMENT ~


* VALIDATION *
    Achecker ga oss feil på rekkefølge av h1,h2,h3 osv. Dette fikset vi opp, blant annet ved å sette h1 i footer, fordi
    den er en egen del.

    W3C-checker ga oss en feil med letter spacing. Vi hadde glemt å skrive px og rettet opp dette. Vi hadde også en fargefeil
    som vi rettet opp.

    HTML checker fant ingen feil.

    Kontrast test: Ved å undersøke kontrastfarger, fant vi at svart tekstfarge på gul-gradvis oransje oppnådde høy kontrast.
    Skjermbildet som er vedlagt viser at også bakgrunnsfargene oppnår AA kontrast nivå. 
    Vi benyttet oss også av fargeblindhet-filteret til Toptal, her ser det imidlertid ut til at bakgrunnsfargene våre ikke ble 
    oppfattet.
    

* ACCESSIBILITY *
    Vi har bevisst valgt å ha siden på norsk. Kan være ekskluderende. AChecker gir oss en del potensielle problemer for dette. 
    
    Alle bilder/medier er under 0,5mb for å sørge for at siden laster raskt og er tilgjengelig også for lavere 
    internetthastigheter.

    Vi brukte skjermleseren NonVisual Desktop Access (NVDA) for å teste ut hvordan en skjermleser fungerer på siden.

    Mer kan leses på siden accessibility/tilgjengelighet


* FARGER OG FONT *
    Vi valgte Chivo & Overpass som fontpar. Vi valgte fonter som er sans-serif da det kan være mer leselig for brukere. 
    Spesielt på mindre skjermer.

    Vi valgte en gjennomgående fargepalett hvor vi sjekket hvordan dette så ut for ulike typer fargeblindhet og sjekket opp mot 
    Color palette:
    1. Charcoal: #264653
    2. Persian green: #2a9d8f
    3. Orange yellow Crayola: #e9c46a
    4. Sandy Brown: #f4a261
    5. Burnt Sienna: #e76f51

        W3C Recommendation for color contrast:

        W3C Recommendation 05 june 2018: WCAG 2.1:
        1.4.3 Contrast (Minimum):
        Level AA
        "The visual presentation of text and images of text has a contrast ratio of at least 4.5:1".

        1.4.6 Contrast (Enhanced) 
        Level AAA
        "The visual presentation of text and images of text has a contrast ratio of at least 7:1". 


* BILDER *
    Alle bilder er kreditert og under lisens som gjør at vi kan bruke bildene. De inneholder alt-tekst med beskrivelse. 
    De fleste bildene er hentet fra Unsplash som ikke krever kreditering. Vi har likevel valgt å kreditere disse. 
    Noen bilder er hentet fra pressepakker som tillater fair use av bilder.
    Vi har sendt mail og bedt om tilatelse fra OsloMet om å bruke bilder fra deres Flickr. 
    https://www.flickr.com/photos/oslomet/albums

        "Du kan få bruke bildene fra OsloMets Flickr-side til eksamensoppgaven din.
        Husk å kreditere "fotograf og OsloMet - storbyuniversitetet"

        Lykke til med eksamen og ha en fin dag!

        Vennlig hilsen
        xx, foto@oslomet.no
    
    GIF-en av fisken vi har brukt på denne siden er hentet fra animated-gif-creator.com. Siden hevder at alt er for fri bruk,
    men det er vanskelig å finne copyright info vedrørende GIFs, samt å finne GIFs som er free use/Creative Commons. 
    Dette er fordi GIFs ofte er laget med forskjellig copyright materiale og er i utgangspunktet utfordrende når det kommer til 
    rettigheter. Vi viser til denne artikkelen om GIFs og copyright: 
    https://www.forbes.com/sites/propointgraphics/2016/04/30/animated-gifs-and-fair-use-what-is-and-isnt-legal-according-to-copyright-law/?sh=14cdeed0371b

    Favicon hentet fra https://www.favicon.cc/?action=icon&file_id=397733 og er utgitt med CC No rights reserved og trenger
    derfor ikke å krediteres.

* KILDER *
    Vi har hentet inspirasjon og skrevet om kode til hamburgermenyen vår. Dette er hentet fra:
    "hiding hamburger meny for tablet and dekstop" fra https://code-boxx.com/simple-responsive-pure-css-hamburger-menu

    Siden topical/aktuelt er kopiert fra en student i gruppen sin obligatoriske oppgave i DATA1100 teknologi og samfunn.
    Alt annen tekst er skrevet av gruppen selv.

    Tabindex i nav courtesy fra https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/tabindex

    Gradient background courtesy fra https://www.w3schools.com/css/css3_gradients.asp


* FUN PAGE *
    Vi har valgt å tolke at siden fun/moro er untatt krav om accessibility og er derfor ikke optimalisert for dette.
    Siden er heller ikke optimalisert for mobil da vi fokuserte på desktop til dette forsøket.

    Vi valgte å lage en egen css-fil til denne siden. Det er fordi denne er så ulik de andre sidene og inneholder en del kode som 
    det ikke er behov for å ha i den generelle style.css. 
    

* KUNNE HA GJORT *
    Vi har brukt en del non-semantic elements (div) istedenfor semantic elements. Vi har valgt å gi hver div en class for å
    kompensere for dette. Vi tenkte i ettertid at disse burde ha vært semantic elements, men det ville ført til veldig mye
    jobb som vi bare ikke hadde tid til å gjøre. 

    I reflection.html, accessibility.html og topical.html ligger det en section inne i main. Denne trenger ikke være der,
    men på grunn av litt misforståelser ble det brukt div-er hele veien istedenfor article/sections. Det førte dessverre til
    at alt havnet inne i en section. Vi valgte å ikke fjerne denne fordi det ville ført til veldig mye ekstra arbeid.

    Vi valgte å kun ha to CSS filer. I ettertid tenkte vi at det kanskje kunne ha vært mer ryddig med flere CSS filer,
    feks en for hver side. Vi har prøvd å kompensere ved å bruke tags og kommentarer for å strukturere bedre.

    Tab index fungerer ikke helt som den skal og vi har ikke hatt tid eller fått til å fikse den. Tanken er at brukeren
    skal kunne navigere siden kun ved hjelp av tab.

    Linker kunne vært i samme farge som color scheme. På en annen side kan det gjøre det vanskelig for brukere å skjønne
    at det er en link.