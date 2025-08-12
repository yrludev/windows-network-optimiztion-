# Windows Network Optimization Toolkit

This toolkit contains several scripts and utilities to help optimize and debloat your Windows network settings for better performance and lower latency.

## Contents

- **debloat nett.bat**: Batch script to remove unnecessary Windows features and services that may slow down your network.
- **MSI_util_v3.exe**: Utility to configure Message Signaled Interrupts (MSI) for network adapters, which can improve network performance and reduce latency.
- **Network_Tweaks.bat**: Batch script to apply various registry and system tweaks for optimizing network performance.
- **Network.reg**: Registry file with additional network optimization settings.
- **Ping Optimization.reg**: Registry file focused on reducing ping and improving network responsiveness.

## How to Run

### 1. Run as Administrator
Most scripts and registry tweaks require administrator privileges to apply changes. To run as admin:

- **Batch Files (.bat):**
  1. Right-click the `.bat` file (e.g., `debloat nett.bat` or `Network_Tweaks.bat`).
  2. Select **Run as administrator**.

- **Registry Files (.reg):**
  1. Right-click the `.reg` file (e.g., `Network.reg` or `Ping Optimization.reg`).
  2. Select **Merge**.
  3. If prompted, allow the Registry Editor to make changes.

- **MSI_util_v3.exe:**
  1. Right-click `MSI_util_v3.exe`.
  2. Select **Run as administrator**.

### 2. What Each File Does

- **debloat nett.bat**: Removes bloatware and disables unnecessary services to free up system resources and improve network performance.
- **MSI_util_v3.exe**: Lets you enable MSI mode for network adapters, which can help reduce DPC latency and improve network throughput.
- **Network_Tweaks.bat**: Applies a set of system and registry tweaks to optimize Windows network stack settings.
- **Network.reg**: Imports registry settings to further optimize network parameters.
- **Ping Optimization.reg**: Imports registry tweaks specifically aimed at reducing ping and improving online gaming or real-time communication.

## Important Notes
- Always create a system restore point before applying tweaks or registry changes.
- Use these scripts and tweaks at your own risk. Results may vary depending on your system and network hardware.

## Support
For questions or issues, please open an issue on the repository or contact the author.
