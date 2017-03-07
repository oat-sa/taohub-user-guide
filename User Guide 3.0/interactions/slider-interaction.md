# Slider Interaction

>The Slider item gives Test-takers the opportunity to demonstrate knowledge of a numeric value, such as a percentage, a total, etc. The answer is conveyed by sliding an indicator on a horizontal scale.

**Step 1:** From the Common Interactions menu in the Library Panel, drag the *Slider* icon onto the blank Item and drop the resulting box in the blue field that appears when the interaction is dragged over it.

This creates a new Slider interaction window. There will be a field for placing in a question at the top, and a graphical control element indicating the scale covered by the answers to the question under that. Below the graphic is the current value depicted by the slider ("0").

**Step 2:** Fill in the question field. 

This will describe the task given to the Test-taker, typically a question involving numbers or a fraction, etc. Note that the A icon on the right allows you to put your text in bold or in italic for instance, and insert a picture. 

**Step 3:** Fill in the interaction properties in the Properties Panel. 

By default, the lower and upper bounds are set for an answer that involves percentages, with the lower set to 0 and the upper to 100. However, these values can be any number, so long as the lower bound is less than the upper bound. By default, the step value, or the interval between possible answers, is set to 1, but this can be changed to any number as well, allowing larger answers to be set to one, two, three, or more significant digits, or smaller numbers set as decimals. These values should be customized to fit the question. (For example, in the question, "What was the population of the Icelandic city of Reykjavik in 2014, using only two significant digits?" the interaction properties for the answer, 120,000, might be set so that the lower value is 100,000, the upper value is 200,000, and the step value is 10,000.)

**Step 4:** Click Response in the blue interaction header.

This provides access to the actual slider, so that the answer can be set. This is done by moving the indicator to the correct value.

Response properties are set to *Match Correct* only, but modal feedback can be set for this interaction. If modal feedback is desired, [more details on how to do this can be found in the Modal Feedback section](../items/modal-feedback.md).

**Step 5:** Click the blue *Done* button.

When this is done, you can preview what your Slider interaction looks like. For more on how to preview, [review its section](../items/preview.md).
