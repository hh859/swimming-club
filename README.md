Aquaskills Swimming Academy is a fictional swimming club website that offers aqua aerobic classes and swimming lessons for children and adults. Its primary purpose is to attract swimming enthusiasts and get them to book classes and training sessions. The idea of the swimming club project was invented through my previous experience as a swimming athlete and teacher. The website's purpose is educational - benefits of swimming, links to the major swimming organisations and latest events, and commercial-sell service to the audience.

## UX AIMS

- To attract audience of different age groups who are interested in swiming 
- To attract users to return to the website and book subsequent sessions
- To provide an easy-to-navigate booking platform with attractive interface
- Offer a fully-responsive design for easy use across various devices

## USER STORIES

  1. Is swimming for me? "I am a first-time visitor considering signing up for the swimming class, so I am looking for benefits of swimming to my health and additional recommendations."
  2. Which class should I book? "I seek advice on the best option for my experience level."
  3. Do you provide personalised support? "Do you offer private lessons?"

 
## DESIGN IDEAS AND DEVELOPMENT 
My first handwritten idea 
PHOTO 
Mobile View 
Laptop View 
Features

### HOME
Navigation Bar
The navigation bar provides navigation across all three website pages, assisting with easy and fast navigation. It has three link pages: the Home page, Swimming Programs page, and Contact page. They are positioned on the right-hand side of the screen. On the small screen, they move to the centre. 

* NAV BAR PICTURE

#### Header 
Right under the Navigation Bar is a principle image with the website title. 

#### Section 1
Under the principal image is a "Why Aquaskills" section with three paragraphs explaining why users must choose to book classes with Aquaskills. For fast access to more information on each option, a "Find Out More" button takes the user straight to the Programs page.

#### Section 2 
This section provides a selection of locations where the classes are conducted. It also has a telephone number should the user wish to contact the venue directly for more information.

#### Section 3 
In my Partnership section, I provided links to the leading swimming organisations that offer the latest updates on the main swimming events in the country and internationally. It also indicates that all programs are compliant with the national swimming standards. 

#### Section 4
Should the user have questions, a "Contact" button is placed at the bottom of the page, providing quick and easy access to the contact form. It has a bright, stand-out colour for higher visibility and navigation support.

#### Footer
Lastly, the footer is positioned at the bottom of the page where the copyright sign is. 


### SWIMMING PROGRAMS 
The second page of the website contains a detailed description of the classes offered, prices, and booking links.

#### Header & Footer
The header and footer remain the same across the entire website. 

#### Section 1
It has a plain heading leading straight to the program description. Programs are divided into three separate sections and are color-coded. Each of them has a pop-up window with more information on the chosen course and a price attached to it. It also has a "Book Now" button for direct access to a booking leap.

The sections' positioning was initially planned in a cascading style, with pop-up images leaping out from the side of each section. With reference to the [W3 School- Pop-ups](https://www.w3schools.com/howto/howto_js_popup.asp) I planned to implement it in my code. It was meant to create an engaging and entertaining interface. However, after several attempts, I was unsuccessful in arranging them according to the plan. Therefore, CSS styling was used to create the current version. 
Sections now have an element of transition, sliding to the left when hovering over. 

#### Section 2
The initial design of the "Why Aquaskills" section was intended to have flipping cards, with the image in front and text at the back. With the code reference, I attempted to implement it in my code. After several attempts, the best I could get was an image attached to the corner of the section which extended every time I hovered over it. Therefore, CSS styling was used to create the current version. 
Sections now have an element of transition, sliding to the left when hovering over. 

## Code Issues 
  * Image size - The size of the principal image is too large, which slows down the uploading time. I faced this issue later in the project and decided not to downsize it. Instead, keep it the way it is and allow user feedback to point it out.
    
  * CSS Variables - instead of keeping colors by their HEX names, I attempted to introduce :root command to give colors names and organise them more neatly. However, after all changes were made and committed to the repository, the header and navbar across the whole website turned white. It indicated a broken link with the header's background colour. After spending a certain time trying to find the issue, I removed variables and restored their HEX names.

  * 3D Flip Image - the "Why Aquaskills" section on the Home page initially intended to have 3D flipping images with background text instead of simple blocks of text. With reference to [H3 School - Flip an Image](https://www.w3schools.com/howto/howto_css_flip_image.asp) I attempted to implement the code into my website. The difficulty was to arrange an increased number of div containers and ensure they were not overriding existing code. As a result, the closest I got to a 3D flip was an image attached to the corner of the section that was expanding when hovered over. After spending a considerable amount of time on the matter, the 3D flip was abolished, and a transition command was added to the sections.

  * Pop-up window - the program content in the "Swimming Programs" section was initially designed to have cascading style sections with text with a pop-up window leaping out from the side when hovered over. The aim was to create a more engaging interface and fill the empty space created by the cascading style. Initially, I tried to use Bootstrap to arrange all elements correctly. It all looked well on the mobile view but was not on the large screen. I then attempted to replace Bootstrap with CSS styling, but it was also not successful. As a result, the cascading style was removed, and sections of the text were created. A transition command was added to make them slide sideways when hovering over.
    A pop-up window now appears on the top of each section, partially covering existing text. Greater development would have been made on this matter had there been more time.
    
  * The main issue of this project was a crash of the platform halfway through and the loss of the majority of the data. As a result, there is little technical aspect I am able to include in this README file.

## Features I would like to implement in the future 
  * A separate page for location with Google Maps - to provide more interactivity and direct access to directions and navigation.
  * More content on the Home and Programs pages. 

## Testing 
 * [HTML Validator](https://validator.w3.org)
  * insert the image
* [CSS Validator](https://validator.w3.org)
  * insert the image

All testing was done on [Google Chrome Developer Tool](https://developer.chrome.com/docs/devtools/). 

### Lighthouse 
insert the imae 
* Performance scored 70 due to the image size and subsequently reduced loading speed. It could have been improved by reducing the image size but instead, it is left for the users to provide feedback on it. 

### Known Bugs
* insert image

## Deployment 



