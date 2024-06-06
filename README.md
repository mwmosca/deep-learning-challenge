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

### Summary
WiP
