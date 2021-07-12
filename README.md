# K-Nearest-Neighbors-Classification_zoo-data-set
In this project, the K-nearest neighbor (KNN) classification algorithm has been implemented and applied to the Zoo Data Set. The original data can be found here: https://archive.ics.uci.edu/ml/datasets/Zoo.

## The data set
### Features
The dataset consists of 101 instances. Each instance corresponds to an animal which has a unique identifier (the name of the animal; first field) and is characterized with 16 features:

hair Boolean
feathers Boolean
eggs Boolean
milk Boolean
airborne Boolean
aquatic Boolean
predator Boolean
toothed Boolean
backbone Boolean
breathes Boolean
venomous Boolean
fins Boolean
legs Numeric (set of values: {0,2,4,5,6,8})
tail Boolean
domestic Boolean
catsize Boolean

## Labels
### Seven pre-defined categories of animals: 
1: mammal 2: bird 3: reptile 4: fish 5: amphibian 6: insect 7: invertebrate

zoo.features contains 101 instances, one line per instance. The first field is the unique instance identifier (name of animals). The following fields contain the 16 features, as described above.

zoo.labels contains the gold labels (i.e., one of the seven classes above), for one instance per line. Again, the first field is the instance identifier, and the second field the instance label.
