# day11_evaluation
Evaluated the model using test data and analyzed prediction results to assess performance

The trained neural network model was evaluated using the test dataset to measure its real-world performance. Unlike training and validation data, the test dataset contains completely unseen data that the model has never encountered before. Evaluating on test data provides an unbiased estimate of how well the model can generalize.

The model’s performance was measured using key metrics such as test accuracy and test loss. Test accuracy indicates the percentage of correctly classified images, while test loss measures the difference between predicted outputs and actual labels. A high test accuracy combined with low loss suggests that the model has learned meaningful patterns rather than memorizing the training data.

In addition to numerical evaluation, prediction analysis was performed. The model generated probability outputs for each image in the test dataset using the softmax activation function. The class with the highest probability was selected as the predicted label. These predicted labels were then compared with the actual labels to verify correctness.

Misclassified examples were also analyzed to understand where the model struggled. This helped identify whether errors occurred due to similar-looking digits, poor image clarity, or model limitations. Such analysis provides insights into potential areas for further improvement.

By the end of Day 11, the model’s performance was critically assessed using both quantitative metrics and qualitative prediction analysis. This step strengthened understanding of model evaluation, generalization capability, and performance interpretation in deep learning systems.
