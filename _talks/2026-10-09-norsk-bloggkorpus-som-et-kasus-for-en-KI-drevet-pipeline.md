---
title: "Norsk Bloggkorpus som et kasus for en KI-drevet pipeline for datarengjøring, anonymisering og tagging av målform og diskursemne"
collection: talks
type: "Talk"
permalink: /talks/2026-10-09-norsk-bloggkorpus-som-et-kasus-for-en-KI-drevet-pipeline
venue: "Norsk Språkteknologikonferanse"
date: 2026-10-09
location: "Universitetet i Oslo, Norway"
---
English: An AI-driven pipeline for data processing, anonymization and tagging of language variant and Topic of Discourse

Norsk Bloggkorpus er et korpus på ca. 20 millioner ord bestående av 1001 norske blogger, publisert i perioden 2010-2021. Dataene ble innhentet høsten 2021 ved å mate en liste med startadresser inn i Trafilatura (Barbaresi 2021). Hver blogg er knyttet til følgende metadata for hver forfatter (der denne informasjonen var tilgjengelig): aldersgruppe (født tiår), kjønn og opprinnelse (landsdel). Korpuset er tagget med Humit-taggeren (Haug et al. 2023) og glossa-søkesystemet (Nøklestad et al. 2017) er integrert i brukergrensesnittet, som vil bli gjort tilgjengelig på www.bloggkorpus.uit.no. Før det kan gjøres tilgjengelig, må det imidlertid rengjøres og anonymiseres. Dette bidraget fokuserer på en KI-drevet pipeline for det pågående arbeidet med rengjøring og anonymisering og diskuterer fordelene ved et korpus som er tagget for målform og diskursemne.

Store språkmodeller har vist seg å være pålitelige til anonymisering (Deußer et al. 2025), og UiOs personverntrygge språkmodell GPT UiO, som kan brukes med røde data, ble valgt til å (1) rengjøre dataene for irrelevant informasjon (f.eks. navigasjonsmenyer) som ikke ble luket ut av Trafilatura, og (2) maskere sensitiv og personlig informasjon. Et prompt for å utføre disse oppgavene ble utformet iterativt ved at språkmodellen selv ble bedt om å finne svakheter i promptet, og ble så matet inn i språkmodellen sammen med tekstutdrag på ca. 30 000 tegn gjennom API-tilgang. Siste skritt i pipelinen er tagging av målform og diskursemne. Da tekstene ble samlet inn, ble hver enkelt blogg knyttet til et emne og en målform. Dette viste seg å være en lite pålitelig måte å tagge dataene på, ettersom selv tematiske blogger kan inneholde svært ulike teksttyper, og enkelte forfattere veksler
mellom ulike målformer med varierende innslag av dialektale trekk. Ved å tagge hvert enkelt blogginnlegg for emne og målform vil man kunne foreta mer presise søk som tillater å f.eks. inkludere innlegg på nynorsk som omhandler politikk, eller ekskludere alle innlegg som handler om matlaging eller hagearbeid. Potensielle fordeler ved en slik inndeling vil bli diskutert, og casestudier som illustrerer hvordan korpuset skiller seg fra andre eksisterende korpuser vil bli presentert.

Barbaresi, A. 2021. Trafilatura: A Web Scraping Library and Command-Line Tool for Text Discovery and Extraction. I Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing: System Demonstrations, 122–131.

Deußer, T., Sparrenberg, L., Berger, A., Hahnbück, M., Bauckhage, C., & Sifa, R. (2025, October). A survey on current trends and recent advances in text anonymization. I IEEE 12th International Conference on Data Science and Advanced Analytics, 1–9.

Haug, D. T. T., Yildirim, A., Hagen, K., & Nøklestad, A. (2023). I Rules and neural nets for morphological tagging of Norwegian - Results and challenges, 425–435.

Nøklestad, A., Hagen, K., Johannessen, J. B., Kosek, M. & Priestley, J. 2017. A modernised version of the Glossa corpus search system. I J. Tiedemann (red.): Proceedings of the 21st Nordic Conference on Computational Linguistics, 251–254.
