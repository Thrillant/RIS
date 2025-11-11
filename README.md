# RIS-Assisted Multi-User MIMO Simulation (MATLAB)

This project simulates a Reconfigurable Intelligent Surface (RIS)-assisted downlink communication system at 28 GHz (mmWave) using MATLAB. It evaluates how RIS placement affects the combined SNR for multiple users under a Rician fading channel model.


🚀 Features

Carrier Frequency: 28 GHz (mmWave)
Rician Fading: Adjustable K-factor for LOS/NLOS balance
RIS Setup: 15×15 rectangular RIS with half-wavelength spacing
Base Station: 2×2 URA (4 isotropic elements) at 30 m height
Users: 3 UEs positioned at 1 km away, heights {2 m, 12 m, 22 m}
Precoding: Zero-Forcing (ZF)

Path Components:
Direct BS–UE link
RIS-assisted reflection path


🛠️ Requirements

MATLAB R2022a or later
Phased Array System Toolbox
Communications Toolbox
Combined BS + RIS path
Noise Model: AWGN with configurable power
Results: Plots Average Combined SNR vs. RIS x-position
