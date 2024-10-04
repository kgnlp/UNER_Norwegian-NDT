# UNER_Norwegian-NDT

The UNER dataset for the Norwegian Dependency Treebank (NDT). UNER_Norwegian-NDT is part of [Universal NER](https://www.universalner.org/) and is based on the [UD_Norwegian-Bokmaal](https://github.com/UniversalDependencies/UD_Norwegian-Bokmaal/tree/master) and [UD_Norwegian-Nynorsk](https://github.com/UniversalDependencies/UD_Norwegian-Nynorsk/tree/master) datasets. This dataset was originally developed as part of [the NorNE dataset](https://github.com/ltgoslo/norne) and then converted into the UNER format.

The canonical reference commit to the Universal Dependencies dataset are [`ccbaec859f3947edf90201c725743b9aa4e7c76c`](https://github.com/UniversalDependencies/UD_Norwegian-Bokmaal/commit/ccbaec859f3947edf90201c725743b9aa4e7c76c) for Bokmaal and [`22c02622958f137314c2335b2a5f088d2b12dba0`](https://github.com/UniversalDependencies/UD_Norwegian-Nynorsk/commit/22c02622958f137314c2335b2a5f088d2b12dba0) for Nynorsk.

If you use this dataset, please cite the UniversalNER [paper](https://aclanthology.org/2024.naacl-long.243/):
```
@inproceedings{
  mayhew2024universal,
  title={Universal NER: A Gold-Standard Multilingual Named Entity Recognition Benchmark},
  author={Stephen Mayhew and Terra Blevins and Shuheng Liu and Marek Šuppa and Hila Gonen and Joseph Marvin Imperial and Börje F. Karlsson and Peiqin Lin and Nikola Ljubešić and LJ Miranda and Barbara Plank and Arij Riab and Yuval Pinter}
  booktitle={Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics (NAACL)},
  year={2024},
  url={https://aclanthology.org/2024.naacl-long.243/}
}
```

And cite the [paper](TODO) for the original dataset: 
```
@inproceedings{jorgensen2020norne,
  title={NorNE: Annotating Named Entities for Norwegian},
  author={J{\o}rgensen, Fredrik and Aasmoe, Tobias and Husev{\aa}g, Anne-Stine Ruud and {\O}vrelid, Lilja and Velldal, Erik},
  booktitle={LREC 2020, Twelfth International Conference On Language Resources And Evaluation},
  year={2020},
  organization={European Language Resources Association (ELRA)}
}
```

## Metadata

The following mapping was used to convert between the NorNE and UNER annotation tagsets:

```
"B-DRV": "B-OTH",
"B-EVT": "B-OTH",
"B-GPE_LOC": "B-LOC",
"B-GPE_ORG": "B-ORG",
"B-LOC": "B-LOC",
"B-MISC": "B-OTH",
"B-ORG": "B-ORG",
"B-PER": "B-PER",
"B-PROD": "B-OTH",
"I-DRV": "I-OTH",
"I-EVT": "I-OTH",
"I-GPE_LOC": "I-LOC",
"I-GPE_ORG": "I-ORG",
"I-LOC": "I-LOC",
"I-MISC": "I-OTH",
"I-ORG": "I-ORG",
"I-PER": "I-PER",
"I-PROD": "I-OTH",
"O": "O",
```
