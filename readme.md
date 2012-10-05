# Hi!

- hello everyone from the cfa summit! this is the repo for sheetsee.js - it's a work in progress, the fellowship isn't over yet! I'll be cleaning it up, making it better and doing documentation in the next few weeks. You can also go to the repo for the Wordpress theme to see its usage there, [see penny work theme](http://github.com/codeforamerica/wp-splost)

Sheetsee.js is a javascript library mashup that allows you to manage visualized web content through Google Spreadsheets. 

The web content and visualizations will update with every auto save by Google. That's cool. No pushing or uploading changes. 

![diagram](https://raw.github.com/jllord/sheetsee.js/master/images/sheetsee_diagram.png)

### Set it and forget it. 

Once you've hooked it up, all you'll need to interact with is the spreadsheet. Think of it as a super simple CMS. 

You can view a working sample of the bits in action at [jllord.github.com/sheetsee.js/](http://jllord.github.com/sheetsee.js/)

## The bits*

It all starts with [tabletop.js](http://builtbybalance.com/Tabletop/). With that you can pile on any other library to style and visualize your data. 

You can feed [raphael.js](http://raphaeljs.com/) the data it needs to make pie charts. 

You can feed [leaflet.js](http://leaflet.cloudmade.com/) the data it needs to make maps.

Use [mustache.js](http://mustache.github.com/) to create templates for the data in your spreadsheet.

*d3 would be awesome to use, too! I'm not using it right now because I need the visualizations to work in IE6. Yeah. I know. See next section. 


## What's it all for?

I'm creating a bond referendum [budget website](http://splost.codeforamerica.org) for the City of Macon as a part of my [Code for America](http://www.codeforamerica.org) fellowship. The project is called [See Penny Work](http://www.seepennywork.in). The site will open up this information to residents. The site is built on Wordpress and will visualize the budget with sheetsee.js. The city's budget staff will be able to make changes to the budget through the linked Google spreadsheet. 

I'll also be making a website to curate hackathon apps for cities with [mishmosh](https://github.com/mishmosh) using sheetsee.js to handle all data in an easy-to-contribute-for-all kind of way. More details soon! 

## More on how to set it up

I know, I know. It will come - most definitely before November 16th (end of the CfA fellowship year).

## License 

This repo is BSD Licensed, read more in [license.md](https://github.com/jllord/sheetsee.js/blob/master/license.md).

<<<<<<< HEAD
=======
# Updates

### 4 Oct 2012

I merged gh-pages with the master branch because gh-pages was more current and master was more out of date experimental bits. 

>>>>>>> e975c3e65604a29f05453b3cf9131d6c46a32d63




