# K-Nearest-Neighbors-Classification_zoo-data-set
In this project, the K-nearest neighbor (KNN) classification algorithm has been implemented and applied to the Zoo Data Set. The original data can be found here: https://archive.ics.uci.edu/ml/datasets/Zoo.

## The data set
### Features
The dataset consists of 101 instances. Each instance corresponds to an animal which has a unique identifier (the name of the animal; first field) and is characterized with 16 features:

  1. hair Boolean
  2. feathers Boolean
  3. eggs Boolean
  4. milk Boolean
  5. airborne Boolean
  6. aquatic Boolean
  7. predator Boolean
  8. toothed Boolean
  9. backbone Boolean
  10.breathes Boolean
  11.venomous Boolean
  12.fins Boolean
  13.legs Numeric (set of values: {0,2,4,5,6,8})
  14.tail Boolean
  15.domestic Boolean
  16.catsize Boolean

## Labels
### Seven pre-defined categories of animals: 
1: mammal 2: bird 3: reptile 4: fish 5: amphibian 6: insect 7: invertebrate

zoo.features contains 101 instances, one line per instance. The first field is the unique instance identifier (name of animals). The following fields contain the 16 features, as described above.

zoo.labels contains the gold labels (i.e., one of the seven classes above), for one instance per line. Again, the first field is the instance identifier, and the second field the instance label.
