# Precinct (VxScan + VxMark) Checklist

This Precinct Checklist is appropriate for any precinct using both VxMark as an accessible ballot-marking device and VxScan as a precinct scanner. The equipment is best tested together, as they need matching configurations and will be used together at the precinct. At the point of Logic and Accuracy testing, both [VxScan](../../../hardware-setup/configure-vxscan.md) and [VxMark](../../../hardware-setup/configuring-and-operating-vxmark.md) should already be configured appropriately.

### **Gather Precinct Materials**

* [ ] Admin Card
* [ ] Poll Worker Card(s)
* [ ] Labelled USB Drive
* [ ] Blank White Piece of Paper - same thickness as ballots
* [ ] Precinct-Specific Test Ballots
  * [ ] VxAdmin Test Deck
  * [ ] Blank Ballot
  * [ ] Overvoted Ballot
  * [ ] Test Ballot Deck Tally

### **Set Up Equipment**

* [ ] Set Up VxMark according to the [VxMark Setup Poll Worker Guide](../../../poll-worker-guides/setting-up-and-opening-polls/vxmark.md)
* [ ] Set Up VxScan according to the [VxScan Setup Poll Worker Guide](../../../poll-worker-guides/setting-up-and-opening-polls/vxscan-setup.md)
* [ ] Insert USB Drive into VxScan
  * [ ] Remove Ballot Bag
  * [ ] Open Enclosure
  * [ ] Insert USB Drive
  * [ ] Close Enclosure
  * [ ] Insert Ballot Bag ****&#x20;

### **Using Equipment**

#### **Part 1: VxScan - Opening**

* [ ] Confirm Election, Election ID, Date, Time, and Precinct (Admin Card)
* [ ] Calibrate Scanner with the blank paper (Admin Card)
* [ ] Confirm VxScan is in "Testing Mode" (Admin Card)
* [ ] Open Polls (Poll Worker Card)

#### Part 2: VxMark - Opening and Marking Ballots

* [ ] Confirm Election, Election ID, Date, Time, and Precinct (Admin Card)
* [ ] Confirm Printer has plenty of paper
* [ ] Confirm VxMark is in "Testing Mode" (Admin Card)
* [ ] Print Zero Report from VxScan (Poll Worker Card)
* [ ] Confirm Zero Report is all Zeros
* [ ] Open Polls on VxMark (Poll Worker Card)
* [ ] Confirm all expected ballot styles show up as options at top of screen
* [ ] Confirm all Poll Worker Cards work
* [ ] Run the [Ballot Style Sub-Checklist](per-ballot-style-per-vxmark-checklist.md) for _each_ ballot style
* [ ] For one of the ballot styles selected at random, confirm that the entire ballot can be filled out and printed using only the audio track over headphones and the accessible controller
* [ ] Print a Test Deck for the Current Precinct (Admin Card)

#### Part 3: VxScan - Casting Votes and Closing

* [ ] Scan Each Ballot in VxMark (machine-marked) Test Deck
  * [ ] Do not scan your own test votes from VxMark&#x20;
* [ ] Scan Each Ballot in VxAdmin (hand-marked) Test Deck
* [ ] Scan Blank Ballot
  * [ ] Confirm it is rejected & select tabulate ballot
* [ ] Scan Overvoted Ballot
  * [ ] Confirm it is rejected & select tabulate ballot
* [ ] Close Polls (Poll Worker Card)
* [ ] Save Results to USB (Poll Worker Card)
* [ ] Switch to "Live Election Mode" (Admin Card)

#### Part 4: VxMark - Closing

* [ ] Print Polls Closed Report (Poll Worker Card)
* [ ] Confirm Polls Closed Report matches Test Deck Tally
* [ ] Close Polls on VxMark (Admin Card)
* [ ] Put the VxMark in "Live Election Mode" (Admin Card)

#### Part 5: VxScan - Removing Results

* [ ] Remove ballot bag
* [ ] Remove ballots from ballot bag
* [ ] Set aside blank piece of paper - you **will not** need this later
* [ ] Set aside test deck ballots - you **will** need this later
* [ ] Open Metal Enclosure
* [ ] Remove USB Drive and set aside

{% hint style="danger" %}
**Pause here until you validate results from the USB Drives at VxAdmin.**
{% endhint %}

### **Pack Up and Seal Equipment**

* [ ] Insert USB Drive into VxScan
* [ ] Close Metal Enclosure
* [ ] Close Ballot Bag Main Opening&#x20;
* [ ] Seal Ballot Bag Main Opening
* [ ] Place Ballot Bag into VxScan
* [ ] Seal Ballot Bag in place
  * [ ] Flap Side 1
  * [ ] Flap Side 2
* [ ] Pack Up VxScan according to [Poll Worker Instructions](../../../poll-worker-guides/closing-polls-and-packing-up/handling-results-and-packing-up-vxscan.md#cleaning-up)
* [ ] Seal Ballot Entry Flap
* [ ] Seal Top Lid
* [ ] Pack Up VxMark according to [Poll Worker Instructions](../../../poll-worker-guides/closing-polls-and-packing-up/packing-up-vxmark.md)
* [ ] Seal VxMark

### **Seal Tracking**

| Seal Location           | Seal Color | Number |
| ----------------------- | ---------- | ------ |
| Ballot Box Main Opening | Red        |        |
| Ballot Box Flap 1       | Yellow     |        |
| Ballot Box Flap 2       | Yellow     |        |
| VxScan                  | Green      |        |
| VxMark                  | Green      |        |
