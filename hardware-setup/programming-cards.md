# Smart Cards

## Overview

VotingWorks uses smart cards to configure and operate precinct equipment. It's the same technology as the chip in your credit card, but instead used to enable administrators and poll workers to configure the equipment and operate the polls. There are two types of cards: **Admin Cards** and **Poll Worker Cards**:

![Admin and Poll Worker Cards](../.gitbook/assets/smartcards.jpg)

### Admin Cards

Admin Cards enable election administrators to configure precinct equipment including:

* Configuring the equipment for a specific precinct
* Configuring VxMarks with the list of contests and candidates
* Toggling between `Test` mode and `Live Election` mode for L\&A
* Updating settings like date and time

Because Admin Cards allow you to configure and unconfigure a machine for an election, they are only used by election administrators and should be kept in a secure location.

### Poll Worker Cards

Poll Worker Cards enable poll workers to manage election day precinct tasks, including:

* Opening the polls
* Printing reports
* Closing the polls
* Exporting precinct results

Every precinct will need at least one Poll Worker Card in order to operate the polls.

## Managing Cards

For each election, you will encode the smart cards specifically for that election. Smart cards can be encoded quickly and easily with VxAdmin, under the `Cards` tab:

![](<../.gitbook/assets/image (208).png>)

You will use the HID Omnikey Card Reader provided with VxAdmin.&#x20;

### Encoding Admin Cards

Insert a smart card labelled "Admin" into the card reader facing toward you. Push the card all the way into the slot, stopping when you feel it tap the bottom of the card reader:

![Admin Smart Card in Smart Card Reader](../.gitbook/assets/IMG\_4477.jpeg)

{% hint style="warning" %}
Admin Cards are write-protected to prevent accidentally overwriting the correct election data. When reusing a previously programmed Admin Card, you must first `Override Write Protection` on the card.
{% endhint %}

Under the `Card` tab in VxAdmin, select `Encode Admin Card`:

![](<../.gitbook/assets/image (130).png>)

Create a Security Code for the card and click Create Card.

![](<../.gitbook/assets/image (118).png>)

Programming an Admin Card will take several seconds during which the lights on the card reader will flash and the screen will show the following:

![](<../.gitbook/assets/Screenshot from 2021-06-28 16-07-45.png>)

After the message is gone, the card is programmed.

### Encoding Poll Worker Cards

Insert the smart card labelled "Poll Worker" into the card reader facing toward you. Push the card all the way into the slot, stopping when you feel it tap the bottom of the card reader:

![Poll Worker Smart Card in Smart Card Reader](../.gitbook/assets/IMG\_4478.jpeg)

Under the Card Tab in VxAdmin, select `Encode Poll Worker Card`:

![](<../.gitbook/assets/image (198).png>)

VxAdmin will show that it is "Programming Card..." briefly. The light on the card reader will blink green and red. For a Poll Worker Card, this process will take less a second or less:

![](<../.gitbook/assets/Screenshot from 2021-06-28 16-07-45.png>)

After the message is gone, the card is programmed.

##
