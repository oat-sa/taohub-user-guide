<!-- created_at: 2016-12-15 authors: - "Catherine Pease" -->

 # Installing TAO

> There are currently two TAO installation packages available on the OAT server: Automatic and Manual. Automatic installation involves setting up a permanent connection to TAO's own server. This affords greater ease of operation, leaving all technical issues to OAT. Manual installation involves setting up a web server and installing TAO on it. This affords a greater degree of flexibility and control.

**1.** On the [OAT download page](http://www.taotesting.com/get-tao/official-tao-packages/), click on the package appropriate for the computer on which you'll be using TAO.

- Automatic Package: Downloads a clickable, executable file.
- Manual Package: Downloads a ZIP file.

By carrying out this step you will initiate the download. Select the target system and/or folder for the installation file, and click _save_.

**2.** When the selected extractable is downloaded, double-click on it to begin the extraction.

This may take a few minutes to complete.

**3.** Installing on your machine.

**Windows installation**

_Note: Applications such as Skype will need to be closed during the installation._

After downloading, the installer can be found in the Downloads folder if no other location was chosen. The installation will begin after double-clicking the file and the wizard will walk you through accepting the agreement, selecting the installation location, and shortcuts. Once completed you will have a TAO Back Office on your computer, which can be accessed through your preferred browser at <http://localhost/:89> or using the 'TAO login' shortcut (login:demo, password: demo).

**Linux Installation**

For users installing the manual package on Linux, follow the additional steps below.

Install the latest versions of the following applications: Apache 2 server, PHP server configuration, MySQL server configuration and PostgreSQL.

_Note: The recommended versions are as follows: Apache 2: version 2.4; PHP server configuration: version 7.3 or later; MySQL server configuration: version 5.0 or later or PostgreSQL: version 7.0 or later._

These are used to create your own web server, upon which TAO will be installed.

Once the Apache 2 server is installed, ensure that the rewrite and PHP 5 modules are enabled, `AllowOverride All` directive is set in `DOCUMENT_ROOT`, and that www-data or Apache user write permission is granted for the following files and folders:

1. `/ (root directory, for the .cache directory only)`
2. `generis/data/`
3. `generis/common/conf`
4. `filemanager/views/data`
5. `taoResults/views/genpics`

Once the PHP server configuration is installed, ensure that `register_globals` and `magic_quotes_gpc` are both off, and `short_open_tag` is on.

The following extensions will be required:

- `mysql`
- `mysqli`
- `curl`
- `json`
- `gd`
- `zip`
- `spl`
- `dom`
- `mbstring`

**4.** Extract the source code from the downloaded archive and install it directly.

This should go in your `htdocs` or `www` folder.

**5.** Run the TAO Installation Wizard online.

This can be found at the website: `http://YOURSERVER/tao/install/`

**6.** When the installation is complete, you should be redirected to `http://YOURSERVER/`

If you are not automatically redirected, type in `http://YOURSERVER/` in the address bar of your browser.
