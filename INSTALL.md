# Guía de instalación paso a paso

A continuación se describen en detalle los pasos necesarios. Puedes ejecutar los scripts automáticos o seguirlos manualmente.

## 1. Habilitar WSL2 e instalar Kali Linux

1. Abre **PowerShell** como **Administrador**.
2. Ejecuta:
   ```powershell
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

wsl --set-default-version 2
wsl --install -d kali-linux
