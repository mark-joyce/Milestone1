# 'Blue Wave' Digital Marketing Agency

Stream One Project: User-Centric Frontend Development - Code Institute

This is a Digital Marketing Agency website to showcase the service that the 'Blue Wave Agency' provides.
The website highlights the services the agency provides with 3 plans available and what each plan involves, as well as the
methods they use for helping businesses advertise online, a portfolio of past work, and a contact form.

## Live Website
The live website for the agency can be found [here](https://mark-joyce.github.io/Milestone1).

![Desktop Demo](https://github.com/mark-joyce/Milestone1/blob/master/assets/images/desktop-landing-demo.png "Desktop Demo")

## UX

### User stories
As a potential client visiting the website I expect to see a showcase of what services the agency provides and a portfolio of their previous work with other clients, along with a method of contacting the agency and marketing processes the agency would use for my business.

### Strategy
My aim in the design was to showcase the possibilities of working with the agency & converting those website visitors into paying clients.

### Scope
For potential clients, I wanted to provide them with an overview of what services the agency provides and how they are carried out with different methods. They would be able to check if the agency is the right fit for what they want and need, with the option to contact the agency if they are interested in working with them.

### Structure
The information is simply structured within one funnel-type page and is logically grouped. In the 'Methods' section, I wanted to show potential paying clients the methods of digital marketing the agency uses such as Facebook Ads & Google Ads, which are used to benefit the clients businesses in the way they want - possibly more sales, lead generation, brand awareness.

### Skeleton
[Landing Page wireframe](https://github.com/mark-joyce/Milestone1/blob/master/wireframes/bluelanding.jpg)

[Contact wireframe](https://github.com/mark-joyce/Milestone1/blob/master/wireframes/contact.jpg)

[Case Study wireframe](https://github.com/mark-joyce/Milestone1/blob/master/wireframes/portfolio.jpg)

[Methods wireframe](https://github.com/mark-joyce/Milestone1/blob/master/wireframes/methods.jpg)

[Services wireframe](https://github.com/mark-joyce/Milestone1/blob/master/wireframes/services.jpg)

### Surface
The color scheme was chosen to create a friendly and natural feel with clean typography, and a blue wave moving at the end of the page to match the agency's name.

## Technologies
1. HTML
2. CSS
3. Bootstrap (4.4.1)

## Features
All the code behind these features can be found in the index.html file, with the help of the contents inside the asset folder i.e the CSS and Images.

- Custom logo created for the header/navbar of the agency website.
- Navbar with 4 different tabs that go directly to that section of the page and auto closes when clicked, and the navbar collapses into a burger menu when under 767px in width.
- 'Work With Us' button is used to get visitors to interact with the page on landing, once clicked it brings them to the 'Our Services' section.
- In the 'Our Services' section, the services of each plan are shown, the 3 'Get Quote' buttons inside the cards bring the user directly to the contact section where they can email or call the agency. Also, a hover effect is created when the card is being interacted with (Cursor on desktop, touch on tablet/mobile).
- Inside the 'Methods We Use', the main methods of the agency are listed with a corresponding image.
- The 'Portfolio' section shows work done with past clients, including the business' name, logo and a description of what they achieved with Blue Wave.
- The 'Contact Us' section gives the website visitors an opportunity to contact the marketing agency. When visitors fill out their details and their message in the form and click the 'Send Email' button, a pop-up shows - telling them their email has been sent and that they will get a response in the next 24 hours. This feature was possible with a function that's inside the assets/js folder.
- 'Back To Top' button is included in the footer for the benefit of the website visitor so they can navigate the website quickly and more efficiently as they're scrolling.
- Also in the footer, the 'Privacy Policy' and 'Terms of Service' links are included if the visitor needs to read them before making a decision to contact the agency to work with them.
- At the websites page end, a GIF of a wave crashing is used to represent the agency's name and to add a fun user experience.


### Features Left to Implement
Plans for additional features to be implemented in the future:

- Add a live chat pop-up feature on the website so visitors can talk to support staff in real time and help them with any questions they have.
- Add more businesses worked with in the portfolio section as the agency grows and gets new clients.

## Testing
The client user story achieved the intended outcome of providing them with a showcase of what services the agency provides and a portfolio of their previous work with other clients.
In the 'Our Services' section, users can see what plan suits them and their business the best, with a list of what's involved in each plan, and a 'Get Quote' button to get the user to contact the agency about their services.
The 'Portfolio' section shows the user some work the agency did with past clients, describing the process they used and their result from it.
The user can also contact the agency inside the 'Contact Us' section if they want to ask any questions or start working with them.
The methods the agency primarily uses are shown too in the 'Methods We Use' so the user can see the processes involved.

How the website looks and works on a mobile phone -  the navbar collapses into a burger menu and when clicked, the 4 available tabs dropdown directly under the menu.
The 3 cards for the services section become stacked on top of each other on the smaller screen but each card still has the hover function when clicked. The cards for the portfolio section stack on top of each other too. The inputs for the contact form become the same width when on a mobile phone.

How the website looks and works on a tablet - the Blue Wave website on a tablet looks almost identical to what it looks and does on a desktop. The only change between them is that the cards from the services section and the portfolio section become more thin.

How the website looks and works on a desktop - the logo and the navigation tabs are centered with a container. The cards in the services section are side by side with each card bigger than the one to its left, which represents the difference of the plans with more services in the 'Medium' and 'Large' plans. The cards of the portfolio are side by side too, and the contact forms inputs are stacked on top of each other.

This [validator](https://validator.w3.org/#validate_by_input) was used to test my HTML and see if there was any errors. In my testing I found that I had to change some code such as using alt's for 3 of the images and fixing a broken div.

This [validator](https://jigsaw.w3.org/css-validator/#validate_by_input) was used to test my CSS and check for errors. In the testing I found I made an error with a font weight and a box shadow.

All links (the Privacy Policy + the Terms of Service) will open in a new tab using 'target="_blank"' for the best user experience.
All links and navigation tabs have been manually tested to ensure that they are pointing to the correct destination.

This site was tested across multiple browsers on desktop (Google Chrome, Internet Explorer, Firefox) and on multiple mobile devices (iPhone X, OnePlus One, iPad) to ensure compatibility and responsiveness.
During the testing phase, I realised that the agency's logo at the top left of the website (```class="brand"```) was distorted and not of good quality when on mobile device browsers, so the width was reduced by 25% in a media query and floated to the left.

## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone https://github.com/mark-joyce/Milestone1` into your terminal. To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.

## Credits

### Content
- All the written content in the Landing, Services, Methods, Portfolio and Contact section were written by me with the [Montserrat font](https://fonts.google.com/specimen/Montserrat?selection.family=Montserrat) and some icons from [here.](https://fontawesome.com/icons)

- The written content of the privacy policy & terms of service pages were created using templates from [here.](https://www.shopify.com/)

### Media
- [Canva](https://www.canva.com/) was used to create the agency's logo, and the logo's of the 'made up' businesses in the portfolio section.

- The photos inside the 'Methods We Use' section and the gif of the wave crashing at the websites page end were all sourced from [Google Images.](https://www.google.com/imghp?hl=en)

### Acknowledgements
- The media query for the smaller logo size on mobile phones was taken from this [site.](https://stackoverflow.com/questions/39759892/html-css-make-image-resize-on-smaller-screens)

- The hover effect on the cards from the 'Our Services' section was taken from [here.](https://www.w3schools.com/howto/howto_css_pricing_table.asp)

- The pop-up after the email sent button is clicked js function was found through these forums [here](https://www.pair.com/support/kb/how-to-use-jquery-to-generate-modal-pop-up-when-clicked/) and [here.](https://getbootstrap.com/docs/4.4/components/modal/)

- The auto close on click function for the navbar on mobiles was found [here.](https://www.codeply.com/go/PqIBtz3HPL)