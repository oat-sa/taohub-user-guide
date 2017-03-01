# CSS SDK

>The TAO platform offers different ways to change the look of an Item. The Item Style Editor allows you to customize a small number of Items. The use of this tool is described more fully [in its own section](../items/style-editor.md).

>For larger numbers of Items, there is the Cascading Style Sheet Software Development Kit (CSS SDK). The CSS SDK is based on a set of files that use the same CSS selectors that are used inside TAO, and these allow you to easily overwrite the default theme. In future versions of TAO, OAT plans to expand this SDK to make the task of adding the same style sheet to a large number of items easier.

>The decision on whether to use the [Item Style Editor](../items/style-editor.md) or the CSS SDK depends on what the user is trying to achieve, and that person's prior knowledge of Cascading Style Sheets (CSS).

### Simple design modifications

For most simple changes, the test author may use the built-in Item Style Editor. This feature allows you to change colors within the Item's background, text, borders, and table headers. It also allows you to change font type and size, and, in accordance with QTI standards, modify Item widths (though this latter feature isn't recommended, as within the TAO platform, Items are responsive, or rather they automatically adapt to the size of device you are using).

#### Pros
* Requires no CSS knowledge
* Instant results
* Covers the most common scenarios

#### Cons
* The design possibilities are limited
* All modifications need to be repeated for each item (time intensive for larger numbers of Items)

### Major design modifications

CSS SDK was designed to assist with major design changes.  However, to make use of it, you will need to have at least some prior knowledge of cascading style sheets (CSS). [The HTMLdog tutorial](http://www.htmldog.com/reference/cssproperties/) will help you get at least a basic understanding. [Codrops' CSS reference](http://tympanus.net/codrops/css_reference/) is very detailed, but may be advanced for beginners.

You will also need some understanding of the browser console. All examples presented here will refer to the developer console in Firefox but the concepts are very similar in all modern browsers. If you are unfamiliar with the browser console, start with the tutorial on the Mozilla website. There is one that focuses on the [Page Inspector](https://developer.mozilla.org/en-US/docs/Tools/Page_Inspector) and another one that explains the [Style Editor](https://developer.mozilla.org/en-US/docs/Tools/Style_Editor) (note, that this should not be confused with the Item Style Editor inside the TAO platform!). 

#### Pros
* You can profoundly change the look of an Item
* You can apply your own corporate identity

#### Cons
* You need to be familiar with CSS
* You need to know your way around the browser console

Keep in mind that, depending on the the style modifications you wish to make, it might be necessary to install additional software.

## Working with item styles 

If you compare an online test to a paper-based one, you could say the item is the paper you are writing on. Or if you prefer word processors, you could say it is an empty document. An item will in any case contain at least one interaction and probably components involving text or pictures. 

Modifying the item style as such would typically involve changing the background color, the text color, the font, or even the background picture.

The CSS SDK uses the selector code `html body div.qti-item` to modify an item directly. As an example, the custom style for an item could look something like this:
<pre>
html body div.qti-item {
    background-color: #eeeeee;
    color: #333333;
    font-family: Arial, Helvetica, sans-serif;
    border: 2px #dddddd solid;
}
</pre>

We recommend that you prefix every selector with `html body div.qti-item` to ensure you do not interfere with the appearance of the TAO platform itself.

### Adding background pictures or fonts

In a regular web environment you would use the following code to add a background image:

<pre>
html body div.qti-item {
    background-image: url(my-image.png);
}
</pre>

Inside the TAO platform this is currently not possible. All external resources need to be compiled into the stylesheet by encoding them in `base64`. OAT provides a [tool to convert resources to base64](http://style.taotesting.com/tool-resource-to-base64-data-uri/). With an encoded image the above code takes on the following appearance:

<pre>
// code has been shortened for readability
html body div.qti-item {
    background-image: url(data:;base64,iVBORw0KGgoAAAANSUhEUgAAAAMAAAADCA
    YAAABWKLW/AAAAEUlEQVR42mNgYGD4z4AGMAUANfEC/pPYlKYAAAAASUVORK5CYII=);
}
</pre>

The same rules apply in the scenario where you want to add an external font with the `@font-face` rules. They will also need to be encoded in `base64`. With TAO's browser support, you will only need the `*.woff` format. However, using the `*.woff2` format could reduce the need to make changes to your item in TAO versions currently under development.

### Including External Stylesheets with @import

As already mentioned, TAO does not support the inclusion of external resources, at least not in a commonly predictable way. It is therefore not possible to include stylesheets using the `@import`-rule.

## Structure of Interactions

All interactions share architecture that is relatively similar to each other. The following example uses an *order interaction*, but its basics are the same as most other interactions available on TAO.

<pre>
    &lt;div class=&quot;qti-interaction qti-blockInteraction qti-orderInteraction&quot;&gt;
        &lt;div class=&quot;qti-prompt-container&quot;&gt;
            &lt;p class=&quot;qti-prompt&quot;&gt;Prompt&lt;/p&gt;
        &lt;/div&gt;
        &lt;div class=&quot;order-interaction-area&quot;&gt;
            &lt;ul class=&quot;choice-area&quot;&gt;
                &lt;li class=&quot;qti-choice&quot;&gt;...&lt;/li&gt;
            &lt;/ul&gt;
            &lt;ul class=&quot;result-area&quot;&gt;
                &lt;li class=&quot;qti-choice&quot;&gt;...&lt;/li&gt;
            &lt;/ul&gt;
        &lt;/div&gt;
    &lt;/div&gt;
</pre>

As you can see the interaction sits in a container with the following CSS classes:

*	`qti-interaction`
*	`qti-blockInteraction` (resp. `qti-inlineInteraction`)
*	`qti-orderInteraction` (or any other type)

Below this level sits the `prompt`, which is embedded in a `qti-prompt-container`. The prompt is followed by two blocks, the `choice-area` and the `result-area`. This is typical for all interactions that consist of two blocks. The actual choices in this example have the class `qti-choice`.

If you want to change, for instance, the background of the choices only in the result area of this particular interaction, your selector would be as follows:

<pre>
html body div.qti-item .qti-orderInteraction .result-area .qti-choice {
    background: grey;
}
</pre>

To modify them for both areas you would write instead:

<pre>
html body div.qti-item .qti-orderInteraction .qti-choice {
    background: grey;
}
</pre>

And finally if the style should apply to all block interactions:

<pre>
html body div.qti-item .qti-blockInteraction .qti-choice {
    background: grey;
}
</pre>

## Working with the Browser Console

Probably one of the most important tools for a CSS developer is the browser console. Here we will concentrate on the one that comes with Firefox, but the consoles in other modern browsers work very much the same way.

There are two panels on the console that are of particular interest, the Inspector and the Style Editor (again, not to be confused with the Item Style Editor inside the TAO platform!).

The Mozilla website has a tutorial for the browser console that pretty much focuses on the [Inspector](https://developer.mozilla.org/en-US/docs/Tools/Page_Inspector), as well as a page that focuses on the [Style Editor](https://developer.mozilla.org/en-US/docs/Tools/Style_Editor). 

It is important to note that item and interactions are different at both design time and runtime. When you are in the Item Creator, these elements contain a number of additional parts, such as toolbars, context menus, etc., that are needed to edit the interaction. Inspecting the source code in this environment can be tricky or even misleading. A better way to review what you have would be to display the item preview and to start the inspection there.

### Finding the Styles for an Element

There are several strategies to find the right CSS selector for applying a particular style. The rules in the SDK are well named and commented but, just as one size doesn't fit all, they cannot address every possible modification. 

The most straightforward way to find a selector is to use the Inspector panel. Right-click the element and select *Inspect Element* (or similar, depending on your browser) to display it in the Inspector. It happens often that the element you have chosen does not have the style you are looking for. In this case select the parent or child elements until you see the style in the *Rule* panel. You can use the Rule panel to also try out a style before you edit your actual stylesheet.

### Testing a Stylesheet

Although seemingly intuitive, going to TAO's Item Style Editor and uploading your CSS file to test your stylesheet is actually a more complicated method to test your stylesheet. After uploading, you will then need to reload the page, select the item again, and enter into authoring mode. This is obviously very impractical. 

Fortunately, this is where the browser's style editor comes to rescue. The best way to start is to use an empty stylesheet, say `my-custom-styles.css`, and then to use this to test your work in the browser console. You should not call your stylesheet `tao-user-styles.css` because this is a reserved name. While nothing will break, this could still cause confusion.

If you compile your stylesheets with a pre-processor, such as SASS, you need at this point to perform an additional step: On the top right of the console click on the little gear icon (representing "Toolbar Options") and check the box that says "Show original sources" ( or"Show source maps", as it might appear in some other browsers). This will help you to identify which of the many source files contains the style you want to edit.

When you scroll over the list of stylesheets on the left hand side of the panel, you will notice some files that start with *getFile*. One of them will have `my-custom-styles.css` at the end; this is the file you need to select. From this point you can copy and paste your new styles into this panel and the styles will be applied immediately.


### What Can You Do If a Style is not Applied?

There is of course always the possibility that you have an invalid rule, a spelling mistake, a missing semicolon, or something similar. If you can rule all of these minor errors out, you will need to check whether your selector is strong enough. Inspect the element in question in the browser console and find out which selector has been applied in the original CSS. It might be that your style is there, but has been struck through. In this case you will need to edit the selector and make it more specific. There is a [good article on CSS Tricks](http://css-tricks.com/specifics-on-css-specificity/) that illustrates some useful techniques. That said, there is also an easy way out - you can simply use a [Specificity Calculator](http://specificity.keegan.st/) to tackle the problem. Adding `!important` to a rule - as is sometimes recommended - should always be the very last resort and used only with great care.

## Using a Pre-processor for Your Stylesheets

In recent years it has become increasingly popular to generate stylesheets with a pre-processor such as *SASS*, *LESS* or *Stylus*. TAO uses *SASS* in the *SCSS* flavor for its stylesheets and this works very well. All source files within the SDK are available either as pure `*.scss` or as `*.css` files. If you can use SASS on your computer we definitely recommend that you do this. Of course any other pre-processor can be used, but we do not provide any sources other than *SASS/SCSS*. 

To work with SASS, open a command line window; navigate to the *SCSS* folder of your project and type 

<pre>
sass --watch .:../css
</pre>

## Working Directly with CSS

The SDK contains a complete stylesheet with the same selectors found in the `*.scss` files. It contains no *CSS* rules but only empty selectors and comments. For the practical work you should not edit this stylesheet directly because you would essentially create a rather large CSS file of which most lines are unused. A better approach would be to start with an empty stylesheet and copy-paste the lines that you need for the rule you are working on from the original file. This way your code remains small and readable while keeping the SDK documentation intact.

## Software and Resources

The [Firefox](https://www.mozilla.org/en-US/firefox/new/) Style Editor at this point is the most suitable on the market for applying CSS. [Chrome](https://www.google.com/chrome/browser/desktop/), on the on the other hand, requires no administration rights for installation.

We recommend that you compress all the pictures you create for a stylesheet. [PngOptimizer](http://psydk.org/pngoptimizer) for Windows does this very well but there are many other applications that may be used. [TinyPNG](https://tinypng.com/) is just one of the many online services that serve as a useful alternative. There is no standalone compressor for JPEG that we can currently recommend - you will need to rely on your graphics editor.

When you work with fonts via `@font-face`, you should not use them as an external resource, such as through [Google Fonts](http://www.google.com/fonts). The reason is that you have no guarantee that a student who takes your test will also simultaneously have the required unrestricted access to the Internet. Fontsquirrel has a nice [generator for web fonts](http://www.fontsquirrel.com/tools/webfont-generator) that allows you to download a font in the right format and to include it in the CSS. Remember that in order to match TAO's current browser requirements, you need the font only in the *.woff* format. Again, though, using *.woff2* fonts could prove to be a time-saver when converting to future versions of TAO that are currently under development.

If you work with pictures and fonts, you need to convert them into a *base64 data URI*. We have a converter on the [TAO Style Guide](http://style.taotesting.com/tool-resource-to-base64-data-uri/) that you can use to generate data Uniform Resource Identifiers (URIs).

If you need a further tutorial on CSS, [HTMLdog](http://www.htmldog.com/reference/cssproperties/) has a good one. It may not be the most up-to-date, but for most users, it will certainly cover most of their needs. [Codrops' CSS reference](http://tympanus.net/codrops/css_reference/) is an excellent resource for those who already know their way around stylesheets.

We found this Calculator for [CSS Specifity](http://specificity.keegan.st/) to work nicely. 

The SASS website has a [beginner's guide](http://sass-lang.com/guide) that should help most people get started. There is also a [page that explains the installation](http://sass-lang.com/install) of SASS. Do note that you will need administrator rights for this installation.

The Mozilla website has a [tutorial for the browser console](https://developer.mozilla.org/en-US/docs/Tools/Page_Inspector) that focuses on all the aspects that a user applying CSS to items would be interested in. There is also a useful page covering the [Style Editor](https://developer.mozilla.org/en-US/docs/Tools/Style_Editor). 