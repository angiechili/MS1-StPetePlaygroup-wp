St Peter's Playgroup Website
 
## Overview
The idea from this project came after I started my search for childcare in my local area. 

I was unable to find a suitable option through web search, so I decided to as around and by word of my mouth I found a perfect match in St Peter's playgroup.

I thought it a shame that such a great quality childcare setting does not have an online platform to showcase their work and attract new clients.

Until now.... click below to see the St Peter's Playgroup brand new website.

https://angiechili.github.io/MS1-StPetePlaygroup-wp/


## Who is this website for?
Ideally, this is a website for new clients. Who are:
-	Parents of children 2 to 5 years old.
-	English/Welsh speakers.
-	Live in and around the Dinas Powys area.
-	Are looking for childcare outside the regular school times.

## What does the business need? (as expressed by the owner)

-	An easy to navigate website that gives new clients an idea of what their business is and what they offer.
-	A low maintenance website that does not need to be updated frequently.
-	A website that encourages clients to visit social media and contact owner directly with more questions. 


## Planning Stage

A Mini marketing research document established that all the websites of the existing settings have the following in common:

-	Bright and varied colours used throughout to separate sections.
-	Basic information about staff, activities, and times. 
-	Contact and location information including links to social media.

Upon the mini marketing research (shared with client) there were a few things that other websites are doing, that we want to avoid:

-	Too much text and information in the same section.
-	Photos and logos not being big enough or pixelated.
-	Too many navigation tabs.


### Structure, layout, and design.
 
St Peter’s playgroup website intends to attract new customer’s by providing basic information about their philosophy, sessions, staff and activities. The site highlights links to active social media where consumers can see more information and photos about St Peter’s playgroup.

In order achieve this I designed mock-ups both graphic and written to help me convey my vision to the client.

The information and research conducting before starting the code consisted of:

1)	Written communication to client of my idea for the website based on our conversations. (see document here)
2)	Wireframes for each section as per initial written structure and clients notes.       (link to wireframes)
3)	Selection of colour palette and fonts to go in-line with SP playgroups current marketing flyers.


	
## Features (listed by priority level)
High level:
-	A section that summarised SP playgroup philosophy and what they do. 
	Implemented in the introduction section of home page.

-	A chart that clearly displays their sessions times (unlike nurseries they do not operate on a full day basis every day).
	Implemented in the “Sessions” section of home page.

-	Clear and noticeable links to social media pages and links to direct messaging (through Facebook and WhatsApp)
	Implemented in the footer section throughout the site.

 

Mid level:
-	A section dedicated to introducing staff and their qualifications in childcare.
±	A whole section was not used for this as the owner mentioned the staff numbers vary with demand. In that case individual staff information would have not always been relevant without frequent updates to the website. Instead, information about combined staff qualifications was included in the introduction section (home page).
-	A diary style section that explains a ‘day at St Peter’s playgroup’.
-	Reasons to choose us section, that highlights what makes SP playgroup a good childcare choice.
±	Not implemented because the owner highlighted that SP playgroup does not follow a structured activity list. They have things they do everyday like making snacks and good morning and afternoon song.
-	Gallery page showcasing photos of SP playgroup setting, gardens and activities.
±	A gallery tab was included in the project. However, we were unable to include real photos of SP playgroup (as originally planned). Instead, a photo collage was created that conveyed what it looks and feels like to be a child attending to SP playgroup sessions.
±	
-	Section dedicated to showcase awards and schemes that SP playgroup is part of.
T	This was not implemented. It was not possible to get logos of enough resolution for all the schemes and awards. In order to achieve what I described to the client in the initial structed I would have needed higher quality logos and knowledge of more dynamic languages like JavaScript. 



### Existing Features
-	Home Page:
About us page was merged within the home page. This is because there was not enough information to create a whole tab. Keeping in line with one of the objectives, it was decided that a more concise about us section would be presented in the front page. 
	Welcome message and summary:
A clear Welcome (Croeso in Welsh) message that explains what is SP playgroup. Includes a short summary about their philosophy , staff and qualifications. 

	Why choose us section:
A concise section that summarises what SP playgroup does and what makes then standout from other childcare settings in the area. In line with business objectives this had to be done in a way that did not mean there was too much text to read. 

	Timetable:
This was a key feature to design and include. As SP playgroup is not a nursery their session times vary. It was important to clearly display how and when their sessions run and what each session includes. The original design can be found in the attached documentation. As you can appreciate there a few design changes but the overall essence of the table needing to display different sessions across 5 days in a week was kept in the finished website.

-	Contact Us page
The page was to include a contact form and a map snippet indicating the exact location of SP playgroup.
The form was initially built with bootstrap rows and cols and placed occupying half of the page (horizontally). I found this did not look right, it was too big and did not include other contact information like telephone numbers, email and address. The map was initially inspired by Code Institute’s Coders Coffeehouse tutorial (see mock-ups). However, once the iframe was included in the code, it did not look right with the form.

	All in one contact form and map:
Through research I found a template that with bootstrap both the form and the map could be done in one container. (See credits for source information) I added my own classes to change colour schemes and messages in line with the website objectives and structure.

-	Gallery page
Initially thought to include real pictures of playgroup setting and activities. This was not possible as the pictures supplied by the client were taken from their Facebook page and did not have the quality needed to perform in a responsive way.

	Collage style gallery page:
An artistic attempt to convey what SP playgroup is all about through photos alone. Bootstrap was used and all images (see credits) had to be carefully selected and re-sized to make them responsive on mobile, tablet, laptop and higher resolutions screens.

## Tech Used
- HTML, CSS .
- Bootstrap (http://getbootstrap.com/).
- Google developer tools.
- Font Awesome (For all the icons featured in the page).
- Balsamiq (to design wireframes)
- Gitpod (used as the development environment)
- Github (To store and deploy project)



## Testing
Testing was done throughout the realisation of the website. For a detailed account of errors and fixed please see commit messages here.

Devices used for testing include:
-	Apple iPad
-	Apple iPad Pro
-	Microsoft Surface Duo
-	Motorola G4
-	Samsung Galaxy S5
-	Google Pixel 2/2 XL
-	Apple iPhone 5/SE
-	Apple iPhone 6/7/8
-	Apple iPhone 6/7/8 Plus
-	Apple iPhone X
-	One plus A3003
-	iPhone 11
-	Lenovo Thinkpad E590 (laptop)

I used the W3C Markup Validator and W3C CSS Validator to validate every page of the project to ensure there were no syntax errors in the project. (see validator screenshots)

Index.html warning (remains unchanged)
I did not add a <h1/6> heading in this section because it’s a image section and does not benefit from a heading. I verified this against CI Love Running tutorial.

Gallery.html warning (remains unchanged)
It was never my intention to add any text to this page, the idea of it is that is a collage of images that do not need text to show what the product is about.


###Deployment

### Credits

Special thanks to fellow Code Institute’s Slack community that helped with quick answers to questions and positive messages all the way through. Special thanks to fellow student Harry Dhillon for widening my understanding of Bootstrap grid and helping me test the code throughout.

## Code
Header:
Logo and icon shades technique from:
https://www.geeksforgeeks.org/how-to-style-icon-color-size-and-shadow-by-using-css/

Navbar and why choose us section:
https://getbootstrap.com/docs/4.5/components/navbar/
https://mdbootstrap.com/docs/standard/navigation/navbar/
https://getbootstrap.com/docs/4.5/components/card/#images

Scallop line separator technique from:
https://codepen.io/chilliconcode/pen/YyRKYZ

Hero image, timetable and footer:
As per AJGreaves ‘Love Running solutions’ tutorial.
https://github.com/Code-Institute-Solutions/Love-Running-Solutions

Contact Us page:
https://mdbootstrap.com/docs/b4/jquery/javascript/google-maps/
Initially tried setting map as per Code Institute’s Coders coffeehouse tutorial.
https://css-cc-46-complete.codingchallenges.repl.co/index.html#home

Gallery page:
https://getbootstrap.com/docs/4.5/content/images/#responsive-images
https://mdbootstrap.com/docs/standard/extended/gallery/ 


## Other resources
All written content was taken from clients brief (Carly Murray owner for St Peter’s playgroup).

Research web images performance from 
https://www.foregroundweb.com/image-size/

Accessibility Guidelines
http://web-accessibility.carnegiemuseums.org/content/maps/

Helpful Bootstrap research
https://medium.com/coder-grrl/the-guide-to-customising-the-bootstrap-4-navbar-i-wish-id-had-6-months-ago-7bc6ce0e3c71#_=_

https://coderwall.com/p/wpjw4w/change-the-bootstrap-navbar-breakpoint

General HTML/CSS research from:
https://stackoverflow.com/
https://css-tricks.com/
https://ux.stackexchange.com/
https://www.w3schools.com/

Mini marketing research sources:
http://www.staubinnurseries.co.uk/st-aubin-penarth.asp
https://www.ribbonspreschool.com/
https://www.daisydaynursery.com/barry-2/
https://little-inspirations.co.uk/barry
http://orchardnurserypenarth.co.uk/pricing/
https://victorianursery.org/reviews
https://www.gibbonsdownchildrenscentre.co.uk/
https://lollipoplaneplaygroup.co.uk/
https://www.wenvoeplaygroup.co.uk/


Design Inspiration sources:
https://www.behance.net/gallery/18995945/Kindergarten-HTML-Template
https://colorlib.com/wp/preschool-kindergarten-websites/

## Media
-   Hero Image (img/children-holding-hands-final-blue.jpg) taken from:
https://www.freepik.com/vectors/background">Background vector created by brgfx - www.freepik.com
please note this image had to be resized and edited for aesthetics purposes.
-   Card image #1 (assets/img/little-boy-with-a-hand-full-of-paint-covering-his-face-resized-1.jpg) taken from:
-   
https://www.freepik.com/photos/school">School photo created by asier_relampagoestudio - www.freepik.com

-   Card image #2 (/img/fruit-smile1.jpg) taken from:
Photo by Any Lane from Pexels

-   Card image #3 (assets/img/boy-and-bear-outdoors-1.jpg) taken from:
-   Photo by Andy Kuzma from Pexels

-   Background timetable (img/stationary.jpg) taken from:
https://www.pexels.com/photo/painting-and-drawing-tools-set-207665/

-   Gallery #1 (./assets/img/boy-with-clay+708x472.jpg) taken from:
https://www.pexels.com/photo/person-making-clay-figures-1449934/

-   Gallery #2 (./assets/img/toy-tower443x665.jpg") taken from:
https://www.pexels.com/photo/person-holding-yellow-and-pink-lego-blocks-298825/

-   Gallery #3 (./assets/img/woman-girl-reading-book-together.jpg) taken from:
https://www.pexels.com/photo/person-making-clay-figures-1449934/

-   Gallery #4 ( ./assets/img/the-hands-of-the-child-who-smeared.jpg) taken from:
https://www.freepik.com/free-photo/hands-child-who-smeared_7365424.htm

-   Gallery #5 (./assets/img/kids-holding-their-hands-clover.jpg) taken from:
https://www.freepik.com/free-photo/kids-holding-their-hands-clover_5105791.htm#page=1&query=kids%20holding%20their%20hands%20clover&position=0

-   Gallery #6 (./assets/img/happy-three-year-baby-girl-jacket-slide-park.jpg taken from:
https://www.freepik.com/free-photo/happy-three-year-baby-girl-jacket-slide-park_9481720.htm