<!--
tags: []

--> 

# Test Scoring Rules and Outcome Declarations

> Test scores are determined by a student's performance in the various [Items](../appendix/glossary.md#item) of a [Test](../appendix/glossary.md#test). Individual item scores can be tallied using different methods to produce the final Test result. This chapter shows how to configure the Test scoring rules, and compute the Outcome Declarations.

>For information on Item Scoring Rules, see [Item Scoring Rules](../items/item-scoring-rules.md).


Follow the steps below to set up your chosen scoring method.

**1.** After you have created your Test by selecting the Items which are to go in it, hover over the cog wheels just below the Action Bar, at the top of the right-hand corner of the canvas, and you will see the option *Manage Test Properties*. Click on this and the properties relating to the scoring of Tests will open in the right-hand panel. 


**2.** Click on the button *Scoring*.

There are four potential configurations from which to choose how you would like the Test to be scored. Enter your choice in *Outcome Processing*:

<!-- Missing Screenshot: Scoring -->

- **None**: If this option is selected, any existing scoring rules will be removed. In this case, no test score will be generated. Scores for the individual items of the Test can be extracted by clicking on *Results*, or the QTI Results API. Use this option if you want to do full custom processing.

- **Custom**: This option is only applicable when a test with custom outcome processing rules is imported - thus the processing rules are defined outside of TAO. In this case, the rules cannot be authored by TAO, so the existing rules are left untouched.

- **Total Score**. If you select this as your chosen configuration, all scores from all parts of the Test will be added together, and the total will be given as the total score. ![Scoring: Total Score](../resources/backend/tests/authoring/settings/test/scoring/total-score.png)

- **Cut Score**: If you choose this option, a cut-off point for passing the test will be fixed. Enter the score which is to be used as the cut-off point in the *Cut Score* box. This is set as a ratio of the total score. A PASS variable is then generated, indicating if the student has passed the test. ![Scoring: Cut Score](../resources/backend/tests/authoring/settings/test/scoring/cut-score.png)


If you choose either of the latter configurations (*Total Score* or *Cut Score*), some additional information is required. A check-box for *Category Score* will appear. If *Category Score* is selected, the scores will be calculated for each category separately. You will also need to set the *Weight* identifier used to calculate the score. This should be entered in the *Weight* box. Different *weights* can be assigned to different items of the test, based on how much they should contribute to the final test score. For example, if a weight of 2 is entered, the score for that item is multiplied by 2 when calculating the final test score (see section [Item Scoring Rules](../items/item-scoring-rules.md) for more information on weighting). If any item in the test has no such weight defined on its individual level, the scoring engine assume the default value = 1.


**3.** Click on the button *Outcome Declarations*. 

The Outcome Declarations are directly related to the scoring rules you have chosen above; the list of generated outcome variables is as follows:
 
- If you selected **None** as the outcome processing method, all outcome variables are removed

-  If you selected **Total score** as the outcome processing method, outcome variables are generated to calculate total scores

-  If you selected **Cut score**, as the outcome processing method, outcome variables are generated to calculate total scores and variables which are checked against the cut-score which has been defined (typically pass/fail)

- If a **WEIGHT** has been applied, additional outcome variables are generated to compute weighted scores

*Note: Outcomes are generated automatically, but in the few cases where this does not occur,the values can be generated using the 'regenerate' button.*  

The configuration of the scoring rules is now complete. 