# SolaceScriptHA

Shell script for installing Solace in HA

Note:

solace-primary is hostname of active node, solace-backup is hostname of backup node, solace-monitoring is hostname of monitoring node

Run Solace Primary

[opc@solace-primary solacescripts]$ bash HAPrimary.sh

Run Solace Backup

[opc@solace-backup solacescripts]$ bash HABackup.sh

Run Solace Monitoring

[opc@solace-monitoring solacescripts]$ bash HAMonitor.sh
