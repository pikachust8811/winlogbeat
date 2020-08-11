# winlogbeat

## Run with PowerShell
```
# Microsoft-Windows-PowerShell%4Operational.evtx
PS C:\Users\Lish\Downloads\winlogbeat-7.8.1-windows-x86_64> .\winlogbeat.exe -e -c .\winlogbeat.yml -E EVTX_FILE=C:\Users\Lish\Desktop\Logs\HOST_Logs\Microsoft-Windows-PowerShell%4Operational.evtx

# Microsoft-Windows-Sysmon%4Operational.evtx
PS C:\Users\Lish\Downloads\winlogbeat-7.8.1-windows-x86_64> .\winlogbeat.exe -e -c .\winlogbeat.yml -E EVTX_FILE=C:\Users\Lish\Desktop\Logs\HOST_Logs\Microsoft-Windows-Sysmon%4Operational.evtx

# Security.evtx
PS C:\Users\Lish\Downloads\winlogbeat-7.8.1-windows-x86_64> .\winlogbeat.exe -e -c .\winlogbeat.yml -E EVTX_FILE=C:\Users\Lish\Desktop\Logs\HOST_Logs\Security.evtx
```
