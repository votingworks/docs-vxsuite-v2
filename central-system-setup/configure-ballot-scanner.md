# Configure VxCentralScan

## Export Ballot Package

To configure VxCentralScan, you must first [export the ballot package](export-ballot-package.md) from VxAdmin **** to a USB drive.&#x20;

## Load Ballot Package

Once you have the ballot package saved to a USB drive, you can load the file to VxCentralScan.

When turned on and authenticated, the VxCentralScan laptop will display the Load Election Configuration screen, prompting you to insert a USB drive.

![](<../.gitbook/assets/Parallels Picture 18.png>)

Insert the USB drive with the ballot package saved from VxAdmin. After a few seconds, VxCentralScan will display all ballot packages found on the USB drive. _`Select`_the correct ballot package.&#x20;

![](<../.gitbook/assets/image (167).png>)

As the package loads, the screen will read Uploading ballot package # of # and VxCentralScan will load each ballot style in the ballot package.

![](<../.gitbook/assets/image (214) (1).png>)

When loading is complete, VxCentralScan prompts you to eject the USB drive. Select _`Eject USB`_ and remove the USB drive.

![](<../.gitbook/assets/image (112).png>)

VxCentralScan is now configured and in Test Mode. The screen will show No ballots have been scanned and election summary information (name, date, county, etc.) will be shown at the bottom of the screen.&#x20;

![](<../.gitbook/assets/image (177).png>)

VxCentralScan is now ready for scanning. To learn how to scan ballots with VxCentralScan, please reference our central scanning guide.

{% content-ref url="../election-ops/scanning-ballots.md" %}
[scanning-ballots.md](../election-ops/scanning-ballots.md)
{% endcontent-ref %}

## Remove Election

To remove a ballot package and reset VxCentralScan:

1. Select _`Admin`_ from the main scanner screen
2. Select _`Delete Election Data from VxCentralScan.`_

![](<../.gitbook/assets/image (140).png>)

Confirm by selecting _`Yes, Delete Election Data`_.

![](<../.gitbook/assets/image (86).png>)

And one more time, by selecting_`I am sure. Delete all election data.`_

![](<../.gitbook/assets/image (121).png>)

You can now re-configure VxCentralScan with a different ballot package.

