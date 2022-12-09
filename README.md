[View live project here](https://lisalindqvist95.github.io/proj1/)

# Crashing Cords
## About
Crashing Cords is a website for the indie-rockband Crashing Cords. The site will be targeted towards fans of the band who want to find official information and it will work as a gathering of relevant data, for example access to tour tickets, merch and social media links. The website will be useful for fans who want to find the latest news about the band. It is also valuable for the band to provide their fans with information, create a stronger brand, grow their fanbase and sell more tickets and merch.

![Responsive Mockup](https://github.com/lisalindqvist95/proj1/blob/main/media/mockup_responsive.png)

## Features
- __Navigation Bar__
 
  - The navigation bar at the top of the landing page gives the user a grasp of the website structure and is helpful for the user to immediately navigate to the part of the website that they want to visit, without having to scroll. 
  - When the user hovers over a link it changes color which helps the user know that it’s a link that will take them to a different part of the website. 
  - The navigation bar is fully responsive to be accessible on all devices. 

 ![Nav Bar](https://github.com/lisalindqvist95/proj1/blob/main/media/navbar.png)

- __The Landing Page__

  - The landing page image includes a concert photo of the band and logo to let the user know that they have found the right page and to improve brand awareness for the band. The logo can be found in the lefthand corner and middle of the landing page to grab the users attention when the first visit the site.

 ![Landing Page](https://github.com/lisalindqvist95/proj1/blob/main/media/landing_page.png)

- __The Tour Dates Section__

  - The Tour Dates Section will allow users to see upcoming tour-dates and links to where they can find tickets to buy. It shows the date of the concert, city and venue. 
  - The dates showing on the website are clickable links so that the user can find more information and buy tickets directly, there is also a link to the ticket website to see all available tour dates. 
  - This part of the website is useful for the people who want to buy tickets to see the band and also useful for the band to sell more concert tickets. 
  - This section is updated when the date for a concert has passed.

 ![Tour Dates](https://github.com/lisalindqvist95/proj1/blob/main/media/tour_dates.png)

- __The Merch Section__
 
  - The Merch Section provides a selection of the merch and albums that the band is currently selling. 
  - If the user hovers over a picture they will get information about what is sold and the price, the text also provides a link to buy the item. To find more available march there is also a link to the official march store. 
  - This section is updated when the band releases new albums or merch. 
  - This section provides information about the merch for fans who did not know that the band had a merch shop. This is also valuable for the band to sell more items, which is a big part of their revenue. 

 ![Merch](https://github.com/lisalindqvist95/proj1/blob/main/media/merch.png)

- __The About Section__
  
  - The About Section will provide new fans who visit the site with a sense of what the band is about and their history. This section will improve brand awareness for old and new fans. 

 ![About](https://github.com/lisalindqvist95/proj1/blob/main/media/about.png)

- __The Connect Section__

  - The Connect Section will allow the user to get the latest news from the band by signing up to their newsletter. 
  - The user is asked to enter their e-mail adress in order to sign up. 
  - The newsletter will also make fans feel more connected to the band. 
 
 ![Connect](https://github.com/lisalindqvist95/proj1/blob/main/media/connect.png)

- __The Footer__

  - The footer section includes links to all the bands social media. The links open in a new tab so that the user won’t accidentally leave the website. It is placed below the Connect Section since social media is a way for the fans to connect with the band. 
  - The social media links are placed in order of importance for the band, from left to right. Spotify and Youtube comes first as they are places where the user can stream their music. The next icons are placed in order of which platforms the band are the most active on. 
  - The footer also includes a logo, copyright info and an e-mail to the record label for business inquiries. 

 ![Footer](https://github.com/lisalindqvist95/proj1/blob/main/media/footer.png)

 ### Possible Features to Implement

- __Photo Gallery__
  
  - A feature that could be implemented on the site is a photo gallery from the latest shows for old fans of the band to look through and for new fans to get a feeling of the band and what they might expect from a concert. To compensate for this not existing on the current site the background images contains pictures of the band instead. 
  
- __New music__ 
  
  - Another feature that should be a part of the page is new music, possibly with new music videos.

- __News__
 
  - There could also be a news section about what the band is currently doing, for the people who don’t want to subscribe to the newsletter but still want ongoing information about the band.

- __Navigation__

  - A feature that could improve is the navbar which should stay at the top of the page when the user scrolls down to improve the user experience. It could also be hamburger-menu on smaller screens so that it woulndt take up as much space.
  - The navbar could contain a dropdown menu with direct links to the official site for tickets and merch, in order for the user to get to those sites faster if they want.

## Testing

### Responsiveness

  - The website is responsive to fit different screen sizes. 
  - It has four media queries for different sizes: max width of 1124px, max width of 800px, max width of 500px and max width of 300px. The width was chosen based on standard screen sizes and the size where the layout started to look distorted. 
  - The responsiveness was tested using DevTools.
  - The text and images will resize depending on the size of the screen so that the user will be able to read the text and see the pictures regardless of the device they’re on. 
  - Since units like vw and % are used in the code to improve responsiveness there was an issue with text and images becoming too small och smaller screens. This was fixed by changing the size in the media queries. 

### Browser Testing

  - The website is tested on the commonly used browsers: Chrome, Safari, Edge, Firefox and Opera. 
  - There was a problem in Firefox where the placeholder text in the form-field wouldn't show. This was fixed by changing the color in the CSS-file. 
  - In Safari there was an issue with the google fonts that would not load. This was fixed by adding the font-weight and font-family to the textelement in the CSS-file.

- __Possible bugs__
  - There could be possible bugs in browsers that have not been tested, specifically older browsers like Internet Explorer, for example [w3schools](https://www.w3schools.com/cssref/tryit.php?filename=trycss3_align-items) notes that Internet Explorer 10 and earlier versions does not support the proberty of "align-items". Older versions of browsers are not as commonly used, Internet Explorer 10 is also discontinued, so this would not cause issues for the majority of users of the site. 

### Validator Testing 
  - HTML
    - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/#textarea)
 - CSS
    - No errors were found when passing through the official [(Jigsaw) validator]()

## Unfixed Bugs
  - __Form function__
    - At the moment the form does not store any data like it should. The form-buttton only takes the user to a HTML-document. This could be fixed with some back-end coding that is not part of this project. It might also be unnecessary to take the user to a comepletly new page, getting a confirmation on the same page would make the user experience better.
  
  - __Links__
    - All links in the merch- and tour-section takes the user to the same page since there is no existing merch or ticket to link to, becuase of the fictional band.

  - __Widows and Orphans__
    - With responsive design and the users ability to resize their displayed window, the occurence of a single word at the end or beginning of a paragraph is almost unavoidable. Even if this is a typography error that decreases readability and looks aesthetically unappealing there is not much to to except if you put a specific width and size to the paragraph, but this would make the site less responsive. To avoid a single word being left at the end of the text in the about-section the code "&nbsp;" was added in the html-file between the last two words before each break in the paragraph. However, this decreases the readability of html-file and makes it more difficult to edit so it is not an optimal solution.


## Deployment
  - The site was created via GitPod an deployed to GitHub pages using the following steps: 
    - The material is added and pushed to GitHub via GitPod
    - In the GitHub repository go to the settings tab above the code
    - In the settings tab navigate to pages
    - Fill in the source Deploy from a branch and choose "main" and save
    
## Credits

### Content

  - The icons in the footer are from [Font Awesome](https://fontawesome.com/)
  - Flex container example code came from [w3schools](https://www.w3schools.com/css/tryit.asp?filename=trycss3_flexbox_flex-wrap_wrap)
  - Center aligning elements code dame from [w3schools](https://www.w3schools.com/cssref/tryit.php?filename=trycss3_align-items)
  - Image hover effect came from [w3schools](https://www.w3schools.com/howto/howto_css_image_overlay.asp)
  - Help with fixing Input field color came from this [stack overflow article](https://stackoverflow.com/questions/6669846/css-input-field-text-color-of-inputted-text)
  - Help to convert a horizontal table inte a vertical table came from this [stack overflow article](https://stackoverflow.com/questions/67023112/convert-a-horizontal-table-into-vertical-with-css)
  - Help to resolve Google Fonts not working in Safari came from this [stack overflow article](https://stackoverflow.com/questions/24061808/google-font-not-working-on-safari)
  - Help on how to remove widows came from this [Techstacher article](https://techstacker.com/how-to-remove-text-widows-orphans-web-typography/)

 
### Media
   - The photos used on the site and merch were taken from [Unsplash](https://unsplash.com/)
   - The images used for mockups were taken from [AdobeStock](https://stock.adobe.com/)
   











 




