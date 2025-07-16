> [!Feature Vector]
> Each Row of Data is called Feature Vector
> Result we derive from Each row is Target

### Training Model:
Dataset can Break into:

Training Dataset: Train the model with this 

Validation Dataset: Validation set used as a reality check during/after training to ensure model can handle unseen data. Evaluate Loss with this data
***Loss is not fed into model (No Feed back loop)***
=> Make Adjustments
Pick Right Model

Test Dataset: Used as to do Final check how generalizable the final chosen model

### Metrics & Performance:
L1 Loss

$$
L1 Loss => sum(|Yreal - Ypredicted|)

$$

L2 Loss or Quadratic
$$
L2Loss => sum((Yreal - Ypredicted)^2)
$$

Binary Cross-Entropy Loss
$$
loss => -1/N * sum(Yreal * log(Ypredicted) + (1-Yreal) * log((1 - Ypredicted)))
$$

***Loss Decreases as performance gets better***

Accuracy => What percentage is predicated within acceptable limits



