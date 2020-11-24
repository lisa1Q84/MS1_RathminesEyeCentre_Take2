# Rathmines Eye Centre Website MS1 - Testing Details

## **How did I test?**

[W3C Markup Validation Service](https://validator.w3.org/)

-   W3C Markup Validation Service has been used for the testing of the  **HTML**  and  **no error**  was found. The result can be seen here  [\[HTML Test\]](https://github.com/lisa1Q84/MS1_RathminesEyeCentre_Take2/blob/master/assets/images/HTML_TEST.png)

[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)

-   W3C CSS Validation service has been used to check the  **CSS**  of the project and  **no error**  was found. The result can be seen here.  [\[CSS Test\]](https://github.com/lisa1Q84/MS1_RathminesEyeCentre_Take2/blob/master/assets/images/CSS_TEST.png) 

The Project was tested for Browser compatibility. It was found that "the CSS `transform:` property is not supported by some older browsers" and "The `display: flex` CSS property does not work correctly in some browsers."

Other than that it was suggested to make improvements in the area of Search Engine Optimisation by adding more links and headlines and offering a HTML site map. This is something I would look into in the future as this would be good for Rathmines Eye Centre to be found easily in Search Engines to gain more customers. 

**Client Stories Testing**

Testing client stories from UX part of README.md

1.  Customers want to easily navigate through the site
    
    -   The Navigation Bar is always fixed on top of the page, It doesn't matter what section of the site they are in.
    -   All menu links are linked to the different sections of the page, so it is easy to move anywhere and to get back up.
    
2.  Customers want to see what kind of services and products are offered
    
    -   There is one section with the offered services, short and simple with eye-catching icons.
    -   There is one sections "products" shortly explaining the type of glasses and lenses customers can buy in REC, including the brands that are being sold. 
    
3.  Customers want to know the optician who will evaluate their sight
    
    -   There is an about section with a photo, introducing the optician, outlying his qualifications and establishing a first level of trust between him and new customers. 
    - Another added level of trust is established when customers read the Carousel Review section (with reviews taken from Google Maps).
    
4.  Customers want to know where to find the Rathmines Eye Centre and how to get in touch for an appointment.
    
    -   A dedicated section shows the Eye Centre on the map below the address and lists the opening times.
    - The Footer has additional information including the phone number, the email address and special regarding Covid-19.
    
5.  Customers want to have information about sight-related topics.
    
    -   There is an expandable FAQ section with the most common questions customers may have when looking for an optician appointment.
    

**Manual Testing of all elements and functionality of every page.**

-   **Navigation Bar**
    
    1.  Check if the  **navbar**  is situated always on top (slightly down to have the attached logo show fully)
    2.  Click The  **Logo**, check if the home page opens.
    3.  Click the  **Home link**  on the menu bar, the page should remain on the home page.
    4.  Click the  **Meet**, make sure the Optician section opens.
    5.  Click the  **Services**, check if the columns are aligned and the text is well visible below them.
    6.  Check the  **Products**, see if the photos are aligned and have the right size.
    7.  Click the  **FAQs**, check if the accordion parts expand when clicking on the link.
    8.  Check for  **Responsiveness**, see if the Nav bar toggles correctly and vertically and if everything is clickable.
    9.  Check the **Carousel**, see if the slides are clickable and if the quotes on top of the images are readable. 
    10. The collapsed bar in mobile view is checked for its links, It does not collapse back after clicking on a link. This can be viewed as an  **open bug**  in the navbar.
    11. 

-   **Meet the Optician Section**
    
    1.  Check  **full name**  and spelling.
    2.  Check the  **address**  given.
    3.  Check the  **Phone Number**  provided. If it is a valid number.
    4.  **Email link**  check, if it opens a default Email client.
    5.  Click the  **Github**  link provided, if it opens the Github of the applicant in a different window.
    6.  Click the  **Linkedin**  link provided, if it opens the Linkedin profile of the applicant in a different window.
    
-   **Services**
    
    1.  Check the responsiveness of the image by reducing the size of the screen.
    
-   **Carousel**
    
    1.  Go to the project section of the site.
    2.  Click Image of the project, it should open the live  **URL**  of the project in a different window..
    3.  Click on the name of the project, it should open the  **Github repository**  of the project.
    4.  Repeat steps 2 and 3 for the second project.
    5.  Repeat steps 2 and 3 for the third project, the name of the project should open  **Repl.it repository**  of the project.
    6.  Check responsiveness by reducing screen size, all images and content should come one by one in small screen size.
-   **Products**
    
    1.  Check the content in the blog.
    2.  Check spelling by online spelling and grammar checker  [Grammarly.com](https://app.grammarly.com/). Few spelling mistakes were found, which were corrected.
-   **Contact**
    
    1.  Check  **Email**  address by clicking on it, a default email client opens.
    2.  Check the  **Contact form**  by putting the name in the  **name section**.
    3.  check contact form by putting email id in the  **email section**.
    4.  check the  **project description**  section by writing some text in it.
    5.  Click the  **Send Project Request button**, Check if it opens the Home page.
    6.  Click the button without filling any section, A pop up  **"Please fill out this field"**  opens.
    
-   **Footer**
    
    1.  Check if the footer is always situated at the bottom of the page by scrolling up and down.
    2.  Check the download link on the footer, pdf should open in a different window.
    3.  Click the  **Linkedin**  link on the footer, my Linkedin page should open.
    4.  Click the  **Github**  link in the footer, my Github link should open.
    5.  Click the  **Twitter**  link in the footer, Home page of twitter should open.

**Project Barrier**

-   Due to a problem with my image sizing, on the mobile version there was a horizontal scroll bar and it took me quite long to find the root cause.

-   The navigation links were bringing the user to the wrong section of the page when clicked so that I had to manually place anchors in each pervious section. In the future I would like to try find another solution to that.
    
- Due to poor time management from my side and a busy schedule of my mentor I was unable to have the last mentor session before the project. In the future I will work on better time management. 

- I tried to add an active menu but was not able to find out how to do it. There are many threads on how to do it but I was not able to implement it correctly I believe. 
    

**Bug report**


- The navbar is not collapsing back after clicking on it, in the mobile view.



