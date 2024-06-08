# deep-learning-challenge
Module 21 Challenge

## Python Library Requirements
- pandas
- sklearn
- tensorflow

## Report
### Overview
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. A deep learning neural network was created for this purpose. It was trained on historical data of more than 34,000 organizations that have received funding from Alphabet Soup.

### Results
#### Data Preprocessing
The target and features for the model extracted from the historical data are listed below. The EIN and NAME columns were removed because they are identifiers; they would not contribute to model accuracy.

| Model Target           | Description                                                              |
| ---------------------- | ------------------------------------------------------------------------ |
| IS_SUCCESSFUL          | binary value indicating whether the venture used its funding effectively |

| Model Feature          | Description                                                              |
| ---------------------- | ------------------------------------------------------------------------ |
| APPLICATION_TYPE       | application category                                                     |
| AFFILIATION            | affiliated sector of industry                                            |
| CLASSIFICATION         | government organization classification                                   |
| USE_CASE               | use case for funding                                                     |
| ORGANIZATION           | organization category                                                    |
| STATUS                 | binary value indicating whether the venture is active                    |
| INCOME_AMT             | income bracket of the venture                                            |
| SPECIAL_CONSIDERATIONS | special considerations for the application                               |
| ASK_AMT                | amount of funding requested                                              |

### Compiling, Training, and Evaluating the Model
Initial sequential model structure:
| Layer    | Neurons | Activation Function |
| -------- | ------- | ------------------- |
| Input    |      43 | N/A                 |
| Hidden 1 |      80 | ReLU                |
| Hidden 2 |      30 | ReLU                |
| Output   |       1 | Sigmoid             |

The input layer contains 43 neurons, 1 for each feature in the training data. <br>
The numbers of neurons in the hidden layers and the number of hidden layers themselves were chosen arbitrarily for the first model iteration. The reLU activation function was selected to allow the model to learn quickly. <br>
The output layer contains only 1 neuron because the classifier is binary. The sigmoid activation function was chosen for this same reason. <br>
This initial model was unable to attain the target accuracy of 75% and therefore had to be modified.

### Summary
WiP
