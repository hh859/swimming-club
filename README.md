Aquaskills Swimming Academy is a fictional swimming club website that offers aqua aerobic classes and swimming lessons for children and adults. Its primary purpose is to attract swimming enthusiasts and get them to book classes and training sessions. The idea of the swimming club project was invented through my previous experience as a swimming athlete and teacher. The website's purpose is educational - benefits of swimming, links to the major swimming organisations and latest events, and commercial - sell services to the audience.

## User Experience Aims

- To attract audience of different age groups who are interested in swimming 
- To attract users to return to the website and book subsequent sessions
- To provide an easy-to-navigate booking platform with an attractive interface
- Offer a fully responsive design for easy use across various devices

## User Stories
  1. Is swimming for me? "I am a first-time visitor considering signing up for the swimming class, so I am looking for benefits of swimming to my health and additional recommendations."
  2. Which class should I book? "I seek advice on the best option for my experience level."
  3. Do you provide personalised support? "Do you offer private lessons?"

## Desing and Development
  * #### My first handwritten idea 
 ![alt text](https://github.com/hh859/swimming-club/blob/main/assets/CSS/Documents/Initial%20Design.jpeg)
  * #### Mobile View
 ![alt text](https://github.com/hh859/swimming-club/blob/main/assets/CSS/Documents/Mobile%20View.png)
  * #### Laptop View
 ![alt text](https://github.com/hh859/swimming-club/blob/main/assets/CSS/Documents/Principal%20Image.png)
   * ### Swimming Programs 
![alt text](https://github.com/hh859/swimming-club/blob/23ee6addb72ce7c77cd17a415853104c0b29ae9b/assets/CSS/Documents/Swimming%20Programs.png)
  * ### Contact Us
![alt text](https://github.com/hh859/swimming-club/blob/23ee6addb72ce7c77cd17a415853104c0b29ae9b/assets/CSS/Documents/Contact%20Us.png)

### Home
The navigation bar provides navigation across all three website pages, assisting with easy and fast navigation. It has three link pages: the Home page, Swimming Programs page, and Contact page. They are positioned on the right-hand side of the screen. On the small screen, they move to the centre. 

![alt text](https://github.com/hh859/swimming-club/blob/main/assets/CSS/Documents/Nav%20Bar%20.png)

#### Header 
Right under the Navigation Bar is a principle image with the website title (as seen on the laptop view). 

#### Section 1
Under the principal image is a "Why Aquaskills" section with three paragraphs explaining why users must choose to book classes with Aquaskills. For fast access to more information on each option, a "Find Out More" button takes the user straight to the Programs page.
The initial design of the "Why Aquaskills" section was intended to have flipping cards, with the image in front and text at the back. With the code reference, I attempted to implement it in my code. After several attempts, the best I could get was an image attached to the corner of the section which extended every time I hovered over it. Therefore, CSS styling was used to create the current version. 
Sections now have an element of transition, sliding to the left when hovering over. 

#### Section 2 
This section provides a selection of locations where the classes are conducted. It also has a telephone number should the user wish to contact the venue directly for more information.

#### Section 3 
In my Partnership section, I provided links to the leading swimming organisations that offer the latest updates on the main swimming events in the country and internationally. It also indicates that all programs are compliant with the national swimming standards. 

#### Section 4
Should the user have questions, a "Contact" button is placed at the bottom of the page, providing quick and easy access to the contact form. It has a bright, stand-out colour for higher visibility and navigation support.

#### Footer
Lastly, the footer is positioned at the bottom of the page where the copyright sign is. 


### Swimming Programs
The second page of the website contains a detailed description of the classes offered, prices, and booking links.

#### Header & Footer
The header and footer remain the same across the entire website. 

#### Section 1
It has a plain heading leading straight to the program description. Programs are divided into three separate sections and are color-coded. Each of them has a pop-up window with more information on the chosen course and a price attached to it. It also has a "Book Now" button for direct access to a booking leap.

The sections' positioning was initially planned in a cascading style, with pop-up images leaping out from the side of each section. With reference to the [W3 School- Pop-ups](https://www.w3schools.com/howto/howto_js_popup.asp), I planned to implement it in my code. It was meant to create an engaging and entertaining interface. However, after several attempts, I was unsuccessful in arranging them according to the plan. Therefore, CSS styling was used to create the current version. 
Sections now have an element of transition, sliding to the left when hovering over. 

## Code Issues 
  * Image size - The size of the principal image is too large, which slows down the uploading time. I faced this issue later in the project and decided not to downsize it. Instead, keep it the way it is and allow user feedback to point it out.
    
  * CSS Variables - instead of keeping colors by their HEX names, I attempted to introduce :root command to give colors names and organise them more neatly. However, after all changes were made and committed to the repository, the header and navbar across the whole website turned white. It indicated a broken link with the header's background colour. After spending a certain time trying to find the issue, I removed variables and restored their HEX names.

  * 3D Flip Image - the "Why Aquaskills" section on the Home page initially intended to have 3D flipping images with background text instead of simple blocks of text. With reference to [W3 School - Flip an Image](https://www.w3schools.com/howto/howto_css_flip_image.asp) I attempted to implement the code into my website. The difficulty was to arrange an increased number of div containers and ensure they were not overriding existing code. As a result, the closest I got to a 3D flip was an image attached to the corner of the section that was expanding when hovered over. After spending a considerable amount of time on the matter, the 3D flip was abolished, and a transition command was added to the sections.

  * Pop-up window - the program content in the "Swimming Programs" section was initially designed to have cascading style sections with text with a pop-up window leaping out from the side when hovered over. The aim was to create a more engaging interface and fill the empty space created by the cascading style. Initially, I tried to use Bootstrap to arrange all elements correctly. It all looked well on the mobile view but was not on the large screen. I then attempted to replace Bootstrap with CSS styling, but it was also not successful. As a result, the cascading style was removed, and sections of the text were created. A transition command was added to make them slide sideways when hovering over.
    A pop-up window now appears on the top of each section, partially covering existing text. Greater development would have been made on this matter had there been more time.
    It is also partially invisible on Mobile view, which I would want to improve to reduce its size or hide it completely. 
    
  * The main issue of this project was a crash of the platform halfway through and the loss of the majority of the data. As a result, there is little technical aspect I am able to include in this README file at this stage.


## Features I would like to implement in the future 
  * A separate page for location with Google Maps - to provide more interactivity and direct access to directions and navigation.
  * More contect to the Home page, with user stories and reviews attached.
  * More content to the Programs page, with higher number of section providing greater range of information about the classes
  * I will certainly spend more time planning the website idea, content, and layout prior to commencing coding.

## Testing 
 * [HTML Validator](https://validator.w3.org)
![alt text](https://github.com/hh859/swimming-club/blob/main/assets/CSS/Documents/HTML%20validator.png)
I tried to fix this error but was not successful. I consulted with my tutor about it. 

* [CSS Validator](https://validator.w3.org)
![alt text](https://github.com/hh859/swimming-club/blob/main/assets/CSS/Documents/CSS%20Validator.png)

All testing was performed on [Google Chrome Developer Tool](https://developer.chrome.com/docs/devtools/). 

### Lighthouse 
![alt text](https://github.com/hh859/swimming-club/blob/main/assets/CSS/Documents/Lighthouse.png)
* Performance scored 80 due to the image size and subsequently reduced loading speed. It could have been improved by reducing the image size but instead, it is left for the users to provide feedback on it. 

### Known Bugs
![alt text](https://github.com/hh859/swimming-club/blob/main/assets/CSS/Documents/Bug.png)
This issue was resolved by removing the button element. 

## Deployment 
  * Navigate to the Settings button and then Pages on the left side
  * Under Build and Deployment select 'deploy from a branch'
  * The link would appear on the top of the page indicating the website has been published

Here is a link to my website  - [Aquaskills Swimming Academy](https://hh859.github.io/swimming-club/)

## Credits 
### Code
  * [Code Institute](https://learn.codeinstitute.net/dashboard) - for most of the coding throughout the project. 
  * [W3 School](https://www.w3schools.com/) - for creating ideas, such as 3D image flip, pop-ups, and other design experiments.
  * [Bootstrap](https://getbootstrap.com/) - for styling trials and possible arrangements.

### Media 
  * All images is the work of Soo Burnell and belong to [Ignant](https://www.ignant.com/2019/07/31/soo-burnells-serene-series-of-swimming-pools-is-inspired-by-wes-andersons-aesthetic/) - which was an inspiration for the design of my website. For the next project, the images from Google would be sourced through usage rights.

## Acknowledgement
  * I would like to express a big gratitude to my Tutor Komal, who provided a lot of help throughout the project. Also, I would like to thank my mentor Jack, who helped me navigate the project. 
    


