**In this notebook, our objectives are as follows:**
1. Perform universal feature extraction from images using dimensionality reduction techniques and subsequently make predictions using classical ML algorithms.
2. Perform image-specific feature extraction from the images and make predictions using classical ML algorithms.
3. Utilize a pre-trained CNN network with a custom MLP head to automatically extract features and make predictions.
4. Utilize a custom CNN network for automatic feature extraction and predictions.

In the final section of this notebook, we will compare these methods, discussing their drawbacks and benefits.

For each model we perform hyperparameter tuning using Bayesian optimization with the `optuna` library.
