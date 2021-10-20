# Configure Ballot Styles

For each election, you will configure your ballots by loading VxAdmin with your election definition. VxAdmin is compatible with multiple types of election definition files including Mississippi’s State Election Management System (SEMS) format.&#x20;

## Download SEMS Files

Before creating ballots, you'll need to download two files from SEMS:

1. On the SEMS home page, click `Election Management` under **Elections**
2. In the **Election Management **view, click `Ballot Styles` on the left-hand navigation
3. In the **Ballot Styles** view, click `Ballot Styles` in the top toolbar, then click `Export` and then `Election Details`.&#x20;
4. In the **Export Election Details **file dialog, click `Browse` and point to the USB drive to save the file. Click `Export` to save the file to the `V:` drive. The main SEMS file should be named `COUNTYID_DATE.txt` and the candidate mapping SEMS file should be named `COUNTYID_CANDMAP_DATE.txt`.&#x20;

## Load Election Files

When VxAdmin has not yet been configured, you'll be presented a screen prompting you to **Configure Election Manager**.

![Configure Election Manager](<../.gitbook/assets/Screenshot from 2020-09-09 14-34-01.png>)

SEMS files can be loaded directly in order to define an election in a self-service fashion. Due to frequent irregularities in SEMS data, however, many customers prefer that VotingWorks check and convert their SEMS files into a VotingWorks election definition file.

### Option 1: From SEMS Files

You must have the two election details files exported from SEMS saved to a USB drive. Insert the USB drive into the VxAdmin laptop's USB port. In the top-right of the screen, the text should change from `No USB` to `Eject USB` .

Click the `Convert from SEMS files` button to open the SEMS file conversion page:

![](../.gitbook/assets/sems\_choice.jpg)

From this view, click `SEMS main file` and select the main SEMS file which should be named `COUNTYID_DATE.txt`. Click `Open`.&#x20;

![](<../.gitbook/assets/Screenshot from 2020-09-09 14-34-32.png>)

You should see `✓ Loaded SEMS main file` when loaded:

![](<../.gitbook/assets/Screenshot from 2020-09-09 14-34-36.png>)

Click `SEMS candidate mapping file` and select the candidate mapping SEMS file which should be named `COUNTYID_CANDMAP_DATE.txt`. Click `Open`.

![](<../.gitbook/assets/Screenshot from 2020-09-09 14-34-53.png>)

VxAdmin will then create all ballots for the election. Once complete, you will see the `Ballots` tab showing the list of all ballots:

![](<../.gitbook/assets/Screenshot from 2021-06-28 12-23-30.png>)

### Option 2: From VotingWorks Election Definition File

Take the election definition file provided by VotingWorks and put it onto a USB Drive. Insert the USB drive into the VxAdmin laptop's USB port. In the top-right of the screen, the text should change from `No USB` to `Eject USB`.

Click `Select Existing Election Definition File` :

![](../.gitbook/assets/vx\_choice.jpg)

Select the file you loaded onto the USB drive and click `Open`:

![](<../.gitbook/assets/Screenshot from 2021-06-28 11-02-37.png>)

VxAdmin will then create all ballots for the election. Once complete, you will see the `Ballots` tab showing the list of all ballots:

![](<../.gitbook/assets/Screenshot from 2021-06-28 12-23-30 (1).png>)

## Changing Election Definitions

If you need to change an election definition, you can remove the current election definition and re-configure with the new one.&#x20;

Click the `Definition` tab and scroll to the bottom. Click the red `Remove Election` button:

![](../.gitbook/assets/remove\_election.jpg)

After confirming that you want to remove the election definition and results data, you will land back on the initial VxAdmin configuration screen. From there you can re-configure VxAdmin and create ballots from a different election file by repeating the steps above.
