# Velociraptor-2025
Velociraptor Troubleshooting &amp; Analyst Guide: A centralized knowledge base for SOC and DFIR teams to document, analyze, and resolve Velociraptor operational issues. Includes step-by-step troubleshooting runbooks, error reference guides, automation scripts, and templates for efficient investigation and response.

## Execution

```
sudo velociraptor --config server.config.yaml frontend -v
```
<img width="942" height="753" alt="image" src="https://github.com/user-attachments/assets/23330323-9fbc-4b3d-a96f-7b29184c5980" />

## GUI INTERFACE
**URL** : https://127.0.0.1:8889/app/index.html#/welcome <br />

<img width="1914" height="750" alt="image" src="https://github.com/user-attachments/assets/11833280-0e3c-428f-82a4-4bd859f1995d" />

# Connect with Windows Client

## Install Velociraptor at Client End
```
https://github.com/Velocidex/velociraptor/releases/download/v0.7.1/velociraptor-v0.7.1-1-windows-amd64.exe
```
<img width="810" height="171" alt="image" src="https://github.com/user-attachments/assets/f623af55-2e8e-48c9-a7c1-aebe404aabab" />

## Edit the client.config.yaml file at client End
- Replace with Server IP where Velociraptor hosted
- <img width="679" height="260" alt="image" src="https://github.com/user-attachments/assets/3a63a046-50a2-458a-9209-14eea6231225" />

## Install as service at client End
```
velociraptor.exe --config client.config.yaml service install
```
<img width="826" height="190" alt="image" src="https://github.com/user-attachments/assets/4cf51841-0023-4c0b-b8b4-68a1cc0d7065" />

## Check the connectivity status on GUI

<img width="1916" height="299" alt="image" src="https://github.com/user-attachments/assets/64afd5b7-f5a3-4879-9f7b-9390efb62206" />

