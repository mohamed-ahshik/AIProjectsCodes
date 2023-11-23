Simple Neural Network Model for binary classification for cats and dogs
using just one hidden layer and a batch size of 10 and epochs of 10


Lessons learned
1) Batch sizes contributes to the model learning. Lower size make the batch graident more noisy so hard to find the global minimum.So use higher value.
2) Input training csv must be randomised with the classes instead of one class after another. This helps the model to generlise better.
   
