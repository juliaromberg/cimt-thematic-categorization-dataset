# cimt-thematic-categorization-dataset

January 17, 2022 (corpus version 1.0)

About

This directory contains a dataset for thematic categorization of transport-related public participation contributions. The dataset is part of the CIMT PartEval Corpus and is further described in the publication "A Corpus of German Citizen Contributions in Mobility Planning: Supporting Evaluation Through Multidimensional Classification", to be published in Proceedings of the 13th Language Resources and Evaluation Conference (LREC 2022).

This work is based on research in the project CIMT/Partizipationsnutzen, which is funded by the Federal Ministry of Education and Research as part of its Social-Ecological Research funding priority, funding no. 01UU1904. (for more information, visit https://www.cimt-hhu.de/en/)

----------

Content

Each of the folders (one per public participation process) contains the coded dataset and the corresponding terms of use. The dataset csv-files contain one entry per document with the following information.

document_id: document id

title: title of contribution

text: content of contribution

url: original url of document

categories: binary coding (1 if category applies, 0 else)

----------

Categorization Scheme

-- modes of transport --

main categories:
+ non-motorized transport
+ motorized transport

sub-category of non-motorized transport
+ cycling
+ walking
+ scooters

sub-category of motorized transport
+ public transport (local)
+ public transport (long-distance)
+ commercial transport

-- specifications --

+ moving traffic
+ stationary traffic (parking)
+ new services
+ inter- and multimodality

More detailed information can be found in the paper.

----------

Citation

If you use the dataset, please cite the following paper:

Julia Romberg, Laura Mark, and Tobias Escher. 2022. A Corpus of German Citizen Contributions in Mobility Planning: Supporting Evaluation Through Multidimensional Classification. In Proceedings of the 13th Language Resources and Evaluation Conference (LREC 2022), Marseille, France. European Language Resources Association (ELRA).

----------

License

The annotated data corpus is available under the Creative Commons CC BY-SA License (https://creativecommons.org/licenses/by-sa/4.0/).

----------

Contact Person

Julia Romberg, julia.romberg@hhu.de, https://www.cimt-hhu.de/en/team/romberg/
