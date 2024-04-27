# Summary

UD Telugu_English-TECT is a Telugu-English code-switching treebank. 

# Introduction

The treebank consists of edited data from the Telugu UD treebank (Rama and Vajilla, 2021), sentences from a grammar book, and the MASSIVE dataset, spoken conversational utterances in Telugu (FitzGerald et al., 2022; Bastianelli et al., 2020). The sentences were randomly selected from each corpus. The sentences were romanized and each sentence was altered to contain at least one code-switch. The sentences were then annotated following the Universal Dependencies annotation scheme. 

# Data Split

In total, there are 98 sentences. The data is split into 62 sentences for train and 36 sentences for test. 

# Language IDs

The following language Ids are stored in the MISC column:

- "te": Telugu
- "en": English
- "univ": Punctuation, symbols, numbers, etc. 

# Acknowledgments

 We want to thank the creators of the Telugu UD treebank and MASSIVE dataset for their corpus. 

## References

* Rama, Taraka and Vajilla, Sowmya (2021). The Telugu UD treebank

'''
@misc{UD_Telugu-MTG,
year = {2021},
title = {The Telugu UD treebank},
author = {Rama, Taraka, Vajjala, Sowmya},
url= {https://github.com/UniversalDependencies/UD_Telugu-MTG}
}
'''

* FitzGerald, J., Hench, C., Peris, C., et al., (2022). Massive: A 1m-example multilingual natural language understanding dataset with 51 typologically-diverse languages. arXiv preprint arXiv:2204.08582.

'''
@misc{fitzgerald2022massive,
      title={MASSIVE: A 1M-Example Multilingual Natural Language Understanding Dataset with 51 Typologically-Diverse Languages}, 
      author={Jack FitzGerald and Christopher Hench and Charith Peris and Scott Mackie and Kay Rottmann and Ana Sanchez and Aaron Nash and Liam Urbach and Vishesh Kakarala and Richa Singh and Swetha Ranganath and Laurie Crist and Misha Britan and Wouter Leeuwis and Gokhan Tur and Prem Natarajan},
      year={2022},
      eprint={2204.08582},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
''' 

* Emanuele Bastianelli, Andrea Vanzo, Pawel Swietojanski, and Verena Rieser. (2020). SLURP: A Spoken Language Understanding Resource Package. In Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP), pages 7252–7262, Online. Association for Computational Linguistics.

'''
@inproceedings{bastianelli-etal-2020-slurp,
    title = "{SLURP}: A Spoken Language Understanding Resource Package",
    author = "Bastianelli, Emanuele  and
      Vanzo, Andrea  and
      Swietojanski, Pawel  and
      Rieser, Verena",
    booktitle = "Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2020.emnlp-main.588",
    doi = "10.18653/v1/2020.emnlp-main.588",
    pages = "7252--7262",
    abstract = "Spoken Language Understanding infers semantic meaning directly from audio data, and thus promises to reduce error propagation and misunderstandings in end-user applications. However, publicly available SLU resources are limited. In this paper, we release SLURP, a new SLU package containing the following: (1) A new challenging dataset in English spanning 18 domains, which is substantially bigger and linguistically more diverse than existing datasets; (2) Competitive baselines based on state-of-the-art NLU and ASR systems; (3) A new transparent metric for entity labelling which enables a detailed error analysis for identifying potential areas of improvement. SLURP is available at https://github.com/pswietojanski/slurp."
}
'''

# Changelog

* 2024-05-15 v2.14
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.14
License: CC BY-SA 4.0
Includes text: yes
Genre: spoken
Lemmas: automatic
UPOS: converted with corrections
XPOS: not available
Features: not available
Relations: automatic
Contributors: Vissamsetty, Anishka
Contributing: here
Contact: anishka18v@gmail.com
===============================================================================
</pre>
