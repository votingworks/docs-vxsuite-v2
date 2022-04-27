# Smart Cards

## Overview

Smart cards are used to configure and operate equipment. It's the same technology as the chip in your credit card, but instead used to enable administrators and poll workers to configure and operate the equipment. There are two types of cards: Admin Cards and Poll Worker Cards**.**

![Admin and Poll Worker Cards](<../.gitbook/assets/image (157).png>)

### Admin Cards

Admin Cards allow election administrators to unlock VxAdmin and VxCentral Scan as well as configure precinct equipment including:

* Configuring the equipment for a specific precinct
* Configuring VxMarks with the list of contests and candidates
* Toggling between Test mode and Live Election mode for L\&A
* Updating settings like date and time

Because Admin Cards allow access to VxAdmin and VxCentralScan as well as configure and unconfigure precinct equipment, they should only be used by election administrators and should be kept in a secure location.

### Poll Worker Cards

Poll Worker Cards allow poll workers to manage election day precinct tasks, including:

* Opening the polls
* Activating voter sessions on VxMark
* Closing the polls
* Printing reports

Every precinct will need at least one Poll Worker Card in order to operate the polls.

## Managing Cards

For each election, you will encode the smart cards specifically for that election. Smart cards can be encoded quickly and easily with VxAdmin, in the Cards tab.

![Cards tab](<../.gitbook/assets/image (130).png>)

You will use the HID Omnikey Card Reader provided with VxAdmin.&#x20;

### Encoding Admin Cards

Insert a smart card labelled Admin Card into the card reader. Push the card into the slot, stopping when you feel it tap the bottom of the card reader. In the Cards tab in VxAdmin, select _`Encode Admin Card.`_

![Insert Admin Card in reader](<../.gitbook/assets/admin card in card reader (1).png>) ![Select Encode Admin Card](<../.gitbook/assets/encode admin card.png>)

Create a Security Code for the card and click _`Create Card`_. Programming an Admin Card will take several seconds during which the lights on the card reader will flash and the screen will show Programming card...

![Create security code](<../.gitbook/assets/create card.png>) ![Wait for programming to complete](<../.gitbook/assets/programming card.png>)

After the message is gone, the card is programmed.

### Encoding Poll Worker Cards

Insert the smart card labelled Poll Worker into the card reader. Push the card into the slot, stopping when you feel it tap the bottom of the card reader. In the Cards tab in VxAdmin, select _Encode Poll Worker Card._

![Insert Poll Worker Card in reader](<../.gitbook/assets/poll worker card in reader.png>) ![Select Encode Poll Worker Card](<../.gitbook/assets/encode poll worker card.png>)

VxAdmin will show that it is Programming card... briefly. The light on the card reader will blink green and red. For a Poll Worker card, this process will take a second or less.

![](<../.gitbook/assets/image (203) (1).png>)

After the message is gone, the card is programmed.

##
