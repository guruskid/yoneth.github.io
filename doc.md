#1. Installation


###1.1 WordPress Installation
This theme requires a working version of WordPress to be installed on your server. You should always run the latest version of WordPress.
If you don't have a WordPress installed on your server, please follow the steps below to install it:

Step 1 - Go to WordPress.org and download the latest version of WordPress.

Step 2 - Create a database for WordPress on your web server and a MySQL user with all privileges for accessing and modifying the database.

Step 3 - Upload the WordPress files in the desired location on your web server.

Step 4 - Run the WordPress installation by accessing your website in a web browser.

___


###1.2 Theme Installation via WordPress

In order to download the theme files package, please log in to [Themeforest](http://www.themeforest.net). Navigate your mouse over your profile name, then go to the [Downloads](http://themeforest.net/downloads) page. Click on the Download button and you will get a few options to download: All files & documentation ; Installable WordPress file only ; License certificate & purchase code (PDF) ; License certificate & purchase code (text). Click the **Installable WordPress file only**

![Installable WordPress file only](http://i.imgur.com/HD0Evli.png)


When you download the theme from Themeforest, you will get an archive file in .zip extension. When done, you should see *billio.zip*.

Please, follow the steps below to install your Billio Theme.

Step 1 - Login to your WordPress Dashboard.

Step 2 - Go to **Appearance > Themes**. Click **Add New** button,located at the top of the screen. 

Step 3 - Continue by clicking **Upload Theme** .

Step 4 - Choose **billio.zip.**

Step 5 - Wait while the theme is uploaded and installed.

Step 6 - Activate the theme and you will be prompted to install required plugins **VIsual Composer** and **Revolution Slider**. With few other recommended plugins.

###1.3 Common Theme Installation Problems

**“Are you sure you want to do this?”**
If you get the “Are you sure you want to do this” message when installing Billio via WordPress, it means you have an upload file size limit. Install the theme via FTP if this happens, or ask your hosting company to increase the limit.

**Missing stylesheet file**
If you get an error saying that the stylesheet is missing, then you have uploaded the wrong folder. Please check that you are uploading the billio.zip (billio.zip) within the Theme Files folder. You have to unzip the file that you download from Themeforest Marketplaces to find this.

___

###1.4 Theme Installation via FTP

If you are going to install the theme using FTP, you will need an FTP Client, such as FileZilla.

When you download the theme from Themeforest, you will get an archive file in .zip extension.

When done, you should see *billio.zip*.

Please, follow the steps below to install your Billio Theme via FTP:

Step 1 - Log into your hosting space (server) via FTP client.

Step 2 - In extracted archive folder, you should see **billio** folder

Step 3 - Upload the **billio** folder to your server in path .../wp-- content/themes/

Step 4 - The uploaded path should look like this: .../wp-content/themes/billio/

Step 5 - Now, login to your WordPress Dashboard and go to Appearance > Themes and activate Billio Theme.

Step 6 - you will be prompted to install required plugins **VIsual Composer** and **Revolution Slider**. With few other recommended plugins.

![FTP folder](http://i.imgur.com/FPjpX9H.png)
___


###1.5 Setting Up Demo Content

####1.5.1 Automatic 1-Click Demo Importer

Setting up the demo content is super easy with our 1-Click Demo Importer.
Please, follow the steps below to import the demo data using the 1-Click Demo Importer:

Step 1 - Log into your WordPress Dashboard.

Step 2 - Go to **Appearance > Import Demo**. 

Step 3 - Choose a Demo, and scroll down to see more options if you want to skip importing some of demo sections : *Skip Content ; Skip theme option ; Skip Sidebar Widget ; Skip Media ; Skip Slide Demo ; Skip WooCommerce Demo*

Step 4 Click the Import button to start the import process.

Step 5 - Wait until the process is done and the page is reloaded. This may take a while. **Do not interrupt/cancel the import process!**

![Demo Import Interface](http://i.imgur.com/6GOwFvj.jpg)

The importer should be run only once. If something went wrong and you need to import the content again, you may need to reset your WordPress.
Use this plugin to reset the WordPress database : [http://wordpress.org/plugins/wordpress-database-reset](http://wordpress.org/plugins/wordpress-database-reset/)

**Warning, although importing demo will not remove your exising content. It is highly recommended for new installations only.**

####1.5.2 Manual Demo Import

Some servers don’t support one click import. If you host your site on a sharing server or your server can’t handle the import traffic, one click import will fail. In this case follow these steps to perform manual demo import.

These steps are guidelines for a manual demo import. File names may vary depending on the Demo you are importing.

#####1.5.3 Import Media files, Pages and Posts

Step 1 - From your dashboard click on Tools -> Import -> WordPress and install WordPress Importer.

Step 2 - Click on Activate plugin & run importer.

Step 3 - Click browse and navigate to demo_content.xml file from Demo Content folder (previously downloaded from Themeforest).

Step 4 - Click **Upload file and import.**

Step 5 - Check **Download and import file attachments**.

Step 6 - Click Submit.

Step 7 - Wait for **All done have Fun! message.**

*If you don’t get the All done have Fun! message go to Appearance -> Menus delete all the menus and start over again until you get the message.*

#####1.5.4 Setup Your Menu

Step 1 - Click on Appearance > Menus.

Step 2 - Switch to Manage Locations tab at the top of the page.

Step 3 - Assign menu **Main Menu** to **Top Navigation**

#####1.5.5 Setup your Homepage & Blog Page

Step 1 - Click on **Settings > Reading.**

Step 2 - Set **Front page displays > A static page** to Home as displayed below:

![Reading Settings](http://i.imgur.com/L8sQubz.png)

#####1.5.5 Theme Options Import

Step 1 - Navigate to Appearance > Theme Options > Import/Export tab.

Step 2 - Copy/Paste content from from **theme_option.json** file from Demo Content folder (previously downloaded from Themeforest).

#####1.5.6 Revolution Slider Import

Step 1 - Click on Revolution Slider tab in your dashboard.

Step 2 - Click on Import Slider button and navigate to Revolution Slider Exports.

Step 3 - Import all exported .zip sliders under *demo content/rev slider* folder one by one.

#####1.5.7 WP Options Import

Step 1 - Click on Plugins > Add New.

Step 2 - Search for **WP Options Importer** plugin by Matthew Boynes or download it manually from here: [https://wordpress.org/plugins/options-importer](https://wordpress.org/plugins/options-importer)

Step 3 - Go to **Tools > Options.**

Step 4 - Select **widget_option.json** file from *Demo Content* folder (previously downloaded from Themeforest).

Step 5 - Click on **Upload File and Import**.

Step 6 - You will be prompted to *What would you like to import?* question, select **All Options**, and tick **Override existing options** for *Additional Settings*

Step 7 - Click on **Import Selected Options**.

___

###1.6 Translating The Theme
Billio is localized and you can easily translate it to any language you like. Please make sure that the font that you are using on your website is supporting your language characters. For example Cyrillic characters.

The theme is already translated to two languages : English and Bahasa. Inside **billio > languages** folder, you will find .po / .mo files for those languages. 

####1.6.1 Translate to any other language

In order to translate the theme to any other language, follow the steps below:

Step 1 - Duplicate this file billio/languages/en_us.po into wp-content/languages/themes

Step 2 - Rename it to your language code, with a prefix detheme- ( for example detheme-id_ID.po for Indonesian Language )

Step 3 - Open it using [poedit](http://poedit.net). Search for string you want to translate into, then save it.

Step 4 - Rename **/billio/languages** directory into something else, for example **lang**, in order to disable this folder from wordpress language indexing.

Step 5 - Once you’ve done with steps above, navigate to **Settings > General > Site Language**. Select your language from select option.


*WATCH A VIDEO TUTORIAL*

####1.6.2 Send us your translation!

If you translate Billio into a language that isn't included, then we'd really appreciate it if you could send it to us. It will be helpful to other users and also you wouldn't have to worry about theme updates. We will give you credits for the translation on our theme description page. Thanks!

[Send us your translation](mailto:support@detheme.com)


#2. First Steps

###2.1 Upload your logo image

You can upload your logo image in the Billio Theme Options. If the logo is not uploaded, then Billio logo will be used.

Billio 

Please, follow the steps below to upload your logo:

Step 1 - Login to your WordPress Dashboard.

Step 2 - Go to Appearance > Theme Options > Main Navigation. Billio has distinct feature that allow you to upload different logo images between homepage and the rest of all pages.  And if your **Sticky Menu** option is active, you are able to set two different logo images, which will be set on default navigation bar and sticky navigation bar.

Step 3 - Upload your logo in any size

*To implement retina logo, please upload your logo resolution exactly double the size you are going to set under **Logo Width** setting*

___

###2.2 Change Post & Custom Post Layout

Billio comes with three layouts: Full, Left Sidebar and Right Sidebar.

Please, follow the steps below to find out how to change your layout:

Step 1 - Login to your WordPress Dashboard.

Step 2 - Go to Appearance > Theme Options > General > General Settings. You will see Main Layout as WP default post, with other type of posts : Recruitments Layout, Reports Layout, WooCommerce, Contact Forms Layout and all other posts that are installed in your WordPress website.

Step 3 - Choose between Full, Left Sidebar and Right Sidebar.

Step 4 - Don't forget to save the changes.

___

###2.3 Mega Menu Setup

The mega menus are available only for top level navigations items only in "Main Menu" area.

Follow the steps below to create a mega menu:

Step 1 - Make sure that **Mega Menu Elements, CSS Classes and Description** option is checked in the **Screen Options** under "Show advanced menu properties" while you are in **Appearance > Menus** page in your WordPress Dasboard.

![Screen Options](http://i.imgur.com/ormhwmX.png)

Step 2 - Now, add a an item to the menu editor. **This has to be a top level item!**

Step 3 - Click on arrow icon in the top right-hand and expand. Tick **Activate Mega Menu Dropdown for this item** checkbox.

![Activate Mega Menu](http://i.imgur.com/zNJak9Y.png)

Step 4 - Click **Add Column**

![Add Column](http://i.imgur.com/Wv4pqoz.png)

Step 5 - Drag it right below mega menu item and then indent it

![Indent Column](http://i.imgur.com/JL6d7Fe.png)

Step 6 - Specify column width by specifying a css class, in example `col-sm-4` to display 4/12 ( or 1/3 ) width.

![Column Width](http://i.imgur.com/uNYFK66.png)

Step 6 - Now, you need to add child menu items, which should be indented under **Mega Menu Column** as shown on the image below

![Child Menu Items](http://i.imgur.com/rmFRWr8.png)

- Step 7 - To add Heading/ Title, click Add Heading Item in Mega Menu Elements and arrange it in the first order.

![Heading Item](http://i.imgur.com/iXcaCfu.png)

Step 6 - Your dropdown should now look something like this :

![Dropdown Mega Menu](http://i.imgur.com/ZcTpZ8p.png)


There are several additional classes available for the mega menu. Simply add them next to the 'megamenu' class separated by one single space.

- col-sm-3 - 1/4 column width
- col-sm-4 - 1/3 column width
- col-sm-6 - 1/2 column width
- col-sm-8 - 2/3 column width


####2.4 Icons in Top Bar

Follow the steps below to create an icon menu:

Step 1 - First, select your Icon from DT Icon shortcode, by creating new blank page. Click on DT Shortcode button

![DT Shortcode](http://i.imgur.com/UKsdhuY.png )

Step 2 - Browse the icon and select an icon by clicking on it. Icon class name will be displayed on top of icon picker. Copy the icon class name.

![Browse Icon](http://i.imgur.com/sMX2c27.png)

Step 3 - Navigate to **Appearance > Menus** then  enable **CSS Classes** 
from **Screen Options** panel ( at the top of Menus page ) by ticking it. 

Step 4 - Create **Links** type menu, enter *URL* and *Link Text*

Step 5 - Enter icon-name copied before in step 2 ; in example **icon-social-android8** ( without quotes ) into CSS Classes field. 

Step 6 - Navigate to **Theme Options > Top Bar Settings > Select Left or Right Section > Type Of Element**, select **Icon from Menu**.


___

###2.5 Create Posts

There are eight custom post types in Billio theme.
Standard, Gallery, Image, Quote, Video, Audio, Link and Aside.

Adding Posts

Step 1 - Log in to your WordPress Administration Panel (Dashboard)..

Step 2 - Click the 'Posts' tab.

Step 3 - Click the 'Add New' sub-tab.

Step 4 - Start filling in the blanks: enter your post title in the upper field, and enter your post body content in the main post editing box below it.

Step 5 - As needed, select a category, add tags, fill in the meta setings below the editor.

Step 6 - Select post format on the right hand side and fill in the meta settings below the editor.

Step 7 - It is important to upload a featured image for your post.

####Showing Posts

Simply create a new page, name it as **Blog**, then make sure that you also set the **Posts Page** to Blog under **Appearance > Settings > Readings**.

![Reading Settings](http://i.imgur.com/L8sQubz.png)

___

###2.6 Add Service Items

BIllio has inbuilt support for Service Custom Post Type. Use it to showcase your services.

Add Service Items

Step 1 - Log in to your WordPress Administration Panel (Dashboard).

Step 2 - Click the _Services_ tab.

Step 3 - Click the _Add New_ sub-tab.

Step 4 - Start filling in the blanks: enter your Service title in the upper field.

Step 5 - Make sure you have Backend Editor mode selected. If you have not, you will see **Backend Editor** button appear under Page Title, then click it.

![Backend Editor](http://i.imgur.com/1w34L6u.png)

Step 6 - Click on Templates icon

![Templates](http://i.imgur.com/QQeoRnp.png)

Step 5 - Select **Service Layout**. It might take a while for your machine to render the layout. Please wait and do no interrupt the process.

Step 6 - Once the layout is loaded. Simply replace texts, titles, and images with your own content.

####2.6.1 Showing Services Item

If you have imported 1-Click Demo Import, **All Services** page will be automatically set. If you did not import it, please follow these steps below :

Step 1 - You need to use Essential Grid Plugin in order to list your Service posts. Make sure Essential Grid plugin is installed and activated.

Step 2 - Go to to **Dashboard > Ess. Grid > Import / Export**. Click on **Import** , choose Essential Grid demo file under **Demo Content/Essential Grid**, pick one file based on the theme you are working on, then click Import.

Step 3 - Navigate to **Dashboard > Ess. Grid** , click on the Settings ( green button ) for **All Services**.

Step 4 - Click **Source** tab, select **Post Types** to **Service** and specify **Post Categories**. Leave other settings as is.

Step 5 - Click **Save Grid** green button at top right of the browser window.

Step 6 - Create a new page, select Visual Composer Template named **All Services Layout**. 

Step 7 - Add Visual Composer element named **Essential Grid** to the page.

Step 8 - Choose grid to **All Services** , then hit **Add Selected Grid**.

Step 9 - Publish the page.
___

###2.7 Project / Equipment Posts

Both **Project** and **Equipment** posts use Essential Grid Custom Type Post. To access Essential Grid Posts, navigate to this following url : [your_domain/wp-admin/edit.php?post_type=essential_grid](your_domain/wp-admin/edit.php?post_type=essential_grid). 

We have modified Essential Grid Custom Type Post to allow user to change its name and its permalink. Go to **Settings** sub tab to configure them.

####2.7.1 Add Project / Equipment items gallery

Please, follow the steps below to add project / equipment items

Step 1 - Navigate to this following url : [your_domain/wp-admin/edit.php?post_type=essential_grid](your_domain/wp-admin/edit.php?post_type=essential_grid) then click 'Add New' sub tab.

Step 2 - Enter your Project / Equipment title in the upper field.

Step 3 - Make sure you have Backend Editor mode selected. If you have not, you will see **Backend Editor** button appear under Page Title, then click it.

![Backend Editor](http://i.imgur.com/1w34L6u.png)

Step 4 - Click on Templates icon

![Templates](http://i.imgur.com/QQeoRnp.png)

Step 5 - Select **Project Layout ( or Equipment Layout )**. It might take a while for your machine to render the layout. Please wait and do no interrupt the process.

Step 6 - Once the layout is loaded. Simply replace texts, titles, and images with your own content.

####2.7.2 Showing Project / Equipment items gallery

If you have imported 1-Click Demo Import, **All Services** page will be automatically set. If you did not import it, please follow these steps below :

Step 1 - You need to use Essential Grid Plugin in order to list your Service posts. Make sure Essential Grid plugin is installed and activated.

Step 2 - Go to to **Dashboard > Ess. Grid > Import / Export**. Click on **Import** , choose the Essential Grid demo file under **Demo Content/Essential Grid**, pick one file based on the theme you are working on, then click Import.

Step 3 - Navigate to **Dashboard > Ess. Grid** , click on the Settings ( green button ) for **Projects ( or Equipment)**.

Step 4 - Click **Source** tab, select **Post Types** to **Services ( or any name Post Types** and specify the **Post Categories**. Leave other settings as is.

Step 5 - Click **Save Grid** green button at top right of the browser window.

Step 6 - Choose your grid , then hit **Add Selected Grid**.

Step 9 - Publish the page.

___

###2.8 Add Recruitment Post
Billio comes with DT Recruitment plugin. This plugin is used to handle simple recruitment/vacancy information on website.

####2.8.1 Simple Recruitment Theme Options
After DT Recruitment plugin installed, you will have additional tab named **Simple Recruitment ** on **Theme Options**. Please visit **Appearance > Theme Options > Simple Recruitment ** on Wordpress Dashboard.

![Add Recruitment Post](http://i.imgur.com/EdOhz7U.jpg)

Step 1 - Set **Job Description Fields**. These custom fields will appear on Recruitment Custom Post.

Step 2 - Set **Email Address**. This email address will be used as target email when visitors submit their application forms. If you using multiple email addresses separate them with comma. Leave it email address blank if you want to use 

site's admin email as target email.

Step 3 - Check **Attachment Type**. Select the file type allowed to attach in the application form.

Step 4 - Set **Attachment Size**. Set the maximum attachment file size allowed to attach in the application form in KiloByte.

Step 5 - Set **Application Form Heading Text**. This heading text will appear on application Form.

Step 6 - Set **Email to Friend Form Heading Text**. This heading text will appear "Email to Friend" Form.

Step 7 - Set **Confirmation Message**. This Message will appear when the application has been successfully sent.

####2.8.2 Create a Recruitment post
Do the below steps to create a recruitment post :

Step 1 - Navigate to **Recruitment > Add New** menu.

Step 2 - Enter the title, description, career job fields and choose or create recruitment category.

![Add Recruitment Post](http://i.imgur.com/xDSEQZt.png)

####2.8.3 Display Recruitment Posts on Page.
Do the below steps to display Recruitment Posts on Page :

Step 1 - Create/Update a page.

Step 2 - Add **Recruitment Grid** Visual Composer Element to a row.

![Add Recruitment Post](http://i.imgur.com/EbNkPpL.png)

Step 3 - Set **Recruitment Grid** settings.

![Add Recruitment Post](http://i.imgur.com/IJ3ledQ.png)


___

###2.9 Add Annual Report
Billio comes with Billio Report Post plugin. This plugin is used to handle simple annual report information on website.

![Add Annual Report](http://i.imgur.com/Qkpxmqw.png)

####2.9.1 Create a report post
Do the below steps to create a report post :

Step 1 - Navigate to **Reports > Add New** menu.

Step 2 - Enter the title, description, document options fields, upload featured image and choose or create report category.

![Add Annual Report](http://i.imgur.com/vMPUmBE.png)


####2.9.2 Display Report Posts on Page.
Do the below steps to display Report Posts on Page :

Step 1 - Create/Update a page.

Step 2 - Add **Report List** Visual COmposer Element to a row.

![Add Annual Report](http://i.imgur.com/nhoqFjv.png)

Step 3 - Set **Report List** settings.

![Add Annual Report](http://i.imgur.com/kJbSVFj.png)

___

###2.10 Add Presentation Page
With Billio you could display Powerpoint Presentation or PDF Document on page.

![Add Presentation Page](http://i.imgur.com/hxnLpK0.png)

Do the below steps to display Presentation on Page :

Step 1 - Create/Update a page.

Step 2 - Add **Document Viewer** Visual COmposer Element to a row.

![Add Presentation Page](http://i.imgur.com/7DGepj6.png)

Step 3 - Set **Document Viewer** settings.

![Add Presentation Page](http://i.imgur.com/YCG7jcN.png)


___

###2.11 Replace Highlight Content & Image
Highlight is custom posts that are displayed on frontend page as boxes with button and background image. See image below :

![Replace Highlight Content & Image](http://i.imgur.com/NFyqxWT.jpg)

To replace Highlight Content & Image, please do the below steps :
Step 1 - If you have imported the demo content, you'll find menu **Projects** on Wordpress Admin Area. Visit that menu. 

Step 2 - Edit posts that has **Homepage Higlight** Category.

![Replace Highlight Content & Image](http://i.imgur.com/KG1huOr.png)

Step 3 - Update title, content, and featured image.

![Replace Highlight Content & Image](http://i.imgur.com/lR12GUz.png)

___

#3. Theme Features


###3.1 Billio Theme Options

The theme comes with an extensive Theme Options. You should take the time to go through all of these options to ensure that you are getting the most out of the theme. The Theme Options are located under Appearance > Theme Options.

![Theme Options](http://i.imgur.com/7fjP2RB.png)
___

###3.2 Page Attribute

Billio theme is an ultra customizable theme which can be seen in individual Page Attribute Settings. 

In those settings, you are offered an extensive set of options which will allow you to customize each post, page, service, recruitment, woocommerce etc.

Here you can see the option settings available from Page Attribute parameters. Every setting is pretty self explanatory

![Page Attribute](http://i.imgur.com/4Z6DiDx.png)


___

###3.3 Visual Composer 

Visual Composer is the #1 Selling Frontend and Backend Page Builder out there, you're in for a treat!

Build your content on the go with new WordPress frontend editing option. No more admin panel needed to create stunning and beautiful content blocks.

Visual Composer for WordPress is drag and drop frontend and backend page builder plugin that will save you tons of time working on the site content. You will be able to take full control over your WordPress site, build any layout you can imagine – no programming knowledge required. Moreover, now you can choose either work on a backend or move your page building process to frontend and instantly see changes you make.

Integrating over 50 custom designed shortcode elements, Billio raises the Visual Composer potential. Constructing the pages with the Drag & Drop Manager will cut your work time extremely short.

For Full Visual Composer Documentation visit the following: [Visual Composer Documentation](https://wpbakery.atlassian.net/wiki/display/VC/Visual+Composer+Pagebuilder+for+WordPress)

![Visual Composer](http://i.imgur.com/YsDcPIL.png)

___


###DT Shortcode

![DT Shortcode](http://i.imgur.com/jbyyeKJ.png)

___

###3.4 Font Options

The theme allows you to change font settings easily. You can choose the font family from the provided dropdowns for Body Text Font, Heading Text Font, Section Heading Text Font and Quote Text Font. The Google Fonts are included in the provided dropdowns.

![Font Options](http://i.imgur.com/oTf7d9s.jpg)
___

###3.5 Main Navigation Settings
Billio Theme has 5 options navigation bar layout to choose i.e. Logo on Left, Logo on Center, Logo on Right, Vertical Menu on Left and Static Navigation with post-nav Area.

![Main Navigation Settings](http://i.imgur.com/3jsQi8e.jpg)
___

###3.6 Page Templates
Billio theme comes with 4 Custom Page Templates.

Included Page Templates:

- Default Template
- Blank Template
- Fullwidth
- Woocommerce Page

Default template 
The Default Template offers a standard layout of the page, but still presented in a beautiful way, completely blending in with the rest of the theme. The Default template has option to set sidebar position.

Blank Template 
This is a simple and minimalistic template. Header and Footer are both disabled on this template which allows you to create gorgeus Landing, Coming Soon, Maintenance Pages or 404 page. 

Fullwidth
If you choose this template, the content of the page will be displayed full width with no margin from the edge of the browser window. Usually this template is used as homepage.

Woocommerce Page 
Woocommerce Page Template only available if you have installed WooCommerce Plugin in your WordPress. Woocommerce Page Template looks like Default Template. The difference is Woocommerce Page Template will display Shop Sidebar Widget Area as Sidebar. The Woocommerce Page template has option to set sidebar position.

![Page Templates](http://i.imgur.com/nT8rDBB.jpg)

___

###3.7 Revolution Slider

Billio theme includes the premium plugin - Revolution Slider.
Once you've installed and activated the Revolution Slider plugin (by going to Appearance > Install Plugins), you will then see the menu item appear at the bottom of the WordPress menu, as below:

![Revolution Slider](http://i.imgur.com/iPDET4b.jpg)

To learn Revolution Slider, please read Revolution Slider plugin 
documentation [here](http://themepunch.com/codecanyon/revolution_wp/documentation/).
___

###3.8 Widgets
Billio theme comes with 5 Beautiful Custom Widgets - which are very easy to use.
Access them by going to Appearance > Widgets in your WordPress Dashboard.

Included Widgets:

- DT Accordion
- DT Recent Comments
- DT Recent Post
- DT Tabs
- DT Twitter Slider

![Widgets](http://i.imgur.com/UoujT6E.jpg)
___

###3.9 Recruitments

Recruitments is one of 4 inbuilt custom post types in Billio Theme. Access Recruitments Custom Type by going to Recruitments menu in your WordPress Dashboard.

This Custom Type has it's own set of custom meta settings which enables you to fill Career Jobs Field Information.

![Recruitments](http://i.imgur.com/WKwXEoN.jpg)

You could customize custom meta settings fields by going to  Appearance > Theme Options > Simple Recruitment  in your WordPress Dashboard.

![Recruitments](http://i.imgur.com/uGNEi25.jpg) 
___

###3.10 Annual Reports

Reports is one of 4 inbuilt custom post types in Billio Theme. Access Reports Custom Type by going to Reports menu in your WordPress Dashboard.

This Custom Type has it's own set of custom meta settings which enables you to attach Report File.
 
![Annual Reports](http://i.imgur.com/L0XKFWf.jpg)
___

###3.11 Presentation
This feature gives you a chance to display Power Point Presentation Slides on web page using Document Viewer Visual Composer Element.

![Presentation](http://i.imgur.com/T4e1lyE.jpg)
___

###4.1. Set up One Page

You can create One Page Site with Billio Theme. You do not have to create multiple pages in order to generate the One Page Site, you need to create only one and simply add extra id to row in your page. This is a neat way to put all content on one page and the navigation will scroll directly to the according page section. Like a complete website, with all information on one page. Generating the page is simple as is the custom menu construction.

**Generate One Page Sections**

Step 1 - Navigate to Pages > Add New and fill in the page title.

Step 2 - Add **Row Visual Composer Element** and fill the row with Content.

Step 3 - Edit Row Settings by clicking pencil icon then fill Extra id field with a value for example 'section-1'

Step 4 - Save Row and Page.

![Set up One Page](http://i.imgur.com/CgzeT4i.jpg)

**Generate One Page Navigation**

Step 1 - Navigate to Appearance > Menus and click Create a New Menu.

Step 2 - Open Link item, enter the URL, which is #one-page-section-id (for example: #section-1) and the Title is of your choice. Press Add to Menu

Step 3 - Drag and reorder these generated menu items, add icons to the items until you get the desired navigation layout. Save the Menu.

Step 4 - Scroll down  the menu editor and check Top Navigation check box.

![Set up One Page](http://i.imgur.com/9Xw1auL.jpg)

___

###4.2. Set up download button
It is easy to add a drowpdown download button to a page in Billio Theme.

![Set up download button](http://i.imgur.com/tJuvVE8.png)

Step 1 - Add **Media Download** Visual Composer element to Row and set the button label.

![Set up download button](http://i.imgur.com/b66sjxx.png)

Step 2 - Add **Media** Visual Composer element to **Media Download** Visual Composer element and then set the title and upload the document/media. 

![Set up download button](http://i.imgur.com/syIc1wM.png)

![Set up download button](http://i.imgur.com/4ax77vD.png)
___

###4.3. Set up Fullwidth Background
As default, image background attach to Visual Composer Row element will be displayed to full fill the section. To make it full width the screen, do the below step :

Step 1 - Click **pencil icon** to set Row Settings.

Step 2 - Click **Extended Options** Tab on Row Settings.

Step 3 - Check **Expand Background** check box, save the changes and update the page.

![Set up Fullwidth Background](http://i.imgur.com/0aD92nd.png)
___

###4.4. Set up Fullwidth content
As default, the content will be displayed to full fill the section. 

![Set up Fullwidth content](http://i.imgur.com/HZUIrK4.png)
![Set up Fullwidth content](http://i.imgur.com/jdq4BVj.png)

To make it full width the screen, do the below step :

Step 1 - Click **pencil icon** to set Row Settings.

Step 2 - Click **Extended Options** Tab on Row Settings.

Step 3 - Check **Expand Column** check box, save the changes and update the page.

![Set up Fullwidth content](http://i.imgur.com/YG6VBic.png)
___

###4.5. Set up Different Banner Image for each pages

To make each pages have different banner images do the below steps :

Step 1 - Navigate to Appearance > Theme Options > Banner.

Step 2 - Choose **Page Banner Image** as Background Banner Type then Save the Theme Options.

![Set up Different Banner Image for each pages](http://i.imgur.com/3XSaiN0.png)

Step 3 - Navigate to a page editor.

Step 4 - Choose/Upload an image for Banner Image by clicking **Set Page Banner** link.

![Set up Different Banner Image for each pages](http://i.imgur.com/KGsjLq2.png) 
___

###4.6. Edit Essential Grid Skin

___

###4.7. Hide comment form

It's easy to hide comment form with Billio Theme. Navigate to **Appearance > Theme Options > General**, scroll window to the bottom until you find **Comments Section**.

Under **Comments Section** there are options to turn on/off comments on posts, pages, services, reports, and projects.

![Hide comment form](http://i.imgur.com/AbtUSso.png)
___

###4.8. Set up footer area ( pre and post )
Pre Footer Area is an area upper footer area and Post Footer Area is an area under footer area. Both of this area is created using a single page.

![Set up footer area](http://i.imgur.com/jIc3ONy.png)

Set up pre/post footer area

Step 1 - Navigate to **Page > Add New** then design a page for pre and post footer area.

Step 2 - Navigate to **Appearance > Theme Options > Footer**. 

Step 3 - Turn ON **Pre and Post Footer**.

Step 4 - Select a page for **Pre Footer Page**.

Step 5 - Select a page for **Post Footer Page**.

![Set up footer area](http://i.imgur.com/DtfIKCa.png)
___

###4.9. Set up post navigation area
Post Navigation Area is an area under the main menu. This area is created using a single page and will be displayed only if you choose **Static Navigation with post-nav Area** as Navigation Layout Type.

![Set up post navigation area](http://i.imgur.com/KYaKGJR.jpg)

To Set up post navigation area, do the below steps :

Step 1 - Navigate to **Page > Add New** then design a page.

![Set up post navigation area](http://i.imgur.com/pMf2KZR.png)

Step 2 - Navigate to **Appearance > Theme Options > Main Navigation**. 

Step 3 - Choose **Static Navigation with post-nav Area** as Layout Type.

Step 4 - Turn ON **Show Post Menu Page**.

Step 5 - Choose a page to use as Post Navigation Area by selecting **Select Post Menu** dropdown.

![Set up post navigation area](http://i.imgur.com/hL3FVG1.png)

___

###4.10. Set up video background
To Set up video background, do the below steps :

Step 1 - Navigate to **Pages** then edit a page.

Step 2 - Add Visual Composer Row Element to the page.

Step 3 - Edit Row Settings by clicking pencil icon.

Step 4 - Click Extended Options Tab.

Step 5 - Select Video Background Type.

Step 6 - Add/Upload Video file in mp4 or webm format.

![Set up video background](http://i.imgur.com/BWxKG8V.png)

___

###4.11. Add custom CSS classes
To add custom code to a page, do below steps :

Step 1 - Edit a page and activate Backend Editor.

Step 2 - Click pencil icon to display Settings Window.

Step 3 - Add Extra Class Name or Extra id then Save The Changes.

![Add custom CSS classes](http://i.imgur.com/aqvyLbz.png) 

Step 4 - Click gear icon to display Page Settings Window.

Step 5 - Add CSS Code in Custom CSS Settings Text Area then Save The Changes and Update the page.

The Above way will apply Custom CSS Code to single page only. To apply Custom CSS Code to the whole site, do the below steps :

Step 1 - Navigate to **Appearance > Theme Options > Advanced Settings**.

Step 2 - Type Custom CSS Code in CSS Code Text Area then Save The Changes.

![Add custom CSS classes](http://i.imgur.com/rX8Qd3m.png) 
___

###4.12. Update theme from WordPress dashboard
Before you could update the theme, you must enter purchase number you got from themeforest. Navigate to **Appearance > Theme Options > Theme Information & Update** then enter purchase number and save the changes.

![Update theme from WordPress dashboard](http://i.imgur.com/2I91HYM.png)

To check if any update version of Billio Theme, navigate to **Appearance > Themes**

There will be **Update Available** link on Billio thumbnail if there is any update version.

![Update theme from WordPress dashboard](http://i.imgur.com/YScfogK.png)

Click **Update Available** link then click **update now** link on popup window to start updating the theme.

![Update theme from WordPress dashboard](http://i.imgur.com/KXVR2Cq.png)

___

#5. Credit

- [WordPress](https://wordpress.org/)
- [Bootstrap front-end framework](http://getbootstrap.com/)
- [Jquery Javascript Library](http://jquery.com/)
- [Redux, Simple Options Framework](http://reduxframework.com/)
- [WPBakery Visual Composer](http://wpbakery.com/)
- [Revolution Slider](http://revolution.themepunch.com/)
- [WooCommerce – a free eCommerce toolkit for WordPress](http://www.woothemes.com/woocommerce/)
- [Contact Form 7 Plugin](http://wordpress.org/plugins/contact-form-7/)
- [Essential Grid Plugin](http://essential.themepunch.com/)
- [WPML The WordPress Multilingual Plugin](https://wpml.org/)
- [Easy Google Fonts Plugin](http://wordpress.org/support/plugin/easy-google-fonts)
- [WordPress Importer](http://wordpress.org/plugins/wordpress-importer/)
- [WP Options Importer](https://github.com/alleyinteractive/options-importer)
- [Modernizr Javascript Library](http://modernizr.com/)
- [Icons](www.flaticon.com)
- [Jquery Appear Plugin by Michael Hixson & Alexander Brovikov](https://github.com/bas2k/jquery.appear/)
-[Isotope JQuery Plugin by David DeSandro / Metafizzy](http://isotope.metafizzy.co)
- [Jquery Validation Plugin by Jörn Zaefferer](http://bassistance.de/jquery-plugins/jquery-plugin-validation/)
- [uisearch.js, cbpTooltipMenu.js, modalEffects.js, Slide Blur, Icon Hover Effects by Codrops](http://www.http://tympanus.net/codrops.com)
- [Chart.js by Nick Downie](http://chartjs.org/)
- [“Shades of Grey” Google Maps Style by Adam Krogh](http://snazzymaps.com/style/38/shades-of-grey)
- [Owl Carousel](http://www.owlgraphic.com/owlcarousel/)
- [Styleable select elements](http://github.hubspot.com/select/docs/welcome/)
- [Reset CSS](http://meyerweb.com/eric/tools/css/reset/)
- [Responsive CSS3 Multi-Level Menu](http://fofwebdesign.co.uk/freebies_for_websites/css/multi-rwd-menu-js.htm)
- [jQuery Tweetie – Simple Twitter Feed Plugin that works with new Twitter 1.1 API](https://github.com/sonnyt/Tweetie)
- [Share Button](http://sharebutton.co/)
- [QueryLoader2 – Preload your images with ease](http://www.gayadesign.com/diy/queryloader2-preload-your-images-with-ease/)
- [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
- [Animated mouse scroll]( http://codepen.io/Ioana/pen/abomd)
