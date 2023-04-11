# Testing

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Flaurabolwell.github.io%2Fgwent-paddleboarders%2F) | ![screenshot](documentation/testing/code-validation/html-validation-home.png) | Pass: No Errors |
| Schedule | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Flaurabolwell.github.io%2Fgwent-paddleboarders%2Fschedule.html) | ![screenshot](documentation/testing/code-validation/html-validation-schedule.png) | Pass: No Errors |
| Gallery | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Flaurabolwell.github.io%2Fgwent-paddleboarders%2Fgallery.html) | ![screenshot](documentation/testing/code-validation/html-validation-gallery.png) | Pass: No Errors |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Flaurabolwell.github.io%2Fgwent-paddleboarders%2Fcontact.html) | ![screenshot](documentation/testing/code-validation/html-validation-contact.png) | Pass: No Errors |
| Confirmation | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Flaurabolwell.github.io%2Fgwent-paddleboarders%2Fconfirmation.html) | ![screenshot](documentation/testing/code-validation/html-validation-confirmation.png) | Pass: No Errors |
| 404 | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Flaurabolwell.github.io%2Fgwent-paddleboarders%2F404.html) | ![screenshot](documentation/testing/code-validation/html-validation-404.png) | Pass: No Errors |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Flaurabolwell.github.io%2Fgwent-paddleboarders%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](documentation/testing/code-validation/css-validation.png) | Pass: All errors shown are from the imported Bootstrap library |


## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](documentation/testing/browser-testing/chrome-home.png) | Works as expected |
| Firefox | ![screenshot](documentation/testing/browser-testing/firefox-home.png) | Works as expected |
| Edge | ![screenshot](documentation/testing/browser-testing/edge-home.png) | Works as expected |
| Brave | ![screenshot](documentation/testing/browser-testing/brave-home.png) | Works as expected |
| Opera | ![screenshot](documentation/testing/browser-testing/opera-home.png) | Works as expected |
| Internet Explorer | ![screenshot](documentation/testing/browser-testing/ie-home.png) | Does not work as expected |


## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Screenshot | Notes |
| --- | --- | --- |
| XS Mobile (DevTools) | ![screenshot](documentation/testing/responsiveness-testing/mobile-xs.png) | Works as expected |
| Small Mobile (DevTools) | ![screenshot](documentation/testing/responsiveness-testing/mobile-small.png) | Works as expected |
| Medium Mobile (DevTools) | ![screenshot](documentation/testing/responsiveness-testing/mobile-medium.png) | Works as expected |
| Large Mobile (DevTools) | ![screenshot](documentation/testing/responsiveness-testing/mobile-large.png) | Works as expected |
| Small Tablet (DevTools) | ![screenshot](documentation/testing/responsiveness-testing/tablet-small.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/testing/responsiveness-testing/tablet.png) | Works as expected |
| Laptop (DevTools) | ![screenshot](documentation/testing/responsiveness-testing/laptop.png) | Works as expected |
| Large Laptop (DevTools) | ![screenshot](documentation/testing/responsiveness-testing/laptop-large.png) | Works as expected |
| Desktop | ![screenshot](documentation/testing/responsiveness-testing/desktop.png) | Works as expected |
| XL Monitor (DevTools) | ![screenshot](documentation/testing/responsiveness-testing/xl-monitor.png) | Scaling starts to have minor issues |
| 4K Monitor (DevTools) | ![screenshot](documentation/testing/responsiveness-testing/4k-monitor.png) | Scaling issues |
| iphone11 | ![screenshot](documentation/testing/responsiveness-testing/iphone11.png) | Works as expected |
| ipad | ![screenshot](documentation/testing/responsiveness-testing/ipad.png) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues. I have made the following changes to the site following lighthouse suggestions:
- Add meta description tags to head element of each page
- Add meta keywords tag to head element of home page
- Converted hero image and all gallery images to webp format
- Change text on schedule-overview buttons from 'More Info' to 'Full Details'

The following screenshots show the final lighthouse testing results. 

| Page | Size | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | Mobile | ![screenshot](documentation/testing/lighthouse/home-mobile.png) | No major issues |
| Home | Desktop | ![screenshot](documentation/testing/lighthouse/home-desktop.png) | No major issues |
| Schedule | Mobile | ![screenshot](documentation/testing/lighthouse/schedule-mobile.png) | No major issues |
| Schedule | Desktop | ![screenshot](documentation/testing/lighthouse/schedule-desktop.png) | No major issues |
| Gallery | Mobile | ![screenshot](documentation/testing/lighthouse/gallery-mobile.png) | No major issues |
| Gallery | Desktop | ![screenshot](documentation/testing/lighthouse/gallery-desktop.png) | No major issues |
| Contact | Mobile | ![screenshot](documentation/testing/lighthouse/contact-mobile.png) | No major issues |
| Contact | Desktop | ![screenshot](documentation/testing/lighthouse/contact-desktop.png) | No major issues |
| Confirmation | Mobile | ![screenshot](documentation/testing/lighthouse/confirmation-mobile.png) | No major issues |
| Confirmation | Desktop | ![screenshot](documentation/testing/lighthouse/confirmation-desktop.png) | No major issues |
| 404 | Mobile | ![screenshot](documentation/testing/lighthouse/404-mobile.png) | No major issues |
| 404 | Desktop | ![screenshot](documentation/testing/lighthouse/404-desktop.png) | No major issues |


## User Story Testing

| User Story | Screenshot | |
| --- | --- | ---|
| As a new site user, I would like to find out what the group is about, so that I can see if it would be suitable for me to join. | ![screenshot](documentation/features/about.png) | |
| As a new site user, I would like to view photos of previous paddles, so that I can get a feel for if the group would be suitable for me. | ![screenshot](documentation/features/gallery-llandegfedd.png) | |
| As a new site user, I would like to find out where and when the group meets, so that I can join the group. | ![screenshot](documentation/features/schedule-overview-large.png) | ![screenshot](documentation/features/single-section.png) |
| As a new site user, I would like to find out how to join a group paddle and if there is any cost, so that I can join the group. | ![screenshot](documentation/features/about.png) | |
| As a new site user, I would like to find out about parking at paddle locations, so that I will know where to park my car when I join the group. | ![screenshot](documentation/features/single-section.png) | |
| As a new site user, I would like to contact the group organisers, so that I can ask any other questions I may have. | ![screenshot](documentation/features/contact.png) | |
| As a returning site user, I would like to find the schedule, so that I can check the times of group paddles. | ![screenshot](documentation/features/schedule-overview-large.png) | ![screenshot](documentation/features/single-section.png)
| As a returning site user, I would like to check the weather conditions at paddle spots, so that I can decide whether to join a particular paddle. | ![screenshot](documentation/features/single-section.png) | |
| As a returning site user, I would like to view photogaphs of social paddles, so that I can show family and friends. | ![screenshot](documentation/features/gallery-llandegfedd.png) | |
| As a returning site user, I would like to contact the group organisers, so that I can suggest new paddle locations. | ![screenshot](documentation/features/contact.png) | |
| As a returning site user, I would like to easily find the group's social media pages, so that I can connect with other paddlers in the group. | ![screenshot](documentation/features/footer.png) | |
| As a site administrator, I should be able to have all paddle information displayed, so that I can update all members and potential members on locations, times and other details eg parking costs. | ![screenshot](documentation/features/four-sections.png) | |
| As a site administrator, I should be able to have images on the site, so that existing members can see photos of themselves from previous paddles and new members can see what our paddles are about. | ![screenshot](documentation/features/gallery-llandegfedd.png) | |
| As a site administrator, I should be able to be contacted by both new and existing members, so that I can listen to any suggestions or answer any queries they may have. | ![screenshot](documentation/features/contact.png) | |


## Bugs and Issues

- Navbar overflow issues

    Due to the long page name I had issues with the navbar content overflowing the page width. To overcome this I set the navbar to collapse when the screen size drops below 768px. I also had the issue of the navbar toggler icon dropping below the navbar brand on devices smaller than 420px. To fix this I added a line break between 'Gwent' and 'Paddleboarders' and used a media query so that the line break would only be visible on devices less than 420px.

- Visible white gutters on blue background

    I had white gutters running down each side of the page even when using the container-fluid class. This was because I was using html section elements and then separate div elements for the bootstrap container/row/column classes. I fixed the issue by removind the unnecessary div elements and adding the appropriate bootstrap class to the section element instead.

- Hero image overflowing below viewport window

    I had set my hero image to have height 100vh, with the navbar above it, this meant that the bottom of the image (and the chevron icon) had overflowed below the viewport window. To fix this, I gave the navbar position:absolute at the top of the page which meant it now overlays the top of the hero image and the image is the right height for the screen.

- Schedule overview card buttons appearing at different heights

    At 1075-1080px, two of the location headings wrap onto a second line, causing the 'Full Details' buttons to sit at different heights. I have fixed this by adding a fixed-height-heading class to all four of these headings and allowing enough room that the text can overflow onto a second line. The buttons are now aligned on all viewport sizes.

    Buttons not aligned:\
    ![screenshot](documentation/issues/schedule-overview-issue.png)\
    Issue fixed:\
    ![screenshot](documentation/issues/schedule-overview-fixed.png)

- Footer not sitting at the bottom of the page on contact, confirmation and 404 pages

    On some screen sizes the page content does not fill the full viewport height and the footer was above the bottom of the screen with white space below. I tried to fix this by fixing the footer to the bottom of the screen but this created the problem that the footer was now over the content on some other screen sizes. My mentor suggested adding the following code to my CSS which has now fixed the issue.
    ```
    html, body {
        height: 100%;
    }

    body > footer {
        : sticky;
        top: 100vh;
    }
    ```

## Unfixed Bugs

- Hero image not displaying correctly on apple devices

    The background-attachment:fixed property is causing the hero image to display incorrectly on small apple devices, ie, iphones and ipads. This is because iOS has an issue preventing background-attachment: fixed from being used with background-size: cover. This issue is documented [here](https://caniuse.com/background-attachment), and this site also suggests there will be issues with it on android browsers (unfortunately I don't have any android devices to manually test).

    Incorrectly displayed hero image (iphone11):\
    ![screenshot](documentation/issues/hero-image-issue.png)\
    Incorrectly displayed hero image (ipad):\
    ![screenshot](documentation/issues/hero-image-issue-ipad.png)

    In order to try to overcome this I have removed the background-attachment: fixed property and added it as a media query so that the image will only be fixed on screen sizes larger than 992px. The image now scrolls with the page on mobile and tablet screen sizes which does not look as good as when it is fixed but at least the image displays correctly, and will also fix any potential display issues on android devices as well as the known issues on iOS.

    Correctly displayed hero image (iphone11):\
    ![screenshot](documentation/issues/hero-image-fixed.png)\
    Correctly displayed hero image (ipad):\
    ![screenshot](documentation/issues/hero-image-fixed-ipad.png)

    I am unsure of whether the fixed property causes the hero image to display incorrectly on safari on macOS as I do not have any suitable devices to manually test.

    
Return back to the [README.md](README.md) file.