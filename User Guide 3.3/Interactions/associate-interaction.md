<!--
created_at: 2016-12-15
authors:         
    - "Catherine Pease"
--> 

# Associate Interaction #

>The Associate Interaction assesses the Test-taker's ability to match associated words or phrases. 

For a quick glimpse of how to create an Associate Interaction in TAO, please watch the following video.

[![How to Create an Associate Item Using TAO](https://img.youtube.com/vi/MXyO4Q3vpH8/hqdefault.jpg)](https://youtube.com/watch?v=MXyO4Q3vpH8&rel=0 "How to Create an Associate Item Using TAO")

Once you have generated a new [Item](../appendix/glossary.md#item), and clicked on *Authoring* in the [Action Bar](../appendix/glossary.md#action-bar), follow the steps below to create a new Associate Interaction:

**1.** From the [Common Interactions library](../appendix/glossary.md#common-interactions-library) on the left, drag the *Associate* icon onto the blank Item and drop it onto the [canvas](../appendix/glossary.md#canvas).

This opens a new Associate Interaction window. There is a question field at the top, two *answer tile* options below this, and then an example of linked boxes at the bottom.

**2.** Fill in the question field where it says 'define prompt', describing the associations (matches) being sought.

This could be in the form of a question ("Which country goes with which capital city?") or instructional ("Match the country with the capital city."). 

*Note: The A icon on the right allows you to bold or italize text, and to insert a picture, [shared stimulus](../appendix/glossary.md#shared-stimulus), [math expression](../appendix/glossary.md#math-expression) or link into your question.*

*Drag-and-drop is enabled for this type of interaction. Test-takers can also use click-and-click to move objects; this is an accessibility feature for test-takers with trouble using drag-and-drop.*

**3.** Fill in the *answer tiles* for the question. 

You will need more than two, so select *Add choice* as many times as is needed to provide all the options to be made available to the test-taker.

*Note: We recommend adding the appropriate matches first (e.g. the correct countries and capitals) in separate tiles first, and then adding the incorrect (unmatched) options.* 

<aside class="optional-extras">
##Optional Extras when Creating a Task

The following options are available in the [Interaction Properties panel](../appendix/glossary.md#interaction-properties-panel) on the right.

###Shuffling the choices

Check the *Shuffle choices* box. This will help disguise the matched pairs you have entered for the question. If this is not clicked, how you've entered the tiles will be how they will appear to the test-taker.

###Limiting the use of a choice

If you want to limit the number of times a particular element is used, click on it. It will then appear in the *Identifier* box in the right-hand panel, which gives you the option to set the *Allowed number of uses*. Setting this to a maximum of 1, for example, will mean that the Test-taker can only use that element in one association. 

###Specifying the correct number of associations

You can specify the minimum and maximum number of associations the test-taker will be asked to provide (before he can continue to the next question) in the *Number of associations* boxes in the Interaction properties panel. By default these are empty, which means the test-taker can include as many (or as few) associations as he likes. Setting the minimum to 0 allows the test-taker to skip the question.

</aside>

**4.** Click *Response* on the right of blue interaction header to define the correct answer(s).

This will provide all the answer tiles created in the previous step, and a series of associate pair boxes, which are to be filled in the next step.

**5.** Click on the first element to be associated, and then click on the first box. Click its match (association), and then click on the second box.

This will provide the first set of correct responses. Continue with this procedure until all association pairs have been linked in the association boxes, leaving the incorrect associations unmatched. 

<aside class="optional-extras">
##Optional Extras when Processing a Response

The following options are available in the [Response Properties panel](../appendix/glossary.md#response-properties-panel) on the right:

###Modifying the scoring method


By default, a test-taker receives one point per completely correct interaction, so in the case of Associate interactions, the test-taker has to select all the correct associations in order for the answer to be considered correct.

You may want to modify the scoring method if, for example, you want the test-taker to receive partial credit for selecting some, but not all, of the correct associations. Or you may wish to give a higher weight to some of the associations than to others. 

You can do this using the *map response* option of *Response processing*, in the Response Properties panel on the right. When you choose this option, there are several settings you need to enter. 

First, assign a weight for each association in the boxes next to each one. 

[Click here](../items/item-scoring-rules.md#item-scoring-rules) for more details on how to use this scoring method, and how to set the values of the associated properties.

###Inserting modal feedback 

If you wish, you can insert [Modal Feedback](../appendix/glossary.md#modal-feedback) into this Interaction. For more information on how to do this, [see the *Modal Feedback* section](../items/modal-feedback.md).

</aside>

**6.** Click the blue *Done* button. Your Associate Interaction is now complete.

After this step, you can preview your Interaction using the steps given in the [Preview instructions](../items/preview.md).
