<!--
created_at: 2016-12-15
authors:         
    - "Catherine Pease"
--> 

# Test Settings

>After [creating a new Test](../tests/creating-a-new-test.md), it will be necessary in most cases to set various properties for the assessment and its individual parts. There are four levels in which properties may be assigned: the *Test* level, the *Test part* level, the *Section* level, and the *Item* level. These properties will appear in the Properties panel on the right when you click on the appropriate properties icon (depicted as three interacting gears). 

>The *Test* level properties icon can be found in the Test bar at the top of the canvas. *Test part* level properties icons can be found in each grey *Test part* bar, while *section* level properties icons will be found on the same line as the section label. *Item* level properties icons will be found next to the item's label.

**1.** Click on the *Test* level properties icon.

This brings up two panels on the right: one governing Identifier and Title, and the other governing Time Limits. The *Identifier* box should, in general, be left as it is, though it is editable. However, the Test *Title* can be renamed to make it easier for the Test-Taker to identify.

You can set a time limit for Tests at either the Item level, or the Test level. To limit the amount of time that the test-taker has to complete the Test, open the *Time Limits* panel, and enter the maximum duration (in hours, minutes, and seconds). If late submissions are to be accepted, check the *Late submission allowed* box. If the duration is to be strictly enforced (i.e. no late submissions are allowed), leave this unchecked.

**2.** Click on the *Test part* level properties icon.

This brings up three panels on the right: a general properties panel, an *Item Session Control* panel, and a *Time Limits* panel. In the general properties panel, the *Identifier* box should be renamed as appropriate. The *Navigation* box, or how the test-taker is allowed to answer questions, should be selected as either linear (first question first, second question second, etc.) or non-linear (can be answered in any order). Lastly, the *Submission* mode needs to be selected as either individual (submitted response by response) or simultaneous (submitted on completion of the *test part*).

In the Item Session Control panel, set these four properties: *Max Attempts* is the number of attempts the test-taker may have (the default setting 0 permits an unlimited number of attempts). Check the *Show Feedback* box if the test-taker should see the modal feedback after completing the Test Part. Check the *Allow Comment* box if the test-taker may provide explanations for responses, or leave feedback for the test. Check the *Allow Skipping* box to allow the test-taker to pass on answering questions within the test part.

The time limits section is similar in nature to the time limits section for the test level properties, except that the answers apply to the test part.

**3.** Click on the *Section* level properties icon.

This brings up five panels on the right: general properties, *Selection* properties, *Ordering*, *Item Session Control*, and *Time Limits*. The last two panels are the same as the last two in the test part properties, while the first three panels differ from previous levels. The general properties include an identifier and title: the default name in the *Identifier* box should generally be maintained, while the *Title* can be changed to suit the Test. In general, the *Visible* box should be checked (or else the test-taker is unable to see the section), and the *Keep Together* box should also be checked if it is important that the entire section be completed before moving onto the next section. *Categories* act as tag references, which may be displayed to the Test-taker.

The *Selection* panel asks if the delivered test section should include only some of the Items assigned it (*Enable selection*), and if so, how many (*Select*). If *With Replacement* is checked while the selection mode is enabled, then questions may be repeated. Normally, they are only allowed to be used once in a Test sitting.

*Ordering* contains only one property setting, which is *Shuffle*. This setting randomizes the question order.

**4.** Click on the *Item* level properties icon.

This brings up three panels: general properties, *Item Session Control*, and *Time Limits*. The last two panels are the same as the last two in both the test part and section level properties. The general properties include entries for: *Identifier*, *Reference*, and *Categories*. It also includes check boxes to indicate the item is *Required* and if it is *Fixed*.

The *Identifier* and *References* boxes generally do not require modification. *Categories* act as tag references which may be displayed to the test-taker. If the *Required* box is checked, the Item will appear on the Test, even if less than the total number of Items appears on a given Test (in a section where selection is enabled). If the *Fixed* box is checked, the Item will appear in a particular order, even if the section ordering calls for shuffling.
