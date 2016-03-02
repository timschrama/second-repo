% CV Tim Schrama
% 
% February 2016

![](https://www.facebook.com/photo.php?fbid=10205321363529806&set=a.1442359415200.2056842.1119510934&type=3&theater)

Personalia
===============

----        	---------------------------
Naam         	Tim Schrama
Adres        	Helmondsingel 160
Postcode     	5709 AG Helmond
Nationaliteit	Nederlands
Geboortedatum 	27-04-1994
Geboorteplaats	Geldrop
Geslacht     	Man
Burgelijke staat	Ongehuwd
Telefoonnummer  +31 6 27881771
E-mailadres  	timschrama1994@hotmail.com	
Rijbewijs    	Personenauto (B)
----        	--------------------------------

- - -

Opleidingen
==================

* September 2015 - heden
	* [WO Master Economics, behavioral economics track](https://www.tilburguniversity.edu/nl/onderwijs/masteropleidingen/economics/program/behavioral-economics/)
		* [Tilburg university](www.uvt.nl), Tilburg

* September 2012 - September 2015
	* [WO Bachelor economics](https://www.tilburguniversity.edu/nl/onderwijs/bacheloropleidingen/economics/) (Behaald)
		* [Tilburg university](www.uvt.nl), Tilburg

* September 2006 - Juni 2012
	* Atheneum (Behaald)
		* [Peellandcollege](http://www.ivo-deurne.nl/news.aspx?pid=5), Deurne

- - -

Overig
===============

* Talen
	* Nederlands (Vloeiend)
	* Engels (Goed)
	* Spaans (Redelijk)

* Hobby's
	* Hardlopen
	* Lezen
	* Lekker eten

- - -

Werkervaring
=================

* Juli 2009 - Heden
	* [Jumbo Brouwhorst](https://www.jumbo.com/content/jumbo-helmond-brouwhorst/), voorheen C1000 en Super de boer Ron Hendrikx
		* Vulploegmedewerker
		* Magazijn verantwoordelijke
		* Vulploegleider / avondverantwoordelijke

* Juli 2010 - Juli 2013 
	* [Elkerliek ziekenhuis Helmond](http://www.elkerliek.nl/Elkerliek)
		* Logistiek

## Level 2

With Pandoc's `--section-divs` option, nested header levels 
create nested DIVs. This stylesheet creates nested indentation 
for them to nest visually.

### Level 3

I should create some auxiliary CSS files that you could include 
after `buttondown.css` to change some things like turning off 
nested indenting.

#### Level 4

Buttondown doesn't re-define the font size or weight of the 
headers, but it does define the font families for them as sans-
serf.

##### Level 5

It doesn't re-define the body text font, and it doesn't make 
the text body narrow --- it leaves it full width. I will probably 
add a style option file for that.

###### Level 6

Level 6 can be quite small.


Lists
=====

Unordered lists
---------------

### A simple list:

Text before

* Alpha
* Beta
* Gamma

Text after

### A nested list:

* Alpha
    * Apple
    * Orange
* Beta
    - A multi-line item to show  
      where the wrapping and sublist line up.
        - Earth
        - Moon
    - Pineapple
* Gamma (with numbered sublist)
    1. One
    2. Two

### A paragraph spaced one:

Not all stylesheets make these have more spacing.

* Alpha

* Beta

* Gamma

And the spacing after might be too tight.

Ordered lists
-------------

### A simple one:

1. One
2. Two
3. Three

### A nested one:

1. One
    1. Alpha
    2. Beta
2. Two (with unordered sublist)
    * Gamma
    * Delta
3. Three
    1. Apple
        1. Circle
        2. Triangle
            1. North
                1. East
                2. West
            2. South
                * Up
                * Down
        3. Square
    1. Orange


Block Quotes
============

We simply italicize them and don't do any fancy quote bar or decoration 
since they are already indented on the left and right.

> We simply italicize them and don't do any fancy quote bar or decoration 
since they are already indented on the left and right.


Code
====

Code blocks are styled more to be set apart a bit more than just the monospaced 
font. A light background color and border (in case the background doesn't print, 
but it looks nice too).

	x = e * 10 / 2;
	y = p - 7;

On screen, the blocks provide scroll boxes and the `inline code spans` 
word wrap. For print, the code blocks also change to word wrap. On screen, the 
`code spans` also get a little border, but lose it in print.

Links
=====

Remove the underline except on hover. When printing, remove all styling and 
print external URLs after the link text to be useful in a printout. There is no 
filter to not print very long URLs though.

A link to [Google][]. A simple link to <http://wikipedia.org>.

I haven't figured out how to not redundantly print the URL after a simple link 
whose link text is the URL.

[Google]: http://www.google.com

Horizontal rule
===============

A thin line that doesn't have that shadow thing that looks terrible, especially 
in print. 

- - -

See the end for what footnotes looks like[^1].

[^1]: A double-line rule with the word "NOTES" in the center.

Images
======

An inline image ![](http://www.jodypaul.com/gr/altair8800Thumb.gif "www.jodypaul.com").

A Pandoc figure style image with caption:

![Daring Fireball][DFlogo]

[DFlogo]: http://daringfireball.net/graphics/logos/ "Daring Fireball!"


Definition Lists
================

Still may tweak this. Trying to use subtle lines to help group it, but it feels 
a bit too table-like. However, without them, it doesn't seem to stand out much.

Term

:   Definition of the term

Term2

:   First definition of Term2
    It can be a long, wrapped paragraph like this.
    
    A definition can include multiple paragraphs if they are indented
    the same in Pandoc and MultiMarkdown 3. MultiMarkdown 2 doesn't
    support this, so it will be interpreted there as a code block
    following the Term2 definition.
    
    - They can also include Markdown
    - If it supports multiple paragraphs, a definition can contain lists and things
    - But the first has to start as a regular paragraph

Term3

:   A term can have multiple definitions. 

:   The second definition of Term3. Depending on the stylesheet for HTML
    you are using or the output format (LaTeX, etc.), this second
    definition may appear styled as a separate term but without the term
    itself.


Tables
======

These get more styling than most things, yet it's still very little compared to 
most table stylings, but way better than an un-styled HTML table. It's to emulate 
a simple textbook style, but we throw in a hover row highlight to be a little 
useful on-screen when scrubbing around the table.

  Right     Left     Center     Default
-------     ------ ----------   -------
     12     12        12            12
    123     123       123          123
      1     1          1             1

Table:  Demonstration of simple table syntax.
