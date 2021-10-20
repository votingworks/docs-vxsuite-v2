# Configure VxBatch

## Export Ballot Package

To configure **VxBatch**, you must first export the ballot package from **VxAdmin **to a USB drive. Navigate to the `Ballots` tab in VxAdmin and click `Export Ballot Package`:

![](../.gitbook/assets/export\_bp.jpg)

You will be prompted to insert a USB drive:

![](<../.gitbook/assets/Parallels Picture 14.png>)

Once you insert a USB drive, the screen updates and prompts you to export the ballot package:

![](<../.gitbook/assets/Parallels Picture 15.png>)

Just click `Export` and VxAdmin will generate the ballot package of all ballot styles, saving it automatically on the USB drive:

![](<../.gitbook/assets/Parallels Picture 16.png>)

You don't need to worry about the exact file location, but if do want to look for it later, the file will be saved inside the `ballot-packages` directory.

Once the file is saved, VxAdmin lets you know and prompts you to eject the USB drive:

![](<../.gitbook/assets/Parallels Picture 17.png>)

After a few seconds, you can pull out the USB drive.

## Load Ballot Package

Once you have the ballot package saved on a USB drive, you can transfer the file to **VxBatch**.

When turned on, the VxBatch laptop will boot to a **Load Election Configuration** screen, prompting you to insert a USB drive:

![](<../.gitbook/assets/Parallels Picture 18.png>)

Insert the USB drive on which you just saved the ballot package from VxAdmin. After a few seconds, VxBatch displays all the ballot packages it finds on that USB drive:

![](<../.gitbook/assets/Parallels Picture 19.png>)

Select the ballot package you want. As the package loads, the screen will read `Uploading ballot package # of #` and VxBatch will iterate through the total number of ballot styles in the ballot package:

![](<../.gitbook/assets/Parallels Picture 20.png>)

When loading is complete, VxBatch prompts you to eject the USB drive:

![](<../.gitbook/assets/Parallels Picture 21.png>)

Then, the main VxBatch screen is shown. The screen will state that `No ballots have been scanned.` Election summary information (name, date, county, etc.) will be shown at the bottom of the screen.

![Configured VxBatch](<../.gitbook/assets/Screenshot from 2020-09-09 14-40-48.png>)

You may now click `Eject USB` and remove the USB drive once `Mount USB` is presented.

VxBatch is now ready for scanning! To learn how to scan ballots with VxBatch, please reference our central scanning guide:

{% content-ref url="../election-ops/scanning-ballots.md" %}
[scanning-ballots.md](../election-ops/scanning-ballots.md)
{% endcontent-ref %}

## Change Ballot Packages

If you later need to change a ballot package, you can remove the package and reset VxBatch through the following steps:

1. Click `Advanced` from the main scanner screen
2. Click `Factory Reset` under Advanced Options
3. Confirm by clicking `Yes, Factory Reset`

![Factory Reset](../.gitbook/assets/factoryreset.png)

You can now re-configure VxBatch with a different ballot package.

