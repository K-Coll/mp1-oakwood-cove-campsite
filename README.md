# Oakwood Cove Camp Site  

Oakwood Cove Campsite is a website to promote a newley developed camp site for motorhomes, caravans and tents. Visitors to the site will also be able to submit a message to the owners of the site using the contact form.  

The site is built using HTML5, CSS3 and Bootstrap v5 for the Milestone Project 1 for Code Institute's Diploma in Web Development.

![Responsive Image](docs/features/responsive-image.png)

[Link to Live Website](https://k-coll.github.io/mp1-oakwood-cove-campsite/)

## Table of Contents

* [User Experience (UX)](#user-experience-ux)
  * [Strategy](#strategy)
    * [User Stories](#user-stories)
  * [Scope](#scope)
  * [Structure](#structure)
    * [Home Page](#home-page)
    * [CampsitePage](#campsite-page)
    * [Local Area Page](#local-area-page)
    * [Contact Page](#contact-page)
  * [Skeleton](#skeleton)
  * [Surface](#surface)
    * [Design](#design)
    * [Colour Scheme](#colour-scheme)
    * [Contrast Checker](#contrast-checker)
    * [Typography](#typography)
    * [Imagery](#imagery)
    * [Media](#media)
* [Features](#features)
  * [Site Level Elements](#site-level-elements)
  * [Page Level Elements](#page-level-elements)
    * [Homepage](#homepage)
    * [Campsite](#campsite)
    * [Local Area](#local-area)
    * [Contact](#contact)
* [Future Implementations](#future-implementations)
* [Accessibility](#accessibility)
* [Testing](#testing)
  * [Testing User Stories](#testing-user-stories)
  * [Validator Testing](#validator-testing)
    * [HTML Validation](#html-validation)
    * [CSS Validation](#css-validation)
  * [Lighthouse](#lighthouse)
  * [Full Testing on Devices and Browsers ](#full-testing)
  * [Links](#links)
  * [Contact Form](#contact-form)
  * [Solved Bugs](#solved-bugs)
* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Applications Used](#applications-used)
  * [Frameworks, Libraries and CDNs Used](#frameworks-libraries-and-CDNs)
  * [VS Code Extensions](#vs-code-extensions)
* [Deployment & Local Development](#deployment-local-development)
  * [Deployment](#deployment)
  * [Local Deployment](#local-deployment)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)
* [Credits](#credits)
  * [Learning Resources](#learning-resources)
  * [Content Used](#content-used)
  * [Acknowledgements](#acknowledgements)

## User Experience (UX)
### Strategy
The Oakwood Cove Camp Site Website is designed to be responsive and accessible on a range of devices. It allows visitors to find out about the campsite, the local area in which it is situated, what facilities and amenities there are and the types of pitches available to book.

### User Stories 
  * #### Site Owner Goals
    1.  As the Site Owner, I want to showcase the newly developed camp site including the grounds, pitches and all the facilities on offer to visitors and potential customers.   
    2.  As the Site Owner, I want to allow potential customers and visitors to the website to contact the camp site owners for any potential enquires or to book a holiday.  

  * #### First Time Visitor Goals
    3. As a First Time Visitor, I want to be able to understand the purpose of the website and know more about the campsite itself.
    4. As a First Time Visitor, I want to know the price range of the campsite to decide if it is within my budget.
    5. As a First Time Visitor, I want to know the address of the campsite and where it is located.
    6. As a First Time Visitor, I to know what types of pitches are available to book.
    7. As a First Time Visitor, I want to know what facilities are available and what the camp site offers.
    8. As a First Time Visitor, I want to get in touch and to have any potential questions answered.
    9. As a First Time Visitor, I want to be able to navigate the site easily to find information.

  * #### Returning Visitor Goals
    10. As a Returning Visitor, I want to know what times of year the campsite is open and what time check in and check out is.
    11. As a Returning Visitor, I want to view a picture of the camp site for my upcoming holiday.
    12. As a Returning Visitor, I want to access useful information and review the facilities on offer while planning for an upcoming holiday at the campsite.
    13. As a Returning Visitor, I want to find useful information regarding the local area surrounding the campsite, in order to plan what I’m doing on my holiday.
    14. As a Returning Visitor, I want to find useful information about the local town in order to plan my holiday.
    15. As a Returning Visitor, I want to find useful information about the local beach in order to plan my holiday.
    16. As a Returning Visitor, I want to find useful information regarding any events in the local area in order to plan my holiday.
    17. As a Returning Visitor, I want to find useful information regarding things to do in the local area in order to plan my holiday.
    18. As a Returning Visitor, I want to follow up on my previous viewing of the website in order to make an enquiry and have any potential questions answered.  
  
### Scope
  The goal for the project is to make an informative, easy to navigate and visually appealing website, with a minimum of three pages.  

### Structure
  Overall the website has four pages. These are:  

*  **The Home Page**  
    This page is the landing page of the website to introduce the camp site and provide information.

* **Campsite**  
    This page is to showcase and promote what’s on offer and provided by the campsite, to enable visitors and potential customers to plan for their holiday.  

* **Local Area**  
    This page is to promote the local area and showcase what visitors can expect to take part in when they book a holiday at the campsite.  

* **Contact**  
    This pages is to provide users with additional information that is asked frequently and to provide an option for users to contact the owners of the campsite regarding a general enquiry or to book specific dates.  

    Social Media icons are also shown in the footer of each page, along with a direct link to the contact page.
  
### Skeleton

  Wireframes were created for this project using Balsamic. For each page, a wireframe was created for mobile, tablet and desktop. I tried to stick to this design as close as possible for the final project.

<details><summary>Home</summary>
<img src="docs/wireframes/pg1-homepage.png">
</details>
<details><summary>Campsite</summary>
<img src="docs/wireframes/pg2-campsite.png">
</details>
<details><summary>Local Area</summary>
<img src="docs/wireframes/pg3-localarea.png">
</details>
<details><summary>Contact</summary>
<img src="docs/wireframes/pg4-contact.png">
</details>

  ### Surface

* #### Design
    The overall design of the website is minimal.  
    
    There was an iterative design process of the website, which was improved upon by adding in a < hr > tag to visually separate different sections. This also incorporates the brand and the theme and creates a more cohesive look to the overall website.
    * The < hr > tag was added after the navigation bar (on the local area and contact pages and covered 100% of the page width)
    * The < hr > tag was also added after the about us section on the main homepage, after the frequently asked questions section (only on small devices) on the contact page, and inbetween the facilities and pitches section on the campsite page. This covered 90% of the page width, with spacing either side, to create a light, airy and breathable divide between sections.  
      <br>
      <details><summary>Feature - < hr > tag - navbar</summary>
      <img src="docs/features/feature-hr-navbar.png">
      </details>  
      <br>  
      <details><summary>Feature - < hr > tag - homepage</summary>
      <img src="docs/features/feature-hr-homepage.png">
      </details>  
      <br>  
      <details><summary>Feature - < hr > tag - campsite</summary>
      <img src="docs/features/feature-hr-campsite.png">
      </details>  
      <br>  
      <details><summary>Feature - < hr > tag - contact</summary>
      <img src="docs/features/feature-hr-contact.png">
      </details>  
 
* #### Colour Scheme
    The idea for the colour scheme is to keep it fresh and bright, whilst also being easy to read and understand. I also wanted to tie the colour scheme into the grounding colours of nature to create a calming outside holistic feel, which the hues of green and blue provides.  

    The overall design of the website is minimalistic; only four main colours are used. This is purposeful so as not to take away focus on the images used within the website and also not the clash with them. The images used have lots of complimentary colours which creates an overall cohesive and pleasing aesthetic.  

    The design of the website to include the colour scheme is to create a gradient effect. The top of the website is lighter, the main body of the website is a mix of light and dark to create contrast, and the bottom of the website is darker.  

    <details><summary>Colour Palette</summary>
    <img src="docs/features/msp1-colour-palette-2.png">
    </details>

* #### Contrast Checker
    Contrast was checked for accessibility using WebAIM's contrast checker - https://webaim.org/resources/contrastchecker/.  
    <br>
    The contrast for the main body of the website is 10.07:1. This is also the contrast for the footer, as it uses the same colours although the footer is light text on dark background. The contrast for the Nav Bar is 7.24:1.  

    <details><summary>Contrast Checker - Main Body / Footer</summary>
    <img src="docs/features/contrast-checker-mainbody.png">
    </details>
    <details><summary>Contrast Checker - Nav Bar</summary>
    <img src="docs/features/contrast-checker-navbar.png">
    </details>

* #### Typography
    Three fonts are used for this website.  
    
    Kalam is used for the website title / logo, for the contact link within the footer and for the submit button. Rubik is used for the menu navigation bar and the headings. Nunito Sans is used for the main body of the website.  
    
    Sans Serif was also used as the fall-back font throughout the entire website, if the other fonts are not working properly.  
    
    These fonts are accessible and were chosen because they are clear and easy to read and are popular for people who have visual or cognitive disabilities.  

* #### Imagery
    The imagery captures a sense of being outdoors and features a lot of the grounding colours of nature, which complement the colours used for the design to tie everything together and give it an overall cohesive look.  
    
    The type of imagery used on the website is sourced from Freepik.com, specifically:  
            * [Home Page Hero Image](https://www.freepik.com/premium-photo/high-angle-view-trees-beach_114914176.htm). From author [EyeEm](https://www.freepik.com/author/EyeEm)  
            * [Campsite Page Hero Image](https://www.freepik.com/free-photo/toddler-brother-sister-autumn-playground_2784350.htm). From author [Freepik](https://www.freepik.com/author/freepik)  
            * [Campsite Page Pitches section](https://www.freepik.com/premium-photo/caravan-camping-site-nature-with-travel-trailers-riva-istanbul-turkey-april-04-2022_31832656.htm) from author [Gizemg](https://www.freepik.com/author/gizemg)  
            * [Local Area Page, Glyndwr Town card](https://www.freepik.com/premium-photo/prague-czech-republic-september-22-2018-charles-bridge-sunrise_26236017.htm). From author [EugenePetrunin](https://www.freepik.com/author/eugenepetrunin)  
            * [Local Area Page, Llŷn Peninsula Beach card](https://www.freepik.com/free-photo/walking-area-front-waikawa-beach-new-zealand_11111961.htm). From author [Wirestock](https://www.freepik.com/author/wirestock)  
            * [Local Area Page, Events card](https://www.freepik.com/premium-photo/blur-festival_5387185.htm). From author [user7814140](https://www.freepik.com/author/user7814140)  
            * [Local Area Page, Things To Do card](https://www.freepik.com/free-photo/low-angle-shot-st-george-s-chapel-middle-park-windsor-uk_10990346.htm). From author [Wirestock](https://www.freepik.com/author/wirestock)    

* #### Media
    Font Awesome icons are also used sparingly throughout.  

    The icons are used within the footer on each page to provide a visual representation of the social media links.  

    The icons are also used on the Campsite page, specifically in the Facilities section to again provide a visual representation of the different facilities and amenities that are provided by the campsite. This also differentiates between the Facilities and Pitches sections breaks up the text, so it’s not two big paragraphs of listed text.  
    <br>
    ![Fontawesome Icons Social Media](docs/features/fontawesome-icons-socialmedia.png)    
    ![Font Awesome Icons Facilities](docs/features/font-awesome-icons-facilities.png)  

## Features

### Site Level Elements
* There is a header at the top of the page which is comprised of the Bootstrap Nav Bar. This houses the name of the camp site and links to all the pages contained within the website to act as a navigational menu bar. It is fully responsive and collapses down to a hamburger menu on medium and small devices. There is a balanced design to this, as the menu text is horizontally centred and in line with the middle of the logo / name of the website. User Stories covered: 9.  
![Logo and navbar](docs/features/feature-hr-navbar.png)  
  <br>  

* There is a footer at the bottom of every page which houses the social media icons and an internal link that takes user directly to the contact page. The social media links for Facebook, Twitter / X and Instagram, show as icons. These are active links but they navigate to the homepages of Facebook, Twitter / X and Instagram respectively and do not link to the actual campsite, as it is a fictional business for project purposes. User Stories covered: 2, 8, 9, 18.

  ![Footer](docs/features/feature-footer.png)  
  <br>  

### Page Level Elements

* #### Homepage 
    The home page is the landing page of the website and features a hero image, which is an aerial image of the camp site to show that is by the beach, underneath the navigational header. There is also a text overlay that houses the tag line for the campsite. The background image is used as decoration and is therefore added in via CSS. User Stories covered: 1, 3, 11. 
    
    ![Hero image and text overlay](docs/features/feature-homepage-hero-image.png)  
    <br> 

    There is some welcome text underneath this which introduces the camp site. Furthermore, there is a general section set out in three columns, which provides additional information such as the opening times, the prices and the address. User Stories covered: 3, 4, 5, 10.  

    ![Welcome message](docs/features/feature-homepage-welcome.png)  
    <br>  
    ![General information](docs/features/feature-general-information.png)  
    <br>  

* #### Campsite
    This page is split into three sections – the hero image to showcase that the campsite is child and family friendly, the facilities section and the pitches section.
    
    ![Campsite Hero image](docs/features/feature-campsite-hero-image.png)  
    <br>  

    The Facilities section utilises the Bootstrap grid and is fully responsive. On large devices, the content is displayed across four columns, whereas on medium and smaller devices, the content is displayed across two columns.  Font Awesome icons were used to help visualise the facilities and amenities that are available in the campsite – such as security, the toilet / shower block, wifi, a shop, etc. User Stories covered: 1, 3, 7, 12.  
    
    ![Facilities](docs/features/feature-facilities.png)  
    <br>   

    The pitches section is split in two – one the left-hand side there is an image of some campervans on the pitches and on the right-hand side there is an ordered list of the pitch types that are available, along with any additional charges. This is also fully responsive. On a large and medium device, the image and listed text appear side by side. On a small device, they are stacked on top of each other, with the image appearing first and the listed text appearing underneath. User Stories covered: 1, 3, 4, 6, 11.  

    ![Pitches](docs/features/feature-pitches.png)    
    <br>  

* #### Local Area
    This page has an introductary section at the top and then utilities the Bootstrap card element that has 4 images, with accompanying text underneath. The information is broken down into four sub headings - Glyndwr Town, Llŷn Peninsula Beach, Events and Things to Do. The aim of this page is to showcase the local area in which the camp site is located, enabling visitors and potential customers to plan their holiday with activities and things to do and enjoy. The purpose of this is to reinforce a sense of community and connection between the campsite, it’s owners and the local area. Again, this page is also fully responsive. On a large and medium device, the four cards are displayed in two columns and two rows. On a small device, the four cards are displayed in one column with four rows, as they are all stacked on top of each other. User Stories covered: 3, 13, 14, 15, 16, 17.  

    ![Local Area intro](docs/features/feature-localarea.png)    
    <br>  
    
    ![Glyndwr Town](docs/features/feature-glyndwr-town.png)    
    <br> 

    ![Beach](docs/features/feature-beach.png)    
    <br> 

    ![Events](docs/features/feature-events.png)    
    <br> 

    ![Things to do](docs/features/feature-things-to-do.png)    
    <br>  

* #### Contact
    This page has an introductory section at the top and is then split into two columns of equal width. One the left is the FAQ section comprised of a Bootstrap accordion that is styled with custom CSS. On the right is the contact form.  
    
    This page has two purposes – one to provide customers with useful information that is often asked, and two to provide an option for users of the website to contact the owners of the campsite. This could be to provide feedback, for a general enquiry or to book a holiday for specific dates. Some elements are mandatory and are required before the form can be submitted properly.  
    
    This page is also fully responsive. On a large and medium device, the FAQ section is on the left-hand side and the Contact Form is on the right hand side. Whereas on a small device, the sections are stacked on top of each other. There is also a horizontal rule in between the two sections when on a small device, to differentiate between the two and to tie in the branding and the theme to create an overall cohesive look. User Stories covered: 3, 13, 14, 15, 16, 17.    

    ![Contact Intro](docs/features/feature-contact-intro.png)    
    <br> 

    ![Frequently asked questions](docs/features/feature-faq.png)    
    <br> 

    ![Contact Form](docs/features/feature-contact-form.png)    
    <br>

## Future Implementations
* Addition of an iframe to incorporate the google maps into the address section
* An information page providing advice and guidance for how to camp responsibly and resourcefully.
* Develop the contact form into a fully functioning booking form. This would have a calendar integrated in so customers can see what dates are available and what dates have already been booked / are fully booked. Customers will be able to choose how many nights they want to book, what pitch type they want to book and where in the campsite they want to be located (by the toilet block, by the entrance, by the beach, don’t mind, etc).
* Create a Photo Gallery to house images of the camp site, the pitches, the facilities and the local area with activities and things to do. This would be used as a showcase so visitors and potential customers can view the campsite in more detail.

## Accessibility
I have tried to ensure the website is as accessible as possible by:
* Using semantic HTML.
* Using descriptive alt attributes for images throughout the website.
* Using easy to read and accessible fonts.
* Adding aria-labels for screen readers.
* Using a cohesive design scheme and colour contrasts to make sure the text is easy to read.
* Using clear navigation.  

The WAVE WebAIM web accessibility evaluation tool was used to ensure the website meets high accessibility standards. All pages of the website passsed with zero errors.

  <details><summary>Wave Home Page</summary>
  <img src="docs/validation/wave-home.png">
  </details>  
  <details><summary>Wave Campsite Page</summary>
  <img src="docs/validation/wave-campsite.png">
  </details>  
  <details><summary>Wave Local Area Page</summary>
  <img src="docs/validation/wave-localarea.png">
  </details>  
  <details><summary>Wave Contact Page</summary>
  <img src="docs/validation/wave-contact.png">
  </details>  

## Testing

Chrome developer tools were used to test, identify and address any issues. This was also used to ensure the website was responsive on different screen sizes throughout the build process.

### Testing User Stories

#### Site Owner Goals

1. As the Site Owner, I want to showcase the newly developed camp site including the grounds, pitches and all the facilities on offer to visitors and potential customers.  

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Homepage Hero Image | Navigate to the Homapage | View Hero Image | Image loads as expected |
| General Information Section | Navigate to the Homapage | View the information section with the subheadings: Timings, Prices, Address | Works as expected; visitor gains knowledge of campsite |
| Facilities | Navigate to the Campsite page, locate the Facilities section with the font awesome icons | Locating the list of facilities and amenities that are on offer, promoting the campsite | Works as expected; visitor gains knowledge of campsite |
| Pitches image and list items | Navigate to the Campsite page, locate the Pitches section | View the image of the pitches and read list of types of pitches available | Works as expected; visitor gains knowledge of campsite |
  
  <details><summary>Homepage Hero Image</summary>
  <img src="docs/user-story-testing/user-story-homepage-hero-image.png">
  </details>  
  <details><summary>General Information Section</summary>
  <img src="docs/user-story-testing/user-story-general-information.png">
  </details>  
  <details><summary>Facilities</summary>
  <img src="docs/user-story-testing/user-story-facilities.png">
  </details>  
  <details><summary>Pitches image and list items</summary>
  <img src="docs/user-story-testing/user-story-pitches.png">
  </details>  
  <br>

2.  As the Site Owner, I want to allow potential customers and visitors to the website to contact the camp site owners for any potential enquires or to book a holiday.      

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact Form | Navigate to the Contact Page and locate the contact form, fill out all required fields and submit contact form | Data submited via contact form | Works as expected; Code Institute form submission confirmation page is displayed to the user once the form has been submitted correctly|
| Footer on any page| On any page scroll down to the footer at the bottom, click on the 'Submit an Enquiry link | Directed to the contact page | Works as expected; vistor is directed to the contact page, which opens within the same window and not a new tab, as it is an internal link|
  
  <details><summary>Contact Form</summary>
  <img src="docs/user-story-testing/user-story-contact-form-2.png">
  <img src="docs/user-story-testing/user-story-contact-form-submit.png">
  </details>  
  <details><summary>Footer on any page</summary>
  <img src="docs/user-story-testing/user-story-footer-contact-link.png">
  </details> 
  <br>

#### First Time Visitor Goals

3.  As a First Time Visitor, I want to be able to understand the purpose of the website and know more about the campsite itself.  

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Tag Line text overlay on hero image | Navigate to the Home Page and locate the tag line, which is the overlay text on the hero image | View tag line and hero image | Works as expected; visitor understands the purpose of the website and gains knowledge of campsite|
| Welcome and about us message | Navigate to the Home Page and locate the welcome information | View Welcome message | Works as expected; visitor understands the purpose of the website and gains knowledge of campsite|
| General Information Section | Navigate to the Homapage | View the information section with the subheadings: Timings, Prices, Address | Works as expected; visitor gains knowledge of campsite |
| Facilities | Navigate to the Campsite page, locate the Facilities section with the font awesome icons | Locating the list of facilities and amenities that are on offer, promoting the campsite | Works as expected; visitor gains knowledge of campsite |
| Pitches image and list items | Navigate to the Campsite page, locate the Pitches section | View the image of the pitches and read list of types of pitches available | Works as expected; visitor gains knowledge of campsite |
| Frequently Asked Questions | Navigate to the Contact Page and locate the Frequently Asked Questions accordion. Click on the downward facing arrow to open the individual questions | Each question will open and collapse | Works as expected|
  
  <details><summary>Tag Line text overlay on hero image</summary>
  <img src="docs/user-story-testing/user-story-homepage-hero-image.png">
  </details>  
  <details><summary>Welcome message and about us</summary>
  <img src="docs/user-story-testing/user-story-about.png">
  </details>  
  <details><summary>General Information Section</summary>
  <img src="docs/user-story-testing/user-story-general-information.png">
  </details>
  <details><summary>Facilities</summary>
  <img src="docs/user-story-testing/user-story-facilities.png">
  </details>  
  <details><summary>Pitches image and list items</summary>
  <img src="docs/user-story-testing/user-story-pitches.png">
  </details>
  <details><summary>Frequently Asked Questions</summary>
  <img src="docs/user-story-testing/user-story-faq.png">
  </details>  
  <br>

4.  As a First Time Visitor, I want to know the price range of the campsite to decide if it is within my budget.     

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Prices | Navigate to the Home Page and locate the general information section. Within this, locate the Prices section| View the Prices information | Works as expected; visitor gains knowledge of the price range for the pitches available|
| Pitches image and list items | Navigate to the Campsite page, locate the Pitches section | View the image of the pitches and read list of types of pitches available | Works as expected; visitor gains additional knowledge regarding any additional fees, for a specific pitch type |

  <details><summary>Prices</summary>
  <img src="docs/user-story-testing/user-story-prices.png">
  </details>  
  <details><summary>Pitches image and list items</summary>
  <img src="docs/user-story-testing/user-story-pitches.png">
  </details> 
  <br>

5.  As a First Time Visitor, I want to know the address of the campsite and where it is located.      

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Address | Navigate to the Home Page and locate the general information section. Within this, locate the Address section| View the Address information | Works as expected; visitor gains knowledge of the address and can do additional research using Google Maps to locate on a map|

<details><summary>Address</summary>
<img src="docs/user-story-testing/user-story-address.png">     
</details>
<br>

6.  As a First Time Visitor, I to know what types of pitches are available to book.      

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Pitches image and list items | Navigate to the Campsite page, locate the Pitches section | View the image of the pitches and read list of types of pitches available | Works as expected; visitor gains knowledge of the types of pitches that are available |

<details><summary>Pitches image and list items</summary>
<img src="docs/user-story-testing/user-story-pitches.png">     
</details>
<br>

7.  As a First Time Visitor, I want to know what facilities are available and what the camp site offers.     

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Facilities | Navigate to the Campsite page, locate the Facilities section with the font awesome icons | Locating the list of facilities and amenities that are on offer | Works as expected; visitor gains knowledge of what facilities and amendities are on offer at the campsite. |

<details><summary>Facilities</summary>
<img src="docs/user-story-testing/user-story-facilities.png">     
</details>
<br>

8.  As a First Time Visitor, I want to get in touch and to have any potential questions answered.       

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact Form | Navigate to the Contact Page and locate the contact form, fill out all required fields and submit contact form | Data submited via contact form | Works as expected; Code Institute form submission confirmation page is displayed to the user once the form has been submitted correctly|
| Frequently Asked Questions | Navigate to the Contact Page and locate the Frequently Asked Questions accordion. Click on the downward facing arrow to open the individual questions | Each question will open and collapse | Works as expected|

<details><summary>Contact Form</summary>
  <img src="docs/user-story-testing/user-story-contact-form-2.png">
  </details>  
  <details><summary>Frequently Asked Questions</summary>
  <img src="docs/user-story-testing/user-story-faq.png">
  </details> 
  <br>

9.  As a First Time Visitor, I want to be able to navigate the site easily to find information.          

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Navigation Bar | Navigate to any page and locate the Navigation Bar at the top of each page | Name of page is bolded and a different colour to emphasise the current page | Works as expected; vistor can easily navigate the website|

<details><summary>Navigation Bar</summary>
<img src="docs/user-story-testing/user-story-navbar-2.png">   
</details>
<br>

#### Returning Visitor Goals

10.  As a Returning Visitor, I want to know what times of year the campsite is open and what time check in and check out is.          

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Timings | Navigate to the Home Page and locate the general information section. Within this, locate the Timings section| View the information regarding the seasonal opening times as well as the check in and check out times | Works as expected; visitor gains knowledge of the operational timings for the campsite|

<details><summary>Timings</summary>
<img src="docs/user-story-testing/user-story-timings.png">   
</details>
<br>

11.  As a Returning Visitor, I want to view a picture of the camp site for my upcoming holiday.           

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Pitches image and list items | Navigate to the Campsite page, locate the Pitches section | View the image of the pitches and read list of types of pitches available | Works as expected; visitor gains knowledge of the types of pitches that are available |

<details><summary>Pitches image and list items</summary>
<img src="docs/user-story-testing/user-story-pitches.png">     
</details>
<br>

12.  As a Returning Visitor, I want to access useful information and review the facilities on offer while planning for an upcoming holiday at the campsite.           

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Facilities | Navigate to the Campsite page, locate the Facilities section with the font awesome icons | Locating the list of facilities and amenities that are on offer | Works as expected; visitor gains knowledge of what facilities and amendities are on offer at the campsite. |

<details><summary>Facilities</summary>
<img src="docs/user-story-testing/user-story-facilities.png">     
</details>
<br>

13.  As a Returning Visitor, I want to find useful information regarding the local area surrounding the campsite, in order to plan what I’m doing on my holiday.           

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Local Area| Navigate to the Local Area page | View the welcome information and scroll down the page to find additional information regarding Glyndwr Town, Llŷn Peninsula Beach, Events and Things to Do| Works as expected; vistor gains knowledge about the local area surrounding the campsite|

<details><summary>Local Area</summary>
<img src="docs/user-story-testing/user-story-localarea.png">   
</details>
<br>

14.  As a Returning Visitor, I want to find useful information about the local town in order to plan my holiday.           

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Glyndwr Town| Navigate to the Local Area page. Locate the image and heading title 'Glyndwr Town'| View the image and information regarding the local town| Works as expected; vistor gains knowledge about the local townand can view a pleasing image to depict this|

<details><summary>Glyndwr Town</summary>
<img src="docs/user-story-testing/user-story-glyndwr-town.png">   
</details>
<br>

15.  As a Returning Visitor, I want to find useful information about the local beach in order to plan my holiday.          

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Llŷn Peninsula Beach| Navigate to the Local Area page. Locate the image and heading title 'Llŷn Peninsula Beach'| View the image and information regarding the local beach| Works as expected; vistor gains knowledge about the local beach and can view a pleasing image to depict this|

<details><summary>Llŷn Peninsula Beach</summary>
<img src="docs/user-story-testing/user-story-beach.png">   
</details>
<br>
<br>

16.  As a Returning Visitor, I want to find useful information regarding any events in the local area in order to plan my holiday.           

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Events| Navigate to the Local Area page. Locate the image and heading title 'Events'| View the image and information regarding the events that are taking place| Works as expected; vistor gains knowledge about any events that are taking place and can view a pleasing image to depict this|

<details><summary>Events</summary>
<img src="docs/user-story-testing/user-story-events.png">   
</details>
<br>

17.  As a Returning Visitor, I want to find useful information regarding things to do in the local area in order to plan my holiday.          

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Things To Do|  Navigate to the Local Area page. Locate the image and heading title 'Things to Do'| View the image and information regarding things to do in the local area| Works as expected; vistor gains knowledge about different things they can do and different activities they can take part it and can view a pleasing image to depict this|

<details><summary>Things To Do</summary>
<img src="docs/user-story-testing/user-story-things-to-do.png">   
</details>
<br>

18.  As a Returning Visitor, I want to follow up on my previous viewing of the website in order to make an enquiry and have any potential questions answered.           

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact Form | Navigate to the Contact Page and locate the contact form, fill out all required fields and submit contact form | Data submited via contact form | Works as expected; Code Institute form submission confirmation page is displayed to the user once the form has been submitted correctly|
| Frequently Asked Questions | Navigate to the Contact Page and locate the Frequently Asked Questions accordion. Click on the downward facing arrow to open the individual questions | Each question will open and collapse | Works as expected|
| Footer on any page| On any page scroll down to the footer at the bottom, click on the 'Submit an Enquiry link | Directed to the contact page | Works as expected; vistor is directed to the contact page, which opens within the same window and not a new tab, as it is an internal link|
  
  <details><summary>Contact Form</summary>
  <img src="docs/user-story-testing/user-story-contact-form-2.png">
  </details>  
  <details><summary>Frequently Asked Questions</summary>
  <img src="docs/user-story-testing/user-story-faq.png">
  </details>
  <details><summary>Footer on any page</summary>
  <img src="docs/user-story-testing/user-story-footer-contact-link.png">
  </details>  
  <br>

### Validator Testing
* #### HTML Validation
    The W3C HTML Markup Validator was used to validate the HTML code of the website. All HTML validation was successful, with no errors showing. However, for the homepage, campsite and local area pages there were warnings. This was due to the use of the headings being out of order. This was a learning I took away from this project and from web desing and development overall. I was able to re-order some headings and style them with targted CSS. With additional time, I would have fixed this and re-ordered all the headings. I plan to do this as part of the future development of this website.

    <details><summary>Home</summary>
    <img src="docs/validation/html-validation-homepage.png">
    </details>
    <details><summary>Campsite</summary>
    <img src="docs/validation/html-validation-campsite.png">
    </details>
    <details><summary>Local Area</summary>
    <img src="docs/validation/html-validation-localarea.png">
    </details>
    <details><summary>Contact</summary>
    <img src="docs/validation/html-validation-contact.png">
    </details>

* #### CSS Validation
    The W3C Jigsaw CSS Validator was used to test the CSS code of the website. All CSS validation was successful. However, there was a warning regarding the use of Google Fonts, which could not be validated. This did not affect the validation of the CSS code as it still passed with no errors found.  

    <details><summary>CSS Validator</summary>
    <img src="docs/validation/css-validator-no-errors.png">
    </details>
    <details><summary>CSS Warning</summary>
    <img src="docs/validation/css-validator-warnings.png">
    </details>

### Lighthouse
I tested my website using Lighthouse within Chrome Developer Tools. This allowed me to test for performance, accessibility, best practices and SEO (seacrh enginer optimisation). Initially, the performance score was the lowest at 85. This was due to the size of the images I was using, even though I had already compressed them down. I then converted the format of the images from jpg to webp format. This improved the performance quite a lot. The overall performance is: 93, 100, 100, 100.

![Lighthouse Testing](docs/validation/lighthouse-testing.png)

### Full Testing on Devices and Browsers
  The website was tested and functioned / performed well on Chrome, Edge and Safari.  

  Full testing was carried out on the following devices:

  * Laptop
    * Macbook Pro, 14 inch 2021, M1 chip
    * Dell Latitude 7420

  * Tablet
    * iPad (7th generation)

  * Mobile
    * iPhone 11

### Links
The internal links feature in the menu navigation bar, as well as the footer – to link to the contact page. The external links feature in the footer for the social media links, as well as on the homepage in the general information section, to link to the marine conservation society. All internal links have been tested and take you to the directed page within the website. All external links have been tested and open in a new tab.

| Link / Feature                  |  Test Case                      | Outcome                                                                    |
| :---------                      | :----------------               | :-----------------------------------                                       |
| Oakwood Cove Campsite           | Click on Brand Name             | User is brought to the homepage                                            |
| Home link                       | Click on Home link              | User is brought to the home page                                           |
| Campsite link                   | Click on the Campsite link      | User is brought to the campsite page                                       |
| Local Area link                 | Click on the Local Area link    | User is brought to the local area page                                     |
| Contact link                    | Click on the Contact link       | User is brought to the contact page                                        |
| Find out more information link  | Click on the link / bolded text | User is taken to the marine conservation website, opens in a new tab       |
| Facebook icon                   | Click on the icon               | User is taken to the homepage of the Facebook website, opens in a new tab  |
| Twitter icon                    | Click on the icon               | User is taken to the homepage of the Twitter website, opens in a new tab   |
| Instagram icon                  | Click on the icon               | User is taken to the homepage of the Instagram website, opens in a new tab |
| Submit an Enquiry link          | Click on the link / bolded text | User is brought to the contact page                                        |   

### Contact Form
* To find the form, navigate to the ‘Contact’ page in the menu navigation bar, or by click on the ‘Submit an Enquiry’ link in the footer.  
* Fill out all the fields, including your first name, last name and a valid ‘@’ email address. 

* If the form is completed properly, you will see the following message:  
    ![form submit message](docs/validation/form-correct.png)  
* If you try to submit without a first name or last name you will see the following message:  
    ![fill in name message](docs/validation/validation-contact-form-name-required.png)  
* If you try to submit without a valid ‘@’ email address, you will see the following message:  
    ![fill in email message](docs/validation/validation-contact-form-email-required.png)  
* If you try to submit a blank message without a description for your enquiry, you will see the following message:  
    ![submit enquiry message](docs/validation/validation-contact-form-message-required.png)  

### Solved Bugs
1.	Nav Bar Section  
On the “Local Area” and “Contact” page, there was no clear distinction between the Nav Bar and the Main Body. To fix this, there was an iterative design process of the website, which was improved upon by adding in a < hr > tag to cover the whole width of the page. This was not added to the “Home” page and the “Campsite” page, as the hero image acts as the section break after the Nav Bar and before the main body text. Therefore, it was deemed unnecessary. This also incorporates the brand and the theme and creates a more cohesive look.  

2.	Footer  
At first, the social media icons were too close together. This caused an issue particularly on small devices, as it was difficult to distinguish which link you wanted to click on. This was fixed by increasing the size of the icons and adding padding to create more space between the < a > links.  

3.	Campsite page – Facilities section  
At first the columns for the facilities section were too close together making the text look squashed together. This made the section itself quite short in comparison to the hero image and the pitches section. This was fixed by adding padding to the top and bottom to the bootstrap columns to create more space in-between the font awesome icons. Furthermore, the overall vertical alignment of this section of the page is now more balanced as it is taller than before.  

4.	Main Page - General Info Section  
On a mobile device there was not enough room between the general info sections, in particular between the middle section in relation to the top and bottom sections. This was fixed by increasing the margins with the bootstrap classes to add spacing in between the columns, when on a small device in a stacked view.  

5.	Local Area - Cards  
Both the “Glyndwr Town” and “Events” cards were the same height and the “Llŷn Peninsula Beach” and “Things To Do” cards were the same height. However, all four cards were not the same height as each other due to the differing amount of text. To fix this, the Bootstrap class of ‘h-100’ was added to each individual card, to make the height equal and all the same.  

6.	Contact Us – Main Body  
I wanted to add a < hr > tag between the FAQ and Contact sections on a small device, as when they were stacked on top of each other, there was no clear distinction between the two sections. However, when adding the < hr > it worked for the small device, but it pushed the Bootstrap grid columns out of alignment on the medium and large devices. This was solved by using a media query to hide this < hr > tag from view on medium and large devices, and to only have it visible on small devices where the sections are stacked on top of each other. A border was not added to the Bootstrap columns themselves, as this wasn’t necessary to distinguish between the sections for the medium and large devices.

## Technologies Used

### Languages Used
* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS#CSS_3)
* [Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
* [Markdown](https://en.wikipedia.org/wiki/Markdown)

### Applications Used
* Git was used for version control.  
* [Github](https://github.com/) was used to store the code.  
* [Gitpod](https://www.gitpod.io/) was used for the CI template and to access VS code.  
* [VS Code](https://code.visualstudio.com/)was used as a code editor.  
* [Balsamic](https://balsamiq.com/) was used to create Wireframes.  
* [Image Compressor](https://imagecompressor.com) was used to decrease the dimensions and size of the images used for the website.  
* [Convertio](https://convertio.co/) was used to convert the image file types from jpg to webp format.  
* [Am I Responsive](https://amiresponsive.co.uk/) was used to display all the pages of the website on different devices. 
* [W3C HTML Markup Validation](https://validator.w3.org) was used to validate the HTML code of the website.
* [W3C Jigsaw CSS Validation](https://jigsaw.w3.org/css-validator/) was used to validate the CSS code of the website.
* [WebAIM Wave Accessibility](https://wave.webaim.org) was used to evaluate the accessibility of the website to ensure it is up to high standards.
* [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) was used to check the contrast of the colours used in the design of the website.

### Frameworks, Libraries and CDNSs
* [Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/) is used throughout the website for template code and responsiveness. This includes the Accordion, Navigation Bar, Card, Containers and Footer. All Bootstrap elements are styled using either Bootstrap CSS or custom CSS.  
* [Google Fonts](https://fonts.google.com/) was used to import the three fonts used into the website.  
* [Font Awesome](https://fontawesome.com/) was used to add icons for visual representation and aesthetic purposes.  

### VS Code Extensions
* [Prettier](https://prettier.io) – was used for code formatting and code completion. 
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) – was used for live previewing the site during the build process. 


## Deployment & Local Deployment
  * ### Deployment
    
    The live website was deployed to Github Pages, by following the below instructions:

    1. Log in (or sign up) to Github.
    2. Find the repository for this project, K-Coll/mp1-oakwood-cove-campsite
    3. Click on the Settings link.
    4. On the left hand side of the navigation bar, click on the Pages link.
    5. In the Source section, choose main from the drop down select branch menu. Select Root from the drop down select folder menu.
    6. Click Save. Your live Github Pages site is now deployed at the URL shown.

  * ### Local Deployment
    * ### How to Fork
      To fork the Oakwood Cover Campsite repository:

      1. Log in (or sign up) to Github.
      2. Go to the repository for this project, K-Coll/mp1-oakwood-cove-campsite.
      3. Click the Fork button in the top right corner.
  
    * ### How to Clone
      To clone the Oakwood Cove Campsite repository:

      1. Log in (or sign up) to GitHub.
      2. Go to the repository for this project, K-Coll/mp1-oakwood-cove-campsite.
      3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
      4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
      5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

## Credits
###  Learning Resources
* [W3 Schools](https://www.w3schools.com) – used for problem solving.  
* [Stack Overflow](https://stackoverflow.com)– for troubleshooting issues and problem solving.  
* [Code Institute Slack Community](https://slack.com/intl/en-gb) – for problem solving and user feedback.  
* Code Institute Love Running Project – for inspiration / adaptation regarding the hero image text overlay.  
* Code Institute Whisky Drop Project – for inspiration and Bootstrap grid system.  
* Code Institue Rosie Resume – for inspiration and Bootstrap grid system.  
* [YouTube: Code used for Footer](https://www.youtube.com/watch?v=X3K5KCRYtRk) – adapted from and inspired by
* [How to make footer stay at bottom of page](https://radu.link/make-footer-stay-bottom-page-bootstrap) – code used.  
* [YouTube: Responsive image and text side by side using HTML and CSS](https://www.youtube.com/watch?v=-A_HESNP1T8) - Code used.
* [Article: Introducing Accessibility in Typography](https://fonts.google.com/knowledge/readability_and_accessibility/introducing_accessibility_in_typography).  
* [Article: Accessible Fonts](https://www.anphira.com/tutorial/accessible-fonts-select-website-font/).  
* [Article: Top 6 UI Fonts for Minimalist Interfaces](https://sparklin.medium.com/top-6-ui-fonts-for-minimalist-interfaces-in-2023-22c72f7620c2).  
* [Article: Typography](https://design.gccollab.ca/component/typography/).  

### Content Used
All text content was written by the developer and is fictional.  

## Acknowledgements
* My mentor Mo Shami.  
* Code Institute Cohort Facilities Kristyna and cohort friends for their motivation and support, as well as our weekly meetings, which I look forward to attending.  
* The Code Institute Slack Community, both directly and indirectly. I was able to search the community and find help as well as ask directly in the various channels for specific issues. This is a supportive environment and community which helped me with problem solving.  
* My mum, family and friends for their support and encouragement.  
