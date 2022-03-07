# Print & Proof Ballots

As soon as an election definition is loaded, ballots are ready for printing. All ballot styles are shown under the Ballots Tab. The number of generated ballot styles generated is shown at the top. You may sort the list by either `Precinct` or `Style` using the buttons next to the `Sort N ballots by:` text.

![](<../.gitbook/assets/image (145).png>)

## Proof and Print a Ballot

To proof a particular ballot, click `View Ballot` button next to the desired ballot precinct and style to open the ballot details view.

The ballot details view presents a rendered ballot, exactly as it will print, for easy proofing and functionality to print ballots on-demand:

![](<../.gitbook/assets/image (162) (1).png>)

You need to select three options before printing a ballot:

* `Official` or `Test or` Sample
* `Absentee` or `Precinct`
* Number of copies

Once selected, simply click `Print [Number] [Mode] [Type] Ballot(s)` to print your desired ballot(s). VxAdmin prints `1 Official Absentee` ballot by default.&#x20;

![](<../.gitbook/assets/image (189).png>)

{% hint style="warning" %}
Only `Test` or `Sample` ballots should be printed for proofing purposes. Please reference the section below for the differences between official, test, and sample ballots.
{% endhint %}

When using a black-and-white printer, VxAdmin will remind you, before printing, to check that you've loaded the printer with the right paper – tinted paper for absentee, white paper for in-person.

![Paper Type Confirmation](<../.gitbook/assets/Screen Shot 2021-02-10 at 6.49.12 PM.png>)

### Official vs. Test vs. Sample Ballots

#### Official Ballot

Official ballots should only be printed for marking by voters. These ballots are denoted by **Official Ballot** in the top-left of the ballot and will be tabulated when VxScan or VxCentralScan is in `Live` mode.

The number of official ballots printed are also presented in the all ballot view and a `Printed Ballot Report` can be generated at any time which includes the count of official ballots printed.&#x20;

{% hint style="danger" %}
If any official ballots are printed for proofing, they should be labeled with a pen as "for proofing" and stored securely or destroyed after proofing so that they cannot be mistaken for valid ballots to be counted.
{% endhint %}

#### Test Ballot

A `Test` ballot should be used for proofing purposes. Test ballots appear the same as an official ballot but are denoted by **Test Ballot** in the top-left of the ballot.

Test ballots will not be tabulated by default and are only read by the VxScan or VxCentralScan when in `Test` mode.

**Sample Ballot**

A `Sample` ballot should be used for display or demonstration use. Test ballots will not be read by the VxScan.

### Absentee vs. Precinct Ballots

An `Absentee` ballot should be used for absentee voting and a `Precinct` ballot should be used for all voters, including affidavit, curbside, and emergency voters. Absentee and precinct ballots are the same with the exception of a label printed at the start and on every page footer for absentee ballots. With a color printer, the label is printed as white text on purple background. With a black-and-white printer, the label is printed as white text on grey background.

![Absentee Header in Color](../.gitbook/assets/header.png)

## Edit Election Definition

If you find any errors while proofing ballots, you have one of two options.

**If you imported directly from SEMS,** you should make changes directly in SEMS, re-export the SEMS files, and then re-configure VxAdmin with the new SEMS files. It's necessary to make edits in SEMS first so that the two systems match for when you eventually export to SEMS at the end of an election.

**If you imported a VotingWorks-provided definition file,** please reach out to VotingWorks for help editing the election definition.
