# Process Late Ballots

You may receive properly post-marked absentee ballots for the next five days after election night that need to be counted. To add these ballots to unofficial results, you will need to:

1. Scan late-received ballots on **VxBatch**, preserving the election-night scans
2. Export the CVRs, including both election-night and late-received.
3. Remove the previous CVR file from **VxAdmin**
4. Load the new CVR file into **VxAdmin**
5. Print combined tally report
6. Export combined results
7. Upload combined results to SEMS

VotingWorks recommends scanning and tabulating all late-received ballots at once though you may process late-received ballots multiple times by repeating these steps.

## Scan Late-Received Ballots

When you turn on VxBatch, you should see previous batches you scanned on election night. You can scan new batches for the properly postmarked ballots received after election night, using the normal scanning instructions, including adjudicating ballots that don't scan. See [Central Scanning](../election-ops/scanning-ballots.md).

## Export CVR

After scanning all late-received ballots, you can export the combined CVR file that should contain all ballots, both election-night and late-received. See instructions under [Tally Results](../election-ops/tabulating-results.md), the portion on exporting CVRs.

## Load CVR

At this point, in **VxAdmin**, you will want to remove the old CVR file and load the new CVR file. (If you loaded an external results file from TSX machines, those results can stay put.)

![](<../.gitbook/assets/image (34).png>)

![](<../.gitbook/assets/image (33).png>)

At this point, any external results file should remain, and you can click "Import CVR Files" to import the new CVR file that contains the combined election-night and late-received ballots:

![](<../.gitbook/assets/image (35).png>)

## Export Results

To export results with the new CVR included, follow the same exact process you did on election night, described in [Export Results](../election-ops/export-results.md).
