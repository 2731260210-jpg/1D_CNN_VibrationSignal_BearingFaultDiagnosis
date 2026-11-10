# 1D-CNN Vibration Signal Bearing Fault Diagnosis

This repository contains notebooks and experiment artifacts for bearing fault
classification with a one-dimensional convolutional neural network.

> Source note: this work is based on the public project
> [Abdulhamid97Mousa/1D_CNN_VibrationSignal_BearingFaultDiagnosis](https://github.com/Abdulhamid97Mousa/1D_CNN_VibrationSignal_BearingFaultDiagnosis).
> The upstream repository did not include a license file when this copy was
> prepared, so no additional license is asserted here.

## Included files

- `1D_CNN_Model_For_Bearings_Fault_Diagnosis.ipynb`: main notebook
- `Experiments/exp01_CNN_2L_vs_3L.ipynb`: two-layer versus three-layer CNN experiment
- `Ball_bearing_fault_diagnosis/` and `Experiments/Ball_bearing_fault_diagnosis/`:
  small trained-model checkpoints and result CSV files

The Python virtual environment, dataset files, and local dataset archive are
intentionally excluded. Install dependencies with `pip install -r requirements.txt`.

Bearing fault diagnosis has been a challenge in the monitoring activities of rotating machinery, and it's receiving more and more attention. The conventional fault diagnosis methods usually extract features from the waveforms or spectrums of vibration signals in order to correctly classify faults.

# CWRU-dataset
Case Western Reserve University Bearing Fault Dataset

https://csegroups.case.edu/bearingdatacenter/pages/download-data-file

Download the dataset from the official source above and place the extracted
`CWRU_DATASETS_ABCD-main` directory in the repository root before running the
notebooks locally.

Data presented here were collected for - 
  1. normal bearings, 
  2. single-point drive end and 
  3. fan end defects.  

Data collected at 12,000 samples/second and at 48,000 samples/second for drive end bearing experiments.  
All fan end bearing data was collected at 12,000 samples/second.  

Data files are in Matlab format.  
Each file contains - 
  1. Fan end 
  2. Drive end vibration data as well as 
  3. motor rotational speed.  
  
    For all files, the following item in the variable name indicates:
      
    DE - drive end accelerometer data

    FE - fan end accelerometer data

    BA - base accelerometer data

    time - time series data

    RPM- rpm during testing



## Stargazers over time

[![Stargazers over time](https://starchart.cc/Abdulhamid97Mousa/1D_CNN_VibrationSignal_BearingFaultDiagnosis.svg)](https://starchart.cc/Abdulhamid97Mousa/1D_CNN_VibrationSignal_BearingFaultDiagnosis)

