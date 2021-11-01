# Central System Checklist

This checklist is for jurisdictions who are using the VotingWorks central system (VxAdmin and VxBatch) without the precinct system (VxMark or VxScan). It only needs to be run once per election. If you are using any precinct equipment, skip to the next section. Links after each section point to articles with more details on the individual steps.

| Name | Date |
| ---- | ---- |

### VxAdmin - Part 1

* [ ] Connect VxAdmin to its printer
* [ ] Ensure the printer has plenty of paper
* [ ] Turn on VxAdmin
* [ ] Confirm that VxAdmin is configured for the appropriate election
* [ ] `Print Test Decks` for  `All Precincts`. This may take a few minutes.
* [ ] Print the `Test Ballot Deck Tally` for `All Precincts`
* [ ] Print an `Unofficial Full Election Tally Report` as the Zero Report
* [ ] Print two additional test ballots from any precinct
  * [ ] Leave one test ballot blank
  * [ ] Mark the second test ballot as an overvote
* [ ] Confirm that you now have all of the following:
  * [ ] Full Test Deck
  * [ ] Test Ballot Deck Tally
  * [ ] Zero Report
  * [ ] Blank Ballot
  * [ ] Overvoted Ballot

{% content-ref url="test-deck-printing.md" %}
[test-deck-printing.md](test-deck-printing.md)
{% endcontent-ref %}

### VxBatch

Repeat the following for each VxBatch:

* [ ] Connect VxBatch to its scanner
* [ ] Turn on the VxBatch laptop and the scanner
* [ ] Confirm that VxBatch is configured for the appropriate election
* [ ] Toggle to `Test` Mode
* [ ] Scan the full test deck
* [ ] Scan the blank ballot
  * [ ] Confirm it shows up as blank
  * [ ] Choose `Original Ballot Removed`.
* [ ] Scan the overvoted ballot
  * [ ] Confirm it shows up as overvote
  * [ ] Choose `Original Ballot Removed`.
* [ ] Verify the count of scanned ballots
* [ ] Export CVRs to USB drive

{% content-ref url="test-deck-scanning.md" %}
[test-deck-scanning.md](test-deck-scanning.md)
{% endcontent-ref %}

### VxAdmin - Part 2

Repeat the following for each VxBatch:

* [ ] Insert USB drive with the CVR files
* [ ] Click "Import CVR Files" in the Tally Tab
* [ ] Import the CVR file from the given VxBatch
* [ ] Confirm that the CVR count in VxAdmin matches the number of ballots in the test deck
* [ ] Print Unofficial Full Election Tally Report
* [ ] Compare to the Test Ballot Deck Tally  and ensure they match
* [ ] Clear CVR files

{% content-ref url="tabulate-test-deck.md" %}
[tabulate-test-deck.md](tabulate-test-deck.md)
{% endcontent-ref %}

### **Cleanup**

* [ ] Confirm that there are no CVR files left in VxAdmin tally tab
* [ ] Toggle VxBatch to **Live Mode **(in `Advanced` tab)
* [ ] Shut down VxAdmin
* [ ] Shut down VxBatch

{% content-ref url="prepare-for-election-day.md" %}
[prepare-for-election-day.md](prepare-for-election-day.md)
{% endcontent-ref %}
