# Century: A Framework and Dataset for Evaluating Historical Contextualisation of Sensitive Images

To better understand how multi-modal models describe and provide context on
historical figures and events, we introduce Century – a novel dataset of
1,500 sensitive historical images. This dataset consists of images
from recent history, created through an
automated method combining knowledge graphs and language models with quality and
diversity criteria created from the practices of museums and digital archives.
_Century_ contains images that depict events and figures that are diverse
across topics and represents all regions of the world.

You can download _Century_ dataset below. Instructions on replicating the
_Century_ evaluation framework can
be found in the [ICLR paper](https://openreview.net/forum?id=1KLBvrYz3V).

## Installation

The data can be downloaded from our [Cloud bitbucket](https://storage.googleapis.com/historical-images-benchmark/iclr_supplementary_materials/century_materials.zip). This will download the entire directory to your device.
In the directory, you will find the following files:

* `knowledge_graph_search_terms.csv`: contains
all search terms of historical events
and figures collected through our
mining method
* `century_dataset_images_only.csv`: contains
all images in _Century_ as Wikipedia
links, alongside other metadata
attributes
* `century_dataset_with_image_quality_labels.csv`: contains all image
annotations collected through human and auto-rater methods, including both
diversity and quality labels
* `README.md`: contains details on all datasets, including column descriptions

## Citing this work

To cite this work, use:

 <!-- mdlint off(SNIPPET_INVALID_LANGUAGE) -->
```latex
@inproceedings{Akbulut25,
      title={Century: A Framework and Dataset for Evaluating Historical Contextualisation of Sensitive Images},
      author={Canfer Akbulut and Kevin Robinson and Maribeth Rauh and Isabela Albuquerque and Olivia Wiles and Laura Weidinger and Verena Rieser and Yana Hasson and Nahema Marchal and Iason Gabriel and William Isaac and Lisa Anne Hendricks},
      booktitle={The Thirteenth International Conference on Learning Representations},
      year={2025},
}
```

## License and disclaimer

Copyright 2024 DeepMind Technologies Limited

All software is licensed under the Apache License, Version 2.0 (Apache 2.0);
you may not use this file except in compliance with the Apache 2.0 license.
You may obtain a copy of the Apache 2.0 license at:
https://www.apache.org/licenses/LICENSE-2.0

All other materials are licensed under the Creative Commons Attribution 4.0
International License (CC-BY). You may obtain a copy of the CC-BY license at:
https://creativecommons.org/licenses/by/4.0/legalcode

Unless required by applicable law or agreed to in writing, all software and
materials distributed here under the Apache 2.0 or CC-BY licenses are
distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
either express or implied. See the licenses for the specific language governing
permissions and limitations under those licenses.

This is not an official Google product.
