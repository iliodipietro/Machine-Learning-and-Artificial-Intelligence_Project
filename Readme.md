#Landmark Recognition

Landmark Recognition is a large-scale classification task
which is raising the interest of machine learners from all
over the world for its peculiar challenging aspects. A huge
amount of landmarks have been captured and gathered in
the Google Landmark Dataset. This extreme classification
scenario is combined with the necessity to confirm the correctness
of the obtained prediction, since the test set contains
’tricky’ samples.
To do so, a retrieval mechanism
based on Deep Local Features is implemented. This solution
provides a full pipeline composed by three main stages:
1)A pre-processing and filtering step to
deal with constraints imposed by both time and computational
resources available;
2)The classification phase has been performed with a ResNet50 model exploiting transfer
learning from ImageNet dataset;
3)DELF module has been adapted to our specific application with a thresholdbased
decision system for an efficient verification of the predictions.
In the following paper the results will be analyzed.
