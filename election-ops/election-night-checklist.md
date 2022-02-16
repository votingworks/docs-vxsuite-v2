# Election Night Checklist

On election night, you will need the [VxCentralScan](../central-system-setup/vxcentralscan-hardware-setup.md) (laptop and scanner) and [VxAdmin](../central-system-setup/vxadmin-hardware-setup.md) (laptop and printer). **Then, run this checklist.**

### [Central Scanning](scanning-ballots.md)

* [ ] Set up VxCentralScan by plugging the laptop and scanner into power and connecting the two via USB
* [ ] Boot up both laptops.
* [ ] Confirm VxCentralScan does not say **TEST MODE** and says **No ballots have been scanned**
  * [ ] If there is a problem, switch the scanner to "Live Mode" or `Delete Ballot Data` from the `Advanced` menu
* [ ] Scan all ballots in batches of approximately 50.
* [ ] Create a pile of ballots for adjudication as rejected from the scanner.
* [ ] Adjudicate ballots with the resolution board.
* [ ] Scan resolution board ballots.
* [ ] Write down how many ballots were scanned by the scanner (on ballot scanner laptop screen).
* [ ] Export CVRs to USB stick.
* [ ] Export Backup to USB stick (in Advanced tab).

### [Tallying](tabulating-results.md) and [Exporting](export-results.md) Results

* [ ] Set up VxAdmin by plugging in the laptop and printer and connecting the two via USB
* [ ] Ensure there are no CVRs imported. If there are, remove them.
* [ ] Print a zero report.
* [ ] Import CVRs from USB drives.
* [ ] If applicable, load SEMS file from other machines (e.g. TSX GEMS results).
* [ ] Print an unofficial tally of all ballots.
* [ ] Export combined SEMS file to USB stick.
* [ ] Upload combined SEMS file to SEMS.
