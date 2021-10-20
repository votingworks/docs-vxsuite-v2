# VxBatch Checklist

The VxBatch Checklist should be run for _each _VxBatch. If your VxBatch is not yet set up or configured,  see [VxBatch Hardware Setup](../../central-system-setup/vxbatch-hardware-setup.md) and [Configuring VxBatch](../../central-system-setup/configure-ballot-scanner.md).

If you split up the test decks by precinct for VxScan L\&A, you'll want to recombine all the precinct test decks into full, "All Precinct" test decks - one for VxAdmin ballots and one for VxMark ballots.&#x20;

| Name | Date |
| ---- | ---- |

* [ ] Connect VxBatch to its scanner
* [ ] Turn on the VxBatch laptop and the scanner
* [ ] Confirm that VxBatch is configured for the appropriate election
* [ ] Toggle to Test Mode
* [ ] Tally the VxMark Test Deck
  * [ ] Scan entire deck
  * [ ] Confirm the count of scanned ballots
  * [ ] Export CVR file to USB drive
* [ ] `Delete Ballot Data` in the `Advanced` Menu
* [ ] Tally the VxAdmin Test Deck
  * [ ] Scan entire deck
  * [ ] Confirm the count of scanned ballots
  * [ ] Export CVR file to USB drive
* [ ] Scan the blank ballot
  * [ ] Confirm it shows up as blank
  * [ ] Choose `Original Ballot Removed`.
* [ ] Scan the overvoted ballot
  * [ ] Confirm it shows up as overvote
  * [ ] Choose `Original Ballot Removed`.

{% content-ref url="../test-deck-scanning.md" %}
[test-deck-scanning.md](../test-deck-scanning.md)
{% endcontent-ref %}

