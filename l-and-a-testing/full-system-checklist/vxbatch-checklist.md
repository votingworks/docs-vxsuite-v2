# VxBatch Checklist

The VxBatch Checklist should be run for _each _VxBatch. If your VxBatch is not yet set up or configured,  see [VxBatch Hardware Setup](../../central-system-setup/vxbatch-hardware-setup.md) and [Configuring VxBatch](../../central-system-setup/configure-ballot-scanner.md).

| Name | Date |
| ---- | ---- |

* [ ] Recombine VxMark + VxScan test decks from each precinct into one batch of ballots. You may also print new test decks - 1 from VxAdmin and 1 from any VxMark - if that is easier.
* [ ] Connect VxBatch to its scanner
* [ ] Turn on the VxBatch laptop and the scanner
* [ ] Confirm that VxBatch is configured for the appropriate election
* [ ] Click `Toggle to Test Mode` from the `Advanced` menu
* [ ] Scan Both Test Decks (machine-marked from VxMark and hand-marked from VxAdmin)
* [ ] Confirm the count of scanned ballots is twice the number of ballots in a single test deck
* [ ] `Export` the CVR file to a USB Drive
* [ ] Scan the blank ballot
  * [ ] Confirm it shows up as blank
  * [ ] Choose Original` Ballot Removed`.
* [ ] Scan the overvoted ballot
  * [ ] Confirm it shows up as an overvote
  * [ ] Choose `Original Ballot Removed`.
* [ ] Click `Toggle to Live Election Mode` in the `Advanced` menu

{% content-ref url="../test-deck-scanning.md" %}
[test-deck-scanning.md](../test-deck-scanning.md)
{% endcontent-ref %}

