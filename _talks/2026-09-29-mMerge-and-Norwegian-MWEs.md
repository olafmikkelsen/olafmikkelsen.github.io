---
title: "A data-driven information-theoretic approach to constructicon building: the mMERGE algorithm and Norwegian multiword expressions"
collection: talks
type: "talk"
permalink: /talks/2026-09-29-mMERGE-and-Norwegian-MWEs
venue: "XXII EURALEX INTERNATIONAL CONGRESS 2026"
date: 2026-09-29
location: "Österreichische Akademie der Wissenschaften, Vienna, Austria"
---

This talk explores the use of objective statistical methods to detect construction candidates in large corpus data. While the idea of applying objective frequency-based criteria to the shaping of construction inventories is not new, this study reports on: 1) the first extensive application of the mMERGE algorithm for the purpose of constructicon building, 2) leveraging a “focused” corpus representative of informal discourse, and 3) a study aimed at building a thorough and representative constructicon for Norwegian. More specifically, this talk advances the computational aspects of constructicography by exploring how constructions can be identified using the newly developed statistical algorithm mMERGE (Ben Youssef 2024; Gries 2022), which represents a data-driven, information-theoretic approach to constructicon building. This aligns with the workshop’s focus on leveraging large corpora and NLP techniques.

mMERGE is a corpus-driven algorithm for the inductive discovery of multiword expressions (MWEs) based on the interaction of multiple distributional dimensions. Implemented in Julia, the algorithm combines measures of token frequency, dispersion across corpus parts, directional association strength, and contextual entropy in order to identify lexically cohesive and distributionally stable sequences (Ben Youssef 2024; Gries 2022).

In this study, we applied mMERGE to the Bokmål part of the Norwegian Blog Corpus (NBC), yielding a dataset consisting of approximately 17 million words drawn from more than 700 blogs written between 2010 and 2022, representing diverse demographic and thematic profiles. This corpus is more “focused” (Barbaresi 2019) than the Norwegian web corpus NoWaC, includes sociodemographic information about language users, contains language that is more informal and spoken-like than that of the Leksikografisk bokmålskorpus, and is significantly larger and more recent than the available spoken corpora (Nordisk dialektkorpus and the BigBrother-corpus).

Following preprocessing and tokenization, the corpus is analyzed iteratively over 10,000 iterations in order to extract candidate MWEs and recurrent lexical bundles. We argue that the use of mMERGE on NBC enables a large-scale, bottom-up exploration of idiomatic regularities in naturally occurring Norwegian online discourse, while also providing a basis for extending the algorithm beyond contiguous MWEs toward partially schematic and slot-based constructions.

In this talk we will present the results of this case study and compare them with a list of 2,000 construction candidates previously collected in the Norwegian Constructicon via crowdsourcing.

References:
Barbaresi, A. (2019). The Vast and the Focused: On the need for thematic web and blog corpora. Proceedings of the Workshop on Challenges in the Management of Large Corpora. Cardiff, UK. 29-32. Retrieved from https://hal.science/hal-02447305v1/file/Barbaresi_The_Vast_and_the_Focused_2019.pdf
Ben Youssef, C. (2024). mMERGE: A corpus-driven multiword expressions discovery algorithm. Doctoral dissertation, University of California, Santa Barbara. ProQuest Dissertations & Theses. Publication No. 31763846. Retrieved from https://www.proquest.com/dissertations-theses/mmerge-corpus-driven-multiword-expressions/docview/3163318667/se-2?accountid=17260
Endresen, A. & O. Mikkelsen. (2024). Ten good reasons to build the Norwegian ConstructiCon, a dictionary of grammar. Lexicographica 40(1), 121-145. https://doi.org/10.1515/lex-2024-0007
Gries, S. T. (2022). Multi-word units (and tokenization more generally): A multi-dimensional and largely information-theoretic approach. Lexis, 19. https://doi.org/10.4000/lexis.6231
Språknett 2024 – The Norwegian Constructicon. A digital network of Norwegian constructions. Available at https://constructicon.github.io/norwegian/
