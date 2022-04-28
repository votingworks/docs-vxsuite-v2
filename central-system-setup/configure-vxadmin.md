# Configure VxAdmin

For each election, you will configure VxAdmin by loading your election definition file. VxAdmin is compatible with multiple types of election definition files including Mississippi’s State Election Management System (SEMS) format.&#x20;

## Download SEMS Files

Before creating an election, you'll need to download two files from SEMS (be sure to complete the SEMS Generate Ballot Styles step first):

1. On the SEMS home page, select _`Election Management`_ under **Elections**
2. In the **Election Management** view, select _`Ballot Styles`_ on the left-hand navigation
3. In the **Ballot Styles** view, select _`Ballot Styles`_ in the top toolbar, then select _`Export`_ and then _`Election Details`_.&#x20;
4. In the **Export Election Details** file dialog, select _`Browse`_ and point to the USB drive to save the file. Select _`Export`_ to save the file to the `V:` drive. The main SEMS file should be named COUNTYID\_DATE.txt and the candidate mapping SEMS file should be named COUNTYID\_CANDMAP\_DATE.txt.&#x20;

## Load Election Files

When VxAdmin is not configured, the screen will display **Configure VxAdmin**.

![Configure VxAdmin](<../.gitbook/assets/image (216).png>)

SEMS files can be loaded to define an election in a self-service fashion. Due to frequent irregularities in SEMS data, however, many customers prefer that VotingWorks check and convert their SEMS files into a VotingWorks election definition file.

### Option 1: From SEMS Files

You must have the two election details files exported from SEMS saved to a USB drive. Insert the USB drive into the VxAdmin laptop's USB hub. In the top-right of the screen, the text should change from _`No USB`_ to _`Eject USB`_ .

Select _`Convert from SEMS files`_ to open the SEMS file conversion page. Then select _`SEMS main file.`_

![Convert from SEMS files](<../.gitbook/assets/convert SEMS.png>) ![SEMS main file](<../.gitbook/assets/Sems main file.png>)

&#x20;Next, select the main SEMS file which should be named COUNTYID\_DATE.txt. Select _`Open`_. _`✓ Loaded SEMS main file`_ will display when loaded.

![Select main SEMS file](<../.gitbook/assets/select sems file.png>) ![Loaded SEMS file displayed](<../.gitbook/assets/loaded sems file.png>)

Next, select _`SEMS candidate mapping file`_ to open the SEMS candidate mapping file. Select the SEMS Candidate Mapping file which should be named COUNTYID\_CANDMAP\_DATE.txt. Select _`Open`_.&#x20;

![Select SEMS candidate mapping file](<../.gitbook/assets/sems candidate mapping.png>) ![Select SEMS CANDMAP file](<../.gitbook/assets/candmap file picker.png>)

Once complete, the Ballots tab will show the list of all ballots.

### Option 2: From VotingWorks Election Definition File

Save the election definition file provided by VotingWorks to a USB drive. Insert the USB drive into the VxAdmin laptop's USB hub. In the top-right of the screen, the text should change from _`No USB`_ to _`Eject USB`_.

Select _`Select Existing Election Definition File.`_Select the file from the USB drive and select _`Open.`_

![Select existing election definition file](<../.gitbook/assets/select existing election def.png>) ![Select main SEMS file](<../.gitbook/assets/select sems file (1).png>)

Once complete, the Ballots tab will show the list of all ballots.

## Remove Election

If you need to change an election definition or reset VxScan for the next election, you must remove the election definition.

Select the Definition tab and scroll to the bottom. Select the red _`Remove Election`_ button.

![Remove Election](<../.gitbook/assets/image (141).png>)

After confirming that you want to remove the election definition and results data, you will return to the initial VxAdmin configuration screen. From there you can re-configure VxAdmin and load a new election definition file by repeating the steps above.
