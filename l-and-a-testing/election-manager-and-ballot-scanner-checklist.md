# Central System (only) Checklist

This checklist is for jurisdictions who are using the VotingWorks central system (VxAdmin and VxCentralScan) without the precinct system (VxMark or VxScan). It only needs to be run once per election. If you are using any precinct equipment, skip to the next section. Links after each section point to articles with more details on the individual steps.

| Name | Date |
| ---- | ---- |

### VxAdmin - Part 1

* [ ] Connect VxAdmin to its printer
* [ ] Ensure the printer has plenty of paper
* [ ] Turn on VxAdmin and printer
* [ ] Confirm that VxAdmin is configured for the appropriate election
* [ ] Print the following reports and ballot packages
  * [ ] Using the Reports tab, print an _`Unofficial Full Election Tally Report`_ as the Zero Report
  * [ ] Using the L\&A tab, select _`List Precinct L&A Packages`_. Print the L\&A Packages for all precincts, or for a specific precinct.
  * [ ] Using the L\&A tab, select _`Print Full Test Deck Tally Report`_ to print the expected results after scanning all test ballots.
* [ ] Remove the following from each L\&A Package:
  * [ ] Precinct Tally Report (expected results of the precinct)
  * [ ] Pre-voted VxMark test ballots
  * [ ] All but two blank hand-marked test ballots from one ballot style (one remains blank, one is hand-marked by an election official to replace a pre-voted hand-marked test ballot)
  * [ ] All but one overvoted hand-marked test ballot
* [ ] Ensure the following items remain for each precinct and ballot style:
  * [ ] Pre-voted hand-marked test ballots
  * [ ] Two blank hand-marked test ballots from one ballot style (one remains blank, one is hand-marked by an election administrator to replace a pre-voted hand-marked test ballot)
  * [ ] One overvoted hand-marked test ballot
* [ ] Confirm that you also have the following materials for the overall election:
  * [ ] Zero Report (Unofficial Full Election Tally Report)
  * [ ] Full Test Deck Tally Report (expected results of all precincts)

{% content-ref url="test-deck-printing.md" %}
[test-deck-printing.md](test-deck-printing.md)
{% endcontent-ref %}

### VxCentralScan

Repeat the following for each VxCentralScan station:

* [ ] Connect VxCentralScan laptop to its scanner
* [ ] Turn on the VxCentralScan laptop and the scanner
* [ ] Confirm that VxCentralScan is configured for the appropriate election
* [ ] Toggle to Test Mode
* [ ] Scan the pre-voted hand-marked test ballots
* [ ] Scan the blank ballot
  * [ ] Confirm it shows up as blank
  * [ ] Choose _`Cast Ballot As Is`_
* [ ] Scan the overvoted ballot
  * [ ] Confirm it shows up as overvote
  * [ ] Choose _`Cast Ballot As Is`_
* [ ] Verify the count of scanned ballots
* [ ] Save Results to USB drive

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
* [ ] Compare to the Test Ballot Deck Tally  - the totals on the Test Ballot Deck Tally should be divided by 4 and then should match your scanning results (the Test Ballot Deck Tally report is programmed for the Full System)
* [ ] Clear CVR files

{% content-ref url="tabulate-test-deck.md" %}
[tabulate-test-deck.md](tabulate-test-deck.md)
{% endcontent-ref %}

### **Cleanup**

* [ ] Confirm that there are no CVR files left in VxAdmin Tally tab
* [ ] Toggle VxCentralScan to **Live Mode** (in _`Admin`_ tab)
* [ ] Shut down VxAdmin
* [ ] Shut down VxCentralScan

{% content-ref url="prepare-for-election-day.md" %}
[prepare-for-election-day.md](prepare-for-election-day.md)
{% endcontent-ref %}
