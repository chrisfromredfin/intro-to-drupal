# Intro to Drupal

Christopher J. Wells  
Redfin Solutions, LLC

---

# Agenda

1. What's a Drupal?
1. Lesson
1. Play
1. Lesson
1. Play

_repeat ad nauseum_

--

<img class="secondary" src="https://en.gravatar.com/userimage/45857937/d42cf9e078d9582683fb05a648c0764e.jpg?size=100">
## Who's this guy?

* Drupal developer since Drupal 4.7 (2005-ish)
* Company only does Drupal development
* Master's in Technology Education (Adult)
* Taught web development at the good ASU

---

# What's a Drupal?

<img src="https://www.drupal.org/files/druplicon-small.png">

--

## Brief History

* Dries Buytaert
* Dorp -> Drop -> Drupal
* "Open Source" project
* Acquia

--

## Core Concepts

* Drupal is a web-based CMS
* Drupal is "modular"
* Drupal is "presentation agnostic"
* Drupal is a community

--

## Web Concepts

_Getting a web page in your browser is harder than you think!_

* Browser makes the request
* Server interprets it
  * may ask a data store for additional data
* Sends back HTML
* HTML is "rendered" ("painted") by your browser

--

## Content

* **node** - a piece of content, but not _necessarily_ a "web page"
* Nodes must be of a **type** - two default types
  * Article
  * Page
* **fields** - extend the definition of a node type
* **views** - collect content together into lists

--

## Modularity 

<img width="33%" src="https://www.gtplanet.net/wp-content/uploads/2017/10/lego-14-860x484.png">  
NOT  
<img width="33%" src="https://cdna1.zoeysite.com/Adzpo594RQGDpLcjBynL1z/cache=expiry:31536000/compress/https://s3.amazonaws.com/zcom-media/sites/a0i0L00000UTMXWQA5/media/catalog/product/u/s/us-toy-tmp-images-catalog-products-m-a-mat30782211.jpg">

--

## Drupal Modules

* Drupal **Core** - what you get when you download Drupal.
  * Required Modules
  * Optional (Core) Modules

* Drupal **Contrib**
  * Third-party, community-supported

<img width="100" height="100" src="https://project.inria.fr/peach/files/2016/03/peach_pic1.png">

--

## Important Core Modules

* **taxonomy** - allows categorization of content (tags)
* **menu** - lets you build menu trees
* **alias** - lets you reassign the URL's for pages
* **block** - puts a box of something on your site (in a **region**)
* **image style** - automatically adjusts images

--

## Things in "Contrib"

* Audio/Video
* Social media
* Permissioned sections / content
* Publishing workflows
* Presentational components

_Many things start in contrib and then get moved into core._

--

## Presentation

* Drupal doesn't care how content _looks_
* Uses pluggable "theme system"
* A **theme** is a collection of files which determine how content will look
* HTML, CSS, _some_ PHP, and a templating language called Twig.

<div class="thumbrow">
  <img width="100" height="100" src="https://project.inria.fr/peach/files/2016/03/peach_pic1.png">
  <img width="100" height="100" src="https://purepng.com/public/uploads/large/purepng.com-plumplumgenus-prunuspeachescherriesbird-cherries-17015273586221b7ko.png">
  <img width="100" height="100" src="data:image/jpeg;base64,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">
</div>

--

<img width="50%" src="https://ssmscdn.yp.ca/image/resize/0066e981-6582-4ba9-b30b-f0f386f6a4f2/ypui-d-mp-pic-gal-lg/stork-s-early-years-child-care-center-2.jpg">
## Where do themes come from?

--

## Community

<img width="70%" src="https://events.drupal.org/sites/default/files/styles/grid_block_image/public/edition_baltimore_0.jpg?itok=3y-Hy1X2">  
_Around 3000 people convene each year in North America for DrupalCon. Other DrupalCons are held in Europe and Asia._  
https://www.drupal.org/association/drupalcon/locations

---

# Hands On

* Drupal is a LAMP/WIMP-based technology.
  * operating system (Linux, Windows)
  * web server (Apache, IIS)
  * database (MySQL)
  * programming language (PHP)

--

# Stack Starter

https://stackstarter.io/spin

# <span style="text-transform: lowercase">unh</span>
is your _spin code_

--

# Get Logged In

# <span style="text-transform: lowercase">admin / test</span>
are your _Drupal login credentials_


--

# Your first content management

TASK: Change your site name to "Adopt-a-Pet, Ltd."

1. go to "Configuration" in top menu
1. go to "Basic site settings"
1. change the site name (and email if desired)

--

# Content CRUD

TASK: Create the "about" page for your site.

<ul class='fragment fade-up'>
<li> go to content in top menu
<li> go to add content
<li> add a new 'basic page'
<li> fill out the fields<ul>
  <li>Title and Body
  <li>Menu settings
  <li>URL alias</ul>
</ul>

--

## Regions and Blocks

<img width="70%" src="https://static.vecteezy.com/system/resources/previews/000/121/909/non_2x/vector-old-newspaper.jpg">

TASK: add a footer block to your site

--

# Moar Typez!

In addition to the brochure functionality, let's build a database of available, adoptable pets. 

TASK: Create a content type for "pet"
* Name (rename the node "title" field)
* Age (integer)
* Description (Body)
* Image

http://unsplash.com

--

# Taxonomy

We will always want to categorize things, Drupal or not.

* TASK: add a "tags-based" categorization to your pets
* TASK: add a "pet type" categorization to your pets  
  {dog, cat, reptile}

This requires (a) a new vocabulary to be created, and (b) a new field on your "pet" type which references that vocab.

--

# Gussy it up

* TASK: Create an image style
* TASK: Model the display of a "pet" appropriately  
  (use your image style)

--

# Contact Forms

* TASK: create a new contact form  
  to get more information about a pet
* additionally asks for:
  * the pet's name (short text)
  * a good callback phone number (short text)
  * other pets you have, special considerations, etc  
    (long plain text)
* form should
  * send to pets@example.com

--

# Modules

Core is great, but we can add some quick wins.

* TASK: add a module called <em>admin_toolbar</em>
* TASK: add a module called _devel_
  * enable <em>devel_generate</em> and generate 50 "pets"
* TASK: add a module called _captcha_
  * protect your contact forms with a captcha

--

# Themes

Let's change our skin!

* TASK: change your theme
* you will need to reconfigure your blocks  
  (they are per-theme)
* there may be theme settings for you to adjust
* if you can't decide, try _kaziranga_!
* there may be a **base theme** it depends on

--

# Views

This site is nothing if you can't browse the available pets.

* TASK: build a "news" view (articles, newest first)
* TASK: build a view to show available pets
  * "featured" pets at the top
  * then pets who've been there the longest,  
    sorted to most recent

--

# Menus

* TASK: update the menu
  * About | Pets | News | Contact

--

# Roles and Permissions

* TASK: create a role for 'manager'
  * they can only manage the pets, not other content
* TASK: create a role for 'blogger'
  * they can only manage the news, not other content
* TASK: create a user who has some or all of these roles

--

# BONUS: Landing Pages / Home

There's a new paradigm of entities in Drupal,  
which are unfortunately known as "paragraphs."

The name doesn't do them justice.

---

# Reach Out

<img class="secondary" src="https://en.gravatar.com/userimage/45857937/d42cf9e078d9582683fb05a648c0764e.jpg?size=100">

* chris@redfinsolutions.com
* github.com/chrisfromredfin
* twitter.com/sceo
* 908-4DRUPAL
* https://redfinsolutions.com
