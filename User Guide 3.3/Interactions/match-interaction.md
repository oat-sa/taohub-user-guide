# Match Interaction

> The Match [Interaction](../appendix/glossary.md#interaction) provides [Test-takers](../appendix/glossary.md#test-taker) with a matrix upon which they can demonstrate their knowledge by accurately matching, or associating, selections from two different sets of elements. Matching is carried out by placing check marks in squares where matching rows and columns intersect.

Once you have generated a new [Item](../appendix/glossary.md#item), and clicked on *Authoring* in the [Action Bar](../appendix/glossary.md#action-bar), follow the steps below to create a new Match interaction:

**1.** From the [Common Interactions Library](../appendix/glossary.md#common-interactions-library) on the left, drag the *Match* icon ![Match](../resources/_icons/match.png) onto the blank item and drop it onto the [Canvas](../appendix/glossary.md#canvas).

This creates a new Match Interaction window. There is a question field at the top, and a default 2-row-by-2-column matrix beneath this.

**2.** Fill in the question field, where it says _define prompt_.

This should describe the match task expected of the test-taker.

*Note: See the section on [Interaction Authoring Tools](../interactions/interaction-authoring-tools.md) for details on text editing options such as using italics or bold text in your item, and inserting features such as shared stimuli or media, tables or formulae.*

**3.** Insert in the rows the first set of elements, and in the columns the second set of elements that are to be matched with the first.

Using the *Add new row* and *Add new column* buttons, add as many rows and columns as will be needed to cover all the matches. If desired, add some unmatched elements in either the rows or the columns to provide an additional challenge for the Test-taker.

<aside class="optional-extras">
## Optional Extras when Creating a Task

The following options are available in the [Interaction Properties Panel](../appendix/glossary.md#interaction-properties-panel) on the right.

### Shuffling the choices

Check the *Shuffle choices* box. The sequence of the row and column options will then be randomized. This is recommended if the order of presentation of either set of elements is not important.

### Limiting the use of a choice

If you want to limit the number of times a particular row or column is used, click on it. It will then appear in the *Identifier* box in the right-hand panel, which gives you the option to set the *Allowed number of uses*. Setting this to a maximum of 1, for example, will mean that the Test-taker can only use that element in one associated match.

### Specifying the correct number of associations

You can specify the minimum and maximum number of associations the test-taker will be asked to provide (before he can continue to the next question) in the *Number of associations* boxes in the Interaction properties panel. By default these are empty, which means the test-taker can include as many (or as few) matches, or  associations, as he likes. Setting the minimum to 0 allows the test-taker to skip the question.
</aside>
 
**4.** Click *Response* on the right of blue interaction header to define the correct answer(s).

<aside class="optional-extras">
## Optional Extras when Processing a Response

The following options are available in the [Response Properties Panel](../appendix/glossary.md#response-properties-panel) on the right.

### Modifying the scoring method

By default, a test-taker receives one point per completely correct interaction, so in the case of Match interactions, the test-taker has to select all the correct matches in order for the answer to be considered correct.

You may want to modify the scoring method if, for example, you want the test-taker to receive partial credit for selecting some, but not all, of the correct matches. Or you may wish to give a higher weight to some of the matches than to others. 

You can do this using the *map response* option of *Response processing*, in the Response Properties panel on the right. When you choose this option, there are several settings you need to enter. 

First, assign a weight for each match in the boxes next to each one. 

[Click here](../items/item-scoring-rules.md#item-scoring-rules) for more details on how to use this scoring method, and how to set the values of the associated properties.

### Inserting modal feedback

If you wish, you can insert [Modal Feedback](../appendix/glossary.md#modal-feedback) into this Interaction. For more details on how to do this, see the [section on Modal Feedback](../items/modal-feedback.md). 
</aside>

**6.** Click the blue *Done* button. Your match interaction is now complete.

After this step, you can preview your interaction using the steps given in the [Preview Instructions](../items/preview.md).
