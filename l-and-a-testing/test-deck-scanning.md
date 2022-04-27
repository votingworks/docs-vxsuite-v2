# Scan Test Decks with VxCentralScan

Before scanning each test deck, confirm that the election information in the footer is correct.&#x20;

If VxCentralScan is not already configured, please follow the instructions to configure VxCentralScan for the election:

{% content-ref url="../central-system-setup/configure-ballot-scanner.md" %}
[configure-ballot-scanner.md](../central-system-setup/configure-ballot-scanner.md)
{% endcontent-ref %}

## Toggle Test Mode

All test deck scanning must be performed in test mode. If VxCentralScan is not already in test mode, change the mode. To change mode, select _`Admin`_at the top right of the screen.

![](<../.gitbook/assets/image (182).png>)

Select _`Toggle to Test Mode`_**.** Changing modes zeros out all existing scans in the previous mode.

![](<../.gitbook/assets/image (177) (1).png>)

Once in test mode, confirm that  TEST MODE is shown at the top of the screen and No ballots have been scanned is displayed.

![](<../.gitbook/assets/image (214).png>)

## Scan Test Deck

Before scanning, take at least one ballot from the test deck and flip it upside down, then replace on the stack. Next, take at least one ballot from the test deck and flip it back to front, then replace on the stack.

Load the stack of ballots into the feeder tray of the scanner. VotingWorks recommends loading no more than 50 ballot sheets at at time.

From `VxCentralScan`, select _`Scan New Batch`_. Ballots feed through the scanner automatically and the number of ballots scanned will increase as each ballot is scanned under Ballot Count. A timestamp will appear under the Finished At header when a batch is done scanning. Repeat the scanning process until all ballots are scanned.

![](<../.gitbook/assets/image (95) (1) (1).png>)

Next, scan the additional test ballots created. One is blank and one should be marked with an overvote. Verify the scanner requests each [ballot be adjudicated](../election-ops/scanning-ballots.md#adjudicate-ballots) before proceeding.

Once finished scanning, confirm that the ballot count listed onscreen matches the number of ballot sheets in the test deck.

## Export Cast Vote Record

To export the Cast Vote Record (CVR) of scanned results, select _`Export`_ in the top right.

![](<../.gitbook/assets/image (133) (1).png>)

An export dialog appears prompting you to insert a USB drive. Once you do, the USB drive is detected in a few seconds, and the export can be done automatically by selecting _`Export`_.

![](<../.gitbook/assets/image (94).png>)

Once the CVR file has been saved to the USB drive, select _`Eject USB`_.

![](<../.gitbook/assets/image (212) (1).png>)

When complete, the Download Complete screen will tell you to remove the USB drive.

![](<../.gitbook/assets/image (87) (1).png>)

##
