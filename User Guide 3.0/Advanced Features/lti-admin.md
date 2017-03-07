<!--
created_at: 2015-05-15
authors:         
    - "Ben Angel"    
--> 

# Setting up a TAO-Moodle delivery as an LTI Administrator

>Through the [Learning Tool Interaction (LTI) standard set forth by IMS Global Learning Consortium](http://developers.imsglobal.org/), Moodle users can make use of TAO-designed tests and deliver them to students through the Moodle platform. Setting up the interface between TAO and Moodle takes only a couple steps to complete. However, you must have administrator privileges on both TAO and Moodle.

**Step 1:** Ensure TAO is configured for LTI.

To do this, you will need to install the required extensions through the Extensions Manager. To use this, review the [Extensions Manager](../advanced-features/add-an-extension.md) section in this guide. You will want to select and install extensions ltiDeliveryProvider and ltiProvider. Once these are in place, reload the TAO page.

The last steps to configure TAO is to go back to settings, and then click on the new LTI Consumers tab. Select the LTI Consumer class (folder), and click on Add Consumer. Name the new consumer, and fill in an easy to remember Consumer key and Shared secret (this is used within the integration). The callback URL can be left blank. Finally, click on Create. If the consumer does not immediately appear, reload the page and it should come up. Record the URL of the page – this is your Tool Base URL.

**Step 2:** Ensure Moodle is correctly configured.

Go to Site Administration in the Moodle platform and open under Advanced Features the pull-down menu for Plugins. Pull to Activity modules and then go to Manage activities. Next, open Settings within External Tools and click on Add external tool configuration. Add an appropriate name to the new configuration and then enter the Consumer key and Shared secret set in TAO. Enter the Tool Base URL where it asks for it. Finally, click on Save Changes.