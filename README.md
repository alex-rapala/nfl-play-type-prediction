# NFL Play Prediction

Using machine learning to predict whether an NFL offense will run or pass on a given play, based on game-context (down, distance, score, time remaining) and pre-snap features (formation, huddle).

Compares logistic regression, decision tree, shallow decision tree, and random forest models. The random forest performed best (72.5% accuracy), with pre-snap features improving all models' predictive power.

Built with `nflreadpy`, `pandas`, and `scikit-learn`.
