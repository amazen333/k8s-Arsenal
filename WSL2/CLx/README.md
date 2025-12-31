# Kubernetes on WSL2 (Community Linux)

This folder contains automation scripts for setting up Kubernetes clusters inside **WSL2** using **Ubuntu/Debian**.

## 📜 Scripts
- `k8s-WSL2-CLx-clones.ps1` → PowerShell script to clone base Ubuntu/Debian distros in WSL2.
- `k8s-WSL2-CLx-master.sh` → Bootstraps a Kubernetes **master node** inside WSL2.
- `k8s-WSL2-CLx-worker.sh` → Prepares a Kubernetes **worker node** inside WSL2.

## 🚀 Usage
```powershell
# Clone Ubuntu/Debian distros
.\k8s-WSL2-CLx-clones.ps1 -BaseDistroName "Ubuntu-Base" -ClonePrefix "CLx" -Count 3 -InstallRoot "D:\WSL\CLx" -DefaultUser "devops" -Role "Worker"

# Run setup scripts inside WSL
wsl -d CLx-Worker-01 bash ./ec2-ubuntu-master.sh
