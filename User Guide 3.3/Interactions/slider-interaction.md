<!--
created_at: 2016-12-15
authors:         
    - "Catherine Pease"
--> 

# Slider Interaction

>The Slider [Interaction](../appendix/glossary.md#interaction) gives [Test-takers](../appendix/glossary.md#test-taker) the opportunity to demonstrate their knowledge of a numerical type, such as a percentage, a total, etc. The answer is conveyed by sliding an indicator on a horizontal scale.

[![Slider Interaction](https://img.youtube.com/vi/fqrbvbavhuA/hqdefault.jpg)](https://youtube.com/watch?v=fqrbvbavhuA&rel=0 "Slider Interaction")


Once you have generated a new [Item](../appendix/glossary.md#item), and clicked on *Authoring* in the [Action Bar](../appendix/glossary.md#action-bar), follow the steps below to create a new Slider interaction:

**1.** From the [Common Interactions Library](../appendix/glossary.md#common-interactions-library) on the left, drag the *Slider* icon onto the blank Item and drop it onto the [canvas](../appendix/glossary.md#canvas).

This creates a new Slider interaction window. There is a question field at the top, followed by a graphical control element (a 'slider') indicating the scale covered by the answers to the question. Below the slider is the current value depicted by the slider ("0").

**2.** Fill in the question field, where it says 'define prompt'. 

This will describe the task given to the test-taker, typically a question involving numbers or a fraction, etc. 

*Note: See the section on [Interaction Authoring Tools](../interactions/interaction-authoring-tools.md) for details on text editing options such as using italics or bold text in your item, and inserting features such as shared stimuli or media, tables or formulae.*

**3.** Adjust the settings on the slider.

This can be done in the [Interaction Properties Panel](../appendix/glossary.md#interaction-properties-panel) on the right.

First, set the upper and lower limits of the slider using the *Upper Bound* and *Lower Bound* boxes.

By default, the lower boundary is set to 0 and the upper to 100. These default values anticipate a percentage answer, but can be adjusted as desired, so long as the lower boundary is less than the upper."

Next, adjust the intervals on the slider in the *Step* box. By default, the *Step* value is set to 1. These values should be customized to fit the question. (For example, in the question "What was the population of the Icelandic city of Reykjavik in 2014?", the interaction properties for the answer, 120,000, might be set so that the lower value is 100,000, the upper value is 200,000, and the step value is 10,000.)

**4.** Click *Response* on the right of blue interaction header to define the correct answer(s).

This provides access to the actual slider, so that the answer can be set. You can do this by moving the indicator to the correct value. 

<aside class="optional-extras">
##Optional Extras when Processing a Response

The following option is available in the [Response Properties Panel](../appendix/glossary.md#response-properties-panel) on the right.

###Inserting modal feedback

If you wish, you can insert [Modal Feedback](../appendix/glossary.md#modal-feedback) into this Interaction. For more information on how to do this, see the [section on Modal Feedback](../items/modal-feedback.md).
</aside>


**5.** Click the blue *Done* button. Your slider interaction is now complete.

After this step, you can preview your interaction using the steps given in the [Preview Instructions](../items/preview.md).
