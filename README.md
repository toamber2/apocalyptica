# apocalyptica
Fansite for Finnish musical group Apocalyptica
#Project Name
##UX
The application is designed with the teen and adult fans of the Finnish symphonic metal band Apocalyptica in mind. Fans can read about the band's history and bios of each current member, see photos of the group, watch footage of a concert and check the touring schedule.
 
This project is a responsive 4-page static website made with Bootstrap 4. Features include embedded YouTube video, contact form, photo gallery, and tables of tour dates, discography and member information.

The wireframes for this project can be found in the wireframes folder, which is located in the github repository.

## User Story 
As a fan, I want to know the band's touring schedule, so I can buy tickets to see them in concert. 
As a fan, I want to learn about the history of the band, so I can increase my familiarity with the band.
As a fan, I want to learn about the individual musicians in the band, so I can learn their training and other projects I might enjoy listening to.
As a fan, I want to see pictures of the band, see video of their performance, and read about thier history.
As a fan, I want to read the discography so I can learn about albums I might want to buy.
As a fan, I want to send messages of support or questions to the band so I can connect with them. 
 

## Features
This application's features include: a contact form, photo gallery, touring calendar, discography, previous members table, band biography, current member biographies

### Existing Features
The photo gallery contains multiple color photos of the band.
The embeded video plays footage of an Apocalyptica concert. 
The touring calendar provides the event, date, and location of summer 2019 performances.
The discography table gives the title and year of release for all the full length Apocalyptica albums.
The previous members table gives the names and instruments of former members, with links to external websites about them.
The band biography section provides an overview of the 26 years that the band has performed.
The biography sections of current members contain summaries of their careers and links to external websites with more info. 

### Features left to implement
The brief for this milestone provides specifications to make a static website that does not use JavaScript. At a future point in time, though, interactivity can be added with the addition of JavaScript. 
The contact form does not hook in to a back end at this time, but that is a feature I can expand upon in the future.

## Technologies used
*bootstrap 4 https://getbootstrap.com/ Bootstrap 4 was used because it provides a responsive grid that enables the site to display on any screen size. Default Bootstrap styling was supplemented with an external CSS stylesheet to provide a more customized appearance. 


## Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Users can see photos of the band on each page, and a gallery of photos on the Photos page. Additionally, the footer has links to Apocolyptica's Instagram and Facebook for more photos. 

Users can see video of the band in concert on the Homepage, and access additional video of the band by visiting the Apocalyptica YouTube channel linked in the footer. 

Users can read about the band in the Bio section on the homepage, and access more information about them by following the Facebook link in the footer. 

Users can see the concert calendar on the homepage, so they can plan to attend a concert. 

Users can send questions or comments to the band using the Contact form on the homepage. 
----------------------------------------------------------------------------------------------------------

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.
## Deployment

To run this website locally, it is useful to install the Live Server extension in Visual Studio Code. When the Live Server extension is installed, there are two ways to run the website locally. Open Visual Studio Code, and open the folder containing the project. Open the index.html file. There is a toolbar at the bottom of the screen. Click on the button "Go Live". If that button is not showing, you may need to run the extension from the command palette. Search for Live Server and select Run. Your browser will then open and display the Apocalyptica website. 
------------------------------------------------------------------------------------------------------
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

### Content

### Media
*https://www.discogs.com/artist/17482-Apocalyptica is the source for photos [discogs1, discogs2, discogs3, discogs4].
*https://www.apocalyptica.com/en/ is the source for photos [band_wall, five_members, band_skull, band_members, apocalyptica_crowd, apocalyptica_logo]
*Members page gallery photos were taken from wikipedia. 
*Eicca's member's page photo attribution: By Tuomas Vitikainen - Own work, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=7378605
*portrait mode from here https://en.wikipedia.org/wiki/Eicca_Toppinen#/media/File:Eicca_Toppinen_-_Ilosaarirock_2009.jpg
*Paava large size By Tuomas Vitikainen - Own work, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=7379186
https://en.wikipedia.org/wiki/Paavo_L%C3%B6tj%C3%B6nen#/media/File:Paavo_L%C3%B6tj%C3%B6nen_-_Ilosaarirock_2009.jpg
*Mikko By P. Schwichtenberg - Own work, CC BY-SA 3.0 ] https://commons.wikimedia.org/w/index.php?curid=34587934
https://en.wikipedia.org/wiki/Mikko_Sir%C3%A9n


### Acknowledgements


# Markdown Cheatsheet
---
https://guides.github.com/features/mastering-markdown/


One pound sign = H1, 2 pound signs = H2 etc.

italics- surround with single asterisks or surround with single underscores

strong text double asterisks or double underscores

strikethrough double tilde

horizontal rule to make a line separating, use triple underscores or triple hyphens. Must be alone on the line.

Escape with backslash

block quotes use the greater than sign
> this is a quote


links text goes in square brackets and the link goes in parentheses. To have tooltip text, include a space and then the text in quotes
[Example ReadMe]("http://www.example.com "Example Here")

Unordered lists

One asterisk for each item

nested items: tab over and type another asterisk

Ordered lists are a little odd. You type the number 1 followed by a period for every item in the ordered list. The list will be ordered accurately even though you've put them down as all being 1.

inline code block- surround with backticks

___

