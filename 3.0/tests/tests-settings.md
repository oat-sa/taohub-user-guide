# Tests Settings

>After [creating a new Test](../tests/creating-a-new-test.md), in most cases it will be necessary to set properties for the assessment and its parts. There are four levels in which properties may be assigned: Test level, Test part level, Section level, and Item level. These properties will appear in the Properties panel when the appropriate properties icon (depicted as three interacting gears) is clicked upon. The Test level properties icon will be found within the test bar at the top of the canvas. Test part level properties icons will be found in each darker Test part bar, while section level properties icons will be found on the same line as the section label. Item level properties icons will be found next to the interaction's label.

**Step 1:** Click on the test level properties icon.

This brings up in the Properties panel two sections: one governing identifier and title, and the other governing time limits. The Identifier should, in general, be left alone, though this is editable. However, the Test Title can be renamed to make it easier for the Test-taker to identify it.

Time limits set for the Test can be added at the Item level, or at the Test level. To add a limit to the amount of time that the Test-taker has to submit all answers to the test, open the *Time Limits* panel, and enter in the maximum duration (in hours, minutes, and seconds). If a late submission will be accepted, click on the appropriate check mark. If the duration is to be strictly enforced (no late submissions allowed), leave this unmarked.

**Step 2:** Click on the test part level properties icon.

This brings up in the Properties panel three sections: a general properties portion, an Item session control portion, and a time limits section. In the general portion, the *identifier* should be renamed as appropriate. The *navigation*, or how the Test-taker is allowed to answer questions, should be selected as either linear (first question first, second question second, etc.) or non-linear (can be answered in any order). Lastly, the *submission* mode will need to be selected as either individual (submitted response by response) or simultaneous (submitted at the end of the completing the test part).

In the item control section, four properties will need to be addressed. *Max Attempts* governs the number of tries the Test-taker may try (if left at the default of zero, an unlimited number of attempts may be tried). *Show Feedback* keeps modal feedback visible after the completion of the test part. *Allow Comment* provides the Test-taker with the ability to provide explanations for performance or other sort of feedback on the test. *Allow Skipping* lets the Test-taker pass on answering questions within the test part.

The time limits section is similar in nature to the time limits section for the test level properties, except that the answers apply to the test part.

**Step 3:** Click on the section level properties icon.

This brings up in the Properties panel five sections: general properties, selection properties, ordering, item session control, and time limits. The last two sections are the same as the last two portions of the test part properties, while the first three portions differ from previous levels. The general properties includes an identifier and title: the *Identifier* should generally be kept as defaulted, while the *Title* can be changed to suit the test. In general, the *Visible* checkmark should be checked (or else the Test-taker won't be able to see the section), and *Keep Together* should also be marked if completing the entire section before moving onto the next section is important.

The selection portion initially asks if the delivered test section should include only some of the Items assigned it (*Enable selection*), and if so, how many (*Select*). If *With Replacement* is selected while selection mode is enabled, then questions may end up repeated. Normally, they are only allowed to be used once in a Test sitting.

Ordering contains only one property setting, and that is *Shuffle*, a function that sets the question order randomly like shuffling a deck of cards.

**Step 4:** Click on the item level properties icon.

This brings up in the Properties panel three sections: general properties, item session control, and time limits. The last two sections are the same as the last two portions of both test part and section level properties. The general properties include entries for: *Identifier*, *Reference*, and *Categories*. It also includes check boxes to indicate the item is *required* and if it is *fixed*.

Identifier and references generally do not require modification. Categories act as tag references which may be displayed to the Test-taker. If the Item is checked as required, then it will appear on the Test, even if less than the total number of Items appears on a given Test (such as would be the case in a section where selection is enabled). If the Item is fixed, it will appear in a particular order, even if the section ordering calls for shuffling.
