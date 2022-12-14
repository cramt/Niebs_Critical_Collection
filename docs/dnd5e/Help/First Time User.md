#Help
If this is your first time using Wikidot, then you've come to the right place.  Whether you are familiar with web development or not, coming to understand Wikidot's modules or page structure will greatly aid you as you bring your website to life.

We want to ease the learning curve so that you can become comfortable with the interface.  This tutorial will by no means cover everything Wikidot offers, but we hope it will spark a curiosity.

[[dnd5e/[toc\|]]]

# Editing Pages

At the bottom of every page, you should see a row of buttons.  Each of these buttons corresponds to an action related to the page you are on.  If you click the Edit button, it will take you into an editing window that reveals the source code of the page.

If you cloned this template, then try editing this page now and see if you can find a hidden paragraph under this one.

[[dnd5e/[div\|class="alert alert-info"]]]

[[dnd5e/!\|THIS IS THE HIDDEN PARAGRAPH.  As you see, this paragraph does not appear on the actual page.  That's because its encased in an invisible text syntax.  What happens if you remove the [!-- located at the beginning of this paragraph?  Try that, then hit the save button below. --]]

[[dnd5e/Div\|]]]

If you did the exercise exactly as written, you will find that only part of the paragraph appears.  If you understand why that is, then you're on your way to becoming a syntax expert!  Go ahead and click the button below if you want clarification.

[[dnd5e/[collapsible\|show="Show me!" hide="Hide me!" class="btn btn-default"]]]

[[dnd5e/[div\|class="row"]]]
[[dnd5e/[div\|class="col-md-6"]]]
[[dnd5e/[include\|:snippets:bs-image
|image=http:*css.wikidot.com/local--files/csi:help-first-time-user/wd_beforeEdit.png
|heading=Before Edit
|caption=The comment encompasses the entire passage.
]]]
[[dnd5e/Div\|]]]
[[dnd5e/[div\|class="col-md-6"]]]
[[dnd5e/[include\|:snippets:bs-image
|image=http:*css.wikidot.com/local--files/csi:help-first-time-user/wd_afterEdit.png
|heading=After Edit
|caption=The initial comment was removed, but look!  It begins again later.
]]]
[[dnd5e/Div\|]]]
[[dnd5e/Div\|]]]

[[dnd5e/Collapsible\|]]]

--------

You may have noticed a toolbar when editing the page.  This toolbar can assist you in creating **bold** and other styled texts, though you can also consult the [[dnd5e/[[help/Quick Reference|quick\|Reference]]]] as well.

For more on page editing, see [[dnd5e/[[help/Editing Pages|editing\|Pages]]]].

# Creating New Pages

Perhaps the most important thing you will be doing when building your site is creating new pages.  The Standard Template gives you a module located on the sidebar that allows you to create pages rather easily, though there are a couple of things you might want to know before starting.

## Non-existent Pages

Firstly, if you **[[dnd5e/[[*demo/Create Page|click\|on this link]]]]**, you will see what happens when a user attempts to visit a non-existent page.  If you click where it says "create page", it will bring you to an editing screen where you may place the initial contents of the page.

## Categories

Next, it is important to discuss the topic of **page categories**.  Every page has a *pagename* and a *title*.  The title is what you see on this page, whereas the pagename is what is encoded in the URL.  For this page, the title is "First Time User", and the pagename is "help:first-time-user".  Note that these need not match!

When you enter the name of a page into the module in the sidebar, you will create a page that, by default, has a pagename and a title that are the same.  For example, if you type "First Page" into the form, you will get a page called "First Page" with a pagename "first-page".

[[dnd5e/[div\|class="alert alert-warning"]]]
Notice the difference between that newly created pagename and the pagename of this page.  This page's name has a special prefix, "help:".  The *help* is called the page's **category**, and the colon separates the category from the name.  The "first-page" page, unfortunately, does not have a category.
[[dnd5e/Div\|]]]

Categories are extremely useful for organizing the pages in your website.  After you've been working for a year, you may find, for instance, that you have a couple hundred pages.  These pages, however, may be blog posts, info pages and so on.  If you don't use categories, these pages will not be distinct.  You can use categories, however, to separate the kinds of pages (ie. "blog:" and "info:").

A variety of Wikidot tools and modules natively account for categories, and hence it is a very good practice to get into the habit of using categories when creating pages.  In order to give a page a category when using the form in the sidebar, simply put the category name followed by a colon like you see above!

For more info, see [[dnd5e/[[help/Creating Pages|creating\|Pages]]]]

# Modules

Let's see an application of using categories with pages.  Wikidot has a handy tool called the ListPages module that does what it says: lists pages.  For example, let's say that you wanted to create a list of all the help pages on this site.

One way you could do this is by going through every page and seeing whether it is a help page or not and then manually form a bulleted list like so:

[[dnd5e/[div\|class="row"]]]
[[dnd5e/[div\|class="col-sm-6"]]]
* First Time User
* Editing Pages
* ?????
[[dnd5e/Div\|]]]
[[dnd5e/[div\|class="col-sm-6"]]]
[[dnd5e/[code\|]]]
* First Time User
* Editing Pages
* ?????
[[dnd5e/Code\|]]]
[[dnd5e/Div\|]]]
[[dnd5e/Div\|]]]

But then, you always have to ask.  What if you missed one?  What if you create another page in the future and forget to update the list?  Even worse, what if you had many lists like this scattered throughout the site, and you had to update them all?  If only there were an easier way!  Well...

[[dnd5e/[div\|class="alert alert-success"]]]
The ListPages module will automatically list pages given criteria.
[[dnd5e/Div\|]]]

It's automatic.  All the work is done for you.  You don't have to worry about missing a page because the module will find them for you.  Furthermore, if you add a page latter, the output of the ListPages module will update accordingly.

Therefore, it is as simple as:

[[dnd5e/[div\|class="row"]]]
[[dnd5e/[div\|class="col-sm-6"]]]
[[dnd5e/[module\|ListPages category="help" separate="false"]]]
* %%title%%
[[dnd5e/Module\|]]]
[[dnd5e/Div\|]]]
[[dnd5e/[div\|class="col-sm-6"]]]
[[dnd5e/[code\|]]]
[[dnd5e/[module\|ListPages category="help" separate="false"]]]
* %%title%%
[[dnd5e/Module\|]]]
[[dnd5e/Code\|]]]
[[dnd5e/Div\|]]]
[[dnd5e/Div\|]]]

And as you can see, all the help pages are automatically listed.

[[dnd5e/[div\|class="alert alert-info"]]]
Note that this could only be done because all the help pages were in the "help" category!
[[dnd5e/Div\|]]]

Of course, ListPages is capable of searching for a variety of things, like date created, author, tags, and so on.  Furthermore, Wikidot has multiple different modules that can make a wide range of tasks simpler.  This page only gives you a taste of what is possible.  For more, visit the [[dnd5e/[[help/Using Modules|using\|Modules]]]] help page and Wikidot's [[dnd5e/Doc Modules/Start\|Documentation]].

# Good luck!

Although there is much more to Wikidot, we hope that this overview gives you enough understanding to begin building your site.  Be sure to consult the [[dnd5e/[[help/_home|user\|Guide]]]] for an official start up guide.  Furthermore, explore the help pages below for more info about each topic.

[[dnd5e/[module\|ListPages category="help" separate="false" order="title" tags="-_deleted"]]]
* %%title_linked%%
[[dnd5e/Module\|]]]

Finally, if you have any questions, do not be afraid to pose a question on the [[dnd5e/Community.wikidot.com\|Community Forums]].  Wikidot experts are almost always available to help out with queries you may have.