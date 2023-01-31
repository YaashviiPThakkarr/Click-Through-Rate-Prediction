# Click-Through-Rate-Prediction

This project covers the steps for creating a click-through rate (CTR) prediction pipeline. I work with the Criteo Labs dataset that was used for a recent Kaggle competition.
## About the Display Advertising Dataset
This dataset contains feature values and click feedback for millions of display ads. Its purpose is to benchmark algorithms for clickthrough rate (CTR) prediction.

The dataset consists of a portion of Criteo's traffic over a period of 7 days. Each row corresponds to a display ad served by Criteo and the first column is indicates whether this ad has been clicked or not. The positive (clicked) and negatives (non-clicked) examples have both been subsampled (but at different rates) in order to reduce the dataset size.

There are 13 features taking integer values (mostly count features) and 26 categorical features. The values of the categorical features have been hashed onto 32 bits for anonymization purposes. The semantic of these features is undisclosed. Some features may have missing values.

The rows are chronologically ordered. When a value is missing, the field is just empty.

Dataset was assembled by Olivier Chapelle (o.chapelle@criteo.com)

### The project covers:
- Part 1 : Featurize categorical data using one-hot-encoding (OHE) 
- Part 2 : Construct an OHE dictionary
- Part 3 : Parse CTR data and generate OHE features
- Visualization 1 : Feature frequency
- Part 4 : CTR prediction and logloss evaluation
- Visualization 2 : ROC curve
- Part 5 : Reduce feature dimension via feature hashing
- Visualization 3 : Hyperparameter heat map
