<!--
created_at: 2018-10-22
authors:         
    - "Catherine Pease"
--> 


# Event Log

> All events in TAO, from a user logging in to creating a new test, are recorded in the TAO [Event Log](../appendix/glossary.md#event-log).
> 
> This section tells you how to find an event in the log, and how to export the event log to another computer. 



**1.** How to search the event log. 

To search TAO's event log, first click the event log icon in the [Assessment Builder Bar](../appendix/glossary.md#assessment-builder-bar). 

The Log Watcher will open. This is the event log page, where the most recent events are listed first.

If you are searching for events which took place over a specific period of time, this period can be defined in the *From* and *To* boxes near the top of the pane, and can be reset at any time by clicking *Reset*.

Clicking the *Reset* button overrides any period settings and shows the full list again. A different period can be selected by entering the desired dates and clicking on *Apply*. 


For each event, the following information is shown:

**Event ID:** Each event is allocated a unique number.

**Event Name:** The TAO description of the event, such as *TestCreatedEvent* 

**Action:** The path to the TAO command which was executed, e.g. /tao/Main/login.

**User ID:** The user's unique ID number.

**User Roles:** The role, for example *TenantRole*.

**Occurred:** The date and time of the event.


**1.** How to export the event log

To export TAO's event log - whether all events, or the subset of events you have chosen - click on the button *Export Log Entries* on the top right.

A dialog box will open in which you can set the CSV options for your file. The default settings are as follows:

**Field delimiter: ;**

**Field encloser: "**

**Multiple values delimiter: |**

**First row column names:** Column names will be included.

These CSV options can, however, be changed.

When you are satisfied with the settings you have chosen, click on the green button *Export*, and the CSV file Log will be downloaded to your browser.