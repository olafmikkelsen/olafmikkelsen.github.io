---
title: "Norsk Bloggkorpus: et nytt korpus for å studere uformell, skriftlig norsk i tidsrommet 2010-2021"
collection: talks
type: "Talk"
permalink: /talks/2026-11-27-norsk-bloggkorpus
venue: "21. Møte om norsk språk (MONS 21)"
date: 2026-11-27
location: "Universitetet i Agder, Kristiansand, Norway"
---
Dette innlegget presenterer Norsk Bloggkorpus (NBK), en samling av 1001 norske blogger med metaspråklig informasjon om bloggforfattere og blogginnlegg. Innlegget tar for seg hvordan korpuset ble samlet inn og presenterer et kasusstudium som illustrerer hvordan dette korpuset kan bidra til norsk språkforskning.

NBK inneholder ca. 20 millioner ord i form av bloggposter som ble åpent publisert i perioden 2010-2021. Dataene ble innhentet gjennom Python-skriptet Trafilatura (Barbaresi 2021). Hver blogg er knyttet til følgende metadata (der denne informasjonen var tilgjengelig): aldersgruppe (født tiår), kjønn (kvinne, mann, annet) og opprinnelse (landsdel). Korpuset er tagget med Humit-taggeren (Haug et al. 2023) og glossa-søkesystemet (Nøklestad et al. 2017) er integrert i brukergrensesnittet. UiOs personverntrygge språkmodell GPT UiO ble brukt til å (i) eliminere irrelevant informasjon, (ii) maskere sensitiv og personlig informasjon, samt (iii) tagge hvert blogginnlegg for målform (bokmål, nynorsk, dialekt) og diskursemne. Gjennom denne formen for tagging kan man foreta mer presise søk som tillater å f.eks. inkludere innlegg på nynorsk som omhandler politikk, eller ekskludere alle innlegg som handler om matlaging eller hagearbeid.

Selv om det allerede finnes en rekke korpuser for norsk språk vil det her argumenteres at det finnes et behov for et korpus som inneholder et språk som er mer uredigert enn i referansekorpus, mer ‘fokusert’ (Barbaresi 2019) enn store webkorpus, samtidig som det er større og nyere enn eksisterende talespråkskorpus for norsk. For å illustrere dette behovet presenteres en undersøkelse av framtidskonstruksjonen bli å + INF (1) innenfor et bruksbasert konstruksjonsgrammatisk rammeverk (Goldberg 2019, Schmid 2020).

(1) Ikke hjelper det å fortelle at taxi hjem til meg BLIR Å KOSTE en formue (A0538, NBK)

Denne konstruksjonen er tradisjonelt regnet som et nordnorsk målmerke (Iversen 1954, Jahr 2009), men data fra NBK tyder på at den er i ferd med å spre seg til hele landet. Ettersom norsk allerede har tre konkurrerende framtidsuttrykk (skal + INF, vil + INF og kommer til å + INF) er det verdt å spørre seg hvorfor enkelte talere inkorporerer en fjerde konstruksjon i sin grammatikk. En multippel korrespondanseanalyse av 676 eksempler av de fire konstruksjonene, annotert for fire variabler (intensjonsstyrt/intensjonsuavhengig, grad av sikkerhet, avstand i tid, betingelse), viser at blir å + INF er semantisk umarkert sammenlignet med de tre andre. Dette tolkes som at talerne har behov for en mer nøytral framtidskonstruksjon som kan brukes i flere kontekster enn de eksisterende konstruksjonene, som er mer spesialiserte i sin framtidsreferanse.

Barbaresi, A. 2021. Trafilatura: A Web Scraping Library and Command-Line Tool for Text Discovery and Extraction. I Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing: System Demonstrations, 122–131.
Barbaresi, A. 2019. The Vast and the Focused: On the need for thematic web and blog corpora. I 7th Workshop on Challenges in the Management of Large Corpora (CMLC-7), 29–32.
Goldberg, A. E. (2019). Explain me this: Creativity, competition, and the partial productivity of constructions. Princeton University Press.
Haug, D. T. T., Yildirim, A., Hagen, K., & Nøklestad, A. (2023). I Rules and neural nets for morphological tagging of Norwegian - Results and challenges, 425–435.
Iversen, R. 1954. Noen syntaktiske notater. Maal og minne, 124–131.
Jahr, E. H. 2009. Futurumskonstruksjonen blir å reise i skriftspråket. Språknytt 3/2009, 31–33.
Nøklestad, A., Hagen, K., Johannessen, J. B., Kosek, M. & Priestley, J. 2017. A modernised version of the Glossa corpus search system. I J. Tiedemann (red.): Proceedings of the 21st Nordic Conference on Computational Linguistics, 251–254.
Schmid, H. J. 2020. The dynamics of the linguistic system: Usage, conventionalization, and entrenchment. Oxford University Press.
