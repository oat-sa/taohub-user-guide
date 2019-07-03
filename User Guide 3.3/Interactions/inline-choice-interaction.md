# Inline Choice Interaction

> Inline Choice [Interactions](../appendix/glossary.md#interaction) allow [Test-takers](../appendix/glossary.md#test-taker) to complete a "Fill  in the Blank" question with one choice taken from a selected list of answers. Like with all inline interactions this interaction needs to be in a *Text Block*  ![Block](../resourses/_icons/font.png)

For a quick glimpse of how to create an Inline Choice Interaction in TAO, please watch the following video.

[![How to Create an Inline Choice Interaction Using TAO](https://img.youtube.com/vi/qdpX6MGrAAM/hqdefault.jpg)](https://youtube.com/watch?v=qdpX6MGrAAM&rel=0 "How to Create an Inline Choice Interaction Using TAO")


Once you have generated a new [Item](../appendix/glossary.md#item), and clicked on *Authoring* in the [Action Bar](../appendix/glossary.md#action-bar), follow the steps below to create a new Inline Choice interaction:

**1.** From the [Inline Interactions Library](../appendix/glossary.md#inline-interactions-library) below *Common Interactions* on the left, drag the *Text Block* ![Block](../resourses/_icons/font.png) onto the blank Item and drop it onto the [canvas](../appendix/glossary.md#canvas).

This creates a field (containing a sample text) in which a text may be entered from a favorite source (a Word document or website, for instance), or typed in. 

To enter your text, click inside the text field.

*Note: See the section on [Interaction Authoring Tools](../interactions/interaction-authoring-tools.md) for details on text editing options such as using italics or bold text in your item, and inserting features such as shared stimuli or media, tables or formulae.*

**2.** Once you have entered the text, drag the *Inline Choice* icon ![Inline Choice](../resourses/_icons/inline-choice.png) from the Inline Interactions library to a space next to where the test-taker will be expected to *fill in the blank*.

This brings up a pop-up window with three default choices. Enter the test-taker's answer options by highlighting the default entries (choice #1, etc.) and typing in each answer option. For fewer choices, click the trash can next to each choice to delete it. To add another choice, click the blue *Add Choice* field below the other choices to generate another field. 

Repeat the above for each place in the text where you would like to the test-taker to fill in the blank.

*Note: Remember to remove the actual words from the text that the Inline Choice blanks are designed to replace.*

<aside class="optional-extras">
## Optional Extras when Creating a Task

The following options are available in the [Interaction Properties Panel](../appendix/glossary.md#interaction-properties-panel) on the right.

### Shuffling the choices

Check the *Shuffle choices* box. This will randomize the order in which answer choices appear for each test-taker. In this manner, guessing or copying strategies is rendered useless.

*Note: Remember that if you use this option, avoid choosing an ordinal list style, e.g. A,B,C or 1,2,3.*

### Obliging the test-taker to give an answer

If you want to prevent test-takers from continuing to the next question without providing an answer, check the *required* box.

</aside>

**3.** To select the right answer, click on each Inline Choice element, and in the header bar of the resulting pop-up window, click *Response*.

This produces the same selection of options that the Test-taker will see. Simply select the correct response to set the right answer.

<aside class="optional-extras">
## Optional Extras when Processing a Response

The following options are available in the [Response Properties Panel](../appendix/glossary.md#response-properties-panel) on the right.

### Modifying the scoring method

By default, a test-taker receives one point per completely correct interaction, so in the case of Inline Choice interactions, the test-taker has to select all the correct choices in order for the answer to be considered correct.

You may want to modify the scoring method if, for example, you want the test-taker to receive partial credit for selecting some, but not all, of the correct choices. Or you may wish to give a higher weight to some of the choices than to others. 

You can do this using the *map response* option of *Response processing*, in the Response Properties panel on the right. When you choose this option, there are several settings you need to enter. 

First, assign a weight for each choice in the boxes next to each one. 

[Click here](../items/item-scoring-rules.md#item-scoring-rules) for more details on how to use this scoring method, and how to set the values of the other associated properties.

### Inserting modal feedback 

If you wish, you can insert [Modal Feedback](../appendix/glossary.md#modal-feedback) into this Interaction. For more information on how to do this, see the [section on Modal Feedback](../items/modal-feedback.md).

### Limiting the duration of the test

Click anywhere outside of the Text Space. This will give you the option of setting the interaction as *Time dependent* (to be completed within a certain interval), by checking the check box. This option is covered in greater detail in [Test Settings](../tests/tests-settings.md).

</aside>
 
**4.** Click the blue *Done* button. Your inline choice interaction is now complete.

After this step, you can preview your interaction using the steps given in the [Preview Instructions](../items/preview.md).
