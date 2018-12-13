<!--
created_at: 2018-11-15
authors:         
    - "Catherine Pease"
--> 

# Providing Test-level Instant Feedback

>[Test takers](../appendix/glossary.md#test-takers) often want direct feedback about how well they have done in their assessment. It is possible to configure a [Test](../appendix/glossary.md#test) to offer them instant test-level feedback.


**Follow the steps below to configure your test to provide test-level instant feedback:**

**1.** Configure your test for [Outcome Processing](../appendix/glossary.md#outcome-processing).

Before you can provide test-takers with instant feedback on whether they have passed or failed, you need to configure the method of scoring for your test. To do this, click on Tests from the [Assessment Builder Bar](../appendix/glossary.md#assessment-builder-bar), and select your test from the [Library](../appendix/glossary.md#library).

Then, click on *Authoring* in the [Action Bar](../appendix/glossary.md#action-bar). Now you are in the test editor. 

Next, click on the *Settings* icon to the right of test name at the top. This is depicted by three interlocking cogs.

After this, open the *Scoring* panel, and select *Cut score* in the  drop-down menu of the *Outcome processing* box.

Then define a *Cut score* for your test.

*Note: This needs to be a ratio (between 0.0 and 1.0) and is computed by dividing the maximum score by the total score. If *Category score* is checked, the same cut score will be applied to all categories (set to individual items)*

When a *Cut score* has been defined, expand *Outcome declarations*, then check the correct generation of *Outcome variables* corresponding to the settings applied. 

<!-- Missing Screenshot: Configuring Scoring to provide Test-level Instant Feedback Tests -->

*Note: The full set of *Outcome variables* can be found in the section [Test Scoring and Outcome Declarations](../tests/test-scoring-and-outcome-declarations.md).*


**2:** Display the pass/fail captions.

The generated outcome variables can be used to display the appropriate pass or fail caption.
 
To do this, add a new [Test part](../appendix/glossary.md#test-part) at the end of the test.

Next, add an (informational) [Item](../appendix/glossary.md#item) to the [Section](../appendix/glossary.md#section)  by clicking on the **A** icon to the right of the section title. This adds a rubric block to the section. 

Then, click inside the blue *New Rubric Block* and insert an appropriate 'pass' caption, such as 'Well done!'. 

Add another rubric block by clicking inside the blue *New Rubric Block* below the first, and insert a 'fail' caption, such as 'Hard luck'.

Finally, specify when each of the captions should be displayed. To do this, click on the [Properties](../appendix/glossary.md#properties) icon on the right of each rubric block. The properties panel will open on the right. 

If you would like the captions in a specific style, you can add a style sheet in the *class* box. This can also be left blank, however. 

Then, click on the *Feedback Block* panel and check the *Activated* box so that your caption can be displayed as feedback. 

Select the relevant outcome variable for your test (defined in the test-level properties) from the drop-down menu in the *Outcome* box, and then a value in the *Match Value* box which indicates the circumstances in which this caption should be displayed. For pass/fail captions, choose *PASS\_ALL\_RENDERING* from the menu in the *Outcome* box, and enter *passed* in the *Match value* box if the caption is for a positive result, and *not_passed* if the caption is for a negative result.

<!-- Missing Screenshot:  Giving Test-level Instant Feedback -->

**3.** View the final outcome.

Save the test and create a new [Delivery](../appendix/glossary.md#delivery) to view the final outcome.

*Note: in an upcoming version of TAO, you will be able to add the actual values of the  outcome variables to be displayed in rubric blocks (e.g. “you received a score of Y out of Z”) in the test-editor. Adding a “printed variable” like this is currently only possible by manipulating the QTI XML manually (outside of TAO).*