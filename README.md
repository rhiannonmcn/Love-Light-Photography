# **_Love Light Photography - Project Portfolio 1 - HTML & CSS_**
Love light photography is a small profesional photography business that offers a wide range of photography services. This site targets the average individual who is looking to capture their event with high quality photography, with a professional but friendly and approachable manner, with a means to see samples of photographs and contact the photographer directly.

You can view the live site here - <a href="https://rhiannonmcn.github.io/Love-Light-Photography/" target="_blank"> Love Light Photography </a>

![Love Light Photography responsive design](assets/images/readme-images/responsive-website-view.png)

# Objective

In this project I aim to deliver a professionaly developed website for users to access a friendly but professional photography service. The main objective is to exhibit a proficiency in HTML AND CSS.

# User Experience (UX)

## Design Prototype

The design for this website were compiled in Adobe XD. The designs produced were low wireframes and a high fidelity wireframe for the homepage for desktop versions only.

## Site Structure

Love Light Photography consists of 5 page website with 4 pages that the user can navigate between via the navigation bar.  The Home page is the default loading page. The Logo is centered and is also linked to the Home Page. On the left hand site of the logo are two navigation links of [Home](index.html) and [Packages](packages.html). And on the right side of the logo are another two navigation links of [Gallery](gallery.html) and [Contact](contact.html).

## Design Choices

* ### Colour Scheme
    The final colour schem chosen was a dark teal with an off white text, as well as off white and light grey to segment pages. Two lighter teal colours were used on the navigation bar to highlight the active page and for the hover effect. This colour scheme is very on trend with the clean and modern look but still has that hint of warmth by sticking to the warmer tones of teal, greys and whites.

![Colour palette image of 6 colours](assets/images/readme-images/colour-palette.png)

* ### Typography
    There were two types of fonts chosen for this website. 'EB Garamond' was used for the body text and 'Cormorant Garamond' for the headings, which is only a slightly different version Garamond than the body text to provide emphasis. Both fonts fall back to 'sans-serif'. The Garamond fonts have a slightly luxurious feel to them and the serif detail, provides a small bit of complexity to the design but with making use of letter spacing and line heights to still keep it in line with the clean look.

# Features

Love Light Phtography is designed and structured like a typical website, making it very natural and intuitive to use to entice the user to explore further.

Each page, except the Home Page has a clear title when landing on the page and short paragraph introducing the content. The language, colour and design used is intended to be friendly and easy to understand.

## Navigation

* The navigation menu is featured at the top of the page and contains the links to main content.

* The logo is centered in the navigation bar and is clickable and links back to the homepage.

* There are three variations of the navigation bar for different screen sizes, and each keep the same colour and design styles with only the structure changing to keep the user experience as smooth as possible.

## Home Page

 * The Home Page is the landing page of the website and the first part that the user will see. It is designed to be welcoming and the purpose of the website easily determined.

 * There is a large hero image chosen both for its style and colour scheme and tone to match the website itself immediately visible and on top of that the site name and catchy slogan.

 * There is a bit of content peeking just above the fold to show users that there is more information on the page. This is a quote designed to give off the intended feel of the website to the user; essentially the ethos of by which the business stands by.

 * There is a section to "Meet the Photographer" which is a succint about me section intended to put the user at ease, keep the welcoming vibe whilst still imparting useful information.

 * The last seection on the Home Page is a Stories section, which provides three different testimonials.

 * The aim of each of these sections of the Home Page is to create a feeling of welcoming and friendliness and to encourage the user to explore the website in the hopes of hitting that Contact Page.

 * Each section is fully responsive, with the multiple column content naturally falling into a single column.

## Packages Page

* The packages page is as described in its navigation link. It lists the available services in a clear manner.

* There is a list of the available packages, using clear colour design elements to distinguish the different packages, as well as headings, images and text.

* It is fully responsive and each package section naturally falls into a single column, with the same clear colour design elements to distinguish each package.

* This page is intended to impart the idea that this service is welcoming, friendly and the perfect fit for what the user is looking for.

## Gallery Page

* The Gallery page provides the user with some sample photography from the photographer. It gives a mix of different events in one large gallery.

* The gallery is easy to use, with a hover function on the images drawing the users eye to the cursor.

* The Galloery page is fully responsive and as the screen reduces in size the columns of images reduce until mobile size where the images are full width.


## Contact Page

* The Contact page is where we want the user to end up. As there is no booking system or online store to purchase a package we want them to contact the business.

*  The contact form is modelled off the usual contact form layout, with four input fields; First Name, Last Name, Email Address and Your Message.

* The contact form cannot be submitted unless the fields are filled correctly using the required attribute.

* The form also uses a GET function to link to a Thank You page. There is no actual information submitted when the user completes the form and the thank you page is purely to show how the user will interact with the form.


* Beside the contact form there are practical details such as a dummy phone number and email. The email has a mailto link which opens to the users default mail software on their device, againing using a dummy email for the purpose of user experience.

* There is also a google map frame beneath the Location section.

* The page is fully responsive with the sections stacking upon each other as the screen size is reduced, keeping the same design elements which distinguish between the different sections.

## Thank You Page

* The Thank You page cannot be accessed by the user from any links on the website. It can only be accessed by submitting the contact form on the Contact page.

* The style and design of the website is consistent, with the navigation bar on top and footer on the bottom so as to allow the user to navigate back to the main website.

## Footer

* The Footer contains the social media links.

* For better UX design, each of the social media links open in a new tab.

* The Facebook, Instagram and Youtube links are purely for educational purposes of the website and only navigate to the home page of each of the sites.

* It also contains an email link which uses a mailto function to open the devices preferred email software. The email used is just a dummy email to show how the user interacts with the link.

# Future Features

* The Stories section on the Home Page could be made a bit more interactive with more stories that could be rotated through.

* The gallery can be expanded whereby a lightbox function can be implemented to achieve a greate user experience and interactivity with the images.

* A Log In could be added whereby clients would have access to their photos of their event in a private gallery. 

# Technologies Used

* HTML5 - Delivers the structure and content for the website.
* CSS3 - Provides the styling for the website.
* Adobe XD - Used to create wireframes for the website
* Adobe Illustrator - Used to create the Logo and social media assets for the website.
* [Adobe Color](https://color.adobe.com/create/color-contrast-analyzer) - Used to test the contrast and a blind safe colour check for the colour palette used.
* Adobe Lightroom - Used to optimise and resize images for screen.
* [Tiny PNG](https://tinypng.com/) - Used to further compress optimised images.
* Gitpod - Used to develop the website.
* GitBash - Terminal used to push changes to the GitHub repository.
* Github - Used to host and deploy the website.

# Testing

## Code Validation

Love Light Photography has been validated via W3C HTML Validator and the W3C CSS Validator. There were 8 minor errors that came up for all of the pages. This was immediately corrected and documented down below.

## Lighthouse Testing

The website was also put through Lighthouse testing via Chrome Devtools which tests a site under 4 different headings; Performance, Accessibility, Best Practices and SEO and it tests it under mobile and desktop criteria.

## Accessibility Testing

[A11y](https://color.a11y.com/) was ussed to check the colour contrast on the website for accessibility purposes.

## Responsive Testing

Responsiveness was tested via a few different mediums manually, including Chrome Devtools, The viewport resizer chrome extension and [The Responsive Design Checker](https://responsivedesignchecker.com/) website. 

## Manual Testing

In addition to the autmated process above, I carried out manual testing on the site as well.

* Naviagtion Menu
    * Verified that all the links link to the appropriate page with no broken links on all pages.
    * Verified that the logo when clicked links back to the Home Page.
    * Verified that the logo image has an alt text and fallback image for non browser support of the svg file.
    * Verified that the hover effects are consistent on all links.
    * Verified that the active page is highlighted.
    * Verified that the navigation bar is full responsive.

* Home Page
    * Verified that the Hero image is not pixelated and is fully responsive.
    * Verified that all images on the home page are optimised and have alt functions.
    * Verified that all the elements are fully responsive

* Packages Page
    * Verified that all the images are optimised and have alt texts. 
    *Verified that all the elements are fully responsive.

* Gallery Page
    * Verfied all the images are optimised and have alt texts.
    * Verified that all elements are fully responsive.

* Contact Page
    * Verified that contact form cannot be submitted without the required information (First Name, Last Name and Email Address)
    * Verified that once the information is submitted via contact form, that the GET function works correctly and retrieves the thank you page.
    * Verified that the mailto function works correctly on the email link.
    * Verified that the page is fully responsive.

* Thank You Page
    * Verified that the thank you page is linked correctly to the contact form.
    * That the Thank You Page is fully responsive.

* Footer
    * Verrified that the email asset links properly with the mailto function.
    * Verified that the social media links are all linked properly to the releveant social media home pages.
    * Verified that all the social media links open in a new tab.

* Browser Testing

Love Light Photography has been manually tested in Google Chrome, Microsoft Edge, Mozilla Firefox and Safari.

    * Verified that all images worked correctly
    * Verified that design and structure was consistent across all browsers.
    * Verfied responsiveness across all browsers.

* Bugs Fixed

### HTML Validation
    The following error was presented once the website was placed through W3C HTML Validator.

    The problem was googled and an answer found in stack overflow helped solve the issue. To rectify this the width and height attributes were added to the footer asset images.

    This resolved the error above but produced a new error. The one below.

    It said that the width and height attributes in the footer images produced " Expected a digit but saw p instead". Once I removed the px from the width and height attributes, it cleared that error up.

### Resonisiveness
    Chrome Devtools was initially used to test the responsiveness of the website. However it proved to be somewhat inconsistent with results despite no code being changed. Therefore another Chrome extension was used, Viweport Resizer and a website, Responsive Design Checker was used in conjunction with Chrome Devtools to make sure the website was fully responsive.

    There was overflow issues that couldnt be dermined easily once certain screen sizes were reached, the mobile screen size. To help identify the overflow issues a piece of code was used to outline all the elements on a page, allowing the elements that didnt line up to be identified.

# Deployment

# Credits

# Acknowledgements

