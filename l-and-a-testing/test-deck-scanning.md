# Scan Test Decks with VxCentralScan

Before scanning each test deck, confirm that the election information in the footer is correct.&#x20;

If VxCentralScan is not already configured, please follow the instructions to configure VxCentralScan for the election:

{% content-ref url="../central-system-setup/configure-ballot-scanner.md" %}
[configure-ballot-scanner.md](../central-system-setup/configure-ballot-scanner.md)
{% endcontent-ref %}

## Toggle Test Mode

All test deck scanning must be performed in test mode. If VxCentralScan is not already in test mode, change the mode. To change mode, select _`Admin`_at the top right of the screen.

![Select Admin](<../.gitbook/assets/image (182).png>)

Select _`Toggle to Test Mode`_**.** Changing modes zeros out all existing scans in the previous mode.

![Toggle to Test Mode](<../.gitbook/assets/image (241).png>)

Once in test mode, confirm the Machine is in Testing Mode is shown at the top of the screen and No ballots have been scanned is displayed.

![](<../.gitbook/assets/image (167).png>)

## Scan Test Deck

Before scanning, take at least one ballot from the test deck and flip it upside down, then replace on the stack. Next, take at least one ballot from the test deck and flip it back to front, then replace on the stack.

Load the stack of ballots into the feeder tray of the scanner. VotingWorks recommends loading no more than 50 ballot sheets at at time.

From VxCentralScan, select _`Scan New Batch`_. Ballots feed through the scanner automatically and the number of ballots scanned will increase as each ballot is scanned under Ballot Count. A timestamp will appear under the Finished At header when a batch is done scanning. Repeat the scanning process until all ballots are scanned.

<figure><img src="../.gitbook/assets/image (244).png" alt=""><figcaption></figcaption></figure>

Next, scan the additional test ballots created. One is blank and one should be marked with an overvote. Verify the scanner requests each [ballot be adjudicated](../election-ops/scanning-ballots.md#adjudicate-ballots) before proceeding.

Once finished scanning, confirm that the ballot count listed onscreen matches the number of ballot sheets in the test deck.

## Save Cast Vote Records

To save the Cast Vote Record (CVR) of scanned results, select _`Save CVRs`_ in the top right.

<figure><img src="../.gitbook/assets/image (237).png" alt=""><figcaption><p>Save CVRs</p></figcaption></figure>

An export dialog appears prompting you to insert a USB drive. Once you do, the USB drive is detected in a few seconds, and the export can be done automatically by selecting _`Save`_. Once the CVR file has been saved to the USB drive, select _`Eject USB`_. When complete, the CVRs Saved screen will prompt you to close and eject the USB drive.

<div>

<figure><img src="../.gitbook/assets/VxCS Save CVRs (1).png" alt=""><figcaption><p>Save</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/VxCS Save CVRs CVRs Saved modal (1).png" alt=""><figcaption><p>Eject USB</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/VxCS Save CVRs CVRs Saved Drive ejected modal.png" alt=""><figcaption><p>Close</p></figcaption></figure>

</div>





##
