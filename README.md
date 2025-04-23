# ECG Classification Using the Clonal Selection Algorithm
This project demonstrates the use of the Clonal Selection Algorithm (CSA), a bio-inspired artificial immune system approach, for classifying Electrocardiogram (ECG) signals. The model was trained on the
PTB Diagnostic ECG Database to classify ECG signals as either normal or abnormal (arrhythmic). The best accuracy achieved was 74.8%, making CSA a promising yet underexplored method for ECG
classification.

## Technologies Used
Python: Main programming language used for the project

NumPy: For numerical operations and data manipulation

Matplotlib/Seaborn: For plotting and visualizing results

Scikit-learn: For machine learning utilities (e.g., splitting data, metrics)

Pandas: For dataset manipulation and preprocessing

## Dataset
This project uses the PTB Diagnostic ECG Database from the PhysioNet platform. It contains 14552 ECG readings, each with 188 columns representing the signal values at various time points. The dataset
is imbalanced, with approximately 27.8% of signals categorized as normal and the rest as abnormal (arrhythmic).

