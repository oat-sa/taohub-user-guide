# Importing Groups

>[Group](../appendix/glossary.md#group) metadata files can be taken from any computer and imported onto any other computer that also has access to TAO. This is done using an operation called *Import*.

**1.**  Click on the *Groups* icon ![class](../resources/_icons/test-takers.png) on the [Assessment Builder Bar](../appendix/glossary.md#assessment-builder-bar).

This will take you to the [Group Library](../appendix/glossary.md#group-library), which you will see on the left.

**2.**  Click on the Class ![class](../resources/_icons/folder.png) in the library in which you wish to import the new group.

**3.**  Click on *Import* in the button bank below the library.

This opens a dialog box which asks you to select the format of the incoming group metadata. The supported formats are RDF (Resource Description Framework) or CSV (Comma-Separated Values).

![Importing Groups of Test-takers](../resources/backend/groups/import-3.png)

**4.** Click the blue *Browse* button to find the file intended for import (alternatively, the file may be dragged and dropped into the box below the button).

**5.** Once the file is selected, click on the blue *Import* button if importing an RDF. If you are importing a CSV file you will click on the blue *Next* button.

![Selecting CSV](../resources/backend/groups/import1.png)

You will then need to map the properties to the CSV columns and then click on the blue Import button.

![Mapping Columns](../resources/backend/groups/import2.png)

This will import the [Test-taker](../appendix/glossary.md#test-taker) group into the Group library, after which its members can receive [Tests](../appendix/glossary.md#test).

## Structure of CSV File

By default, the CSV file should follow to next rules:
Value separator: Semicolon
Row separator: Newline

```
Label;Deliveries
Group Label;https://nec.local/tao.rdf#i1567762787708426
Group Label2;https://nec.local/tao.rdf#i1567767601342667
```

In that example, we have 2 columns. The first line is header, next lines are values.
Required columns:
Label - a label of group. That value using for the BackOffice.
Deliveries - ID of delivery

