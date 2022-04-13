# Print & Proof Ballots

Once VxAdmin is configured, ballots are ready for proofing and printing. All ballot styles are found in the Ballots tab. The number of generated ballot styles generated is shown at the top. The list may be sorted by _`Precinct`_ or _`Style`_ using the buttons next to Sort N ballots by.

![](<../.gitbook/assets/image (145) (1).png>)

## Proof and Print a Ballot

To proof a ballot, select _`View Ballot`_to the right of the ballot to review

The ballot preview will display the ballot, exactly as it will print, for easy proofing and printing.

![](<../.gitbook/assets/image (162) (1) (1).png>)

You need to select three options before printing a ballot:

* _`Official`_ or _`Test`_or_`Sample`_
* _`Absentee`_ or _`Precinct`_
* Number of copies

Once selected, simply click _`Print [Number] [Mode] [Type] Ballot(s)`_ to print your desired ballot(s). VxAdmin prints 1 Official Absentee ballot by default.&#x20;

![](<../.gitbook/assets/image (189).png>)

{% hint style="warning" %}
Only test or sample ballots should be printed for proofing purposes. Please reference the section below for the differences between official, test, and sample ballots.
{% endhint %}

### Official vs. Test vs. Sample Ballots

#### Official Ballot

Official ballots should only be printed for marking by voters. These ballots are titled **Official Ballot** in the top-left ballot corner and will be tabulated when VxScan or VxCentralScan is in Live mode.

The number of official ballots printed is displayed in the all ballot view and a Printed Ballot Report can be generated at any time which includes the count of official ballots printed.&#x20;

{% hint style="danger" %}
If any official ballots are printed for proofing, they should be labeled with a pen as "for proofing" and stored securely or destroyed after proofing so that they cannot be mistaken for valid ballots to be counted.
{% endhint %}

To have official ballots printed by a vendor, use the .pdfs found in the [ballot package](export-ballot-package.md).

#### Test Ballot

A test ballot should be used for proofing purposes. Test ballots appear the same as an official ballot but are titled **Test Ballot** in the top-left ballot corner.

Test ballots will not be tabulated by default and are only read by the VxScan or VxCentralScan when in Test mode.

**Sample Ballot**

A sample ballot should be used for display or demonstration use. Sample ballots will not be read by the VxScan. Sample ballots are also available as .pdfs in the [ballot package](export-ballot-package.md). The .pdfs can be used to print them on larger paper.

### Absentee vs. Precinct Ballots

An absentee ballot should be used for absentee voting and a precinct ballot should be used for all voters, including affidavit, curbside, and emergency voters. Absentee and precinct ballots are the same with the exception of a label printed in the top-left corner and on every page footer for absentee ballots. With a color printer, the label is printed as white text on purple background. With a black-and-white printer, the label is printed as white text on grey background.

![Absentee Header in Color](../.gitbook/assets/header.png)

## Edit Election Definition

If you find any errors while proofing ballots, you have one of two options.

**If you imported directly from SEMS,** you should make changes directly in SEMS, re-export the SEMS files, and then re-configure VxAdmin with the new SEMS files. It's necessary to make edits in SEMS first so that the two systems match for when you eventually export to SEMS at the end of an election.

**If you imported a VotingWorks-provided definition file,** please reach out to VotingWorks for help editing the election definition.
