# ekf-sensor-fusion-demo
A minimal Extended Kalman Filter (EKF) implementation for fusing IMU and GPS data
# Minimal EKF-Based Sensor Fusion Demo (IMU + GPS)

This project is a minimal implementation of an Extended Kalman Filter (EKF) for fusing IMU and GPS data to estimate position and velocity.

## ✨ Features

- Lightweight EKF algorithm in pure C
- IMU model with noise and bias
- GPS position update
- Python visualization for trajectory and error
- Easy to integrate with embedded systems

## 📂 Project Structure
ekf-sensor-fusion-demo/
├── src/ # EKF algorithm and sensor models
├── data/ # Sample IMU + GPS data (CSV format)
├── python/ # Visualization scripts
└── README.md



## 🛠️ Technologies

- Language: C, Python (for visualization)
- Algorithm: Extended Kalman Filter
- Sensors: Accelerometer, Gyroscope, GPS
- Tools: GCC / Keil / STM32CubeIDE (optional), matplotlib

## 📈 Demo

*Coming soon:*  
Plot of fused trajectory vs. GPS-only data.

## 📦 How to Run

1. Compile the C code using your favorite toolchain.
2. Replace `data/imu_gps_sample.csv` with your own data.
3. Run `python/plot_trajectory.py` to visualize the results.

## 📄 License

MIT License
