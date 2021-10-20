# Scan Test Decks with VxBatch

These instructions apply to both the VxAdmin and VxMark test decks. If you have both, we recommend scanning each separately and verifying the results of each separately.

Before scanning each test deck, confirm that the election information in the footer is correct.&#x20;

If VxBatch is not already configured, please follow the instructions to configure VxBatch for the election:

{% content-ref url="../central-system-setup/configure-ballot-scanner.md" %}
[configure-ballot-scanner.md](../central-system-setup/configure-ballot-scanner.md)
{% endcontent-ref %}

## Toggle Test Mode

All test deck scanning must be performed in test mode. To change modes, click `Advanced` in the top right and then click `Toggle to Test Mode` under **Advanced Options. **Changing modes zeros out all existing scans in the previous mode.

![Advanced Button](../.gitbook/assets/advanced\_fresh.png)

![Toggle to Test Mode](../.gitbook/assets/toggletestmode.png)

Once in test mode, confirm that  `TEST MODE` is shown at the top of the screen and `No ballots have been scanned.`

![VxBatch in Test Mode](<../.gitbook/assets/Screenshot from 2020-09-09 14-46-54.png>)

## Scan Test Deck

Before scanning, take at least one ballot from the test deck and flip it upside down, then replace on the stack. Next, take at least one ballot from the test deck and flip it back to front, then replace on the stack.

Load the stack of ballots into the feeder tray of the scanner. VotingWorks recommends loading no more than 50 ballot sheets at at time.

From VxBatch, click `Scan New Batch`. Ballots will feed through the scanner automatically and the number of ballots scanned within each batch will progress onscreen. The batch is finished scanning when a timestamp is presented under the `Finished At` header for that particular batch. Repeat the scanning process for as many batches are necessary to finish scanning all ballots in the test deck.

![Test Mode Scanned Batches](../.gitbook/assets/scanned\_test\_deck\_batches.png)

Next, scan the additional test ballots created. One is blank and one should be marked with an overvote. Verify the scanner requests each [ballot be adjudicated](../election-ops/scanning-ballots.md#adjudicate-ballots) before proceeding.

Once finished scanning, confirm that the ballot count listed onscreen matches the number of ballot sheets in the test deck.

## Export Cast Vote Record

To export the Cast Vote Record (CVR) of scanned results, click `Export` in the top right:

![Export CVR](../.gitbook/assets/export-cvrs.png)

An export dialog appears prompting you to insert a USB stick. Once you do, the USB stick is detected in a few seconds, and the export can be done automatically by clicking the "Export" button:

![](<../.gitbook/assets/export-dialog (1).png>)



Once the CVR file has been saved to the USB stick, a dialog prompts to eject the drive:

![](<../.gitbook/assets/image (14).png>)



Once the close button appears, it's safe to physically remove the USB drive:

![](<../.gitbook/assets/Screen Shot 2021-03-19 at 7.04.24 PM.png>)

## Clear Ballot Data

{% hint style="warning" %}
The following only applies if you are using VxMarks and thus your L\&A process involves scanning two test decks.
{% endhint %}

Before scanning the second test deck, the ballot data needs to be be cleared.

Click the `Advanced` button in the top navigation bar.

Click the `Delete Ballot Data` button and confirm.

Repeat the steps above from [Scan Test Deck](test-deck-scanning.md#scan-test-deck) for the second test deck.
