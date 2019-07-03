# Choice Interaction

>Choice [Interactions](../appendix/glossary.md#interaction) or multiple choice question, present a test type that has been made popular by such time-honored exams as the SAT, ACT, PSAT/NMSQT, etc. Choice interactions are preferable to free-response test interactions in cases where a large quantity of test questions need to be covered in a short exam period.

[![How to Create a Multiple-Choice Item Using TAO](https://img.youtube.com/vi/8upgdOSTKK0/hqdefault.jpg)](https://youtube.com/watch?v=8upgdOSTKK0&rel=0 "How to Create a Multiple-Choice Item Using TAO")


Once you have generated a new [Item](../appendix/glossary.md#item), and clicked on *Authoring* in the [Action Bar](../appendix/glossary.md#action-bar), follow the steps below to create a new Choice Interaction: 
  
**1.** From the [Common Interactions Library](../appendix/glossary.md#common-interactions-library) on the left, drag the *Choice* icon onto the blank item and drop it onto the [Canvas](../appendix/glossary.md#canvas).

This provides the answer choices for your choice interaction.

**2.** Enter the question in the question field at the top of the interaction where it says _define prompt_. 

*Note: See the section on [Interaction Authoring Tools](../interactions/interaction-authoring-tools.md) for details on text editing options such as using italics or bold text in your item, and inserting features such as shared stimuli or media, tables or formulae.*

**3.** A choice interaction has three default answer choices. Click on *choice #1* to type the first answer choice in this field. Repeat this step with the other choices to populate the other fields with your answer choices.

You can add more choices by clicking the blue *Add Choice* field below the first three choices (keep clicking until the desired number of choices appear in the item), and you can delete choices by clicking the trash can icon to the right of the choice you wish to delete.

**4.** After defining all answer choices, set the minimum and maximum number of answer choices that the Test-Taker will be asked to provide (before he can continue to the next question). 

This can be done in the *Allowed Choices* boxes in the [Interaction Properties Panel](../appendix/glossary.md#interaction-properties-panel) on the right. Setting the minimum to "0" allows the [Test-taker](../appendix/glossary.md#test-taker) to skip the question.

By default, your choice interaction is made of checkboxes. Leaving the maximum on "0" allows test-takers to select an unlimited number of choices.

To set up a [radio button](../appendix/glossary.md#radio-button) test interaction, select a maximum of 1. This means that your test-taker will not be allowed to select more than one choice. You can see on your interaction that radio buttons will be displayed.

<aside class="optional-extras">
## Optional Extras when Creating a Task

The following options are available in the Interaction Properties panel on the right.

### Presenting the answer choices in list format

To present the choices as a list, select one of the options in *[List style](../appendix/glossary.md#list-style)*, which is located below the *Allowed Choices*.

### Shuffling the choices 

Check the *Shuffle choices* box. This will randomize the order in which answer choices appear for each test-taker. In this manner, guessing or copying strategies is rendered useless. Where the order of items is unimportant, this is recommended. 

*Note: Remember that if you use this option, avoid choosing an ordinal list style, eg. A,B,C or 1,2,3.*

### Presenting the answer options horizontally

Answer choices can be presented either vertically or horizontally. This can be defined in the *Orientation* option. The default is vertical.
</aside>

**5.** Click *Response* on the right of the blue interaction header to define the correct answer(s).

This activates options for setting the correct answer.

**6.** Select the correct answer by clicking the box in front of it.

You can select more than one answer.

<aside class="optional-extras">
## Optional Extras when Processing a Response

The following options are available in the [Response Properties Panel](../appendix/glossary.md#response-properties-panel) on the right.

### Modifying the scoring method

By default, a test-taker receives one point per completely correct interaction, so in the case of Choice interactions, the test-taker has to select all the correct choices in order for the answer to be considered correct.

You may want to modify the scoring method if, for example, you want the test-taker to receive partial credit for selecting some, but not all, of the correct choices. Or you may wish to give a higher weight to some of the choices than to others. 

You can do this using the *map response* option of *Response processing*, in the Response Properties panel on the right. When you choose this option, there are several settings you need to enter. 

First, assign a weight to each choice in each of the corresponding Interaction boxes. 

[Click here](../items/item-scoring-rules.md#item-scoring-rules) for more details on how to use this scoring method, and how to set the values of the associated properties.

### Inserting modal feedback

If you wish, you can insert [Modal Feedback](../appendix/glossary.md#modal-feedback) into this Interaction. For more information on how to do this, [see the *Modal Feedback* section](../items/modal-feedback.md).
</aside>


**7.** Click the blue *Done* button. Your choice interaction is now complete.

After this step, you can preview your interaction using the steps given in the [Preview Instructions](../items/preview.md).