<!--
created_at: 2016-12-15
authors:         
    - "Catherine Pease"
--> 

# Text Entry Interaction

>Text Entry [Interactions](../appendix/glossary.md#interaction) allow [Test-takers](../appendix/glossary.md#test-taker) to complete a "Fill in the Blank" question with an exact text answer. This interaction is one of two *Block*-related interactions, the other being *Inline Choice* (covered in its own section).

Once you have generated a new [Item](../appendix/glossary.md#item), and clicked on *Authoring* in the [Action Bar](../appendix/glossary.md#action-bar), follow the steps below to create a new Text Entry Interaction:

**1.** From the [Inline Interactions Library](../appendix/glossary.md#inline-interactions-library) below *Common Interactions* on the left, drag the *Block* interaction, represented by a letter *A* icon, onto the blank Item and drop it onto the [Canvas](../appendix/glossary.md#canvas).

This creates a field (containing a sample text) in which a text may be entered from a favorite source (a Word document or website, for instance), or typed in. 

To enter your text, click inside the text field.

*Note: See the section on [Interaction Authoring Tools](../interactions/interaction-authoring-tools.md) for details on text editing options such as using italics or bold text in your item, and inserting features such as shared stimuli or media, tables or formulae.*

<!-- Missing Screenshot: Text Entry Interaction -->

**2.** Once you have entered the text, drag the *Text Entry* icon from the Inline Interactions library to the space next to where the test-taker will be expected to *fill in the blank*.

This creates a pop-up window containing the blank, which is to be filled by the test-taker. No changes can be made here: the window just confirms that you have created the blank. However, a correct answer will need to be selected and this is done in the *Response* mode.

*Note: Remember to remove the actual words from the text that the Text Entry blanks are designed to replace.*

<aside class="optional-extras">
##Optional Extras when Creating a Task

The following options are available in the [Interaction Properties Panel](../appendix/glossary.md#interaction-properties-panel) on the right.

###Inserting a 'placeholder' text in the blanks 

If you would like to put a text in the fields the test-taker is supposed to fill in, such as "Write your answer here", enter it in the *Placeholder Text* field.
 
###Placing constraints on the answer

You can specify a certain [Pattern](../appendix/glossary.md#pattern) which should be used in the answer. This can be done in the *Pattern Mask* box.
 
###Giving hints about the text length

You can provide a hint for the test-taker about the length of the text by filling in the *Expected Length* field. This tells the test-taker the number of words expected.

###Changing the base of numerical values

The *Base* feature is used to set the number base for the interpretation of numerical values entered by the test-taker. By default this is 10, i.e. its interpretation is based on the decimal system. If it uses a different system, change this here. 

</aside>

**3.** Click *Response* in the pop-up window to define the correct answer(s).

This opens the response entry window, in which you can enter the correct answers. Remember that you will need to produce an answer that the test-taker will be expected to match exactly, character-for-character, including spaces. 

Repeat steps 2 and 3 until all the desired Text Entry blanks have been inserted into the text.

<aside class="optional-extras">
##Optional Extras when Processing a Response

The following options are available in the [Response Properties Panel](../appendix/glossary.md#response-properties-panel) on the right.

###Modifying the scoring method

By default, a test-taker receives one point per completely correct interaction, so in the case of Text Entry interactions, the test-taker has to select all the correct answers in order for the answer to be considered correct.

You may want to modify the scoring method if, for example, you want the test-taker to receive partial credit for selecting some, but not all, of the correct answers. Or you may wish to give a higher weight to some of the answers than to others. 

You can do this using the *map response* option of *Response processing*, in the Response Properties panel on the right. When you choose this option, there are several settings you need to enter.
 
First, assign a weight for each response in the boxes next to each one.

[Click here](../items/item-scoring-rules.md#item-scoring-rules) for more details on how to use this scoring method, and how to set the values of the other associated properties.


###Inserting modal feedback 

If you wish, you can insert [modal feedback](../appendix/glossary.md#modal-feedback) into this Interaction. For more information on Modal Feedback, see the [section on Modal Feedback](../items/modal-feedback.md).

###Limiting the duration of the test

Click anywhere outside of the Text Space. This will give you the option of setting the interaction as *Time dependent* (to be completed within a certain interval), by checking the check box. This option is covered in greater detail in [Test Settings](../tests/tests-settings.md).

</aside>

**4.** Click the blue *Done* button. Your text entry interaction is now complete.

After this step, you can preview your interaction using the steps given in the [Preview Instructions](../items/preview.md).
