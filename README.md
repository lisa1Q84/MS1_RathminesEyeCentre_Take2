# **Rathmines Eye Centre Website**



# Table of content:

   [Description]
-   [User Experience]
    -   User Stories
    -   Strategy
    -   Scope
    -   Structure
    -   Look
    -   Surface
-   [Technologies]
-   [Testing]
-   [Bugs]
-   [Deployment]
-   [Credits]

## Description

Rathmines Eye Centre is an optician in Dublin 6. Their website is meant to showcase their services and products and offer customers a way to get in touch and book appointments. Their old website deserves an upgrade which is why this project was taken on. The current website can be viewed [[here]](http://www.rathmineseyecentre.com/).

The newly created live site can be viewed  [\[here\]](https://lisa1q84.github.io/MS1_RathminesEyeCentre_Take2/). This site was designed as a project to be submitted for grading in the first milestone project in Full Stack Software Development with the Code Institute.

## User Experience

----------

**USER STORIES**

----------

External User Goal: 

1.   Customers want to easily navigate through the site
    
2.  Customers want to see what kind of services and products are offered
    
3.  Customers want to know the optician who will evaluate their sight
    
4.  Customers want to know where to find the Rathmines Eye Centre and how to get in touch for an appointment.
    
5.  Customers want to have information about sight-related topics.
    

Business Owner Goal:

1.  The business owner would like to offer a portal for clients to book eye-appointments.
2.  The business owner  would like to advertise his services and increase walk-in customers.
3. The business owner would like to advertise his contact details and location.
3.  The business owner would like to inform potential and actual clients about important eye related questions.
4.  The business owner would like to establish trust with potential customers.
5.  The business owner would like customers to know exactly where he is located.

----------

**STRATEGY**

----------

The main focus of this project is to provide a simple, informational website for the Rathmines Eye Centre to increase their appointments and sales and make it easier for customers to make contact/ find them.  

During Covid-19 the number of walk-in customers has surely decreased and it is harder to attract customers from the street as more and more people stay indoors. Before making contact with any optician, potential customers will do some online research about opticians in their area and this website could help attract them to come to Rathmines Eye Centre. 

----------

**SCOPE**

----------

Features:

-   Navigation menu – a basic and easily visible navigation menu offering the user the ability to access the areas in the scroll-down site immediately .
    
-   Footer - There will be a footer containing contact details , their social link (REC only have facebook) as well as information about current Covid-19 opening times (as well as a request for customers to wear a mask, make appointments and not come when they are feeling unwell. 

The sections will be:
    
-   Home - A big image of the shop as well as a short description to catch the users attention
    
-   Services – A section with icons describing the services offered in REC

-   Carousel - Meant to be a break between services and products the carousel is not a menu point but more a separation unit including three clickable photos with customer reviews from Google Reviews overlaid. 
    
-   Products - A short description of the products and brands that are sold in REC.

- FAQs - An expandable section (to not take too much space in the mobile view) with the most frequently asked questions from customers.

- Contact - A section including a map, the address and opening times of the eye centre

----------

**STRUCTURE** 

----------

The site must full-fill the goal to attract customers  without being too pushy. This is why, after trying thinking about adding a "book an appointment button or a call to action banner, I decided to not to add them after all and instead try to be more informative (adding the Reviews and the FAQ) to build trust with the customer.

I decided to include a journey that takes turns with advertising services and products and building trust. This is why the site is organised in this specific way:

-Meet the optician
-Services
-Review Carousel
-Products
-FAQs
-Contact Form


The clear, scrollable site makes it easy for the customer to arrive to the contact form without desperately pointing to it. 


**LOOK**

----------

The website for eye-care professionals needs to be friendly and inviting but serious enough to look trustworthy.

Colours:

-   To go with the Eye clinics shop design (black and white) I will be using a palette of black, white and blue - to add some colour and to make it look friendlier.

Typography:

-   Space Mono font is used on the menu and the headings to give the page a unique, playful and modern look.
-   Roboto, being more clean, will be used for content in the main body of the page with Sans Serif as the backup. 

I found the two of them to pair nicely together when trying them together on google-fonts.

Effects:

There is a hover effect over the menu items in the navigation bar as well as a number of font-awesome icons next to headlines. 

Imagery:

-  I will use an image I took myself of the storefront  of the Rathmines Eye Centre, a photo of the optician from their facebook page ( we did not manage to take a fresh one) as well as generic images containing glasses and lenses from websites offering free stock images. I mentioned the creators in the credit section below.


## Technologies

-   HTML5 – I used HTML to create the websites main structures
-   CSS3. – I used CSS to style the components created with HTML 
-   GitPod – Used for writing the code
-   GitHub – Used for hosting the files used for the website.
-   Bootstrap – I used Bootstrap 4 as a framework
-   FontAwesome - I placed icons from this library next to several headlines and in the footer.
-   Google Fonts – I used Roboto and Space Mono One SC 
-   Git – Version control used to track changes, commit and push code to Github.
-   W3 HTML Validation was done via  [https://validator.w3.org/](https://validator.w3.org/)
-   W3 CSS Validation was done via  [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/)  
- The Rathmines Eye Centre Logo was created with https://www.canva.com/ as they had none.


## Testing

All testing was documented in a separate filed that can be accessed [here.](https://github.com/lisa1Q84/MS1_RathminesEyeCentre_Take2/blob/master/TESTING.md)

## Bugs

Bug: Scrollbar on the bottom when in the mobile view. Fixed this by moving the image width and height to CSS and by making them smaller. 

Bug: Carousel images look stretched in mobile view. I did not find out how to fix this because every attempt to fix it ended in me disabling the carousel. I kept it because the important part in the carousel are the reviews. 

Bug: I tried to activate the menu (so that the menu item that the user is on is highlighted) but was not able to so now the menu does change colour only when hovering on the items.

Bug: On creating a parallax effect for the background when scrolling rather than keeping the background fixed there is a white band being pulled up when scrolling to bottom.  
Fix: Changed position on the ‘sales-pitch’ element from ‘absolute’ to ‘relative’.


## Deployment

The following steps were taken to deploy the website.

1.  Create a GitHub account at  [https://www.github.com](https://www.github.com/). locate the MS1_RathminesEyeCentre_Take2 (There was a Take one that unfortunately was lost) repository for the website. You can find the link here:
[Rathmines Eye Centre Take2 Repository ](https://github.com/lisa1Q84/MS1_RathminesEyeCentre_Take2)
2.  Click on the setting cog in the centre right near the top of the page.
3.  Scroll down to the section that says GitHub Pages.
4.  Ensure 'branch: master' is selected.
5.  Click 'Save'
6.  The site link will be displayed above this section where is says 'Your site is published at - .....'
7.  Click the link to open the website in a new tab and the website is deployed!

More information on github pages can be found  [here](https://pages.github.com/).

Run in Gitpod:

1.  Create a GitHub account at  [https://www.github.com](https://www.github.com/).
2.  Install the gitpod browser extension for Chrome browser.
3.  Restart the Chrome browser.
4.  Log into  [GitPod](https://www.gitpod.io/)  using your GitHub account.
5.  Next open GitHub and locate the DoggyStyle repository for the website at  [https://github.com/raymondkeogh/doggystyle](https://github.com/raymondkeogh/doggystyle)
6.  Click on the green GitPod button in the top right hands side of the screen.
7.  This will open a new GitPod workspace with the DoggyStyle respository files in it.

Run in Local IDE:

1.  GitHub and locate the DoggyStyle repository for the website. The link is here:
https://github.com/lisa1Q84/MS1_RathminesEyeCentre_Take2
3.  Click on the the button near the top of the page that says "Code"
4.  In the box that pops up under the HTTPS section copy the URL.
5.  In your local IDE open the command terminal.
6.  Change the working directory to the location where you will be working on the project.
7.  Type in 'git clone' and the url you got from the HTTPS popup from the code button.
8.  Press enter to create you local clone.
9.  Happy Coding!

## Credits

**Code used**

I used this bootsrap carousel code (the one with Indicators)  but added and overlay and the quotes:

https://getbootstrap.com/docs/4.0/components/carousel/

I altered this bootsrap code for my navbar. [[https://getbootstrap.com/docs/4.0/components/navbar/](https://getbootstrap.com/docs/4.0/components/navbar/)] ([https://getbootstrap.com/docs/4.0/components/navbar/](https://getbootstrap.com/docs/4.0/components/navbar/))

I used this code to help create the scrolling effect on the website.  [https://www.w3schools.com/howto/tryhow_css_parallax_demo.htm](https://www.w3schools.com/howto/tryhow_css_parallax_demo.htm)  

I used code snippets from here when struggling to align my columns: https://coreui.io/docs/layout/grid/#equal-width

**Content**

All text content was taken from the original Rathmines Eye Centre website: http://www.rathmineseyecentre.com/  with the owners permission. For the "Meet the optician section I wrote a fictional bio as Mr. Hugh has not had the chance to send me a real one. 


Image for the logo was created on Canva by myself. You can see it [here.](https://github.com/lisa1Q84/MS1_RathminesEyeCentre_Take2/blob/master/assets/images/logo.png)

The main image for the website was taken by myself as they had no photos of their shop that was big enough. 

The carousel images were taken from:
https://www.pexels.com/photo/different-choices-of-eyeglasses-1627639/ 
https://www.pexels.com/photo/assorted-sunglasses-704241/
(Photographer: Francesco Paggiaro)


and the product images from:
https://www.pexels.com/photo/dawn-man-person-love-5843352/ ([](https://www.pexels.com/@n-voitkevich)
(Photographer:Nataliya Vaitkevich)
and https://www.pexels.com/photo/photo-of-man-wearing-eyeglasses-910143/ (Photographer:  Philip Boakye)

The photo of Dr. Hugh was taken from : https://www.facebook.com/rathmineseyecentre/


**Acknowledgements**

I would like to thank:

-   Code institute for giving me the chance to learn something entirely new, my mentor Ignatius for his support and my friends for making me a lot of coffee. 

- Rathmines Eye Centre for allowing me to use their website content and images for my project.


> Written with [StackEdit](https://stackedit.io/).
