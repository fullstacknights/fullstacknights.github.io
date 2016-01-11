# Fullstack Nights Site

This is the official home for Fullstack Nights.

We are using a modified Jekyll theme based on [Freelancer bootstrap theme ](http://startbootstrap.com/templates/freelancer/). Please visit their site for more information on the theme and how to use it.

## What to change for next meetups?

Most of the changes are going to be done in the _config.yml file:

* **active_meetup**: This will be used as a toggle for the Eventbrite form widget (or any other ticketing service). It basically substitutes the tickets.hmtl for the newsletter.html.
* **sub_header**: the sites sub-header/sub-title. Basically a catchphrase or motto.
* **google_analytics**
    * **id**: if we ever want to change the Google Analytics account a simple swap of this setting should do it.
* **eventbrite**
    * **ticket\_form\_widget**: for each event we will have a new widget, just change the html here and it'll be taken care of.
* **social**: a list of the social networks/accounts of Fullstack Nights
* **address**: the physical address of the venue.
* **team**:
    * **description**: a simple description of the team.
    * **members**: a list of all the team members. If the team ever changes then this is the place to change it. The team.html consumes this list to display the team members pic, name, and social networks.
        * **name**: team member name
        * **img**: path to member pic
        * **social**: a list of all the social networks the team member wants displayed.

=========

For more details, read the [documentation](http://jekyllrb.com/)
