# Portfolio-milestone-project

This is a personal portfolio site intended to recruiters. This site includes all the relevant details about me and my skills. 
Based on my research, I have arranged the details in an order which is easier for anyone to easily navigate through. 

## UX
-----

### User stories

As someone from the recruitment team, I would like to see Vishal's overall experience and skills.
As someone who would be interviewing for my team, I would like to see a glimpse of his personality, experience and work that makes him stand out from the average person.

### Strategy

The target audience for this website are recruiters/companies. So idea is to create the site more as an online resume with portfolio and downloadable CV included. 

### Scope

Once the audience is identified, I researched various websites and job portals to understand the requirements they are looking for. 
Based on the research and user stories, I identified 6 areas - Strong summary, Career progression, Technical skills, Education and certification, Portfolio, Contact details, References/quotes from clients and downloadable CV. 

### Structure

The next part was to identify the best way to layout these sections. From my research, I came to the conclusion it would be best to place them based on relevance.
To understand this bit, I talked to a couple of people who have been part of the recruitment team in my company. 
As part of the interview with them, I also created cards for each section and asked them to order them based on what they would be looking for first. 
Based on this, I created the wireframe.

### Skeleton

The About me section highlights my interest in both design and development. 


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
- Feature 1 - allows users to navigate to the particular section by clicking on the sections from navbar. They can scroll if needed as well.
- Feature 2 - scrollspy from bootstrap included so that each section is highlighted in the navbar when they are navigated to.
- Feature 3 - fixed navbar which makes it easier to navigate to 
- Feature 4 - responsive layout: Education and Experience will be shown as one under the other in mobile view. The same with the portfolio tiles and Contact section.

In future, I plan to add functionality to the form in Contact section. Currently only the layout is added.

### Features Left to Implement
- For future, I plan to include some quotes from previous clients below portfolio before moving into the Contact section.

## Technologies Used

HTML, CSS
Google fonts
bootstrap (includes the library css, javascrip and jquery)
jquery and js cdn for the bootstrap functions to work

## Testing

The About me section highlights my interest in both design and development. 

During my UX, the users mentioned they would still prefer a downloadable CV which I have added as part of navbar. 
This downloads as a separate window, this has been tested successfully. 

The users also ranked education and experience in more or less the same level and would be easier to compare. 
So they have been added as two columns side-by-side for desktops and tablets. They are vertically placed in mobile view. 

All the links in the site have been tested to be working successfully. 

The website is created to be responsive. As metioned above for the Education/Experience section, there are other parts also which are responsive. 
The navbar changes to menu icon in mobile view. All the links have been tested to work positively. 
Portfolio section tiles appears as 3 columns in desktop and tablet view but as a single column in mobile. 
Contact section appears as two different columns in desktop and tablet - one with contact details and the other column with form. They appear vertically in mobile. 
All of the above has been tested successfully. 

I have added the css scroll feature for the html page. This does not work on Internet Explorer. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X