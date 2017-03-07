<!--
    created_at: 2016-12-15
    authors:         
      - Catherine Pease
--> 

# Add an Extension

>[Extensions](../appendix/glossary.md#extension) add new functionalities to TAO, providing various TAO customizations. Extensions improve upon the basic TAO program by interfacing TAO with existing test-taking or test-scoring software, or enhancing test elements, as required by an institution.


**1.** Open the *[Extensions manager](../appendix/glossary.md#extensions-manager)*.

You can find the Extensions manager by hovering over the *Settings* icon, which is depicted by interlocking cogs in the [Assessment Builder bar](../appendix/glossary.md#assessment-builder-bar). Click to open.

The *Extensions manager* is one of several Settings options (the others are: File Sources, Result Server Manager, and LTI Consumers). When it is open, the screen shows a Settings canvas with the *Extensions manager* as the active tab in the row of tabs above that canvas. If a different Settings screen is shown instead, click on the tab that reads *Extensions Manager* to get to that particular canvas.

**2.** Review the *Installed Extensions* list and the *Available Extensions* list.

*Installed Extensions* are those extensions which are active and ready for use. *Available Extensions* are extensions on your server which are currently inactive - i.e. not installed.

**3.** Install a (currently inactive) *Available Extension* by clicking on the check box at the end of the line pertaining to that Extension. 

When all desired Extensions are selected, click *Install* at the bottom of the page. A window will appear asking for  confirmation that you wish to install these Extensions.
Click *Yes*. The Extensions selected will then be installed, the page will be reloaded, and the new extension will then be ready for use. 

If you wish to add an extension which is not in the list of *Available Extensions*, check it is listed in your `composer.json`. Add it there if necessary, and run `composer update`, as well as an update of your TAO installation `php /path/to/tao-root/tao/scripts/taoUpdate.php`. Then click on *Install* at the bottom of the page, and proceed as above.


Although each Extension improves on the basic TAO program by adding extra functionality, extensions can affect the speed of processing. It is therefore advantageous to add only those extensions which you will really need in order to do what you want to do in TAO. Also, it should be noted that there is not an easy way to remove an extension, once installed, so extension installation should be undertaken with appropriate caution.

