# Cleaner Copenhagen

The idea behind this project was to create a simple website for a group that picks up litter in the parks of Copenhagen.
This group consists of volunteers and for recruitment relies on word of mouth and visitors to this website.
The target group is people living in or close to Copenhagen. Anyone able to show up in person can join, so location is the only criteria along
with fitness to be able to walk around for a period. This is a cleaner group, but it's also a social group, so adults, teenagers, and children 
are all welcome.

The name Cleaner Copenhagen is meant as a play on words, as in they are, and are searching for, cleaners in Copenhagen, and they are also 
striving for a cleaner Copenhagen.

## Features

### Existing features:
* __Navigation bar__
    * The navigation bar is on all four pages. It has links to the Home page, the About page, the What We Do page, and the Contact page.
    Visually, it is identical on each page but with a bottom border under the current page. It always sticks to the top when scrolling.
    * This section allows the user to always be able to navigate to all parts of the website without going back to the home page, or
    scrolling to the top.

![Nav Bar](/assets/readme-pictures/navbar-readme.PNG)

* __Landing page image / hero image__
    * The landing page has a large image with a text bar horizontally over the middle which contains an inspiring message to join the group.
    The text bar has a different message on each page that corresponds to the purpose/content.
    * The image is a bright city park with a curving road which communicates to the user what the group is aiming for: a beautiful spotless 
    clean park.

![Landing page](/assets/readme-pictures/hero-image-readme.PNG)

* __Call to action__
    * The following section has three boxes each with links to the different pages on the site. Each box has a short description of why the 
    user should click the link.
    * Each box has large green icons that gives a visual hint of what the content of the link is. Along with the description this makes it 
    easier for the user to quickly understand what it is.

![Call to action](/assets/readme-pictures/call-to-action-readme.PNG)

* __Meetup times__
    * This section lets the user know that the group is active and meeting up four times every week. Where and when is short and precise. 
    The dates and places will update according to group activities.
    * Each box has a background image of people picking up litter in green and bright scenery, which serves to give a positive outdoor feeling.
    Each box also links to the contact page where it's possible contact the group, to this there are added hover-animations to hint to the user
    that the boxes are clickable.

![Meetup times](/assets/readme-pictures/meetup-places-readme.PNG)

* __Footer__
    - The footer includes four links to FaceBook, YouTube, Instagram, and Twitter that each opens in a new tab. To the right is a copyright 
    statement. The social media links are represented with icons, and have animations when hovering over them. The footer is at the bottom 
    of every page.
    - The footer is valuable to the user as they can easily navigate through the social media accounts of the group.

![Footer](/assets/readme-pictures/footer-readme.PNG)

* __About us__
    * It has four areas; two text based, one picture, and one button. The text is unspecific but invites the user to contact them for more 
    details. The picture shows two children holding a bag a litter together, which is meant to symbolise unity and also complement the title 
    "doing good together". The button underneath is visually striking due to the size, the border, and the message icon. It is meant to quickly 
    signal it's purpose.
    * This section is to casually inform the user of who is behind the group. It is valuable to the user to know that the group is for everyone,
    and that it also sets up additional family-oriented events.

![About us](/assets/readme-pictures/about-us-readme.PNG)
    
* __What we do - top__
    * This section has a similar setup as the "about us" page, but with no contact button. In the middle there is a picture showing a girl
    holding two plastic bags with litter in order to show that litter can be found in the parks. 
    * It is valuable to the user to understand why the group operates, due to the fact that parks in Copenhagen are generally quite clean.

![What we do - top](/assets/readme-pictures/whatwedo-top-readme.PNG)

* __What we do - bottom__
    * In three headings with text this section talks about what the activities are about. It's fun, anyone can join, and there are only a few
    things to bring.
    * It is valuable to the user to understand that the activities are not dangerous and can be done by everyone, and also the specifics of
    what to bring.

![What we do - bottom](/assets/readme-pictures/whatwedo-bottom-readme.PNG)

* __Contact__
    * This is the contact form and it follows the style of the home page boxes. Along with the first name, last name, and email. The user can write a message, clear form, and submit.
    * It is valuable to the user to be able to contact the group if they wish to become a member, ask questions, or any other requests/comments.

![Contact](/assets/readme-pictures/contact-readme.PNG)

### Features left to implement
* Clicking on an event could fill in part of a form of which event the user wishes to register for.
* Form should accomodate users wishes to register for specific events.
* I was advised to not include a submit button in the form with a method and action (method="post", action="https://formdump.codeinstitute.net/", type="submit"), and instead have the type="button"



## Testing
* Chrome Developer Tools was used for testing all media queries down to 280px to fit the smallest devide available on the Google device list.
Also, developer tools was used to manipulate CSS to see direct outcomes. All pages have been tested with chrome developer tools to verify that
text, pictures, and boxes all adapt well to the breakpoints for different screens. 

* Breakpoints are set to the following and are all tested to work:
    * __1340px__
        * This Breakpoint deals with the navigation bar and shrinks the text to avoid colission with the logo. 
        * The meetup times on the home page are made smaller in order to maintain proper form.On the what we do page, the text is also shrunk in order to avoid collission.
    * __950px__
        * This breakpoint is generally for tablet screens and deals with a number of element collissions by changing the general design from horizontal to vertical.
        * Breakpoint is chosen due to navigation bar space, along with lack of meetup times space.
        * The navigation bar is pushed under the logo to make space for its size, but still floats to the right. 
        * The call-to-action boxes are places vertically, instead of horinzontally, and the same is done to the meetup times boxes.
        * On the about us page all the elements are also put vertically. Before the image was in the center, but now it is placed under the two text areas. The button remains in the bottom.
        * The vertical design is also used on the what we do page, and all text sections are now in a vertical line.
        * The footer has a change in its spacing between the social media icons, and they are now much closer together, and the font-size of both sides. The widths of the left right footers are changed from 66%-33% to 50%-50%.
        * Contact form's width is set to shrink/grow according to the screen size, text areas's width are smaller.
    * __550px__
        * Breakpoint is chosen due to text being pushed together and needing more space on the About page and the What We Do page.
        * The navigation bar now centers its elements.
        * The logo font-size is lowered.
        * The footer font-sizes are lowered for both sides.
        * The about us page's height is increased, and padding and margin of the elements are changed to accomodate text pushed together.
        * The what we do page's height is increased, and padding and margin of the elements are changed to accomodate text pushed together.
        * Contact form's width is increased, but still adapts to screen size. Clear and sumbit buttons's widths are smaller.
    * __400px__
        * Breakpoint is chosen due to navigation bar and logo space. Also, text and pictures need more space on About and What We Do pages.
        * Logo now takes two lines, and header's height adapts and is now 150px instead of 110px.
        * Navigation bar's font-size is down in order to fit one line.
        * About us page's height is increased to fit elements pushed together. Margin is changed for elements on same page. Picture is shrunk.
        * What we do page's height in increased. Margin is changed for elements on same page. Picture is shrunk.
    * __300px__
        * This is to accomodate the smallest screen sizes down to the lowest on the Google Developer Tool list (280px). Navigation bar space needed.
        * Navigation bar's font-size is lowered.
        * The height of the what we do page is increased, and margin of the elements on the same page is changed.


### Browser testing 
* Test on Firefox was good, but Google fonts seems to not be able to load, so the backup font was displayed.
* Microsoft Edge was without any issues.
* Media query tested on my own phone, Samsung Galaxy S9 using Chrome, no issues
* Media query tested on my own tablet, Ipad pro 2018 using Safari, one issue with margins, now fixed.
* General testing with my own laptop, Asus 13 inch using Chrome, no issues.

All links were tested. The links connecting to external sources (social media) open in a new tab and those linking to external pages all work as intended. There are links on each site, except for the what we do page, but the user still has an easy to understand sticky nagivation bar. 

I believe the webpage is set up for the users to easily achieve their goal, which is to get general information about the group, who they are, 
where and when they operate, a way to contact them with questions/requests for membership/general inquiries and comments.

### Bugs discovered during testing:
* I found the Google Developer Tool to not be stable in showing if the website responded correctly to different screensizes. Many times it would show 
that everything worked fine and smoothly only to display something different the next time it was opened. Similarly, it would show that something was off 
(footer not showing, lines out of bounds etc) only to show them correctly after closing and opening.
Also, some tests of media queries would succeed every time on Google Developer, but fail when manipulating actual browser window.
* Firefox did not show the Google font during testing.
* Safari did not show contact form buttons as Chrome, and I had to change margins.


### Validator testing:
* W3 Markup Validation Service completed for all HTML pages with no issues.
* Jigsaw test for CSS completed with no issues

### Unfixed bugs:
Testing in Firefox went well with functionality, but the Google Font Lato was not loaded.

## Deployment
The site was deployed to GitHub pages, and goes as follows:
In the GitHub repository, go to the Settings tab
From the source section drop-down menu, select the Master Branch
After selecting the master branch, the page will automatically be refreshed with a ribbon display to indicate the successful deployment.
The live link can be found here - https://andreaschristensen89.github.io/cleancopenhagen/


## Credits:
### Pictures
Images were compressed using the webpage https://tinypng.com/
All images were taken from https://www.freepik.com/, which requires attributions. The following are the code snippest the website provides when downloading.

* Hero-image:
    `<a href="https://www.freepik.com/photos/summer">Summer photo created by onlyyouqj - www.freepik.com</a>`

* Meetuptimes:
    * Kongens Have
        `<a href="https://www.freepik.com/photos/tree">Tree photo created by freepik - www.freepik.com</a>`
    * Fælledparken
        `<a href="https://www.freepik.com/photos/hand">Hand photo created by prostooleh - www.freepik.com</a>`
    * Søndermarken
        `<a href="https://www.freepik.com/photos/kids">Kids photo created by prostooleh - www.freepik.com</a>`
    * Utterslev Mose
        `<a href="https://www.freepik.com/photos/kids">Kids photo created by prostooleh - www.freepik.com</a>`

* About us
    `<a href='https://www.freepik.com/photos/kids'>Kids photo created by prostooleh - www.freepik.com</a>`

* What we do
    `<a href='https://www.freepik.com/photos/hand'>Hand photo created by prostooleh - www.freepik.com</a>`


### Text content
Content was all formulated by myself, but I took inspiration from another site with a similar focus:
https://www.doinggoodtogether.org/bhf/clean-up-your-neighborhood


### Icons
Icons and script were taken from https://fontawesome.com/ 


### Coding help
* For help with varius issues with animations, sticky navigation bar, css background manipulation etc. I often resorted to https://stackoverflow.com/
* Code Institute Slack Community for additional help with details (aria-label, general requirements, deployment)

### Design
* For design of the different pages I took inspiration from other students of Code Institute that request reviews of their projects. Also, I looked at various websites of professionals, e.g. https://www.wimhofmethod.com/
* For color schemes I used a blog on Visme that had 50 examples of good color combinations: https://visme.co/blog/website-color-schemes/

## User Experience Considerations:

### The User
* What are the goals for a first time visitor
   * Quickly understand what the group is doing, and where and when it is operating
   * Be able to navigate effortless through the pages
   * Easily reach the contact page and understand how to contact the group
* What are the goals for a returning visitor
   * Confirm meeting points/times
   * Check for updates of meeting times/places
   * Quickly find contact page to ask questions/inquiries/give comments/recommendations

## Design choices
* Overview: The aim is to provide easy-to-navigate pages that make it easy and clear to navigate around, with many links to the contact/join page.
    Information should not be detailed but fast to read and understand, and straight to the point.

### Color Scheme 
Colors are chosen to represent a "natural" scenery that hint of being in a park/forest, 
which hopefully leads users to envision being outside in nature.
* Background color: **#EAE7DC**
* Logo, titles, navbar elements, top of call-to-action divs, top of form: **#61892F**
* Font of call-to-action divs: **rgb(211, 203, 161)**
* Cover text hero-image, Call-to-action divs headings: **standard white**
* Call-to-action icons: **standard green**
* Footer background color: **rgb(177, 142, 96)**
* Footer icons and text: **#EEE2DC**

### Choice of text
For text choice I leaned towards the Love Running project, which used Lato and Oswald. After testing with other fonts (Roboto, Open Sans, Raleway)
I found Lato to work quite well with both text and headings.

### Pictures:
Sunny, bright and green pictures from parks were targeted to with the aim of thinking of nice weather, as the activity would be outside. Pictures with families/children were favored to give a family friendly atmosphere.

### Languages used
* HTML
* CSS
* Markdown language for readme file

### Accesibility
All non-text elements is marked with aria-label, and the contrast between background and foreground colors were implemented in color scheme.


## Future:
- Use semantic markup to structure HTML
- Add 404.md description
