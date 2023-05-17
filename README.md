# Hand Digit Classification
A simple neural network build on the MNIST dataset.
> Multilayer Perceptron classifier (MLP): <br>
> The MLP has an input layer, two hidden layers with 128 neurons each, a dropout layer to prevent overfitting, and an output layer with 10 neurons (one for each class).

This was done as my project during college, in the course CS3203: Data Science and Machine Learning. 

Major oversights:
- No Data Augmentation: A slight change in how input images are processed.
- Outcome: Very bad real life performance.
- Very simple model, is effective but CNN can outperform this very easily.
- No learning rate scheduler: Adjusts the learning rate dynamically during training to help the model converge faster and more accurately.
- Report is incomplete, no mention about improvements.

## To-do
- [ ] Improve the code.
- [ ] Create an interface.
- [ ] Include API calls.
- [ ] Real time processing (interactive canvas).
- [ ] Add above changes to the report.
