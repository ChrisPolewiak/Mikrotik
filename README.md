Scripts for daily tasks

## Backup.script
Simple script to create FTP backup your configuration. Backup created using Export command not Backup, so it exclude User Accouts but you can simply edit configuraton before upload. Required if you recover a configuration on different hardware/model
***Note - Mikrotik cannot use encrypted FTP (FTPS), so use this script only in secured environment (VPN).***


## AutoUpdate.script
Automatic Mikrotik update. You can schedule this script for daily use, this will automatically update your device and reboot it after.
***Note - use in DEV/TEST Environment before run on PROD. Sometimes updates can hang/lock your device...***

