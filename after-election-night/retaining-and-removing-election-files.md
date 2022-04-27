# Retaining & Removing Election Files

### Retaining Election Files

After certification of an election and before configuring a new election, all election files and data should be saved and configuration files removed from the previous election.

VotingWorks recommends retaining the following files after each election:

* [ ] VxAdmin results file
* [ ] VxAdmin tally reports
* [ ] VxAdmin log
* [ ] VxCentralScan CVR files
* [ ] VxCentralScan backup files
* [ ] VxCentralScan log
* [ ] VxScan CVR files
* [ ] VxScan backup files

### VxAdmin&#x20;

To save the recommended VxAdmin files, follow these steps:

1. In the Tally tab, select _`Save Results File`_
2. In the Tally tab, select _`View Unofficial Full Election Tally Report`_, select _`Save Report as PDF`_
3. In the Advanced tab, _`Export Log File`_

![Save Results File](<../.gitbook/assets/save results file vxadmin.png>) ![View Unofficial Full Election Tally Report](<../.gitbook/assets/view unofficial full election tally report vxadmin.png>) ![Export Log File](<../.gitbook/assets/export log file vxadmin.png>)

### VxCentralScan CVR Files

VxCentralScan CVR files and backup files are saved on election night. If the CVR files were not retained for retention, follow the [Exporting Cast Vote Records steps under Central Scanning](../election-ops/scanning-ballots.md).

Save the VxCentralScan log by navigating to the Admin menu and selecting _`Export Logs...`_

![Export Logs](<../.gitbook/assets/image (221).png>)

### VxScan CVR Files

VxScan CVR files are saved onto USB drives at the precinct on election night. Retaining the files on the USB drives is sufficient. If the CVR file was not saved for a precinct be sure to save a copy (select _`Export Results to USB Drive`_) when saving the backup. To save the VxScan backup files, [setup the VxScan](../poll-worker-guides/setting-up-and-opening-polls/vxscan-setup.md) and follow the following steps:\
\
1\. Insert an Admin Card

2\. Insert a USB drive

3\. Select _`Export Backup to USB Drive`_

![Export Backup to USB Drive](<../.gitbook/assets/image (125).png>)

### Removing Election Files

Each VotingWorks component has a red button to remove election files.

In VxAdmin, go to the Definition tab, select _`Remove Election`_.

![Remove Election](<../.gitbook/assets/image (190).png>)

In VxCentralScan, go to the Admin screen, select _`Delete Election Data from VxCentralScan`_.

![Delete Election Data from VxCentralScan](<../.gitbook/assets/image (218).png>)

In VxScan, insert an Admin Card and select Unconfigure Machine.

![Unconfigure Machine](<../.gitbook/assets/image (132).png>)

In VxMark, insert an Admin Card and select _`Unconfigure Machine`_.

![Unconfigure Machine](<../.gitbook/assets/image (107).png>)
