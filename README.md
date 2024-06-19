# e-RTE-3-ITA Dataset: Textual Entailment with Natural Language Explanations

## Description
The e-RTE-3-ITA dataset is an emended, enriched, and manually curated version of the Italian RTE-3 dataset, which is the Italian translation of the Textual Entailment English dataset used in the RTE-3 Challenge (http://pascallin.ecs.soton.ac.uk/Challenges/RTE3/Datasets/).

Like RTE-3 and RTE-3-ITA, the e-RTE-3-ITA dataset is composed of a development set and a test set, each containing 800 text-hypothesis (T/H) pairs.

In the e-RTE3-it dataset, each text-hypothesis pair, in addition to the ’entailment’, ’contradiction’, or ’neutrality’ label, has been enriched with:
- an explanation for the label itself;
- the level of confidence with which the annotators could write the explanation;
- in cases where the annotators did not agree with the original label, an alternative label along with an explanation for the new label.

Furthermore, in e-RTE-3-it, label mismatches between RTE-3-ITA and the original English dataset have been emended, so that e-RTE-3-ITA and the original RTE-3 datasets are perfectly overlapping.

This release contains the following files:

- DEV.xml (800 T/H pairs enriched with explanations corresponding to the RTE-3 English development set)
- TEST.xml (800 T/H pairs enriched with explanations corresponding to the RTE-3 English test set)
- e-RTE-3-it.dtd (DTD for the dataset)


For further information about this data release, please contact:

Andrea Zaninello	<azaninello@fbk.eu>  
Sofia Brenna <sbrenna@fbk.eu>
Bernardo Magnini	<magnini@fbk.eu>


## Citation

If you use this dataset, please cite this article:
```bibtex
@inproceedings{zaninello-etal-2023-erte3it,
    title = "Textual Entailment with Natural Language Explanations: The Italian e-RTE-3 Dataset",
    author = "Andrea Zaninello and Sofia Brenna and Bernardo Magnini",
    booktitle = "Proceedings of the 9th Italian Conference on Computational Linguistics",
    month = dec,
    year = "2023",
    address = "Venice, Italy",
    publisher = "CEUR Workshop Proceedings (CEUR-WS.org)",
    volume = "35.96",
}
```
