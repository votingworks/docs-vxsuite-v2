# Precinct (VxScan + VxMark) Checklist

This Precinct Checklist is appropriate for any precinct using both VxMark as an accessible ballot-marking device and VxScan as a precinct scanner. The equipment is best tested together, as they need matching configurations and will be used together at the precinct. At the point of Logic and Accuracy testing, both [VxScan](../../../hardware-setup/configure-vxscan.md) and [VxMark](../../../hardware-setup/configuring-and-operating-vxmark.md) should already be configured.

| Name: | Date: |
| ----- | ----- |

### **Gather Precinct Materials**

* [ ] Admin Card
* [ ] Poll Worker Card(s)
* [ ] Labelled USB drive
* [ ] Blank white piece of paper - same thickness as ballots
* [ ] [Ballot Style Checklist](per-ballot-style-per-vxmark-checklist.md) for each ballot style
* [ ] Precinct-specific test ballots
  * [ ] VxAdmin Test Deck
  * [ ] Blank ballot
  * [ ] Overvoted ballot
  * [ ] Test Ballot Deck Tally

### **Set Up Equipment**

* [ ] Set Up VxMark according to the [VxMark Setup Poll Worker Guide](../../../poll-worker-guides/setting-up-and-opening-polls/vxmark.md)
* [ ] Set Up VxScan according to the [VxScan Setup Poll Worker Guide](../../../poll-worker-guides/setting-up-and-opening-polls/vxscan-setup.md)
* [ ] Insert USB drive into VxScan
  * [ ] Remove ballot bag
  * [ ] Open enclosure
  * [ ] Insert USB drive
  * [ ] Close enclosure
  * [ ] Insert ballot bag ****&#x20;

### **Using Equipment**

#### **Part 1: VxScan - Opening**

* [ ] Confirm Election, Election ID, Date, Time, and Precinct (Admin Card)
* [ ] Calibrate scanner with the blank paper (Admin Card)
* [ ] Confirm VxScan is in Testing Mode (Admin Card)
* [ ] Open polls (Poll Worker Card)

#### Part 2: VxMark - Opening and Marking Ballots

* [ ] Confirm Election, Election ID, Date, Time, and Precinct (Admin Card)
* [ ] Confirm printer has plenty of paper
* [ ] Confirm VxMark is in Testing Mode (Admin Card)
* [ ] Print Tally Report from VxScan to serve as the Zero Report (Poll Worker Card)
* [ ] Confirm Zero Report is all zeros
* [ ] Open polls on VxMark (Poll Worker Card)
* [ ] Confirm all expected ballot styles show up as options at top of screen
* [ ] Confirm all Poll Worker Cards work
* [ ] Run the [Ballot Style Sub-Checklist](per-ballot-style-per-vxmark-checklist.md) for _each_ ballot style
* [ ] For one of the ballot styles selected at random, confirm that the entire ballot can be filled out and printed using only the audio track over headphones and the accessible controller (do not scan this ballot)
* [ ] Print a Test Deck for the current precinct (Admin Card)

#### Part 3: VxScan - Casting Votes and Closing

* [ ] Scan each ballot in VxMark (machine-marked) Test Deck
  * [ ] Do not scan your own test votes from VxMark&#x20;
* [ ] Scan each ballot in VxAdmin (hand-marked) Test Deck
* [ ] Scan blank ballot
  * [ ] Confirm it is rejected & select _`Count Ballot`_
* [ ] Scan overvoted ballot
  * [ ] Confirm it is rejected & select _`Count Ballot`_
* [ ] Close polls (Poll Worker Card)
* [ ] Switch to _`Live Election Mode`_ (Admin Card)

#### Part 4: VxMark - Closing

* [ ] Print Polls Closed Report (Poll Worker Card)
* [ ] Confirm Polls Closed Report matches Test Deck Tally (x2 if scanning VxMark & VxScan ballots)
* [ ] Scan QR code
* [ ] Close polls (Admin Card)
* [ ] Switch to _`Live Election Mode`_(Admin Card)

#### Part 5: VxScan - Removing Results

* [ ] Remove ballot bag
* [ ] Remove ballots from ballot bag
* [ ] Set aside blank piece of paper - you **will not** need this later
* [ ] Set aside test deck ballots - you **will** need this later
* [ ] Open metal enclosure
* [ ] Remove USB drive and set aside

{% hint style="danger" %}
**Validate results from the USB drives at** [**VxAdmin**](../vxadmin-checklist-part-2.md)**.**
{% endhint %}

### **Pack Up and Seal Equipment**

* [ ] Insert USB drive into VxScan
* [ ] Close metal enclosure
* [ ] Close Ballot Bag Main Opening&#x20;
* [ ] Seal Ballot Bag Main Opening
* [ ] Place Ballot Bag into VxScan
* [ ] Seal Ballot Bag in place
  * [ ] Flap side 1
  * [ ] Flap side 2
* [ ] Pack Up VxScan according to [Poll Worker Instructions](../../../poll-worker-guides/closing-polls-and-packing-up/handling-results-and-packing-up-vxscan.md#cleaning-up)
* [ ] Zip ballot entry flap and top
* [ ] Seal ballot entry flap and top together
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
