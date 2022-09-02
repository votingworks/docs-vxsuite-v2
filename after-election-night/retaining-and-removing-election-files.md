# Retaining & Removing Election Files

### Retaining Election Files

After certification of an election and before configuring a new election, all election files and data should be saved and configuration files removed from the previous election.

VotingWorks recommends retaining the following files after each election:

* [ ] VxAdmin results file
* [ ] VxAdmin tally reports
* [ ] VxAdmin log
* [ ] VxCentralScan backup files
* [ ] VxScan backup files

### VxAdmin&#x20;

To save the recommended VxAdmin files, follow these steps when logged in as an Election Manager:

1. In the Reports tab, select _`Save Results`_
2. In the Reports tab, select _`Official Full Election Tally Report`_, select _`Save Report as PDF`_

<div>

<figure><img src="../.gitbook/assets/VxAdmin Reports Save Results File.png" alt=""><figcaption><p>Save Results File</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/VxAdmin Reports Official Full Election Tally Report.png" alt=""><figcaption><p>Save Official Full Election Tally Report</p></figcaption></figure>

</div>

Next, login as a System Administrator, select _`Log`_, and _`Save Log File`_.

<figure><img src="../.gitbook/assets/image (41).png" alt=""><figcaption><p>Save Log File</p></figcaption></figure>

### VxCentralScan Backup Files

VxCentralScan backup files are saved on election night. This file includes the CVRs, logs, and ballot images. If the backup file was not saved on election night, simply go to the Admin menu and select _`Save Backup`_.

<figure><img src="../.gitbook/assets/image (127).png" alt=""><figcaption><p>Save Backup</p></figcaption></figure>

### VxScan CVR Files

VxScan CVR files include the VxScan's CVRs, logs, and ballot images. To save the VxScan backup files, [setup the VxScan](../poll-worker-guides/setting-up-and-opening-polls/vxscan-setup.md) and follow the following steps:\
\
1\. Insert an Election Manager Card

2\. Insert a USB drive

3\. Select _`Save Backup`_

<figure><img src="../.gitbook/assets/image (72).png" alt=""><figcaption><p>Save Backup</p></figcaption></figure>

### Removing Election Files

Each VotingWorks component has a red button to remove election files.

In VxAdmin, login with a System Administrator Card and go to the Definition tab, select _`Remove Election`_.

![Remove Election](<../.gitbook/assets/image (190) (2).png>)

In VxCentralScan, go to the Admin screen, select _`Delete Election Data from VxCentralScan`_.

<figure><img src="../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

In VxScan, insert an Election Manager Card and select _`Delete All Election Data from VxScan`_.

<figure><img src="../.gitbook/assets/image (151).png" alt=""><figcaption><p>Delete All Election Data from VxScan</p></figcaption></figure>

In VxMark, insert an Election Manager Card and select _`Unconfigure Machine`_.

<figure><img src="../.gitbook/assets/image (54).png" alt=""><figcaption><p>Unconfigure Machine</p></figcaption></figure>
