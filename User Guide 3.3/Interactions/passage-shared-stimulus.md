<!--
created_at: 2018-11-12
authors:         
    - "Catherine Pease"
--> 

# Passage (or Shared Stimulus)

>A stimulus is a piece of information, usually in text form, which sets the context for a question or a series of questions. A [Shared Stimulus](../appendix/glossary.md#shared-stimulus) is one that is shared between multiple [Items](../appendix/glossary.md#item).

*Note: In most versions of TAO, the term "shared stimulus" has been replaced by the term "passage".*  


Below is a template for a shared stimulus in the form of an empty XML file, which you can use to author a new shared stimulus (outside of TAO): 

```
<?xml version="1.0" encoding="UTF-8"?>
<div xmlns="http://www.imsglobal.org/xsd/imsqti_v2p1" xmlns:xi="http://www.w3.org/2001/XInclude" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" class="stimulus_content" xsi:schemaLocation="http://www.imsglobal.org/xsd/imsqti_v2p1 http://www.imsglobal.org/question/qtiv2p1pd2/xsd/imsqti_v2p1.xsd">

<h1>Title</h1>
<p>Text here...</p>

</div>
```

To create a shared stimulus with a media file, reference the media file using its relative location and include it in a zip file together with the XML file, then import the zip file.
