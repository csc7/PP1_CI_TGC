# TGC - The Green Company
This repository belongs to my first milestone project in the Full-stack Development course at Code Institute, covering HTML and CSS along with Git version control and other design tools.

The live link for this projects is [this one](https://csc7.github.io/PP1_CI_TGC/)

# Project Goals
The goals of the project is to develop a website for a company that provides several geophysical services for diverse projects in the curren energy transition towards greener energies and less CO2 emissions.

Specifically, the goals are the following ones:
* To show all services that the company offers.
* To offer the company a simple way of being contacted.
* To offer the company a simple way of selling services.
* To provide users a clear view of the services available.
* To provide users a simple way of requesting services.
* to provide users a simple way of contacting the company.

# User Goals
* A website where navigation is easy and intuitive.
* Capability of show the same information, in the same easy and intuitive way, in different devices and screen sizes.
* Rather than a description of the service, a fast way of requesting the service.
* A simple way of contacting the company.
* An option where a user is able to give personal details while keeping the decision of opting out of marketing communications. 

# User Stories
* "Our wind energy company is small in size and benefits from flexible procedures for contracting services; we want a website like the one of The Green Company that offers them with a quick way of contracting, so that we can address our project requests very quickly and agilely".
* "We are a manpower company that needs to respond to client requests as quick as possible, with as many services as possible; we see The Green Company's website a convenient way to select and hire different types of geophysical services".
* "I am a consultant who sometimes needs to build dedicated teams to address service requests for specific projects (most of them in the study of grounds for solar projects); I see The Green Company as an excellent way to get information about available services without the need of going through long processes and without the need of exchanging personal data (which many times is confidential due to the nature of the projects I work in)".
* "Our company deals with many energy projects (most of then in the geothermal and eolic energy spectrum) and we find the website of The Green Company a quick and convenient way of having a summary of most required services, with the additional benefit of contracting them directly".

# Site Owner Goals
* To show all services that the company offers in a summarised way.
* To offer a quick way to contract services (to add value when compared to other companies and to increase chances of capturing clients not fully decided).
* To receive consultations from potential clients.
* To capture clients.
* To sell services.
* To show in the home page an introduction and a few words about what the company is.
* To show another page with a brief description of the company.
* To show another page with the services that the company is able to offer.
* To provide a simple contact form where the client feels that privacy is respected.
* To offer a quick call to action, through a button, to contract services.

# User Requirements and Expectations
* To find a website that summarises as many geophysical services as possible.
* To have the option to contact the company without getting into complex processes, while mantaining the option to avoid unsolicited marketing communications.
* To be able to easily contact services if needed.
* To easily find basic information, location, contact details, and social media information of the company.

UX:\
STRATEGY\
SCOPE\
STRUCTURE\
SKELETON\
SURFACE\

# Design Choices
EXPLAIN
# Colors
Green is the main color of the project. The reason for this selection is to be in line with the nature of the company (whose services are focused in the current transition energy) and with the name of the company: The Green Company.
The background color is azure in order to have contrast with the content of the website while keeping the green-color tendency of the design.
# Fonts
Google fonts, https://fonts.google.com/, were implemented in the website. Roboto was selected for the paragraph as it is modern and easy to read. Following Google's recommendations, Baloo Tammudu 2 was also selected as complement for the titles.\
Arial font is used as a back-up in case the previous fonts cannot be loaded.\
Color #003300 (dark green) was selected for the body in order to have strong contrast with the white background of the body.\
To differentiate the navigation menu and the request service button,  #135f13 (different dark green) is selected; while #276609 is selected to highlight all headings.\
The name of the company in the logo uses #73ac3e to have a unique color.
# Structure
Following expectations of the owner, the metadata includes the following keywords to help search engines to find the website: geophysics, services, modelling, acquisition, processing, wind, geothermal, carbon, capture, CO2, operations. In addition, to help find the developer and this project, the following keywords are added: Code Institute, software development, student, full-stack course, milestone project.

In order to achive the goals related to easiness and/or simplicity, a navigation area in the header is provided. In the same area, the company's logo is place to the left, and a "quick" button to request services on the right, so users are able to contract services in a very fast way.

This "quick" button, whose name is "Request Service", pops up a modal form where the user is able to contract specific services.

The body of the pages are structured as follows for each of the pages:
* Home: it contains an environmental-friendly background video with a slogan of the company and the services it offers.\
To keep navigation simple, this page is designed to fit in a screen of 1024x768 pixels withough having to scroll with the mouse.
* About Us: it has an upper section, divided in three subsections, where a picture, title and text for the following items are allocated: Mission, Values and Vision. In order to keep symmetry as accurate as possible, Values (which are shown in a list) are located in the middle.\
This section is followed, downwards, by another section (which lies in the middle of the body) that contains a table with the projects of the company.\
Finally, at the bottom of the body, there is another section that contains a table that shows the amount of people per department in the company.\
The desined is carried out for a screen size of 1024x1536 pixels (double in vertical lenght than the home page).
* Our services: it contains pictures, titles and text for each of the services being provided by the company. They are structured in a 4x4 arrange for desktop presentation, 2x8 for tablets, and 1x16 for mobile devices.\
For the desktop case, the desined is carried out for a screen size of 1024x1536 pixels (as before, double, in vertical lenght, than the home page).
* Contact Us: on the left, it has a picture of the office (above) and a location map (below). On the right, there is a form where the users are able to send consultations. It has options to avoid marketing communications and being contacted by telephone, as expected by users.\
Similar to the home page, to keep navigation simple, this page is designed to fit in a screen of 1024x768 pixels withough having to scroll with the mouse.

The footer contains links for social media, office location and company's principal e-mail of contact.
# Wireframes
Wireframes were developed at the beginning of the project with Balsamic Wireframes software. The first design was carried out for desktop devices, assuming a screen size of 1024x768 pixels.\

Tablets...\

Mobile devices...
# Technologies used
* HTML
* CSS
# Features
* The header with the navigation is responsive...
* The body changes to adapt to different devices as follows:
    * Home: ...
    * About Us: ...
    * Our Services: ...
    * Contact Us: ...
* The footer
# Validation
The following errors were found and solved:
* For HTML files:
    * Home Page:
        * Error: stray end tag i - Deleted extra closing i tag.
        * Error: aria-labelledby attribute not pointing to an local element (in current document). Changed the attribute value to point to the ID element of the modal button in the section/project (exampleModalCenter).
        * Error: stray start tag script. It was actually caused by the closing body tag placed before the end ot the HTML file, leaving some scripts tags outside the body tag. Soved by moving the closing tag to the end, just before the closing html tag.
        * Warning: Use h1 element as a top-level heading only. Change headings of text above background videos from h1 and h2 to h2 and h3.

        modal in background

        positioning errors of contact form, etc.

        inverted right left columns in contact us page to have a better responsive experience (user experience)

        responsive multiply heith by 2 for tablet

        carousel-item class with text "jump", when setting heith to avoid jump, images in servicous carousel didn't wokr. So applied specificity in text carousel.

https://validator.w3.org/ was used to validate the HTML file.

# Testing of User Stories(Feature-Action-Expected result-Actual result)
EXPLAIN
# Bugs
EXPLAIN
# Deployment
EXPLAIN
# Credit
* Code Institute: I have used the learning material in the course as a guide and reference.
* Love Running - Essentials Project, from Code Institute, as main guide and source of design concepts and code for this project.
* Balsamiq Wireframes: I have used it to create all the wireframes.
* ...
* Font Awesome:
    * Logo of "The Green Company": downloaded on June 9th, 2021, 23:54 from https://fontawesome.com/v5.15/icons/leaf?style=solid <i class="fas fa-leaf"></i>
    * Icos for LinkedIn, Facebook, Twitter, Instagram, map locator and e-mail/envelope: downloaded on June 10th, 2021, 10:05 from https://fontawesome.com/v5.15/icons?d=gallery&p=2
    * ...
* Bootstrap:
    * To get started and install required links and scripts (in the HTML head and below the footer, respectively). Webpage accessed and code copied on June 10th, 2021, 00:23, from https://getbootstrap.com/docs/4.0/getting-started/introduction/
    * "Request Service" button for modal: code copied on June 10th, 2021, 00:14 from https://getbootstrap.com/docs/4.0/components/modal/
    * Carousel in our-services page: copied on June 17th, 2021, at 5:50, from https://getbootstrap.com/docs/4.0/components/carousel/
* Google:
    * Fonts: Baloo Tammudu 2 and Roboto, first imported on June 10th, 2021, 01:10, from https://fonts.google.com/.
    * Google maps: accessed on June 15th, 2021, at 16:18, at https://developers.google.com/maps/documentation/embed/get-started
* W3Schools:
    * References for coding.
    * Font color picker: accessed on June 10th, 2021, 01:45, at https://www.w3schools.com/colors/colors_picker.asp
    * CSS flex-direction property: accessed and copied on June 10th, 2021, 6:40, from https://www.w3schools.com/cssref/css3_pr_flex-direction.asp
    * Video: accessed on June 10th, 2021, 07:45, to https://www.w3schools.com/howto/howto_css_fullscreen_video.asp
    * Center a table with CSS: accessed on June 15th, 2021, at 1:50, at https://www.w3schools.com/howto/howto_css_table_center.asp
    * Borders: accessed on June 16th, 2021, 2:33, from https://www.w3schools.com/css/css_border_rounded.asp.
    * Form styling: accessed on June 16th, 2021, 3:33, from https://www.w3schools.com/css/tryit.asp?filename=trycss_form_responsive .
* Stackoverflow:
    * Borders of input fields in forms: accessed on June 17th, 2021, at 3:15, at https://stackoverflow.com/questions/3397113/how-to-remove-focus-border-outline-around-text-input-boxes-chrome
    * Solution to show modal window above page elements: copied on June 19th, 2021, at 3:17, from https://stackoverflow.com/questions/10636667/bootstrap-modal-appearing-under-background
    * Alignment on anchor element on top: accessed on June 20th, 2021, at 0:48, at https://stackoverflow.com/questions/924282/why-is-vertical-aligntext-top-not-working-in-css
* Home page video: "Wind Turbine on a Field at Sunrise", downloaded on June 9th, 2021, at 22:38, from https://www.pexels.com/video/wind-turbine-on-a-field-at-sunrise-857010/
* Videos:
    * Home page: invisiblepower, Wind Turbine on a Field at Sunrise, downloaded on June 9th, 2021, at 22:38, from https://www.pexels.com/video/wind-turbine-on-a-field-at-sunrise-857010/
* Images:
    * About Us page:
        * Mission: target-3535310_640.jpg, downloaded on June 15th, 2021, at 2:37, from https://pixabay.com/photos/target-business-idea-growth-3535310/
        * Values: paper-3213924_640.jpg, downloaded on June 15th, 2021, at 2:51, from https://pixabay.com/photos/paper-business-finance-document-3213924/
        * Vision: vision-2372177_640.jpg, downloaded on June 15th, 2021, at 2:19, from https://pixabay.com/photos/vision-mission-goal-target-2372177/
    * Our Services page:
        * pexels-kalina-ost-2865025.jpg, downloaded on May 7th, 2021, from https://www.pexels.com/es-es/foto/foto-del-paisaje-del-molino-de-viento-blanco-2865025/
        * pexels-kelly-lacy-2800832.jpg, downloaded on May 7th, 2021, from https://www.pexels.com/es-es/foto/foto-de-vista-superior-de-paneles-solares-2800832/
        * pexels-kelly-lacy-4320473.jpg, downloaded on May 8th, 2021, from https://www.pexels.com/es-es/foto/naturaleza-campo-construccion-industria-4320473/
        * pexels-kelly-lacy-4320481.jpg, downloaded on May 7th, 2021, from https://www.pexels.com/es-es/foto/tierra-campo-verano-construccion-4320481/
    * Contact Us page:
        * Backgraound image: stockvault-office-building236904.jpg, downloaded on June 16th, 2021, 2:09, from https://www.stockvault.net/photo/236904/office-building
        

* Maps in Contact Us page:
    * Leaflet, accessed on June 15th, 2021, 16:45, from https://leafletjs.com/examples/quick-start/. Finally not used.
    * Google maps: iframe element for Madrid copied on June 16th, 2021, at 1:53, from https://www.google.com/maps/


# Acknowledgements
I would like to acknowledge and thank the following people for being part of this project and for helping me in the development of it:
* Code Institute, for providing knowledge, guide and tools.
* My mentor (CHECK IF I CAN PUBLISH HIS NAME), for helping with very valuable guide and support.
* ...
