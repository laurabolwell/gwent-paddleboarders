# GWENT PADDLEBOARDERS

### Milestone Project 1 - User-Centric Frontend Development

Gwent Paddleboarders is a site for a social group of paddleboarders based in South Wales. It is run by a group of volunteers who want to grow the local paddleboard community, building connections and providing ample opportunities so that people never have to paddle alone.

The site provides some basic information about the group but the main focus is to provide information about the meet-ups which take place each week. It also shows some photographs from previous social paddles and has a contact page should a user wish to get in touch.

The website is designed to be fully responsive, allowing visitors to view it on a wide range of devices.

![screenshot](documentation/amiresponsive.png)

I used [https://ui.dev/amiresponsive](https://ui.dev/amiresponsive?url=https://laurabolwell.github.io/gwent-paddleboarders) to create this image.

[View Gwent Paddleboarders on Github Pages](https://laurabolwell.github.io/gwent-paddleboarders)


## UX

Gwent Paddleboarders originally started as a Facebook group, but this has rapidly grown to over 1400 members and as a result the important information about paddleboarding meet-ups is becoming lost in the general chat on the page. 

The end user of this project are paddleboarders in South Wales who wish to paddle with the group. The users range in age from 18 to 60 and the site would mainly be accessed on mobile devices. 

The end user wants to be able to find out details of social paddles taking place and how to join one. 
Other features are that the user will be able to see photographs of recent paddles, see maps and current weather conditions at paddle locations, get in touch with the organisers, and easily navigate to the group's social media pages.

### Colour Scheme

![screenshot](documentation/coolors-palette.png)

The website uses a palette of blues to tie in with the water theme and to give a sense of calm. I used [coolors.co](https://coolors.co/023047-227596-bce1f0-ffffff) to generate my colour palette.

- \#023047 used as the background for the navbar and footer, and used for text, headings, and buttons.
- \#227596 used as a background for sections of the page, for block dividing lines, and for buttons.
- \#BCE1F0 used for hover effects.
- \#FFFFFF used as a background for sections of the page, block dividing lines, and for text on non-white backgrounds.

I've used CSS `:root` variables to easily update the global colour scheme by changing only one value, instead of everywhere in the CSS file.

```css
:root {
    --navy: #023047;
    --mid-blue: #227596;
    --light-blue: #BCE1F0;
    --white: #FFF;
}
```

### Typography

Google Fonts:
* [Montserrat](https://fonts.google.com/specimen/Montserrat) was used for headings and the navbar.
* [Roboto](https://fonts.google.com/specimen/Roboto) was used for the body text.

[Font Awesome](www.fontawesome.com) icons were used throughout the site, such as the social media icons in the footer.


## User Stories

### New Site Users

- As a new site user, I would like to find out what the group is about, so that I can see if it would be suitable for me to join.
- As a new site user, I would like to view photos of previous paddles, so that I can get a feel for if the group would be suitable for me.
- As a new site user, I would like to find out where and when the group meets, so that I can join the group.
- As a new site user, I would like to find out how to join a group paddle and if there is any cost, so that I can join the group.
- As a new site user, I would like to find out about parking at paddle locations, so that I will know where to park my car when I join the group.
- As a new site user, I would like to contact the group organisers, so that I can ask any other questions I may have.

### Returning Site Users

- As a returning site user, I would like to find the schedule, so that I can check the times of group paddles.
- As a returning site user, I would like to check the weather conditions at paddle spots, so that I can decide whether to join a particular paddle.
- As a returning site user, I would like to view photogaphs of social paddles, so that I can show family and friends.
- As a returning site user, I would like to contact the group organisers, so that I can suggest new paddle locations.
- As a returning site user, I would like to easily find the group's social media pages, so that I can connect with other paddlers in the group.

### Site Admin

- As a site administrator, I should be able to have all paddle information displayed, so that I can update all members and potential members on locations, times and other details eg parking costs.
- As a site administrator, I should be able to have images on the site, so that existing members can see photos of themselves from previous paddles and new members can see what our paddles are about.
- As a site administrator, I should be able to be contacted by both new and existing members, so that I can listen to any suggestions or answer any queries they may have.

## Wireframes

To follow best practice, wireframes were developed for mobile, tablet, and desktop sizes.
I've used [Balsamiq](https://balsamiq.com/wireframes) to design my site wireframes.

### Home Page Wireframes

| Size | Screenshot |
| --- | --- |
| Mobile | ![screenshot](documentation/wireframes/mobile-home.png) |
| Tablet | ![screenshot](documentation/wireframes/tablet-home.png) |
| Desktop | ![screenshot](documentation/wireframes/desktop-home.png) |

### Schedule Page Wireframes

| Size | Screenshot |
| --- | --- |
| Mobile | ![screenshot](documentation/wireframes/mobile-schedule.png) |
| Tablet | ![screenshot](documentation/wireframes/tablet-schedule.png) |
| Desktop | ![screenshot](documentation/wireframes/desktop-schedule.png) |

### Gallery Page Wireframes

| Size | Screenshot |
| --- | --- |
| Mobile | ![screenshot](documentation/wireframes/mobile-gallery.png) |
| Tablet | ![screenshot](documentation/wireframes/tablet-gallery.png) |
| Desktop | ![screenshot](documentation/wireframes/desktop-gallery.png) |

### Contact Page Wireframes

| Size | Screenshot |
| --- | --- |
| Mobile | ![screenshot](documentation/wireframes/mobile-contact.png) |
| Tablet | ![screenshot](documentation/wireframes/tablet-contact.png) |
| Desktop | ![screenshot](documentation/wireframes/desktop-contact.png) |

### Confirmation Page Wireframes

| Size | Screenshot |
| --- | --- |
| Mobile | ![screenshot](documentation/wireframes/mobile-confirmation.png) |
| Tablet | ![screenshot](documentation/wireframes/tablet-confirmation.png) |
| Desktop | ![screenshot](documentation/wireframes/desktop-confirmation.png) |

### 404 Page Wireframes

| Size | Screenshot |
| --- | --- |
| Mobile | ![screenshot](documentation/wireframes/mobile-404.png) |
| Tablet | ![screenshot](documentation/wireframes/tablet-404.png) |
| Desktop | ![screenshot](documentation/wireframes/desktop-404.png) |


### Existing Features

The website is comprised of six pages, four of which are accessible from the navigation menu (Home, Schedule, Gallery and Contact pages). The fifth page is a confirmation page which is shown when the user submits the form on the contact page, and the sixth is a 404 error page which is shown if a user tries to navigate to an invalid address within the site. 

#### All Pages on the website have: 

- **Navbar**

    - A responsive navigation bar displayed clearly at the top of the page which allows the user to navigate around the site. On the left of the navbar is the name of the club and on the right of the navbar are the links to the website pages: Home, Schedule, Gallery, and Contact.
    - The nav links are shown in white text while the current active page is shown in a light-blue, this gives the user feedback as to their current position on the site while still providing a good contrast against the navy navbar background colour. 
    - Hover effects (larger size and changed color) on navbar-brand and the navbar links give instant feedback to the user.

    Navbar with active Home page:\
    ![screenshot](documentation/features/navbar.png)
    Navbar with active home page and hover on Schedule page:\
    ![screenshot](documentation/features/navbar-hover.png)

- **Navbar Mobile Toggler**

    - On screen sizes less than 768px, the navbar collapses to a burger toggler. This was implemented to give the site a clean look and prevent the navbar from becoming too cluttered. Both the burger icon and dropdown menu are on the right side of the screen, this provides a good user experience as most users would use their right thumb to click on the icon and then the dropdown menu appears in close proximity to it.
    - On screen sizes less than 420px, a line break appears between 'Gwent' and 'Paddleboarders' to prevent the burger icon from overflowing onto the next line.

    Collapsed navbar:\
    ![screenshot](documentation/features/navbar-collapsed.png)\
    Collapsed navbar on screens less than 420px:\
    ![screenshot](documentation/features/navbar-collapsed-small.png)\
    Collapsed navbar with menu open:\
    ![screenshot](documentation/features/navbar-collapsed-open.png)\
    Collapsed navbar with menu open on screens less than 420px:\
    ![screenshot](documentation/features/navbar-collapsed-small-open.png)\

- **Footer**

    - The footer contains links to the Facebook, Instagram, and YouTube sites of the group. It also has a link to the Contact page. Universally recognisable icons were used rather than text to the give the footer a clean look. The icons change color when hovered over to give instant feedback to the user. The three external social media links open in a new page while the Contact page link opens in the current window.

    Footer:\
    ![screenshot](documentation/features/footer.png)\
    Footer with hover effect on Facebook icon:\
    ![screenshot](documentation/features/footer-hover.png)\

#### Home Page

- **Hero Image with chevron icon**

    - The landing page shows a large image of 2 paddleboarders that covers the full viewport height which gives a clean look to the page. There is a clearly visible chevron icon at the bottom of the screen alerting users that there is further content below this image. Users can either scroll down or click on the icon to reach the next section.

    Homepage Hero Image:\
    ![screenshot](documentation/features/hero-image.png)\

- **'About Section**

    - The section gives some information about the group that new users would need to know before joining a paddle. It also lets potential members know that the group does not offer tuition or hire and is not suitable for beginners.

    About Section:\
    ![screenshot](documentation/features/about.png)\

- **Benefits Section**

    - This section gives the users some information of benefits of paddleboarding in general and also benefits of paddleboarding in a group.
    - On large screens the three subsections are displayed in a row, on medium screens two sections are displayed next two each other with the third below, and on small screens the sections are stacked vertically.

    Benefits (small screen):\
    ![screenshot](documentation/features/benefits-small.png)\
    Benefits (medium screen):\
    ![screenshot](documentation/features/benefits-medium.png)\
    Benefits (large screen):\
    ![screenshot](documentation/features/benefits-large.png)\

- **Schedule Overview**

    - This section provides a brief overview of the schedule of social paddles taking place each week. There are four cards (one for each of the four paddles) with each showing the day, location and time.
    - Each card has a button linking to the Schedule page which shows the full information for the paddle. The buttons are large and have a colour-changing hover effect.
    - On large screens the four cards are displayed in a row, on medium screens they are displayed in two rows of two, and on small screens they are stacked vertically.

    Schedule overview (small screen):\
    ![screenshot](documentation/features/schedule-overview-small.png)\
    Schedule overview (medium screen):\
    ![screenshot](documentation/features/schedule-overview-medium.png)\
    Schedule overview (large screen):\
    ![screenshot](documentation/features/schedule-overview-large.png)\

#### Schedule Page

- **Links to jump to each section of the page**

    - Across the top of the page just below the navbar there are four buttons which link to each of the four sections of the schedule page. This allows the user to jump straight to the information for the day they are looking for, minimising the amount of scrolling needed. Each button has a hover effect which is visible against both the white and blue background sections of the schedule page.
    - The buttons are displayed in two rows of two on mobile devices and in one row on all other devices.
    - The buttons stick to the top of the page when scrolling to enable easier navigation around the page.

    Link buttons:\
    ![screenshot](documentation/features/jump-links.png)\
    Link buttons with hover effect shown on Thursday:\
    ![screenshot](documentation/features/jump-links-hover.png)\

- **Paddle Information Sections**

    - The schedule page has four distinct sections, one for each of the four planned social paddles that take place each week. Each section has some text giving the user vital information about the paddle as well as parking information and any fees that may apply. It also has a safety disclaimer.
    - Within the text there is a button linking to the what3words meeting location. This opens in a new window, or in the what3words app if it is downloaded on the device.
    - For each section on the page there is a embedded google map showing the meeting location.    
    - For each section on the page there is a widget showing current wind conditions and how they will change over the next week. This will enable users to see at a glance if the conditions are good enough for them to attend the paddle.
    - On large screens the text and map/conditions appear side by side but on small screens they are stacked vertically.
    
    Zoomed out view showing the four sections:\
    ![screenshot](documentation/features/four-sections.png)\
    Single section showing the text, what3words link, Google Map, and Windy.com conditions widget:\
    ![screenshot](documentation/features/single-section.png)\

#### Gallery Page

- **Carousel Sections**

    - The gallery page has four distinct sections, one for each of the paddle locations, and each section contains a carousel of images from paddles at that location.
    - The carousels cycle through the images automatically but also contain controls for users to manually move forward or backwards through the images if they wish to. 
    -The carousels will give new users a feel for if the group would be suitable for them and will give existing members a chance to see photos of them participating in paddles.

    Carousels for two of the four sections:\
    ![screenshot](documentation/features/gallery-llandegfedd.png)\
    ![screenshot](documentation/features/gallery-cardiff.png)\

#### Contact Page

- **Contact Form**

    - The form contains fields for the users' name, email address, phone number and a message.
    - The name, email address and message fields must be filled in order to submit the form, an asterisk next to each of the field names informs the user of this. If any of this information is missing (or the email address is in an incorrect format), the user will be guided to fill in what they have missed.
    - The phone number is an optional field. If a user wishes to enter their phone number, it must be entered in the correct format, which the placeholder text describes for the user.
    - The 'Send' button changes colour when hovered over.

    Contact Page:\
    ![screenshot](documentation/features/contact.png)\

#### Confirmation Page

- **Thank You Message and Automatic Redirection to Homepage**

    - A thank you message informs the user that their message has been successfully sent and gives them a timeframe within which to expect a response.
    - The confirmation page has a full working navbar and footer if the user wishes to navigate to a new area of the site themselves. 
    - There is an automatic redirection to the homepage after 10 seconds (with countdown timer).

    Confirmation Page:\
    ![screenshot](documentation/features/confirmation.png)\
    Confirmation Page Showing Timer Counting Down:\
    ![screenshot](documentation/features/confirmation-counting-down.png)\

- #### 404 Page

- **Error Message and Automatic Redirection to Homepage**

    - An error message informs the user that they have tried to navigate to an invalid address.
    - The 404 page has a full working navbar and footer if the user wishes to navigate to a new area of the site themselves.
    - There is an automatic redirection to the homepage after 10 seconds (with countdown timer).

    404 Page:\
    ![screenshot](documentation/features/404.png)\
    404 Page Showing Timer Counting Down:\
    ![screenshot](documentation/features/404-counting-down.png)\


### Future Features

- Booking System
    - It would sometimes be useful for the organisers to know how many people are planning on attending the paddle, particularly in bad weather when they need to know if anyone will show up. A booking sytstem would help them keep track of this.
- Equipment Information Page
    - Information about the various equipment and clothing needed for different water and weather conditions with links to local businesses who sell them.
- Shop
    - The group is planning to have branded merchandise made in the near future and a shop page would allow the group members to view and purchase it.


## Tools & Technologies Used

- [HTML](https://en.wikipedia.org/wiki/HTML) used for the main site content.
- [CSS](https://en.wikipedia.org/wiki/CSS) used for the main site design and layout.
- [CSS :root variables](https://www.w3schools.com/css/css3_variables.asp) used for reusable colours throughout the site.
- [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp) and [CSS Grid](https://www.w3schools.com/css/css_grid.asp) used in conjunction with the [Bootstrap](getbootstrap.com) classes for an enhanced responsive layout.
- [Bootstrap](getbootstrap.com) used as the front-end CSS framework for modern responsiveness and pre-built components.
- [JavaScript](https://www.javascript.com) used for user interaction on the navbar mobile toggler and the countdown timer, implemented through [Bootstrap](getbootstrap.com).
- [Git](https://git-scm.com) used for version control. (`git add`, `git commit`, `git push`)
- [GitHub](https://github.com) used for secure online code storage.
- [GitHub Pages](https://pages.github.com) used for hosting the deployed front-end site.
- [Gitpod](https://gitpod.io) used as a cloud-based IDE for development.
- [Markdown Builder by Tim Nelson](https://traveltimn.github.io/markdown-builder/) used to help generate the Markdown files.
- [Tiny PNG](tinypng.com) used to compress images.
- [Favicon.io](favicon.io) used to create favicon.
- [Am I Responsive?](https://ui.dev/amiresponsive) used to show the website on a range of devices.
- [Hover.css](https://ianlunn.github.io/Hover/) used to create hover effects for the navbar.

## Testing

For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Deployment

The site was deployed to GitHub Pages. The steps to deploy are as follows:
- In the [GitHub repository](https://github.com/laurabolwell/gwent-paddleboarders), navigate to the Settings tab 
- From the source section drop-down menu, select the **Main** Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://laurabolwell.github.io/gwent-paddleboarders)

### Local Deployment

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://github.com/laurabolwell/gwent-paddleboarders) 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash or Terminal
5. Change the current working directory to the one where you want the cloned directory
6. In your IDE Terminal, type the following command to clone my repository:
	- `git clone https://github.com/laurabolwell/gwent-paddleboarders.git`
7. Press Enter to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/laurabolwell/gwent-paddleboarders)

Please note that in order to directly open the project in Gitpod, you need to have the browser extension installed.
A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository.
You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/laurabolwell/gwent-paddleboarders)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

### Local VS Deployment

There are no known differences between the local and deployed version.

## Credits

### Content

| Source | Location | Notes |
| --- | --- | --- |
| [Markdown Builder](https://traveltimn.github.io/markdown-builder) | README and TESTING | Tool to help generate the Markdown files |
| [Bootstrap](https://getbootstrap.com/docs/5.2/components/navbar/#how-it-works) | Entire site | Navbar including mobile toggler |
| [Bootstrap](https://getbootstrap.com/docs/5.2/components/carousel/#how-it-works) | Gallery page | Carousel with controls code used |
| [Chris Beams](https://chris.beams.io/posts/git-commit) | version control | "How to Write a Git Commit Message" |
| [W3Schools](https://www.w3schools.com/html/html_form_elements.asp) | Contact page | Used for form elements |
| [W3Schools](https://www.w3schools.com/css/css3_variables.asp) | Entire site | How to use CSS :root variables |
| [Flexbox Froggy](https://flexboxfroggy.com/) | Entire site | Modern responsive layouts |
| [Slack](https://code-institute-room.slack.com/archives/C7J2ZAVHB/p1593185727369600) | Entire site | Border on navbar toggler icon |
| Tim Nelson | Confirmation and 404 page | meta tag to redirect to home page (sent via slack)|
| [StackOverflow](https://stackoverflow.com/questions/31106189/create-a-simple-10-second-countdown) | Confirmation and 404 pages | 10 second countdown |



### Media

| Source | Location | Type | Notes |
| --- | --- | --- | --- |
| [Pexels](https://www.pexels.com/photo/people-with-rows-on-paddleboards-987955/) | Home page | Image | Hero image |
| [Flaticon](https://www.flaticon.com/free-icon/paddle-surf_5130467?term=paddle+board&page=1&position=8&origin=search&related_id=5130467) | Entire site | Image |Image converted to icon and used for favicon  |
| [B4245 Paddleboarding Facebook Private Group](https://www.facebook.com/groups/273749281620017) | Gallery page | Image | All gallery images taken from private facebook group with permission from group owner |
| [The Paddleshack](https://thepaddleshack.ie/benefits-of-paddle-boarding/) | Home page | Text | Text adatped for benefits section |
| [TinyPNG](https://tinypng.com) | Entire site | Image | Tool for image compression |

### Acknowledgements

- I would like to thank my Code Institute mentor, [Tim Nelson](https://github.com/TravelTimN) for their support throughout the development of this project.
- I would like to thank the [Code Institute](https://codeinstitute.net) tutor team for their assistance with troubleshooting and debugging some project issues.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for the moral support; it kept me going during periods of self doubt and imposter syndrome.
- I would like to thank my husband Lewis, for believing in me, and supporting me in making this transition into software development.
