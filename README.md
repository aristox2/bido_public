# bido

<p align="center">
  <img src="bido_graph.gif" alt="bido mosaic graph assembly" width="720">
</p>

a sanctions-evasion detection engine. resolves entities across multilingual open sources into a graph structure, then surfaces coordination patterns via network analysis.

## architecture

- **mosaic** — c++17 in-memory graph core over resolved entities; edges built from co-occurrence and cross-source references
- **python + spacy microservices** — multilingual named-entity extraction; languages targeted per collection
- **cascade resolution** — entities pass through progressive resolution stages before being committed to the graph; false-positive suppression handled at boundary layers

## where is it? 

sure as hell ain't here, the source is not published. why? 
short answer is that its still in dev. 
long answer is that the detection logic is the substance of the project, and publishing the heuristics would be counterproductive to their purpose. 

## stack

`c++17` · `python` · `spacy`
