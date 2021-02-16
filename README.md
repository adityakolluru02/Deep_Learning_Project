#### In my project, I used Transfer Learning approach to train a ResNet50 model to classify two kinds of bees.

#### I followed two approaches while training the model:

	1) Keeping the base layers frozen and not changing their weights.

	In this approach, I ran for 10 epochs with following results:
		Training:
		Accuracy:0.87 Loss:0.28
		
		Validation:
		Accuracy: 0.90 Loss: 0.24

		Test:
		Accuracy: 0.95 

	2) Unfreezing the base model to a certain depth, and the training these layers again

	Here, I ran 10 epochs with following results:
		Training:
		Accuracy: 0.98 Loss: 0.02
		
		Validation:
		Accuracy: 0.96 Loss:0.19

		Test:
		Accuracy: 0.96
