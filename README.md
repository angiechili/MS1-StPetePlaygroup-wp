# St Peter's Playgroup Website
 
## Overview
The idea for this project came after I started my search for childcare in my local area. 

I was unable to find a suitable option through a web search, so I decided to ask around and by word of my mouth I found a perfect match in St Peter's playgroup.

I thought it a shame that such a great quality childcare setting did not have an online platform to showcase their work and attract new clients.

Until now.... click below to see the St Peter's Playgroup brand new website.

https://angiechili.github.io/MS1-StPetePlaygroup-wp/

### Who is this website for?
Ideally, this is a website for new clients. Who are:
-   Parents of children 2 to 5 years old.
-   English/Welsh speakers.
-   Live in and around the Dinas Powys area.
-   Are looking for childcare outside the regular school times.

### What does the business need? (as expressed by the owner)

-   An easy to navigate website that gives new clients an idea of what their business is and what they offer.
-   A low maintenance website that does not need to be updated frequently.
-   A website that encourages clients to visit social media and contact the owner directly with more questions. 

## Planning Stage

A Mini marketing research [document](https://github.com/angiechili/MS1-StPetePlaygroup-wp/blob/master/documentation/mini%20-market-research%20png.png) 
established that all the websites of the existing settings have the following in common:

-   Bright and varied colours used throughout to separate sections.
-   Basic information about staff, activities, and times. 
-   Contact and location information including links to social media.

Upon the mini marketing research (shared with the client) there were a few things that other websites are doing, that we want to avoid:

-   Too much text and information in the same section.
-   Photos and logos not being big enough or pixelated.
-   Too many navigation tabs.

### Structure, layout, and design.
 
St Peter's playgroup website intends to attract new customer's by providing basic information about their philosophy, sessions, staff and activities. The site highlights links to active social media where consumers can see more information and photos about St Peter's playgroup.

In order to achieve this, I designed mock-ups both graphic and written to help me convey my vision to the client. Based on the mini marketing research, it was decided we wanted build a site with the common characteristics of other sites, and avoiding what we thought was not good about them. (as discussed above)

The structure, layout and design plans initially took form as:

1)  Written communication sent to the client, explaining my idea for the website based on our conversations. See full [document](https://github.com/angiechili/MS1-StPetePlaygroup-wp/blob/fb90f796bf02a9d938e1a286aa3580c3659314a7/documentation/wireframe-website-structure.JPG).
2)  Wireframes for each section as per initial written structure and clients notes.Link to [wireframes](https://github.com/angiechili/MS1-StPetePlaygroup-wp/blob/fb90f796bf02a9d938e1a286aa3580c3659314a7/documentation/wireframes-St%20Peter%27sPlaygroup).
3)  Selection of colour palette and fonts to go in line with SP playgroups current marketing flyers.

    
## Features (listed by priority level)
High level:
-   A section that summarised SP playgroup philosophy and what they do. 
    Implemented in the introduction section of the home page. [IMPLEMENTED](https://github.com/angiechili/MS1-StPetePlaygroup-wp/blob/fb90f796bf02a9d938e1a286aa3580c3659314a7/index.html)

-   A chart that clearly displays their sessions times (unlike nurseries they do not operate on a full-day basis every day).
    Implemented in the "Sessions" section of the home page. [IMPLEMENTED](https://github.com/angiechili/MS1-StPetePlaygroup-wp/blob/fb90f796bf02a9d938e1a286aa3580c3659314a7/index.html)

-   Clear and noticeable links to social media pages and links to direct messaging (through Facebook and WhatsApp)
    Implemented in the footer section throughout the site. [IMPLEMENTED](https://github.com/angiechili/MS1-StPetePlaygroup-wp/blob/fb90f796bf02a9d938e1a286aa3580c3659314a7/index.html)

 

Mid-level:
-   A section dedicated to introducing staff and their qualifications in childcare. **IMPLEMENTED** as a short summary.
    A whole section was not used for this, because the owner mentioned the staff numbers vary with demand. In that case, individual staff information would have not always been relevant without frequent updates to the website. Instead, information about combined staff qualifications was included in the introduction section.

-   Diary style section that explains a 'day at St Peter's playgroup'. **IMPLEMENTED** as an alternative version.
    Not implemented as originally planned, because the owner highlighted that SP playgroup does not follow a structured activity list. They have things they do every day like making snacks and good morning and afternoon song.
    Replaced with 'Reasons to choose us section', that highlights what makes SP playgroup a great childcare choice.

-   Gallery page showcasing photos of SP playgroup setting, gardens and activities. **NOT FULLY IMPLEMENTED**
    A gallery tab was included in the project. However, we were unable to include real photos of SP playgroup (as originally planned). Instead, a photo collage was created that shows what it looks and feels like to be a child attending to SP playgroup sessions.

-   Section dedicated to showcasing awards and schemes that SP playgroup is part of. **NOT IMPLEMENTED**
    This was not implemented. It was not possible to get logos of enough resolution for all the schemes and awards. In order to achieve what I described to the client in the initial structure, I would have needed higher quality logos and knowledge of more dynamic languages like JavaScript. 


### Existing Features
**Home Page:**
About us page was merged within the home page. This is because there was not enough information to create a whole tab. Keeping in line with one of the objectives, it was decided that a more concise about us section would be presented on the front page. 
- Welcome message and summary:
    A clear Welcome (Croeso in Welsh) message that explains what is SP playgroup. Includes a short summary about their philosophy, staff and qualifications. 

- Why choose us section:
A concise section that summarises what SP playgroup does and what makes them stand out from other childcare settings in the area. In line with business objectives, this had to be done in a way that did not mean there was too much text to read. 

- Timetable:
This was a key feature to design and include. As SP playgroup is not a nursery their session times vary. It was important to clearly display how and when their sessions run and what each session includes. The original design can be found in the attached document. As you can appreciate there a few design changes but the overall essence of the table needing to display different sessions across 5 days in a week was kept in the finished website.

**Contact Us page**
The page was to include a contact form and a map snippet indicating the exact location of SP playgroup.
The form was initially built with bootstrap rows and cols and placed occupying half of the page (horizontally). I found this did not look right, it was too big and did not include other contact information like telephone numbers, email and address. The map was initially inspired by Code Institute's Coders Coffeehouse tutorial (see mock-ups). However, once the iframe was included in the code, it did not look right with the form.

- All in one contact form and map:
Through research, I found a template that with bootstrap both the form and the map could be done in one container. (See credits for source information) I added my own classes to change colour schemes and messages in line with the website objectives and structure.

**Gallery page**
Initially thought to include real pictures of playgroup setting and activities. This was not possible as the pictures supplied by the client were taken from their Facebook page and did not have the quality needed to perform in a responsive way.

**Collage style gallery page:**
An artistic attempt to convey what SP playgroup is all about through photos alone. Bootstrap was used and all images (see credits) had to be carefully selected and re-sized to make them responsive on mobile, tablet, laptop and higher resolutions screens.

## Tech Used
- HTML, CSS .
- Bootstrap (http://getbootstrap.com/).
- Google developer tools.
- Font Awesome (For all the icons featured on the page).
- Balsamiq (to design wireframes)
- Gitpod (used as the development environment)
- Github (To store and deploy project)


## Testing
Testing was done throughout the realisation of the website. For a detailed account of errors and fixes please see commit messages [here] (https://github.com/angiechili/MS1-StPetePlaygroup-wp/commits/master).

Devices used for testing include:
-   Apple iPad
-   Apple iPad Pro
-   Microsoft Surface Duo
-   Motorola G4
-   Samsung Galaxy S5
-   Google Pixel 2/2 XL
-   Apple iPhone 5/SE
-   Apple iPhone 6/7/8
-   Apple iPhone 6/7/8 Plus
-   Apple iPhone X
-   One plus A3003
-   iPhone 11
-   Lenovo Thinkpad E590 (laptop)

I used the W3C Markup Validator and W3C CSS Validator to validate every page of the project to ensure there were no syntax errors in the project. (see validator [screenshots](https://github.com/angiechili/MS1-StPetePlaygroup-wp/blob/fb90f796bf02a9d938e1a286aa3580c3659314a7/documentation/validator%20-screenshots))

Index.html warning (remains unchanged)
I did not add a <h1/6> heading in this section because it's an images section and does not benefit from a heading. I verified this against CI Love Running tutorial.

Gallery.html warning (remains unchanged)
It was never my intention to add any text to this page, the idea of it is that is a collage of images that do not need text to show what the product is about.

## Deployment
**Github**

This project is deployed using GitHub pages using the following process,

**Deploying a GitHub Repository via GitHub Pages**

1. In your Repository section, select the Repository you wish to deploy.
2. In the top horizontal menu, locate and click the Settings link.
3. Inside the Setting page, around halfway down locate the GitHub Pages section.
4. Under Source, select the None tab and change it to Master and click Save.
5. Finally once the page resets scroll back down to the GitHub Pages Section to see the following message "Your site is ready to be published at (Link to the GitHub Page Web Address)". It can take time for the link to open your project initially, so please don't be worried if it down not load immediately.

**Forking the Github Repository**

You can fork a GitHub Repository to make a copy of the original repository to view or make changes without it affecting the original repository.

1. Find the GitHub repository.
2. At the top of the page to the right, under your account, click the Fork button.
3. You will now have a copy of the repository in your GitHub account.

**Making a Local Clone**

1. Find the GitHub Repository.
2. Click the Code button
3. Copy the link shown.
4. In Gitpod, change the directory to the location you would like the cloned directory to be located.
5. Type git clone, and paste the link you copied in step 3.
6. Press Enter to have the local clone created.

## Credits

Special thanks to Code Institute's Slack community that helped with quick answers to questions and positive messages all the way through. Special thanks to fellow student Harry Dhillon for widening my understanding of Bootstrap grid and helping me test the code.

### Code

- Logo and icon shades technique from:
https://www.geeksforgeeks.org/how-to-style-icon-color-size-and-shadow-by-using-css/

- Navbar and why choose us section:
https://getbootstrap.com/docs/4.5/components/navbar/
https://mdbootstrap.com/docs/standard/navigation/navbar/
https://getbootstrap.com/docs/4.5/components/card/#images

- Scallop line separator technique from:
https://codepen.io/chilliconcode/pen/YyRKYZ

- Hero image, timetable and footer:
As per AJGreaves 'Love Running solutions' tutorial.
https://github.com/Code-Institute-Solutions/Love-Running-Solutions

- Contact Us page:
https://mdbootstrap.com/docs/b4/jquery/javascript/google-maps/
Initially tried setting map as per Code Institute's Coders coffeehouse tutorial.
https://css-cc-46-complete.codingchallenges.repl.co/index.html#home

- Gallery page:
https://getbootstrap.com/docs/4.5/content/images/#responsive-images
https://mdbootstrap.com/docs/standard/extended/gallery/ 

### Other resources
All written content was taken from the clients brief (Carly Murray owner of St Peter's playgroup).

- Research web images performance from 
https://www.foregroundweb.com/image-size/

- Accessibility Guidelines
http://web-accessibility.carnegiemuseums.org/content/maps/

- Helpful Bootstrap research
https://medium.com/coder-grrl/the-guide-to-customising-the-bootstrap-4-navbar-i-wish-id-had-6-months-ago-7bc6ce0e3c71#_=_

https://coderwall.com/p/wpjw4w/change-the-bootstrap-navbar-breakpoint

- General HTML/CSS research from:
https://stackoverflow.com/
https://css-tricks.com/
https://ux.stackexchange.com/
https://www.w3schools.com/

- Mini marketing research sources:
http://www.staubinnurseries.co.uk/st-aubin-penarth.asp
https://www.ribbonspreschool.com/
https://www.daisydaynursery.com/barry-2/
https://little-inspirations.co.uk/barry
http://orchardnurserypenarth.co.uk/pricing/
https://victorianursery.org/reviews
https://www.gibbonsdownchildrenscentre.co.uk/
https://lollipoplaneplaygroup.co.uk/
https://www.wenvoeplaygroup.co.uk/

- Design Inspiration sources:
https://www.behance.net/gallery/18995945/Kindergarten-HTML-Template
https://colorlib.com/wp/preschool-kindergarten-websites/

### Media
-   Hero Image (img/children-holding-hands-final-blue.jpg) taken from:
https://www.freepik.com/vectors/background">Background vector created by brgfx - www.freepik.com
please note this image had to be resized and edited for aesthetics purposes.

-   Card image #1 (assets/img/little-boy-with-a-hand-full-of-paint-covering-his-face-resized-1.jpg) taken from:
https://www.freepik.com/photos/school">School photo created by asier_relampagoestudio - www.freepik.com

-   Card image #2 (/img/fruit-smile1.jpg) taken from:
https://www.pexels.com/photo/smile-made-of-ripe-fruits-5946078/
Photo by Any Lane from Pexels

-   Card image #3 (assets/img/boy-and-bear-outdoors-1.jpg) taken from:
https://www.pexels.com/photo/girl-sitting-beside-a-teddy-bear-2803979/
Photo by Andy Kuzma from Pexels

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
