# EcgAnalyzer
R peak detection in ECGs using stationary wavelet transform

This is an iJupter notebook that uses Python code and numpy libraries to detect R peaks in ECG signals and then given an annotation file, calculates Sensitivity and Positive Predictive Rate. It is currently only compatible with MiT-BiH arrhythmia DB signal format. The signals are loaded using the physionet's WFDB python library. 
