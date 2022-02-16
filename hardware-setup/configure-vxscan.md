# Configure VxScan

Before you can configure VxScan, you will have to setup the machine. You may follow the steps in the Poll Worker VxScan Setup Guide:

{% content-ref url="../poll-worker-guides/setting-up-and-opening-polls/vxscan-setup.md" %}
[vxscan-setup.md](../poll-worker-guides/setting-up-and-opening-polls/vxscan-setup.md)
{% endcontent-ref %}

To configure **VxCentralScan**, you must do two things:

1. [Export the ballot package](../central-system-setup/export-ballot-package.md) to a USB Flash Drive.
2. [Encode an Admin Card](programming-cards.md#encoding-admin-cards).

## Loading The Ballot Package

An unconfigured machine will prompt you to insert a USB drive with the election's ballot package:

![](<../.gitbook/assets/image (103).png>)

After you insert the USB drive, VxScan will begin loading all ballot styles for the election:

![](<../.gitbook/assets/image (120).png>)

If the USB drive contains multiple ballot packages, VxScan will use the most recent.

After the ballot package is done loading, you will land on the **Polls Closed** screen in **Live Election Mode:**

![](<../.gitbook/assets/image (191).png>)

## **Setting Precinct**

After configuring, VxScan will be setup for **All Precincts,** which means that it will accept and tabulate ballots from all precincts. If you are using VxScan to service a vote center or otherwise have more than one precinct's voters casting ballots at a single location, then you may want to leave VxScan set to **All Precincts.**&#x20;

In most cases, you will set VxScan to only accept ballots for one precinct. In order to do so, you will need the Admin Card configured for the current election. Insert the Admin Card into the card reader on the back of the VxScan's screen, with the front of the Admin Card facing the opposite direction as the screen. VxScan will then display the admin screen. Tap the precinct button to open a list of all precincts:

![](<../.gitbook/assets/image (110).png>)

Select a precinct in the dropdown list:&#x20;

![](<../.gitbook/assets/image (129).png>)

Your chosen precinct will appear on the precinct button and in the lower left-hand corner of the screen:

![](<../.gitbook/assets/image (139).png>)

## Setting Mode

Use the toggle button to switch between **Testing Mode** and **Live Election Mode**. You will want to put the machine in **Testing Mode** before Logic and Accuracy Testing and return it to **Live Election Mode** at the very end of Logic and Accuracy Testing.&#x20;

![](<../.gitbook/assets/image (119).png>)

## Calibrating the Scanner

Before each election you must calibrate the VxScan's sensors to ensure the scanner accurately identifies marks. It may be easiest to incorporate calibration into Logic and Accuracy Testing. Calibration requires a sheet of blank paper of the same type as your ballots.

To begin, tap the `Calibrate Scanner` button on the admin screen:

![](<../.gitbook/assets/image (143).png>)

VxScan will prompt you to insert a blank piece of paper before calibration can start:

![](<../.gitbook/assets/Calibrate Insert Paper.png>)

When you insert a piece of blank paper, the scanner will grip the paper and an option to `Calibrate` will appear. After tapping that option, VxScan will slowly process the piece of paper.

![](<../.gitbook/assets/Calibrate Ready.png>) ![](<../.gitbook/assets/Calibration In Progress.png>) ![](<../.gitbook/assets/Calibration Succeeded.png>)

After calibration is complete, don't forget to retrieve the blank piece of paper from inside the ballot bag! If you are doing calibration during Logic and Accuracy Testing, you may choose to leave the paper in until you retrieve testing ballots and confirm the ballot bag is empty at the end of testing.
