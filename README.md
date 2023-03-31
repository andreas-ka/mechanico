# Mechanico #

Mechanico is a website dedicated to people who loves and shares the joy of mechanical keyboards.
It's a meeting ground for all related to keyboards, a place to socialize and get friends for life.
Get the know how and see when the next keyboard meetup is scheduled.
_________________________________________________________________________________________________

## Mock-Up ##
Just a rudimentary mockup to get a feel for how the site will turn out.
![Mockup image 1](/assets/images/mechanico-mockup.png)
_________________________________________________________________________________________________

## Image from Am i Resonsive
Finished site.
![Responsive image 1](/assets/images/amiresponsive.png)

_________________________________________________________________________________________________

## Features ##

- A static navigation bar that highlights the current position on the website
- Footer with included links to our social media sites.
- Audio file so the visitor can listen to a keyboard.
- Calendar that shows the upcoming events.
- Form so the people who are interested in joining us can submit their contact information.


### Navigation Bar ###
![Navbar image 1](/assets/images/readme-navbar.png)

- The navigation bar is made static and moves with the page when you scroll
both eye-catching and handy. Highlights current active link.
- Designed with the same colors as the hero image, a gradient of pink to the left and purple to the right.

_________________________________________________________________________________________________

### Landing page and header ###
![Landing page image 1](/assets/images/readme-hero-and-quote.png)

- Has a minimalistic design that continues through to the other pages.
- A hero image that displays a custom keyboard that sets the color scheme of the site.
- The rest of the page contains a left column of text and a right column containing a custom keyboard.
- At the bottom of the page you find the footer containing icons and links to our social media
- Under the columns, I placed an audio player so people can listen to the sound och a thocky keyboard.

_________________________________________________________________________________________________

### Footer ###
![Footer image 1](/assets/images/readme-footer.png)
Consist of fontawesome icons for all the social media links and is displayed the same on all web pages.

_________________________________________________________________________________________________

### Meet Ups ###
![Meet ups image 1](/assets/images/readme-meetup.png)
- Meet-Ups is the site to see when the next community gathering is.
- It's a box design where you have the information about the event and an image next to it.
- Will also use a cross pattern for easier visibility between the different meetup events.
- Each event is designed with a ul list with icons from fontawsome to give it the same look as the footer.
- Included in every event is a link to its location on google maps and a link to either buy tickets or RSVP.


_________________________________________________________________________________________________

### Join US ###
![Join Us image 1](/assets/images/readme-form.png)
- On this webpage, the user is greeted first by a quote from the dictionary telling what a keyboard is.
- Under the hero image and quote you have the form with a background of a keyboard and coffee mug in the same color scheme as the site.
- The form consists of first and last name, then an email field and a radio button choice if you currently own or not a custom keyboard.
- Last we have the Submit button that takes you to a formdump page telling you that we will reach out soon, after 10 seconds the browser refreshes and takes you back to index.html if you do not want to wait there's a link you can click to go back.
_________________________________________________________________________________________________

### Audio ###
![Audio image 1](/assets/images/readme-audio.png)
- Added thock-keyboard.mp3 to be played at the landing page, so it doesn't start automatically and the default is muted, user have to engage to play it.


_________________________________________________________________________________________________

### Deployment ###
![Deploy image 1](/assets/images/readme-deployment.png)
- Website is made with gitpod and then git commit and git push to my repository on GitHub.
- There you can click on your repository in mind and press settings.
- Next step is that on your left you have a navigation menu where you can click on Pages
- The last step is to deploy your website.

_________________________________________________________________________________________________
## Testing ##
- Tested responsive in chrome on a MacBook 14" and also on a 37" monitor.
- Checked responsive through an iPhone 11 mini and an iPhone 14 max.
- Made sure every link worked on the website, both internal and external to a new tab, and that the form redirects back to
the index after 10 seconds.
- Tested so the form functions on both mobile and desktop.
- Made sure the navbar works fine on all screen sizes. On bigger screens the links are next to each other, on mobile
and smaller screens i made it so it goes into a column formation to have a bigger font and user experience.
- During testing i found out that the form element when scrolling was displaying over the navbar, fixed with z-index so the
navbar is always over the other content when scrolling.
- Noticed during final stages that on mobile the heading above form at mobile overlapped, fixed by setting images responsive.
- Thanks to my beloved girlfriend who helped me test the site from time to time.
- Tested the whole webite and readme with the Google extension Grammarly.
- Noticed the performance on mobile was slow so changed the hero-image and keyboard-purple to webp format instead of jpg.

_________________________________________________________________________________________________
## Bugs ##
- Had an issue where the header image wasn't showing after deploying to GitHub
- Issue with two scrollbars. The solution was found on StackOverflow and linked in the credits section.
- Had a problem with the form not working on submit, changed POST to GET and i did the trick.
- The form went above the navbar, fixed with z-index.
- Found a section that was not needed, and could be replaced with a div thanks to W3C validation.
- There was some problem with the meetup page when making it responsive, an overlap with images and text.
Fixed it with some margin and padding.- No bugs found.
- Huge learning process and i would have done the layout in code differently the next time, with more use
of classes to ease the responsive settings.

_________________________________________________________________________________________________
## Unfixed Bugs ##
- No bugs found.
- Huge learning process and i would have done the layout in code differently the next time, with more use
of classes to ease the responsive settings.

_________________________________________________________________________________________________
## Validator Testing ##
- Html validated through W3C validator.
![Deploy image 1](/assets/images/html-validation.png)
- CSS validated W3C CSS
![Deploy image 1](/assets/images/css-validation.png)

Google Lighthouse scores.
- Desktop
![Deploy image 1](/assets/images/chrome-desktop-performance.png)
- Mobile
![Deploy image 1](/assets/images/chrome-mobile-performance.png)

_________________________________________________________________________________________________
## Future features or ideas ##

- Would have liked a page where you can learn how to build your keyboard and what you need.
- A full about section where you can read about members and current projects/builds.
- Style the navbar even more, and maybe implement a drop-down menu.
_________________________________________________________________________________________________
## Credits ##

- Credit to Tristan Sterling also known as captainsterling on Instagram, it is his amazing photographs i was kind enough to borrow. https://www.sterlingandcophotography.com/etc/


- Credit to Alexotos, a huge profile in the keyboard community who let me use his images, the hero image is from him.
https://www.alexotos.com/


- Logo in hero image made from the website https://logo.com


- Inspiration and code help from the "Love Running" Project.


- Code inspiration to put the hero-image-logo.png on top of hero-image.jpg (scratched that idea later on)
https://stackoverflow.com/questions/12991351/css-force-image-resize-and-keep-aspect-ratio


- Tips for the static navbar
https://www.w3docs.com/snippets/css/how-to-create-a-fixed-navbar-with-css.html


- CSS Gradient tool for the navbar
https://cssgradient.io/


- Found this on StackOverflow how you can style the audio tag
https://stackoverflow.com/questions/4126708/is-it-possible-to-style-html5-audio-tag


- Learned about z-index from
https://www.freecodecamp.org/news/z-index-in-css-what-it-is-and-what-it-does/#:~:text=What%20is%20a%20Z%20Index,%2C%20or%20position%3Afixed%20).


- My mentor Nikki helped me understand flex box by sending me this link
https://css-tricks.com/snippets/css/a-guide-to-flexbox/


- Used this URL to learn about styling the fieldset element
https://www.w3schools.com/tags/tag_fieldset.asp


- Learned all about form styling from this site
https://blog.logrocket.com/how-to-style-forms-with-css-a-beginners-guide/


- Thanks to fontawesome for the icons
https://fontawesome.com/


- Did some photo modifications on Photopea.
https://www.photopea.com/


- Mockup made in Keynote


- This site taught me that i have to have p inside a li element
https://caniuse.com/


- Google Fonts for the "Playfair Display" font used on the site.
https://fonts.google.com/


- Solved two scrollbars by googling and found this thread on stackoverflow
https://stackoverflow.com/questions/9866220/why-are-two-vertical-scrollbars-showing


- This page helped figure out the form problem, use GET instead of POST
https://stackoverflow.com/questions/12221692/http-error-405-0-method-not-allowed-post-fails


- Learned more about responsive images from this link.
https://www.w3schools.com/howto/howto_css_image_responsive.asp


- Huge thanks to my family for letting me do this.