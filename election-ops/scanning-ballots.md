# Central Scanning

VxCentralScan is a central scanning solution that allows you to quickly scan large batches of ballots. If you are using VxScan at your precincts, then you'll use VxCentralScan to scan absentee and affidavit ballots. If you are not using VxScan at your precincts, then you'll use VxCentralScan to scan all ballots.

## Scan Ballot Batches

Before scanning the first ballot batch, confirm that VxCentralScan displays `No ballots have been scanned` and that the scanner display shows no scans. If otherwise, you should select the `Delete Ballot Data` option under the `Admin` menu.

![](<../.gitbook/assets/image (193).png>)

To load a ballot batch, place a stack of ballots into the feeder tray of the scanner connected to VxCentralScan. VotingWorks recommends scanning no more than 50 ballot sheets per batch. The ballots need to be in a neat stack, unfolded and lying flat, but ballots can be in any orientation (e.g. upside down or backwards is fine).

Click `Scan New Batch` in the top right to start scanning. Ballots will feed through the scanner automatically and the number of ballots scanned within each batch will progress onscreen. The batch is finished scanning when a timestamp is presented under the `Finished At` header for that particular batch.

![](<../.gitbook/assets/image (88).png>)

Once the batch finishes scanning, remove it from the output tray on the scanner and place the next stack of ballots in the feeder tray. Repeat the scanning process for as many batches are necessary to finish scanning all ballots.

![](<../.gitbook/assets/image (159).png>)

## Adjudicate Ballots

VxCentralScan will stop scanning and present a review screen if scanning cannot be completed due to a blank sheet, overvoted contest, scan mode mismatch, or an otherwise unreadable ballot sheet. The review screen will display an image of the scanned ballot sheet, the reason why scanning was stopped, and confirm that this ballot sheet has not been tabulated yet.

### Blank & Overvoted Ballots

#### Original Ballot Scan

If scanning an original voter-marked ballot, remove the last ballot sheet scanned from the scanner output tray and confirm it matches the ballot sheet displayed onscreen. Once removed, click `Original Ballot Removed` and confirm by clicking `Confirm Ballot Removed and Continue Scanning`. Once confirmed, the scanner will resume scanning ballots in the batch.&#x20;

The example below shows an **Overvote** detected that is being removed for Resolution Board processing.

![Overvote - Original Ballot Removed](../.gitbook/assets/overvote\_original.png)

The removed ballot should be duplicated and prepared for the Resolution Board. Using a red pen, mark the removed ballot as `Original` and the duplicated ballot as `Duplicate` with both ballots number consecutively. For example, the first ballot removed should be marked as `Original #1` and the ballot used for duplication as `Duplicate #1`. Place both the original and duplicate ballots in an envelope to provide to the Resolution Board.

The Resolution Board will examine the original ballot and mark the duplicate ballot in a manner consistent with the voter’s intent and applicable laws. When all original ballot batches have been scanned, a final batch containing all the duplicated ballots may be scanned to reincorporate these ballots into the tally.

#### Duplicate Ballot Scan

If scanning a duplicated ballot prepared by the Resolution Board, first confirm that the reason presented on screen is valid and that the duplicate ballot should be tabulated as such. VotingWorks recommends scanning all duplicate ballots as the last batch on election night.

To tabulate the duplicate ballot, click `Tabulate Duplicate Ballot` and then `Tabulate Ballot and Continue Scanning`. The duplicate ballot will be recorded with the condition shown on screen and the scanner will continue scanning the remaining ballots in the batch.

The example below shows a **Blank Ballot** duplicated by the Resolution Board that is being tabulated as a blank ballot.

![Blank Ballot - Tabulate Duplicate Ballot](../.gitbook/assets/blank\_tabulate.png)

### Unreadable Ballots

VxCentralScan may show an **Unreadable** ballot screen for a properly marked ballot if it's unable to decode ballot information due to page skew, dust, or tampering of the ballot. When a ballot sheet is shown as unreadable, you can safely remove the ballot and re-scan the ballot sheet. If the ballot is unreadable on a second scan, you should remove the ballot and prepare a duplicate ballot for the Resolution Board to review.

![Unreadable Ballot](../.gitbook/assets/unreadable.png)

### Mode Mismatch

A mode mismatch error will appear if the scanner mode (`Test` or `Official`) does not match the ballot type (`Test` or `Official`) and the scanned sheet will not be tabulated. In these cases, you should either remove the ballot from the stack or switch scanner modes.

The example below shows a `Test` ballot that was scanned in `Live` mode.

![](../.gitbook/assets/modemismatch.png)

