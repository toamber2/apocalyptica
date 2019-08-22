# Apocalyptica Fansite
Fansite for Finnish musical group Apocalyptica

## UX
The application is designed with the teen and adult fans of the Finnish symphonic metal band Apocalyptica in mind. Fans can read about the band's history and bios of each current member, see photos of the group, watch footage of a concert, see the discography and check the touring schedule.
 
This project is a responsive 4-page static website made with Bootstrap 4. Features include embedded YouTube video, contact form, photo gallery, and tables of tour dates, discography and member information.

The wireframes for this project can be found in the wireframes folder, which is located in the github repository [here](https://github.com/toamber2/apocalyptica/tree/master/wireframes)

## User Story 
* As a fan, I want to know the band's touring schedule, so I can buy tickets to see them in concert. 
* As a fan, I want to learn about the history of the band, so I can increase my familiarity with the band.
* As a fan, I want to learn about the individual musicians in the band, so I can learn their training and other projects I might enjoy listening to.
* As a fan, I want to see pictures of the band, see video of their performance, and read about thier history.
* As a fan, I want to read the discography so I can learn about albums I might want to buy.
* As a fan, I want to send messages of support or questions to the band so I can connect with them. 
 

## Features
This application's features include: a contact form, photo gallery, touring calendar, discography, previous members table, band biography, current member biographies

### Existing Features
* The photo gallery contains multiple color photos of the band.
* The embeded video plays footage of an Apocalyptica concert. 
* The touring calendar provides the event, date, and location of summer 2019 performances, with a link to purchase tickets.
* The discography table gives the title and year of release for all the full length Apocalyptica albums.
* The previous members table gives the names and instruments of former members, with links to external websites about them.
* The band biography section provides an overview of the 26 years that the band has performed.
* The biography sections of current members contain summaries of their careers and links to external websites with more info. 

### Features left to implement
The brief for this milestone provides specifications to make a static website that does not use JavaScript. At a future point in time, though, interactivity can be

The contact form does not hook in to a back end at this time, but that is a feature I can expand upon in the future.

## Technologies used
Bootstrap 4 [Bootstrap](https://getbootstrap.com/) was used because it provides a responsive grid that enables the site to display on any screen size. Default Bootstrap styling was supplemented with an external CSS stylesheet to provide a more customized appearance. Each page has scripts for JavaScript, JQuery, and Popper.js which Bootstrap requires as dependencies. 


## Testing
### Validation
The html code was validated using [W3Schools Markup Validation Service]("https://validator.w3.org/") and the css was validated using [Jigsaw]("https://jigsaw.w3.org/css-validator/").

### Testing User Stories
* Users can see photos of the band on the Jumbotron on each page, and a gallery of photos on the Photos page. Additionally, the footer has links to Apocolyptica's Instagram and Facebook for more photos. 

* Users can see video of the band in concert on the Music page, and access additional video of the band by visiting the Apocalyptica YouTube channel linked in the footer. 

* Users can read about the band in the Bio section on the homepage, by reading the individual bios on the Members page, and can access more information about them by following the Facebook link in the footer. 

* Users can see the concert calendar on the homepage, so they can plan to attend a concert. They can purchase tickets to a show by clicking the "buy" link.

* Users can click "Contact" in the navbar and be directed to the Contact page. There they can view the Contact form. The form has text input fields for Name, Email and Message. 

If a user clicks Submit without entering a value for all three of these fields, they will get a message that informs them that they must enter a value for the required field. 

If a user enters an email address without an @ sign, tney will be prompted to add that character. If they add the @ character at the end, they will be prompted to add the rest of the email address. 

If the user enters appropriate values in all three fields and then clicks Submit, the site will return a 405 error. This error occurs because the contact form is not connected to a backend at this time.

### Testing Responsiveness
Photos, video, tables, contact form and photo cards are responsive at each screen size: mobile, tablet, and desktop. Tablet and mobile screen sizes render well in portrait and landscape modes. This was tested using Chrome Developer Tools.

### Testing Links
Each link was tested and each opens in a new tab when clicked.

## Deployment
### Live
The website was deployed using GitHub Pages and can be viewed at [My Github](https://toamber2.github.io/apocalyptica/). Features are responsive and render as desired in the deployed version. 

### Local
To run this website locally, it is useful to install the Live Server extension in Visual Studio Code. When the Live Server extension is installed, there are two ways to run the website locally. Open Visual Studio Code, and open the folder containing the project. Open the index.html file. There is a toolbar at the bottom of the screen. Click on the button "Go Live". If that button is not showing, you may need to run the extension from the command palette. Search for Live Server and select Run. Your browser will then open and display the Apocalyptica Fansite. 

## Credits
Code samples from [the Bootstrap documentation]("https://getbootstrap.com/docs/4.3/getting-started/introduction/") were used for the header, footer, embedded responsive video, photo gallery cards  and contact form.

### Content
* The touring calendar content was taken from the official Apocalyptica website. [Apocalyptica Offical Website]("https://www.apocalyptica.com/en/")
* The embedded video of concert footage is taken from [Apocalyptica's offical YouTube channel](https://www.youtube.com/user/ApocalypticaVideos), which is linked in the footer as well. 
* The Music page bio comes from an interview with Eicca in [StringOvation magazine]("https://www.connollymusic.com/stringovation/artist-interview-apocalyptica")
* The bio on the Home page is from [musicfinland.com]("https://musicfinland.com/en/news/finnish-music-export-award-goes-to-apocalyptica-agency)"
* The individual member page bios are from [Wikipedia]("https://en.wikipedia.org/wiki/Apocalyptica")



### Media
* [Discogs](https://www.discogs.com/artist/17482-Apocalyptica) is the source for photos: discogs1.jpg, discogs2.jpg, discogs3.jpg, discogs4.jpg
* [The offical band website](https://www.apocalyptica.com/en/) is the source for photos: band_wall.jpg, five_members.jpg, band_skull.jpg, band_members.jpg, apocalyptica_crowd.jpg, apocalyptica_logo.jpg. 
* Members page gallery photos were taken from [wikipedia]("https://en.wikipedia.org/wiki/Apocalyptica").
* Eicca's member's page photo attribution: [By Tuomas Vitikainen - Own work, CC BY-SA 3.0](https://commons.wikimedia.org/w/index.php?curid=7378605)
* Eicca's portrait mode from here [Wikipedia](https://en.wikipedia.org/wiki/Eicca_Toppinen#/media/File:Eicca_Toppinen_-_Ilosaarirock_2009.jpg)
* Paava large size [By Tuomas Vitikainen - Own work, CC BY-SA 3.0](https://commons.wikimedia.org/w/index.php?curid=7379186)
[Wikipedia](https://en.wikipedia.org/wiki/Paavo_L%C3%B6tj%C3%B6nen#/media/File:Paavo_L%C3%B6tj%C3%B6nen_-_Ilosaarirock_2009.jpg)
* Mikko [By P. Schwichtenberg - Own work, CC BY-SA 3.0](https://commons.wikimedia.org/w/index.php?curid=34587934)
 and [ also from Wikipedia](https://en.wikipedia.org/wiki/Mikko_Sir%C3%A9n)
 * The contact page jumbotron image was taken from [Wikipedia]("https://upload.wikimedia.org/wikipedia/commons/8/81/Apocalyptica_-_Ilosaarirock_2009.jpg")


### Acknowledgements
Heartfelt thanks to Anna Greaves and Simen Daehlin for their assistance with questions throughout the project.

