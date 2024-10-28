# Results of codes present

| Model              | Condition      | Hazard - Category | Product - Category | Hazard | Product |
|--------------------|----------------|-------------------|--------------------|--------|---------|
| Logistic Regression | default        | Accuracy: 74 <br> F1_macro: 38 | Accuracy: 64 <br> F1_macro: 37 | Accuracy: 51 <br> F1_macro: 11 | Accuracy: 26 <br> F1_macro: 07 |
| SVM                | default        | Accuracy: 76 <br> F1_macro: 52 | Accuracy: 69 <br> F1_macro: 49 | Accuracy: 54 <br> F1_macro: 20 | Accuracy: 36 <br> F1_macro: 15 |
| Random Forest (RF)  | default        | Accuracy: 75 <br> F1_macro: 47 | Accuracy: 63 <br> F1_macro: 39 | Accuracy: 58 <br> F1_macro: 28 | Accuracy: 42 <br> F1_macro: 20 |
| MLP Classifier      | default        | Accuracy: 77 <br> F1_macro: 55 | Accuracy: 70 <br> F1_macro: 51 | Accuracy: 56 <br> F1_macro: 25 | Accuracy: 39 <br> F1_macro: 19 |
| Gradient Boosting   | default        | Accuracy: 71 <br> F1_macro: 47 | Accuracy: 64 <br> F1_macro: 44 | Accuracy: 46 <br> F1_macro: 20 | N/A |
| Random Forest (RF)  | randomsearchcv | N/A                | N/A                | Accuracy: 58 <br> F1_macro: 30 | N/A |
| Logistic Regression | Threshold Grouping        | Accuracy: 83 <br> F1_macro: 44 | Accuracy: 58 <br> F1_macro: 38 | Accuracy: 64 <br> F1_macro: 22 | Accuracy: 46 <br> F1_macro: 04 |
| SVM                | Threshold Grouping        | Accuracy: 87 <br> F1_macro: 64 | Accuracy: 64 <br> F1_macro: 51 | Accuracy: 68 <br> F1_macro: 41 | Accuracy: 54 <br> F1_macro: 18 |
| Random Forest (RF)  | Threshold Grouping        | Accuracy: 83 <br> F1_macro: 56 | Accuracy: 49 <br> F1_macro: 34 | Accuracy: 61 <br> F1_macro: 31 | Accuracy: 49 <br> F1_macro: 13 |
| MLP Classifier      | Threshold Grouping        | Accuracy: 87 <br> F1_macro: 73 | Accuracy: 68 <br> F1_macro: 56 | Accuracy: 70 <br> F1_macro: 48 | Accuracy: 55 <br> F1_macro: 31 |
| LSTM     | Default        | Accuracy: 75 <br> F1_macro: 46 | Accuracy: 50 <br> F1_macro: 16 | Accuracy: 47 <br> F1_macro: 08 | Accuracy: 12 <br> F1_macro: 02 |
| FFNN     | Default        | Accuracy: 75 <br> F1_macro: 39 | Accuracy: 63 <br> F1_macro: 34 | Accuracy: 46 <br> F1_macro: 08 | Accuracy: 05 <br> F1_macro: 00 |
| Bi-LSTM     | Default        | Accuracy: 74 <br> F1_macro: 40 | Accuracy: 67 <br> F1_macro: 40 | Accuracy: 49 <br> F1_macro: 12 | Accuracy: 22 <br> F1_macro: 05 |
| LSTM     | Stacking      | Accuracy: 74 <br> F1_macro: 47 | Accuracy: 64 <br> F1_macro: 40 | Accuracy: 42 <br> F1_macro: 05 | Accuracy: 07 <br> F1_macro: 00 |
| Bi-LSTM     | Stacking      | Accuracy: 74 <br> F1_macro: 42 | Accuracy: 66 <br> F1_macro: 41 | Accuracy: 42 <br> F1_macro: 07 | Accuracy: 14 <br> F1_macro: 02 |
| Ensemble     | LSTM + Bi-LSTM + RNN + FFNN        | Accuracy: 77 <br> F1_macro: 51 | Accuracy: 69 <br> F1_macro: 40 | Accuracy: 51 <br> F1_macro: 12 | Accuracy: 14 <br> F1_macro: 02 |
