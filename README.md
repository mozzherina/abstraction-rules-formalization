# Abstraction rules formalization

This repository contains full information about formalisation of rules for ODCMs' abstractions originally specified for OntoUML as GODPs.  


- [Terms and Abbreviations](#terms-and-abbreviations)
- [Structure of the project](#structure-of-the-project)
- [Authors](#authors)
- [How to cite this project](#how-to-cite-this-project)
- [Acknowledgements](#acknowledgements)


## Terms and Abbreviations

- ODCM    - Ontology Driven-Conceptual Model
- UFO     - Unified Foundational Ontology
- gUFO    - lightweight implementation of UFO for Semantic Web applications
- UML     - Unified Modeling Language
- OntoUML - language designed to enrich UML with the concepts of the UFO
- DOL     - The Distributed Ontology, Modeling and Specification Language 
- Hets    - The heterogeneous tool set
- ODP     - Ontology Design Pattern
- GODP    - Generic Ontology Design Pattern


## Structure of the project

The project contains Hets execution file. Since the current available version of Hets does not support GODPs, we provide a distribution that accepts the patterns. To run it, you need to install Hets according to the instructions in [Hets Website](http://hets.eu/), and then replace the executable with the file provided here. 

Each folder contains the following information about the abstraction rule: 
1. models of matching and replacing graphs (*.png);
2. GODP in DOL based on gUFO (*.dol);
3. example for pattern instantiation (*.dol, *.png).

```txt
/
|   hets
+---rule-1_folder/
|   |   graph_matching.jpg
|   |   graph_replacing.jpg
|   |   formalisation.dol
|   |   example.dol
|   |   example_matching.jpg
|   |   example_replacing.jpg
+---rule-2_folder/
...
+---rule-11_folder/
```


## Authors

- MSc. Elena Romanenko [[GitHub]](https://github.com/mozzherina), Free University of Bozen-Bolzano, Italy
- Prof. Oliver Kutz [[Personal Page]](http://www.inf.unibz.it/~okutz/), Free University of Bozen-Bolzano, Italy
- Prof. Diego Calvanese [[Personal Page]](https://www.inf.unibz.it/~calvanese/), Free University of Bozen-Bolzano, Italy
- Prof. Giancarlo Guizzardi [[Personal Page]](https://people.utwente.nl/g.guizzardi), University of Twente, The Netherlands


## How to cite this project

In case you would like to cite this work, you can refer to the original paper:

*Romanenko, E., Kutz, O., Calvanese, D., & Guizzardi, G.* (2023). **Model-Theoretic Semantics for Abstractions of Ontology-Driven Conceptual Models**. Manuscript submitted for publication.


## Acknowledgements
We would like to thank all developers of [Hets](http://hets.eu/), The heterogeneous tool set, for their incledible support during this project.
