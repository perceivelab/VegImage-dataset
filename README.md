# VegImage-dataset

The dataset contains fruit images and related annotations and is divided into the following classes and subclasses:

- Malus domestica (ambrosia, braeburn, cameo, fuji, golden delicius, granny smith, pink lady, renetta, royal gala, stark delicious)

- Prunus avium (bing, black tartarian, burlat, ferrovia, lapins,ranier, stella)

- Pyrus communis (abate, anjou, conference, coscia, doyenne du comice, kaiser, williams)

The dataset includes about 3600 images and it’s splitted into two folders (train and test), inside each folder you will find images in JPG format.
For each image there is an XML file containing: the annotations (BB) for each object and other information according to the "FruitOntology.owl" ontology.
There are also two JSON files generated from XML files for training with MaskRCNN.

### Download dataset

Link to dataset files: https://tinyurl.com/VegImage

### Citation

If you use this dataset, please cite the following works:

> F. Murabito, C. Spampinato, S. Palazzo and M. Shah. _Exploiting Structured HighLevel Knowledge for Domain-Specific Visual Classification_, submitted to PAMI 2017.
