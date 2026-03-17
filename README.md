This plugin adds a mini-calendar to your forum, which can be displayed in the forum's header (or footer).

The full annual calendar can be accessed via `inplaykalender.php`. Past or future years (e.g., 2020) can be accessed via `inplaykalender.php?y=2020`.

<h1>Features</h1>

<ul>
<li> Display of information from the Inplaytracker 3.0
<li> Display of information from the Plottracker
<li> Display of birthdays
<li> Addition of custom events [e.g., users can add events like parties that aren't "significant" enough to be a full plot]
<li> Permission management to determine which user groups can add events
<li> Color-coded display of events in the header, including a legend within the calendar
<li> Dedicated page: `inplaykalender.php`
<li> Configuration of the in-game year and active months via the Admin CP
</ul>

<h1>New Templates</h1>
The following new templates are added; you can find them within the global templates:

<ul>
<li>header_inplaykalender
<li>header_inplaykalender_bit
<li>inplaykalender
<li>inplaykalender_add
<li>inplaykalender_day_bit
<li>inplaykalender_day_bit_popup
<li>inplaykalender_month_bit
<li>inplaykalender_nav
<li>inplaykalender_nav_add
<li>inplaykalender_no_day_bit
</ul>

<h1>Template Modifications</h1>
The variable `{$header_inplaykalender}` is added to the header template. This displays the calendar at the top of the header.

<h1>New CSS</h1>
An `inplaykalender.css` file is added to all of your themes. <h1>Demo</h1>

<center>
<a href="https://snipboard.io/7IUOre.jpg"><img src="https://snipboard.io/7IUOre.jpg" /></a>

<img src="https://snipboard.io/97UJLk.jpg" />

<img src="https://snipboard.io/HRA2cE.jpg" />

<a href="https://belle.eightletters.de">Live Demo</a></center>

<h1>Entering the In-Play Period</h1>
You can enter the in-play period in the ACP under <b>Configuration &bull; In-Play Calendar Settings</b>. List your game months separated by commas (with no spaces in between)! Entering this information correctly is <b>very important</b>. <br /><br />

What if your game spans a New Year? For example, if you are playing in November and December of 2020, but also in January of 2021? It's quite simple: you can also specify in-play months as follows: <b>November 2020,December 2020,Januar 2021</b> (again, no spaces between the commas here!). From now on, the calendar displayed on the main calendar page (inplaykalender.php) will always show the specific year you have entered as your game year in the ACP.

You can choose to display as many months as you like—though I recommend a maximum of three. ;)

Enjoy!
