---
description: Open-source software, commercial off-the-shelf hardware, and paper ballots.
---

# VotingWorks

This guide walks you through the complete process to set up, test, and operate on election day.

If you have any questions, please don't hesitate to reach out to the VotingWorks team by emailing [help@vx.support](mailto:help@vx.support) or calling **(510) 426-9991**.

## System Overview

VotingWorks consists of two subsystems:

1. **Central System:** all the equipment necessary for use at election central for on-demand ballot printing, election programming, central batch ballot scanning, and results tabulation.
2. **Precinct System:** all equipment necessary for use at the precinct to scan hand-marked ballots and provide an accessible ballot marking device for voters unable to hand mark paper ballots.

### Central System

VotingWorks Central System includes two products:

1. **VxAdmin**: the main tool for local election administrators, which programs elections, prints ballots, and tabulates results on election night.
2. **VxCentralScan**: a central scanner used for rapidly scanning absentee ballots on election night.

![Central System: VxCentralScan (left) and VxAdmin (right)](<.gitbook/assets/image (178).png>)

### Precinct System

VotingWorks Precinct System consists of two portable self-contained products:

1. **VxMark**: an accessible ballot marking device and attached printer that produces a voter-verifiable paper ballot.
2. **VxScan**: a voter-facing precinct scanner that scans paper ballots and notifies voters of ballot issues for second-chance voting.

Voters at the precinct vote on hand-marked paper ballots with the ability to vote on a VxMark if requested. After marking ballots, all voters scan their ballots using VxScan.\


![Open Precinct System: VxMark BMD (left), VxMark printer (middle), VxScan (right) ](.gitbook/assets/precinct\_open.jpg)

![Closed Precinct System: VxMark BMD (left), VxMark printer (middle), VxScan (right)](.gitbook/assets/precinct\_closed.jpg)

## Paper Ballots

All votes cast using VotingWorks are on paper ballots for security and post-election auditing.&#x20;

There are two types of VotingWorks paper ballots:

* **Hand-marked paper ballot**
  * All absentee voters will receive a hand-marked paper ballot that is printed on-demand. Absentee ballots are scanned by election administrators using a high-speed central scanner (VxCentralScan).
  * Most in-precinct voters will receive a hand-marked paper ballot that is printed in-bulk or on-demand. Precinct ballots are scanned by voters using a precinct scanner (VxScan).&#x20;
* **Machine-marked paper ballot** (via ballot marking device)
  * In-precinct voters may request to use the accessible ballot marking device (VxMark), which prints a voter verifiable paper ballot. Machine-marked precinct ballots are scanned by voters using the same precinct scanner (VxScan).

![Sample Hand-Marked Paper Ballot](.gitbook/assets/sampleballot.png)
