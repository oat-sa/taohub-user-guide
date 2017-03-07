# Select Point Interaction

>The Select Point Interaction gives Test-Takers the opportunity to demonstrate their knowledge by selecting an invisibly-defined portion of an image (region on a map, person in a line-up, etc.).

>This interaction is one of a series of *[Graphic](../appendix/glossary.md#graphic)* interactions (the others are covered in their own sections). All graphic interactions can be found in the Graphic Interactions menu in the Library. 

[![Select Point Interaction]()](https://www.youtube.com/watch?v=5OYeuVPxK_o)

Once you have generated a new [Item](../appendix/glossary.md#item), and clicked on *Authoring* in the [Action Bar](../appendix/glossary.md#action-bar), follow the steps below to create a new Select Point Interaction:

**1.** From the [Graphic Interactions library](../appendix/glossary.md#graphic-interactions-library) near the bottom of the *Interactions library* on the left, drag the *Select Point* icon onto the blank Item and drop it onto the [canvas](../appendix/glossary.md#canvas).

**2.** Choose the desired background graphic.

A [Resource Manager](../appendix/glossary.md#resource-manager) window will appear with which you can select a background graphic. You can re-use a background already in the resource manager, or you can upload a new one. To select one from the list of previously uploaded graphics, highlight the appropriate background graphic in the resource manager list and click the green *Select* button. To upload a new one, click on the blue *Add file(s)* button to browse the files on your computer, and then upload one to the resource manager by clicking the green *Upload* button.

Highlight the file you have chosen as your background by clicking on it, and it will appear on the right in the preview panel. Click *Select* in the bottom right of the window to continue.

A new authoring window will appear with the background graphic in the center of the canvas. Above the graphic there is a question field.

**3.** Fill in the question field, where it says 'define prompt'. 

This should cover such important information as what the background graphic represents, and what the test-taker is expected to select in this interaction. 

*Note: The A icon on the right allows you to bold or italize text, and to insert a picture, [shared stimulus](../appendix/glossary.md#shared-stimulus), [math expression](../appendix/glossary.md#math-expression) or link into your question.*

<aside class="optional-extras">
##Optional Extras when Creating a Task

The following option is available in the [Interaction Properties panel](../appendix/glossary.md#interaction-properties-panel) on the right.

###Specifying correct number of answers 

You can specify the number minimum and maximum of points that the test-taker will be asked to select (before he can continue to the next question) in the *Allowed Choices* boxes. By default, these are empty, which means the test-taker can include as many (or as few) of the answer options as he likes. (Setting the minimum to 0 allows the Test-taker to skip the question.)
</aside> 

**4.** Click *Response* on the right of blue interaction header to define the correct answer(s).

This opens the graphic with an [Associable Hotspot Panel](../appendix/glossary.md#associable-hotspot-panel) on the left, used for inserting selected shapes that will represent *[Associable Hotspots](../appendix/glossary.md#associable-hotspots)* into the graphic (these include four different shapes: rectangle, circle, ellipse, and polygon). Below the Hotspot Panel is a trash can icon, which allows the user to delete poorly-placed or misshapen Hotspots. 

To insert a rectangle, click on one corner and drag it across the intended area the Hotspot is supposed to cover. To insert a circle or ellipse, select its center and drag outward or inward until the Hotspot is the right size. To insert a polygon, begin at one corner, then click on each corner in succession until the Hotspot is complete. You can make all the shapes bigger or smaller (or in the case of polygons change the shape), but if necessary, click on the problem Hotspot, click the trash can to delete it, and then try again.

**5.** Insert the *Associable Hotspots* onto the background graphic.

Test-takers will not see these Hotspots on the background graphic, but selecting a point within the Hotspot will register it as a correct answer. 

**6.** Set the weights to be awarded for each Hotspot.

In the scoring method normally used as a default, a Test-taker receives one point per completely correct interaction (so the test-taker has to select all the correct responses in order for the answer to be considered correct).

In this type of interaction, however, each Hotspot is evaluated individually, and thus *Map Response* is used as the *[Response processing](../appendix/glossary.md#response-processing]* method (see [Response Properties panel](../appendix/glossary.md#response-properties-panel) on the right).

By clicking on each Hotspot, a pop-up window appears next to it, which allows you to set the weight to be awarded if the test-taker selects it correctly.  

[Click here](../items/item-scoring-rules.md#item-scoring-rules) for more details on how to use this scoring method, and how to set the values of the other associated properties.

<aside class="optional-extras">
##Optional Extras for Processing the Response

The following options are available in the Response Properties panel on the right.

###Inserting modal feedback

If you wish, you can insert [Modal Feedback](../appendix/glossary.md#modal-feedback) into this Interaction. For more information on how to do this, [see the *Modal Feedback* section](../items/modal-feedback.md).

###Limiting the duration of the test

Click anywhere outside of the Text Space. This will give you the option of setting the Interaction as *Time dependent* (to be completed within a certain interval), by checking the check box. [This option is covered in greater detail in Test Settings](../tests/tests-settings.md).

</aside>

**7.** Click the blue *Done* button. Your Select Point Interaction is now complete.

You can now preview your Interaction using the steps given in the [Preview instructions](../items/preview.md).
