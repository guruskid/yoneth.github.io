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
Highlight is custom posts that are displayed on frontend page as boxes with button and background image. See below image :
![Replace Highlight Content & Image](http://i.imgur.com/NFyqxWT.jpg)

To replace Highlight Content & Image, please do the below steps :
Step 1 - If you have imported the demo content, you'll find menu **Projects** on Wordpress Admin Area. Visit that menu. 

Step 2 - Edit posts that has **Homepage Higlight** Category.

![Replace Highlight Content & Image](http://i.imgur.com/KG1huOr.png)

Step 3 - Update title, content, and featured image.

![Replace Highlight Content & Image](http://i.imgur.com/lR12GUz.png)
