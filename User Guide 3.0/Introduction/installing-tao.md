<!--
created_at: 2015-05-15
authors:         
    - "Ben Angel"    
--> 

# Installing TAO

>There are currently two TAO installation packages available on the OAT server, one for Automatic Installation, and the other for Manual Installation. Manual installation involves setting up a web server and installing TAO on it. This affords a greater degree of control by the institution. Automatic installation involves setting up a permanent connection to TAO's own server, and affords greater ease of operation, leaving all technical issues to OAT.

**Step 1:** On the [OAT download page](http://www.taotesting.com/get-tao/official-tao-packages/), click on the package appropriate for the computer on which you'll be using TAO.

- Automatic Package: Downloads an executable extractable package.
- Manual Package: Downloads a ZIP package.

Doing this step will initiate the download. Select the target system and/or folder for the installation file, and hit save.

**Step 2:** When the selected extractable is downloaded, double-click on it to begin the extraction.

This may take a few minutes to complete.

For users installing the automatic package or the manual package on Windows, the next step is to activate the UniController executable installer. This can be found in the TAO_2.6.7_with_server folder. Applications such as Skype will need to be closed during the installation, which begins after clicking the *Start All* button. This will create a TAO Back Office on your computer, which can be accessed through your favorite browser at http://localhost/tao (Login and Password are initially set to "tao").

For users installing the manual package on Linux, follow these additional steps.

**Step 3:** (Linux only) Install the following applications: Apache 2 server (recommended version 2.2.17), PHP server configuration (version 5.3 or 5.5, or any version between), MySQL server configuration (greater than version 5.0), and PostgreSQL (greater than version 7.0).

These are used to create your own web server, upon which TAO will be installed.

Once the Apache 2 server is installed, ensure that the rewrite and PHP 5 modules are enabled, "AllowOverride All" directive is set in DOCUMENT_ROOT, and that www-data or Apache user write permission is granted for the following files and folders:

1. / (root directory, for the .cache directory only)
2. generis/data/
3. generis/common/conf
4. filemanager/views/data
5. taoResults/views/genpics

Once the PHP server configuration is installed, ensure that register_globals and magic_quotes_gpc are both off, and short_open_tag is on. The following extensions will be required: mysql, mysqli, curl, json, gd, zip, spl, dom, and mbstring.

**Step 4:** Extract the source code from the downloaded archive and install it directly.

This should go in your [htdocs, www] folder.

**Step 5:** Run the TAO Installation Wizard from online.

This can be found at the website: http://YOURSERVER/tao/install/

**Step 6:** After the installation is complete, you should be redirected to http://YOURSERVER/

If this is not the case, you may need to direct yourself to that address using your favorite browser.