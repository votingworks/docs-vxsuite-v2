# Configure VxScan

Before you configure VxScan, you must setup the machine. Follow the steps in the [Poll Worker VxScan Setup Guide](../poll-worker-guides/setting-up-and-opening-polls/vxscan-setup.md).

To configure **VxScan**, you must do two things:

1. [Save the ballot package](../central-system-setup/save-ballot-package.md) to a USB drive.
2. [Create an Election Manager Card](../hardware-setup/programming-cards.md).

## Loading The Ballot Package

An unconfigured machine will prompt you to insert a USB drive with the election's ballot package.

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

After you insert the USB drive, VxScan will automatically begin loading all ballot styles for the election.

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

If the USB drive contains multiple ballot packages, VxScan will use the most recent.

After the ballot package is done loading, the Polls Closed screen will display in Testing Mode.

![VxScan in Testing Mode](<../.gitbook/assets/image (230).png>)

## **Setting Precinct**

Once configured, VxScan will be setup for All Precincts**,** which means that it will accept and tabulate ballots from all precincts. If you are using VxScan to service a vote center or otherwise have more than one precinct's voters casting ballots at a single location, then you may want to leave VxScan set to All Precincts**.**&#x20;

In most cases, you will set VxScan to only accept ballots for one precinct. In order to do so, you will need the Election Manager Card configured for the current election. To select the precinct, insert the Election Manager Card into the card reader and select the precinct dropdown to open a list of all precincts.

![Select All Precincts](<../.gitbook/assets/image (221).png>)

Select a precinct in the dropdown list.

![](<../.gitbook/assets/image (129).png>)

Your chosen precinct will appear on the precinct button and in the lower left-hand corner of the screen.

![](<../.gitbook/assets/image (223).png>)

## Setting Mode

Use the toggle button to switch between _`Testing Mode`_ and _`Live Election Mode`_. You will want to put the machine in Testing Mode before Logic and Accuracy Testing and return it to Live Election Mode after Logic and Accuracy Testing and before Election Day.&#x20;

![](<../.gitbook/assets/image (179).png>)

## Calibrating the Scanner

Before each election you must calibrate the VxScan's sensors to ensure the scanner accurately identifies marks. It may be easiest to incorporate calibration into Logic and Accuracy Testing. Calibration requires a sheet of blank paper of the same type as your ballots.

Select _`Calibrate Scanner`_ on the admin screen to start the calibration process.

![Select Calibrate Scanner](<../.gitbook/assets/image (168).png>)

VxScan will prompt you to insert a blank piece of paper. Insert a piece of blank paper. The scanner will grip the paper and an option to Calibrate will appear. Select _`Calibrate`_ and VxScan will slowly process the piece of paper.

<div>

<figure><img src="../.gitbook/assets/Calibrate Insert Paper (1).png" alt=""><figcaption><p>Insert blank sheet</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/Calibrate Ready (1).png" alt=""><figcaption><p>Select Calibrate</p></figcaption></figure>

</div>

![](<../.gitbook/assets/Calibration In Progress.png>) ![](<../.gitbook/assets/Calibration Succeeded.png>)

After calibration is complete, retrieve the blank piece of paper from inside the ballot bag. If you are calibrating during Logic and Accuracy Testing, you may choose to leave the paper in until you retrieve all testing materials and confirm the ballot bag is empty at the end of testing.

## Remove Election

To remove a ballot package and reset VxScan:

1. Insert an Election Manager Card
2. Select Delete _`All Election Data from VxScan`_.

![Select Delete All Election Data from VxScan](<../.gitbook/assets/image (234).png>)

Confirm your selection by selecting _`Yes, Delete All.`_

![Select Yes, Delete All](<../.gitbook/assets/image (160).png>)

You can now re-configure VxScan with a different ballot package.
