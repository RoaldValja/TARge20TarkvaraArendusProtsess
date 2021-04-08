# Coming Soon
## Purpose

Coming Soon web page should display a countdown towards the release date of this page.

## User personas

* Customer
* Developer
* Owner

## User stories

* Customer checks the web page for when the site is ready for use.
* Developer checks the web page to know how much time he has to finish the features.
* Owner checks the web page to know when he can promote the new site.

## Website structure

* [Home Page](../index.html)
    * [Models Page](../models/models.html)
    * [UML Page](../uml/umls.html)
    * [ERD Page](../erd/erd.html)
    * [Git and GitHub](../git/git-notes.html)
    * [Coming Soon](index.html)

## Page description

Web page displays the logo, title of the page, a paragraph telling that its coming soon and shows how much time is left until the page gets released. Time is seperated into days, hours, minutes and seconds.
If the web page timer reaches 0 and the page hasn't been updated yet, it should display 'Released' in plain text.

## Wireframes

* Widescreen layout
    * Logo should be at the top center of the screen.
    * Title and coming soon text should be below the logo.
    * Days, hours, minutes and seconds blocks should be below coming soon and be situated next to each other in the same order.
* 650 pixels wide layout
    * Logo resizes with browser width.
    * timer displays only days.
* 600 pixels high layout
    * Title disappears.
* 400 pixels high layout
    * Coming soon text disappears.

## Non-functional requirements
* Responsive design with specific width and height of browser.
* Support every browser.
* Be able to handle 100 visitors at a time.