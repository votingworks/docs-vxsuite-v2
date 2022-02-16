# Configure VxCentralScan

## Export Ballot Package

To configure **VxCentralScan**, you must first [export the ballot package](export-ballot-package.md) from **VxAdmin** to a USB drive.&#x20;

## Load Ballot Package

Once you have the ballot package saved on a USB drive, you can load the file to **VxCentralScan**.

When turned on and authenticated, the VxCentralScan laptop will boot to a **Load Election Configuration** screen, prompting you to insert a USB drive:

![](<../.gitbook/assets/Parallels Picture 18.png>)

Insert the USB drive on which you just saved the ballot package from VxAdmin. After a few seconds, VxCentralScan displays all the ballot packages it finds on that USB drive:

![](<../.gitbook/assets/image (167).png>)

Select the ballot package you want. As the package loads, the screen will read `Uploading ballot package # of #` and VxCentralScan will iterate through the total number of ballot styles in the ballot package.

![](<../.gitbook/assets/image (214).png>)

When loading is complete, VxCentralScan prompts you to eject the USB drive. You may now click `Eject USB` and remove the USB drive.

![](<../.gitbook/assets/image (112).png>)

Then, the main VxCentralScan screen is shown. The screen will state that `No ballots have been scanned.` Election summary information (name, date, county, etc.) will be shown at the bottom of the screen.

![](<../.gitbook/assets/image (124).png>)

VxCentralScan is now ready for scanning! To learn how to scan ballots with VxCentralScan, please reference our central scanning guide:

{% content-ref url="../election-ops/scanning-ballots.md" %}
[scanning-ballots.md](../election-ops/scanning-ballots.md)
{% endcontent-ref %}

## Remove Election

If you later need to remove a ballot package, you can remove the package and reset VxCentralScan through the following steps:

1. Click `Admin` from the main scanner screen
2. Click `Delete Election Data fromVxCentralScan button`.

![](<../.gitbook/assets/image (140).png>)

You can now re-configure VxCentralScan with a different ballot package.

