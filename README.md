# Papilion AB

![Image papilogo](https://user-images.githubusercontent.com/65713111/88453147-d7c0a700-ce64-11ea-9afb-967a0313ef3b.png)

The aim of this project is to **sell creative workshops** via **Papilion AB** a Swedish based creative consultancy service provider.
Please see my [live site] (https://rticulus.github.io/papilion-courses/) deployed on Github. 

### Table of Contents

- Overview
- Description
- UX
- Features
- Features left to implement
- 
- Testing
- Code validity
- Credits
- Acknowledgments
- Support

- Deployment



## Overview

Papilion is a creative community of consultant artists from many backgrounds and walks of life. We believe our knowledge and collective 50years of experience in art, theatre, dance, music, community engagement and group development can help you and your organisation reach positive and progressive outcomes, whatever your target or goal


## Description

This site is a simple, accessible booking and viewing space for anyone from industry, school or clubs to book creative services at a glance. A lot is yet to be developed, however you are able to see the services provided and immediately book a consultancy or query which can be received and responded to within 24hrs. 

***


## UX

#### User Stories

- *"As a User I go on a lot of sites and I am overloaded with information and pop-ups trying to sell me other things I did not come looking for. Can you make your site simple and easy to access?”*

- *"As a mobile-User sometimes I would like be able to go to the next page quicker by having the navigation accessible at all times”*

- *”As a mother and User, I would like to stay on this site while I check your social medias on another tab…”*

#### 1. Strategy

The aim of this site is that people can immediately contact us to book a workshop or query the available services.
I have opted for a simple clean approach with the images selling our service. The idea being customers would be enthused by the images, find the service they personally require and immediately book a consultation.

##### Project Goals:

- Sell more creative workshops

- Inform the customer on what services are available and why they should choose us

- Facilitate contact through online forms


##### Customer Goals:

- Immediate information on available services

- Ability to book a timely consultation
	
- Option to request more information

#### 2. Scope

The site is predominantly a booking site for physical creative workshops:

- Brand colours with easy to read content

- Motion in the form of carousels of great images

- 5-pages with links from navigation and services plus a big booking button 

- A booking form for client information so they can be contacted

- Location via an interactive map

- Contact form to request more information


#### 3. Structure

The structure is aimed at easy practical access to short succinct info on each service.

- For the merely curious they can contact us via the query form and for those who know what they want, a booking form is provided with a calendar to book specific dates. 

- Images of activities we provide and a direct booking button is also available.

- Easy navigation throughout


#### 4. Skeleton Surface

- Wireframes: clearly defined 5-page site

- Fixed navigation bar for easy reference to pages

- Main(Home) page, About (Support Options) page, Image Gallery page, Contact page with contact form and Booking page that opens up over any page you were previously on

- Footer with Social Media

![About us](https://user-images.githubusercontent.com/65713111/88452741-8236cb00-ce61-11ea-9a83-7094247af61a.png)

![Contact_2](https://user-images.githubusercontent.com/65713111/88452742-8367f800-ce61-11ea-8a2a-93a8d2dcc2a7.png)

![Contact](https://user-images.githubusercontent.com/65713111/88452743-8367f800-ce61-11ea-9849-130249d6e17b.png)

![Home_2](https://user-images.githubusercontent.com/65713111/88452744-84008e80-ce61-11ea-863e-4cda5e60342a.png)

![Home](https://user-images.githubusercontent.com/65713111/88452745-84992500-ce61-11ea-9369-5e0d22542e0b.png)

![services](https://user-images.githubusercontent.com/65713111/88452746-8531bb80-ce61-11ea-8e69-acc5b3f7e519.png)

***


## Features

* Feature 1 - Intro - “Home” logo will always take you back to the homepage wherever you are on the site

* Feature 2 - Links - These allow the user to go to the relevant information for them specifically, without needing to scroll through the entire site.

* Feature 3 - Navigation - easy navigation with a fixed, direct navigation link to topic/service (theatre, dance, music and art)page and section, navbar hover-highlight style for better navigation

* Feature 4 - Booking Form - This allows the user to easily book a date for their workshop and informs Papilion to contact them to finalise the contract

* Feature 5 - Query Form -  This allows the user to ask a question or query a service. Papilion can then contact them to follow up.

* Feature 6 - Social  - These are direct links to social networks, each links directly to the social site which opens on a separate page. The only generic link is LinkedIn.


## Features left to implement

Wishlist of ideas to be implemented at a future date:

* Chat

It would be a service benefit and potential sales angle to have live chat, or at least a Bot to to give FAQs

* Online Resource 

For teachers and team leaders, an online resource package preparing the groups for workshop visits

* Map  

I would like to integrate a more interactive map than is presently available. Users should be available to, for safety, see the location and surroundings of the theatre venue where we are based and where most workshops happen.

* Booking  

I would like to create a better system so users can book by checking available slots and creating a payment system to assist in service and sales handling. 


## __Technology Used__

I have listed the following languages and technology used to produce this project below:

* Markdown
    * For the ReadMe file
* HTML 5
    * For the base information and structure of the webpages
* CSS 3
    * For the styling and beauty of the webpages
* Bootstrap 4
    * Was used for the gallery, query and booking forms.
* Hover.css
    * For hover animation on the desktop navbar.


## Testing

* The first few commits were big structural dumps, testing the skeleton structure and then the skeleton with placeholders, all worked well. 

1. Booking form:
    1. Go to the "Book Us Here" button on any page or the "Book Now" page (which is a pop-up):
    2. Try to submit the empty form and an error message about the required fields appears
    3. Try to submit the form without an email address and an error message appears
    4. Try to submit the form without a Booking Date and you will return to your original page, informing Papilion you required consultation with an interest to book.
    5. Try to submit the form with all inputs valid and you have completed submission and will be returned to your original page

2. Query form:
    1. Go to the "Contact Us" page and "Any Questions":
    2. Try to submit the empty form and an error message about the required fields appears
    3. Try to submit the form without an email address and an error message appears
    4. Try to submit the form with all inputs valid and you have completed your query and will be returned to your original page

3. Fixed Navbar- 
    1. Scroll on any page and navbar stays fixed 
    2. Home page service links connect to Services page
    3. On Service page, services (ie. Theatre, Dance, Music, Grafitti) falls short of the navbar, can be fixed with JavaScript
4. 
There was testing throughout the project to make sure that the project looks good and works on multiple screen sizes and devices.  
This was done through the Google Chrome developer tools by reducing the width of the screen from desktop to mobile device view.

5. 
I have fully tested all the links on the site to make sure that they go through to the correct pages.  
I have also made sure that any which are linked to outside sites open in a new window.  


### Code validity

> HTML - [W3C](https://validator.w3.org/) - Markup Validation
>
> CSS - [W3C](https://jigsaw.w3.org/css-validator/) - CSS Validation
>
Ran code. Everything is clean. One warning keeps coming up, I am aware it only affects older browsers:
(Warning: The date input type is not supported in all browsers. Please be sure to test, and consider using a polyfill.
From line 190, column 29; to line 190, column 164: <input type="date" id="dateFormat" class="form-control" name="trip-start" value="2020-07-21" min="2020-01-01" max="2021-08-30" required>↩↩ )


### Credits

Selection of images taken from free-to-use stock image sites:

- Home page images are Papilion's own. Photos by Camilla Cherry Photography

- Services: [Pixabay](https://pixabay.com/)

- Gallery:  [Pexels](https://www.pexels.com)


### Acknowledgments

Thanks to my partner for the cups of coffees.
Thankyou to my mentor Rohit Sharma for his support and great advice.
Gratitude to HTK Sverige for allowing me to remake and reinvent the website.

### Support

For any issue or assistance, please contact rtawoshe@gmail.com


### Deployment

Steps taken to deploy on Github

1. My code was written in Visual Studio Code and transferred to Github.
2. In Github it is stored on a public repository: https://rticulus.github.io/papilion-courses/
3. Under services in Github, followed instructions to deploy.
4. The code is now available for anyone to access via Github pages

All is equal in the final commit and the version now available on Github.






