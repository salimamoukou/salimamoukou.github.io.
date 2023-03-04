# Abstract

Despite attractive theoretical guarantees and practical successes, Predictive Interval (PI) given by Conformal Prediction (CP) may not reflect the
uncertainty of a given model. To address this problem, we propose to learn the distribution of the nonconformity scores using a Quantile Regression Forest (QRF), then use the QRF’s weights to give more importance to samples with residuals similar to the test point. The lengths of the resulting PI are better aligned with the uncertainty of the model. In addition, the weights learnt by
the QRF provide a partition of the features space, allowing for more efficient computations and improved adaptiveness of the PI through groupwise conformalization. We show that our approach enjoys an assumption-free finite sample marginal and training-conditional coverage, and under suitable assumptions, it also ensures conditional coverage. Our methods work for any nonconformity score and are available as a Python package. We
provide experimental results on simulated and real-world data that showcase significant improvements compared to existing methods.

[PDF](https://drive.google.com/drive/u/0/folders/1ttzg_slFqOm0RrqDpI0mkDIlAaH2Sp0f) - [CODE](https://github.com/salimamoukou/ACPI)

