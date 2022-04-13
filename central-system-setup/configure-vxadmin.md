# Configure VxAdmin

For each election, you will configure VxAdmin by loading your election definition file. VxAdmin is compatible with multiple types of election definition files including Mississippi’s State Election Management System (SEMS) format.&#x20;

## Download SEMS Files

Before creating an election, you'll need to download two files from SEMS:

1. On the SEMS home page, select _`Election Management`_ under **Elections**
2. In the **Election Management** view, select _`Ballot Styles`_ on the left-hand navigation
3. In the **Ballot Styles** view, select _`Ballot Styles`_ in the top toolbar, then select _`Export`_ and then _`Election Details`_.&#x20;
4. In the **Export Election Details** file dialog, select _`Browse`_ and point to the USB drive to save the file. Select _`Export`_ to save the file to the `V:` drive. The main SEMS file should be named COUNTYID\_DATE.txt and the candidate mapping SEMS file should be named COUNTYID\_CANDMAP\_DATE.txt.&#x20;

## Load Election Files

When VxAdmin is not configured, the screen will display **Configure VxAdmin**.

![](<../.gitbook/assets/image (184) (1) (1).png>)

SEMS files can be loaded to define an election in a self-service fashion. Due to frequent irregularities in SEMS data, however, many customers prefer that VotingWorks check and convert their SEMS files into a VotingWorks election definition file.

### Option 1: From SEMS Files

You must have the two election details files exported from SEMS saved to a USB drive. Insert the USB drive into the VxAdmin laptop's USB hub. In the top-right of the screen, the text should change from _`No USB`_ to _`Eject USB`_ .

Select _`Convert from SEMS files`_ to open the SEMS file conversion page.

![](<../.gitbook/assets/image (200) (1).png>)

Next, select _`SEMS main file.`_

![](<../.gitbook/assets/image (152).png>)

&#x20;Then select the main SEMS file which should be named COUNTYID\_DATE.txt. Select _`Open`_.&#x20;

![](<../.gitbook/assets/image (119).png>)

_`✓ Loaded SEMS main file`_ will display when loaded.

![](<../.gitbook/assets/image (90).png>)

Once complete, the Ballots tab will show the list of all ballots.

### Option 2: From VotingWorks Election Definition File

Save the election definition file provided by VotingWorks to a USB drive. Insert the USB drive into the VxAdmin laptop's USB hub. In the top-right of the screen, the text should change from _`No USB`_ to _`Eject USB`_.

Select _`Select Existing Election Definition File.`_

![](<../.gitbook/assets/image (141).png>)

Select the file from the USB drive and select _`Open.`_

![](<../.gitbook/assets/image (98).png>)

Once complete, the Ballots tab will show the list of all ballots.

## Remove Election

If you need to change an election definition or reset VxScan for the next election, you must remove the election definition.

Select the Definition tab and scroll to the bottom. Select the red _`Remove Election`_ button.

![](<../.gitbook/assets/image (101) (1).png>)

After confirming that you want to remove the election definition and results data, you will return to the initial VxAdmin configuration screen. From there you can re-configure VxAdmin and load a new election definition file by repeating the steps above.
