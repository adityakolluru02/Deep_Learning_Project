# Deep Learning Project - Bees Classification

### In my project, I used Transfer Learning approach to train a ResNet50 model to classify two kinds of bees.

#### I followed these approaches while training the model:

   1. Keeping the base layers frozen and not changing their weights.

      In this approach, I ran for 10 epochs with following results:

      	Training Accuracy:   0.8708             Loss:0.2867
		
      	Validation Accuracy: 0.8882             Loss: 0.2705

      	Test Accuracy:       0.875 

   2. Unfreezing the base model to a certain depth, and the training these layers again.

      Here, I ran another 10 epochs with following results:

      	Training Accuracy:   0.9892             Loss: 0.0272
		
      	Validation Accuracy: 0.9559             Loss:0.1562

      	Test Accuracy:       0.9499

   3. Completely unfreezing all the layers and the training these layers again.

      Here, I ran another 20 epochs with following results:

      	Training Accuracy:   0.9991             Loss: 0.0040
		
      	Validation Accuracy: 0.9559             Loss:0.2000

      	Test Accuracy:       0.9624
