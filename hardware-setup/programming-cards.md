---
description: Smartcards can only be created by a System Administrator
---

# Smartcards

## Overview

Smartcards are used to configure and operate equipment. It's the same technology as the chip in your credit card, but instead used to enable election administrators and poll workers to configure and operate the equipment. There are three types of cards: System Administrator, Election Manager, and Poll Worker Cards**.**

<figure><img src="../.gitbook/assets/image (89).png" alt=""><figcaption><p>Smartcards</p></figcaption></figure>

### System Administrator Cards

System Administrator Cards allow an election administrator to create/load an election definition, proof sample ballots, create smartcards, and remove the election definition from VxAdmin. This card is also used to perform software updates on all machines.

System Administrator Cards should only need to be used at the very beginning and very end of an election. Keep this card in a secure location when not in use and from election to election.&#x20;

### Election Manager Cards

Election Manager Cards allow election administrators to use central system devices and configure precinct system devices. Election Managers are responsible for:

* printing ballots
* preparing L\&A materials
* centrally scanning ballots
* configuring precinct equipment
* tallying CVRs
* printing and exporting results

Election Manager Cards should only be used by election administrators and should be kept secure at all times.

### Poll Worker Cards

Poll Worker Cards allow poll workers to manage election day precinct tasks, including:

* Opening the polls
* Activating voter sessions on VxMark
* Closing the polls
* Printing precinct tally reports

Every precinct will need at least one Poll Worker Card in order to operate the polls.

## Creating Cards

For each election, you will create Election Manager and Poll Worker Cards specifically for that election. Smartcards can be created quickly and easily with VxAdmin, in the Smartcards tab.

![](<../.gitbook/assets/image (238).png>)

You will use the HID Omnikey Card Reader provided with VxAdmin to program a card. Simply insert the card of your choice and select the correct button for the card.

![Insert card into card reader](<../.gitbook/assets/admin card in card reader.png>) ![Select Election Manager Card or Poll Worker Car](<../.gitbook/assets/vxadmin smartcards create new card EM PW buttons highlighted.png>)

When creating an Election Manager card, the screen will provide you with a unique PIN for that card. Keep the PIN secure. When creating a Poll Worker card, the screen will simply confirm the card is created.

![Election Manager Card confirmation screen with PIN](<../.gitbook/assets/vxadmin smarcards EM confirmation.png>) ![Poll Worker Card confirmation screen](<../.gitbook/assets/VxAdmin smart cards PW conf screen.png>)

To create an additional System Administrator Card or reset the PIN, select _`Create System Administrator Cards`_ from the Election Cards screen. If a PIN already exists, a _`Reset Card PIN`_ button will appear.  If the card is not programmed a PIN will be generated.

<figure><img src="../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>

### Unprogramming Cards

If a card has already been programmed, when you insert the card into the card reader, a prompt to _`Unprogram Card`_ will be displayed. Select the _`Unprogram Card`_ button to clear the card.

![Select Unprogram Card](<../.gitbook/assets/image (217).png>)
