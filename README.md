# Custom Signal Filtering & Sensor Noise Reduction in MATLAB

## 📌 Project Overview
Developed a lightweight **Digital Signal Processing (DSP)** script in MATLAB to clean high-frequency sensor noise using fundamental matrix operations. By avoiding specialized toolboxes, this project demonstrates core proficiency in vectorized indexing, signal visualization, and data normalization.

## 📊 Methodology & MATLAB Core Concepts Used
* **Data Ingestion:** Loaded and normalized raw temporal signal arrays using `audioread`.
* **Vectorized Indexing:** Implemented a custom sliding-window Low-Pass Filter (Moving Average) using boundary-safe array indexing rather than computationally expensive loops.
* **Data Visualization:** Generated side-by-side time-domain comparison waveforms using `subplot` and `plot` formatting.

## 📈 Visualizing the Filter Results
![Signal Comparison](waveforms.png)

*The blue waveform demonstrates significant attenuation of high-frequency noise spikes compared to the raw red sensor signal.*

## 🚀 How to Run
1. Clone this repository or download the files.
2. Open `signal_filter.m` in MATLAB or MATLAB Mobile.
3. Place your noisy sensor data file (`signal.wav`) in the root directory and click **Run**.
