# deep-learning-challenge

Original Neural Network (NN) Model:
The accuracy during training appears stagnant, hovering around 57-58%, and the loss reduces slightly but remains relatively high.
When evaluated on the test dataset, the model has a loss of NaN and an accuracy of approximately 0.465.

Optimized Neural Network (NN) Model:
The optimized model shows similar training behavior, with the accuracy improving slightly to ~0.4689 during evaluation on the test set.
However, the loss is still NaN, indicating a persistent issue in the model.


Comparison:
Accuracy Trends:

The training accuracy for both models remained nearly the same (~57%).
The test accuracy showed a negligible improvement, moving from 46.51% to 46.89% in the optimized model.
Both models underperformed, indicating the need for further adjustments.
Loss Behavior:

Both models encountered NaN loss during evaluation, signaling issues with numerical stability or input preprocessing.
Optimization Impact:

The applied optimization techniques improved test accuracy slightly but did not address the core issue of NaN loss.
Training stability remained comparable between the two models.
