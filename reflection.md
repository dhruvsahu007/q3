# Reflection

## Initial Random Prediction vs. Final Results
At the start, the perceptron's predictions are essentially random due to randomly initialized weights and bias. This results in poor accuracy and high loss. As training progresses, the model learns to adjust its parameters to minimize the loss, leading to much better predictions. By the end, the model can accurately distinguish apples from bananas based on the features, as seen in the high final accuracy and low loss.

## Learning Rate Impact
The learning rate (LR) controls how much the model updates its weights in response to the error each epoch. A high LR can speed up convergence but risks overshooting the minimum, causing instability. A low LR ensures stable convergence but may require many epochs. In this project, a moderate LR (0.1) was chosen to balance speed and stability, allowing the model to converge within 500 epochs or less if the loss threshold is met.

## DJ-Knob / Child-Learning Analogy
Tuning the learning rate is like adjusting a DJ's volume knob or teaching a child. If you turn the knob too quickly (high LR), the music might become too loud or too soft abruptly, missing the sweet spot. If you turn it too slowly (low LR), it takes a long time to reach the right volume. Similarly, a child learning with too big steps may make wild mistakes, while too small steps make progress slow. The right balance helps the model (or child) learn efficiently and effectively. 