# Portfolio-milestone-project

This is a personal portfolio site intended to recruiters. This site includes all the relevant details about me and my skills. 
Based on my research, I have arranged the details in an order which is easier for anyone to easily navigate through. 

You can find the deployed site [here](https://vishkid84.github.io/Portfolio-milestone-project/)

## UX

### User stories

As someone from the recruitment team, I would like to see Vishal's overall experience and skills.<br>
As someone who would be interviewing for my team, I would like to see a glimpse of his personality, education/experience and work that makes him stand out from the average person.

### Strategy

The target audience for this website are recruiters/companies. So idea is to create the site more as an online resume with portfolio and downloadable CV included. 

### Scope

Once the audience is identified, I researched various websites and job portals to understand the requirements they are looking for. 
Based on the research and user stories, I identified 8 areas - Strong summary, Career progression, Technical skills, Education and certification, Portfolio, Contact details, References/quotes from clients and downloadable CV. 

### Structure

The next part was to identify the best way to layout these sections. From my research, I came to the conclusion it would be best to place them based on relevance.
To understand this bit, I talked to a couple of people who have been part of the recruitment team in my company. 
As part of the interview with them, I also created cards for each section and asked them to order them based on what they would be looking for first. 
Based on this, I created the wireframe.

### Skeleton

You can see the wireframes below:

[Desktop view](https://github.com/vishkid84/Portfolio-milestone-project/blob/master/assets/wireframes/Desktop%20view.png)<br>
[Mobile view](https://github.com/vishkid84/Portfolio-milestone-project/blob/master/assets/wireframes/Mobile%20view.png)<br>
[Wireframe with color scheme](https://github.com/vishkid84/Portfolio-milestone-project/blob/master/assets/wireframes/wireframe%20with%20colors%20scheme.png)<br>

### Surface

Based on all the above, I created the website in easily navigatable manner. 
I used a greyscale image for the landing page and a color scheme that complements well. 


## Features

The landing page opens with my background image and text with my name and role. 

There are 6 sections in the navbar:
1. About me: A brief discussion about me, experience and skills
2. Skills: Progress bars with my technical skills
3. Education/Experience: This section has two different timelines for my education and experience each
4. Portfolio: This section contains tiles with images of the work done and will take to the original work when clicked on them
5. Contact: This section has my contact details. Also includes a form to fill in the details and message as an alternative method to reach me. The form is only and dummy and does not work currently.  
6. Download CV: This is not a section but a button to download a PDF version of my CV

### Existing Features
- Feature 1 - allows users to navigate to the particular section by clicking on the sections from navbar. They can scroll if needed as well
- Feature 2 - scrollspy from bootstrap included so that each section is highlighted in the navbar when they are navigated to
- Feature 3 - fixed navbar which makes it easier to navigate to 
- Feature 4 - responsive layout

### Features Left to Implement
- In future, I plan to add functionality to the form in Contact section. Currently only the layout is added.
- For future, I plan to include some quotes from previous clients below portfolio before moving into the Contact section.

## Technologies Used

HTML <br>
CSS <br>
Google fonts <br>
Bootstrap 4.3.1 <br>
jquery and js cdn for the bootstrap functions to work

## Testing

The About me section highlights my interest in both design and development also giving a glimpse of my personaity. 
The users mentioned they would still prefer a downloadable CV which I have added as part of navbar which downloads as a separate window, this has been tested successfully. 
The users also ranked education and experience in more or less the same level and would be easier to compare. So they have been added as two columns side-by-side for desktops and tablets. They are vertically placed in mobile view. 
Portfolio section also added, when hovered over gives the project name and brief description. When clicked on, it navigates to the project in a separate window.
All of the above helped achieve the user stories.

All the links in the site have been tested manually and found to be working successfully. 

In the Contact section, the 'required' attribute has been added to email, phone and email address. Users would not be able to submit without filling in these sections.
Furthermore, if email address is not valid, an error message pops up about it.

The website is created to be responsive. As mentioned above for the Education/Experience section, there are other parts also which are responsive. 
The navbar changes to menu icon in mobile view. 
Portfolio section tiles appears as 3 columns in desktop and tablet view but as a single column in mobile. 
Contact section appears as two different columns in desktop and tablet - one with contact details and the other column with form. They appear vertically in mobile. 
All of the above has been tested manually and found to be working. 

The website has been tested across different browsers (Chrome, Firefox, Microsoft Edge, IE10). I have added the smooth scroll feature in css. 
This does not work on Internet Explorer, Edge and ios. Tested across multiple devices and found that hover effect does not work without adding additional code
and 'background-attachment: fixed' does not work on ios.

## Deployment

The site was written in gitpod and pushed into the GitHub repository. This is hosted using GitHub, deployed directly from the master branch. 
The deployed site will update automatically upon new commits to the master branch.

To run this locally, open the command prompt or terminal. Then paste this into it: 'git clone https://github.com/vishkid84/Portfolio-milestone-project.git'

## Credits

### Content

All the text content were written by me

### Media

The images in the portfolio section are those which were used in those projects. The name of the original project and the course if any mentioned there. 

### Acknowledgements

The timeline was modified based on a previous code institute section. The github link [here](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/tree/master/16-adding-work-history)<br>
The hover effect in portfolio modified based on tutorial from w3schools [here](https://www.w3schools.com/howto/howto_css_image_overlay_slide.asp)<br>
The hover effect was not working in ios. Found the solution [here](https://stackoverflow.com/questions/18047353/fix-css-hover-on-iphone-ipad-ipod)<br>
The solution to style anchor like a button instead of adding button tag as a descendent of an a tag which is invalid was found [here](https://stackoverflow.com/questions/6393827/can-i-nest-a-button-element-inside-an-a-using-html5)
