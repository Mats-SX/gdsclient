# Changes in 1.6


## Breaking changes


## New features

* Added new method `gds.alpha.graph.nodeLabel.write` to write back node labels to Neo4j database.
* Added new convenience methods to the `Model` object:
  * `model_info` to get model metadata obtained during training.
  * `classes` to list all classes used during training (only for Node Classification models).
  * `best_parameters` which returns a pandas `Series` containing the parameters of the model winning the model selection training.
  * `pipeline` which returns information about the pipeline steps that are part of running predictions with the model.


## Bug fixes


## Improvements


## Other changes
