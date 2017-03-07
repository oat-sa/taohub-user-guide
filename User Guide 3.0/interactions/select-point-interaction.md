# Select Point Interaction

>The Select Point interaction gives Test-takers the opportunity to demonstrate knowledge by selecting an invisibly-defined portion of an image (region on a map, person in a line-up, etc.).

>All graphic interactions can be found in the Graphic Interactions menu (the third bar down) in the Library Panel. All require dragging the appropriate icon, such as the Select Point interaction icon, over the blank Item and dropping it on the blue block field that appears when the icon is passed over it. This will result in the Resource Manager window coming up, through which the test-author will select a background graphic. A list of previously uploaded graphics will appear, above which is a blue button for selecting new graphics to upload. Once this background graphic is selected or uploaded, work may begin on the specific interaction.

>For the Select Point interaction, a new authoring window will appear with the background graphic in the center of the canvas. Above the graphic will be a field for writing in the question associated with this interaction. This reflects what the Test-taker sees when encountering this interaction.

**Step 1:** Fill in the question field. 

This should cover such important information as what the background graphic represents, and what the Test-taker is supposed to select in this interaction. Note that the A icon on the right allows you to put your text in bold or in italic for instance, and insert a picture.

**Step 2:** Determine if the question will be time dependent, and check if appropriate in the Interaction Properties window.

Time dependence is useful for limiting the time in which a Test-taker has to get through interactions within the examination. [This will be covered in greater detail in Test Settings](../tests/tests-settings.md).

**Step 3:** Click Response in the blue interactions header.

This opens the graphic with an Associable Hotspot Panel on the left, used for inserting selected shapes that will represent Associable Hotspots into the graphic (these include four different shapes: rectangle, circle, oval, and polygon). Below the Hotspot Panel is a trash can icon, which allows the user to delete a poorly-placed or misshaped Hotspots. To place a rectangle, click on one corner and drag across the intended area the Hotspot is supposed to cover. To place a circle or oval, select its center and drag outward or inward until the Hotspot is at the right size. To place a polygon, begin at one corner, then click on each corner in succession until the Hotspot is completed. All the shapes can be edited, but if necessary, click on the problem Hotspot, then click the trash can to delete it, and then try again.

**Step 4:** Insert the Associable Hotspots onto the background graphic.

These Hotspots will not appear on the background graphic, but selecting a point within the Hotspot will register as a correct answer. 

**Step 5:** Define the properties in the Properties Panel.

This interaction scores only using *Map Response* as a response processing method, which means that additional entries will be required for the *Score Range*. A minimum score that the Test-taker can receive must be selected, as must a maximum score. Scores are assigned to each individual Hotspot, and if the weight assigned for each selection is to be reflected in the final score, the total for all correct selections should be entered as a maximum score a value equal to all these values. If the maximum is set to less, any score higher than the maximum will be set to the maximum. The same would be applicable to the minimum; if the score registered is less than this number, the point value will raise to the minimum. The map default is the point value given even if no correct answers are given by the test-taker. *Define Correct Response* should be checked.

Clicking on each Hotspot will bring up a small window asking what score should be assigned for selecting a point within it. Again, all potential sets of maximum scores should equal the maximum score for the item if the full score weight for each answer is to be taken into consideration. 

If modal feedback is desired for this interaction, enter it at this point. For more details on how to do this, [see the Modal Feedback section](../items/modal-feedback.md).

**Step 6:** Click the blue *Done* button.

When this is done, you can preview what your Select Point interaction looks like. For more on how to preview, [review its section](../items/preview.md).
