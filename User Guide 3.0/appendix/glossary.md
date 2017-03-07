# Glossary

>The following are specialized terms that users of TAO may frequently run into while using the program to author tests, administrate them, or generate assessment reports.

**A**

**Adaptive Item:** An [Item]() that changes either its interaction, its scoring, or both following unsatisfactory attempts by the Test-taker to provide an correct response. The adaptivity usually is used to adapt assessment questions into learning experiences for the candidate, guiding that person through the Item while scoring performance. Advanced.

**Adaptive Test:** A Test that varies presentation of [Items](../terminology/what-is-an-item.md) based on Test-taker response. Generally achieved through the use of pre-conditions and branching. Advanced.

**Assessment Variable:** Technical term for the final score assigned to a Test-taker's performance in an [Item](../terminology/what-is-an-item.md) Session or a [Test](../terminology/what-is-a-test.md) Session.

**Attempt:** A singular candidate interaction with an [Item](../terminology/what-is-an-item.md) that possibly assigns values to or updates an associated Response Variable.

**Authoring System:** A system used by authors to create and edit [Items](../terminology/what-is-an-item.md) and [Tests](../terminology/what-is-a-test.md). [TAO](../introduction/what-is-tao.md) is an example of an authoring system.

**B**

**Base-type:** A predefined data type used to define a value set from which Item Variables are drawn.

**Basic Item:** An [Item](../terminology/what-is-an-item.md) that contains one and only one [Interaction](../terminology/what-is-an-interaction.md).

**C**

**Candidate Session:** The time during which the candidate or Test-taker is interacting with an [Assessment Item](../terminology/what-is-an-item.md) as part of an Attempt. An attempt may extend across more than one candidate session (such as when a Test-taker terminates one candidate session to move on from a difficult-to-answer question to do other Items first, effectively suspending the Attempt, and then comes back to start another candidate session in order to finish that Attempt before the exam ends).

**Cloning Engine:** A system for creating multiple similar items (or Item Clones) from an Item Template. [TAO](../introduction/what-is-tao.md) uses a cloning engine to assist users in authoring Items.

**Composite Item:** An [Item](../terminology/what-is-an-item.md) that contains more than one [Interaction](../terminology/what-is-an-interaction.md).

**Container:** An aggregate data type that can contain multiple values of unmodified Base-types, or even be empty.

**D**

[**Delivery System:**](../terminology/what-is-a-delivery.md) A system that administers and delivers assessments to Test-takers through the use of a delivery engine, or a process that coordinates both Item delivery and [response evaluation (scoring)](../items/item-scoring-rules.md) and feedback.

**E**

**F**

**Feedback:** Any material presented to the candidate as a result of an outcome variable meeting or exceeding particular conditions. This can include integrated, [modal](../items/modal-feedback.md), and test feedback.

**G**

**H**

**I**

[**Interaction:**](../terminology/what-is-an-interaction.md) The part of an [Item](../terminology/what-is-an-item.md) that allows the candidate to interact in an assessment, selecting or constructing a response.

**Integrated Feedback:** Feedback that is integrated into an [Item](../terminology/what-is-an-item.md). Unlike with [Modal Feedback](../items/modal-feedback.md), Test-takers may update their responses while viewing Integrated Feedback.

[**Item:**](../terminology/what-is-an-item.md) The smallest exchangeable object in an assessment. An item is more than a 'Question' in that it contains also the contextual instructions, the processing to be applied to the Test-taker's response(s), and any Feedback (including hints and solutions). May also be called Assessment Item.

**Item Clone:** An [Item](../terminology/what-is-an-item.md) that appears similar to others created by an Item Template. These are identical except for designated variables called Template Variables.

**Item Fragment:** Part of an [Item](../terminology/what-is-an-item.md) managed independently from other parts. If it introduces all Items in a set, such a fragment is often referred to as a set leader.

**Item Session:** The accumulation of all Test-taker Attempts at a particular [Item](../terminology/what-is-an-item.md).

**Item Set:** A group of [Items](../terminology/what-is-an-item.md) that share common characteristics. 

**Item Template:** A template used for producing large numbers of similar [Items](../terminology/what-is-an-item.md), often called Cloned Items. These will have one or more designated Template Variables, and will be governed by a set of Template processing rules that are assigned these values. These may be produced by a special purpose Cloning Engine, such as [TAO](../introduction/what-is-tao.md).

**Item Variable:** A variable that records Test-taker responses and any outcomes assigned during [response processing](../items/item-scoring-rules.md) during an Item Session. As a special kind of Assessment Variable, Item Variables are also used to define Item Templates.

**J**

**K**

**L**

**M**

**Material:** All static text, image, or media objects that are intended for the Test-taker rather than for being interpreted by a processing system. [Interactions](../terminology/what-is-an-interaction.md) are not considered as material.

[**Modal Feedback:**](../items/modal-feedback.md) Feedback that is not integrated into an [Item's](../terminology/what-is-an-item.md) body during presentation to the Test-taker.

**Multiple Response:** A Response Variable that serves as a container for multiple values taken from a value set defined by a base-type. These are processed as an unordered list, and may be empty.

**N**

**Non-adaptive Item:** An [Item](../terminology/what-is-an-item.md) that does not change following attempts made by a Test-taker.

**O**

**Object Bank:** A collection of objects used during an assessment, including [Items](../terminology/what-is-an-item.md), Item Fragments, or Test parts.

**Ordered Response:** A Response Variable that is a Container for multiple values taken from a value set defined by a Base-type. These are processed as an ordered list (sequence) of values, but may be empty.

**Outcome:** The result of an [Assessment Test](../terminology/what-is-a-test.md) or [Item](../terminology/what-is-an-item.md). These are represented by one or more Outcome Variables.

**Outcome Processing:** The process that aggregates values of [Item](../terminology/what-is-an-item.md) Outcomes (or Responses) to make [Test](../terminology/what-is-a-test.md) outcomes.

**Outcome Variable:** Variables taken from outcome declarations. Values are set either from a default given within the declaration or by a response rule encountered during [Response Processing (for Item outcomes)](../items/item-scoring-rules.md) or Outcome Processing (for Test outcomes).

**P**

**Pool:** A special type of Object Bank that includes related [Items](../terminology/what-is-an-item.md) transported together with metadata that describes the group as a whole.

**Q**

**R**

**Response:** Data provided by the Test-taker through interaction with an [Item](../terminology/what-is-an-item.md) or Item Part. Associated values are represented as Response Variables.

[**Response Processing:**](../items/item-scoring-rules.md) The process by which Response Variable values are scored and Item Outcome values are assigned.

**Response Variable:** Variables taken from response declarations and bound to [Interactions]() in the [Item body](../terminology/what-is-an-item.md), they record the candidate's responses.

**S**

**Scoring Engine:** The part of the assessment system that process Test-taker responses and scores them based on [Response Processing](../items/item-scoring-rules.md) rules.

**Single Response:** A Response Variable that takes a single value from the value set defined by a Base-type.

**T**

**Test Feedback:** Feedback presented to a Test-taker conditionally based on final score values.

**Template Processing:** Rules used to set values for Template Variables. These are typically set by a random process that selects a specific clone to be used for an Item Session.

**Template Variable:** Variables taken from template declarations that record values that render an item template unique. These values determine the clone within a set defined by an Item Template that will be used for a given Item Session.

**Test (or Assessment):** An organized collection of [Items](../terminology/what-is-an-item.md) that are used to measure performance of a candidate with respect to that person's level of mastery of a given subject. Assessments contain all instructions required for navigation through a sequence of Items. They also calculate the final score earned by the Test-taker.

**Test Fragment:** Part of a [Test](../terminology/what-is-a-test.md) managed independently.

**Test Report:** A report describing a [Test](../terminology/what-is-a-test.md) Session.

**Test Session:** The interaction of a candidate with a [Test](../terminology/what-is-a-test.md) and the [Items](../terminology/what-is-an-item.md) it contains.

**Test-taker (or Candidate):** A person that participates in a [Test](../terminology/what-is-a-test.md), assessment or exam by answering questions.

**Time Dependent Item:** An [Item](../terminology/what-is-an-item.md) that records the accumulated elapsed time for a Candidate Session in a Response Variable, used during [Response Processing](../items/item-scoring-rules.md).

**Time Independent Item:** An Item that does not use the accumulated elapsed time during [Response Processing](../items/item-scoring-rules.md).

**U**

**V**

**W**

**X**

**Y**

**Z**
