![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


Fonts from google fonts
Pictures are all my partner's work

# Bespoke Brushwork

At Bespoke Brushwork we have passion for paintwork, creating the best designs in a range of formats for our customers. Our goal is to ensure you are completely satisfied with a stunning and unique art-piece you can appreciate forever, be it as a fond memory of a marked occasion or simply a beloved decoration.

We cater to a wide variety of clientele, be it a spouse marking an anniversary with an intimate, personalised piece, or a beautifully stylised sign to mark your Christmas party at work.

The aim of the Bespoke Brushwork web-service is to connect our clients with our skilled artist and to have open and evolving conversations with people about their artistic needs. We are not limited to paintwork nor are we limited to a particular art style. We want our customers to have faith in the quality of our work, exemplified across the site, and to either order a piece to be specially made and collected/delivered, or to have their home or place of work become the art via window, mirror, or mural work.

![Responsive Mockup](assets/images/readme/full-mock-up.png)

## Features 

- __Navigation Bar__

  - Featured on all three main pages and the supplementary confirmation page, the fully responsive navigation bar includes links to the Logo, Home page, Gallery and Enquire page and is identical in each page to allow for easy navigation.
  - This section allows the user to easily navigate across all pages and all devices without having to revert via the ‘back’ button.
  - The nav forms a burger menu which can be dropped down to optimise use of space on smaller screens, and has a responsive hover selector that causes the different menu options to light up when hovered over on large screens.
  - Each page has a 'live' class, that indicates to users which page they are currently on improving their experience.

![Nav Bar](assets/images/readme/nav.png)
![Nav Bar on smaller screen](assets/images/readme/burger-nav.png)

- __The Landing Page Slideshow__

  - The focus of the landing page is a slideshow of some of the artist's work, overlaid with some text to indicate to users what to expect from the site.
  - This section, which, along with the About Us and Services sections, makes up index.html, introduces the user to Bespoke Brushwork with an eye catching animation that cycles through several different art-pieces to grab their attention.
  - The slideshow is responsive, on larger screens showing two images at a time, this was done by halving the width and action percentages of the animation in a media query, and on smaller screens one at a time.
  - It allows users to immediately see some of the types art they can request as well as the different styles and quality of the pieces.

![Landing Page](assets/images/readme/desktop.png)
![Landing Page including image slideshow](assets/images/readme/desktop-alt.png)

- __About Us Section__

  - The About Us section allows the user to learn a bit about Bespoke Brushwork as an organisation, including our passion and goal.
  - The section is responsive, has readable colour contrast, is in keeping with the overall colour theme, and contains links to the gallery and enquire pages to assist with the user journey.
  - This user will get a taste of the range of art-services we provide, which should encourage and inspire them in selecting art they'll love. 

![About Us](assets/images/readme/about-us.png)

- __Services Section__

  - This section will give the user a non-exhaustive list of some of the different art-styles, applications and events available to request a commission from Bespoke Brushwork. 
  - The section is clearly readable, responsive and has a faded facade of one of the artist's pieces in the background. 
  - The code for the structure of this piece is taken from the meetup times section of the love-running code institute project.

![Some of Our Services](assets/images/readme/services.png)

- __The Footer__ 

  - The footer section includes links to the three main social media sites. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media.
  - Currently these only link to the homepages of the respective social media sites, in time, we will create pages on each application for Bespoke Brushwork and link them to the sites. See [Features Left to Implement](#not-yet-implemented).

![Footer](assets/images/readme/footer.png)

- __Gallery__

  - The gallery, gallery.html, will provide the user with supporting images to see a broader range of the available art styles and the skills of the artist. 
  - This section is valuable to the user as they will be able to scan for ideas for their own art selection, the quality of the work, the variety of colours and the responsivity of the page also makes for an aesthetically pleasing experience. 

![Gallery](assets/images/readme/gallery.png)

- __The Enquire Page__

  - This page, form.html, will allow the user to make contact with the artist.
  - The page is composed of a form which requires the user's contact information and that they input a description of the type of work they would like produced.

![Enquire](assets/images/readme/enquire.png)

- __The Confirmation Page__

  - The confirmation page, confirmation.html, has the same background as the enquire page and is only available when the form has been submitted. The purpose of this page is to indicate to users that they have successfully submitted the form, it gives users comfort that their request has been received and the consistency with the enquire page is good for the user experience.

![Confirmation](assets/images/readme/confirmation.png)

<a name="not-yet-implemented">### Features Left to Implement</a>

- Creating the social media pages for Bespoke Brushwork to be linked in the Footer.
- Creating a database for storage of customer information and linking it to the enquire form.
- Clarifying the user journey on the enquire page. Setting up an email / business specific contact point for the information to come through to as well as defining SLAs so customers can know how long they should expect to wait for a response and the general pricing they should expect.
- Implementing JavaScript for hero image slideshow rather than CSS animation for greater flexibility and smoother functionality.

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/) - screenshots confirming the same are linked below
  - [index.html validation](assets/images/readme/index-validation.png)
  - [gallery.html validation](assets/images/readme/gallery-validation.png)
  - [form.html validation](assets/images/readme/form-validation.png)
  - [confirmation.html validation](assets/images/readme/confirmation-validation.png)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator#warnings)
  - [style.css validation](assets/images/readme/css-validation.png)

### Bugs

- NOT YET FIXED - Images all taken from smart phone rather than online repository. Currently take up too much space (as of 10:00 20/07/2024) and are impacting the performance of the site. Currently investigating means of size reduction to get each page to a state of high performance (a score of 90 or above in the Lighthouse section of Dev Tools).
- FIXED - Height issue with hero image slideshow on large screens due to nature of non-JavaScript method, resolved via media query and altering the inputs of the slideshow animation.
- FIXED - General improvement in responsivity across the site, mainly corrected via media query particularly on About Us and Services sections on index.html.
- FIXED - Hover effect put in place on all Anchor elements to improve user experience, HOWEVER, was not supposed to affect social media anchors in footer, increased selector specificity to exclude footer items and improve user experience.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab
  - On the left-hand sidebar, in the Code and automation section, select Pages.
  Ensure:
    -  Source is set to 'Deploy from Branch'.
    -  Main branch is selected.
    -  Folder is set to / (root).
  - Under Branch, click Save.
  - Go to Code tab - refresh after a few minutes.
  - Under Environments on the right-hand side click 'github-pages' then View Deployment to see the sight.

## Credits 

- I followed the tutorial for code institute's love running example project as the skeleton for the Bespoke Brushwork project, particularly when creating the header and footer, the services section, styling the form, and creating the masonry effect in the gallery - The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 
- The explanation for deployment was taken from code institute's Love Running tutorial also - 'Love Running - Essentials Project - 'Let's Deploy'' Lesson.
- The animation slideshow for the hero-image is done entirely with HTML and CSS, the guidance for which can be found here https://www.youtube.com/watch?v=qDww4CbxtD4.
- The code guidance for the text overlay on the slideshow came from the following https://www.youtube.com/watch?v=Si4ViAvvnwU.

### Content 

- The only written content in the site is in the About Us section - written by me.
- The premise for the site and idea for the business came from my partner (the artist).
- The icons in the footer and in the services section were taken from [Font Awesome](https://fontawesome.com/).
- Favicon taken from [favicon.io](https://favicon.io/).
- Fonts taken from [Google Fonts](https://fonts.google.com/)

### Media

- All images used across the site are primary source pictures of my partner's artwork.

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

