# Central System Checklist

This checklist is for jurisdictions who are using the VotingWorks central system (VxAdmin and VxCentralScan) without the precinct system (VxMark or VxScan). It only needs to be run once per election. If you are using any precinct equipment, skip to the next section. Links after each section point to articles with more details on the individual steps.

| Name | Date |
| ---- | ---- |

### VxAdmin - Part 1

* [ ] Connect VxAdmin to its printer
* [ ] Ensure the printer has plenty of paper
* [ ] Turn on VxAdmin and printer
* [ ] Confirm that VxAdmin is configured for the appropriate election
* [ ] _`Print Test Decks`_ for  _`All Precincts`_- this may take a few minutes
* [ ] Print the _`Test Ballot Deck Tally`_ for _`All Precincts`_
* [ ] Print an _`Unofficial Full Election Tally Report`_ as the Zero Report
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

### VxCentralScan

Repeat the following for each VxCentralScan station:

* [ ] Connect VxCentralScan laptop to its scanner
* [ ] Turn on the VxCentralScan laptop and the scanner
* [ ] Confirm that VxCentralScan is configured for the appropriate election
* [ ] Toggle to Test Mode
* [ ] Scan the full test deck
* [ ] Scan the blank ballot
  * [ ] Confirm it shows up as blank
  * [ ] Choose _`Tabulate Duplicate Ballot`_
* [ ] Scan the overvoted ballot
  * [ ] Confirm it shows up as overvote
  * [ ] Choose _`Tabulate Duplicate Ballot`_
* [ ] Verify the count of scanned ballots
* [ ] Export CVRs to USB drive

{% content-ref url="test-deck-scanning.md" %}
[test-deck-scanning.md](test-deck-scanning.md)
{% endcontent-ref %}

### VxAdmin - Part 2

Repeat the following for each VxCentralScan USB drive:

* [ ] Insert USB drive with the CVR files
* [ ] Select _`Import CVR Files`_ in the Tally tab
* [ ] Import the CVR file from the given VxCentralScan
* [ ] Confirm that the CVR count in VxAdmin matches the number of ballots in the test deck
* [ ] Print _`Unofficial Full Election Tally Report`_
* [ ] Compare to the Test Ballot Deck Tally  and ensure they match
* [ ] Clear CVR files

{% content-ref url="tabulate-test-deck.md" %}
[tabulate-test-deck.md](tabulate-test-deck.md)
{% endcontent-ref %}

### **Cleanup**

* [ ] Confirm that there are no CVR files left in VxAdmin Tally tab
* [ ] Toggle VxCentralScan to **Live Mode** (in `Admin` tab)
* [ ] Shut down VxAdmin
* [ ] Shut down VxCentralScan

{% content-ref url="prepare-for-election-day.md" %}
[prepare-for-election-day.md](prepare-for-election-day.md)
{% endcontent-ref %}
