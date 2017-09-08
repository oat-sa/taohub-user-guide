<!--
tags: []

-->

# PCI Interactions


>Portable Custom Interactions (PCIs) are interactions which are developed for a specific scenario, generally to fulfill the specific need of a customer, hence they are not classical QTI interactions.

The following types of PCI are part of the standard TAO package: *Audio, Likert, Liquid, Text Reader*, and *Math Entry*.
 

- **Audio**: An *Audio* Interaction enables the user to record a short spoken response. The test-taker is presented with an image of a tape recorder, and can record speech by clicking on the record button, and check the recording using the play-back button. The response format is an audio file. Audio interactions are only compatible with *Firefox* and *Chrome*, not with *Internet Explorer* or *Edge*. *Chrome* requires a connection via *https*, whereas at the present time *Firefox* allows both *https* and *http* connections (this is, however, expected to change to only *https* in the future).

![PCI: Audio Interaction](../resources/backend/items/authoring/interactions/pci/audio-interaction.png)

- **Likert**: In a *Likert* Interaction, a scale from 1-5 is used to represent people's attitudes to a topic. This is commonly used in qualitative surveys. The scale is presented using 'thumbs-down' and 'thumbs-up' images to represent a negative or positive response, and offers five buttons from which to select a choice. The response is a simple integer representing the selected choice.

<!-- Missing Screenshot: Likert-Interaction -->

- **Liquid**: A *Liquid* Interaction contains a simple simulation of a liquid container. The container has a scale on the left-hand side. This type of interaction can be used to ask questions about volume. To record the correct answer, click on *Response* and then click inside the cube at the desired point. If the answer is "5 liters", for example, click in the cube at the level of the 5 on the scale on the left-hand side, and the cube will 'fill' to that level with a simulated blue liquid.

<!-- Missing Screenshot: Liquid-Interaction -->

- **Text reader**: A *Text Reader* Interaction provides a space for a simple reading passage, and offers the possibility of scrolling and paging. By clicking on the **A** icon on the right, you can bold or italize text, and insert a picture, [shared stimulus](../appendix/glossary.md#shared-stimulus), [math expression](../appendix/glossary.md#math-expression) or link into your text.

<!-- Missing Screenshot: Text-Reader-Interaction -->

- **Math Entry**: A *Math Entry* Interaction employs a Math Editor, which allows for the use of mathematical symbols in the interaction. The editor provides a list of mathematical symbols and an empty text field. Please note that the editor only provides the possibility of drawing mathematical symbols, but does not carry out any calculation. See the [Math Expressions section](../items/math-expressions.md) for more information on how to use the Math Editor.

<!-- Missing Screenshot: Math-Entry-Interaction -->

**1.** To create any of these types of interaction, once you have created a new Item, click on the [Custom Interactions library](../appendix/glossary.md#custom-interactions-library) below *Graphic Interactions* on the left, and drag the appropriate interaction type onto the blank Item, drop it onto the [canvas](../appendix/glossary.md#canvas), and then populate the Item.