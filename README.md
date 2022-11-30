## README Document for Code Institute Portfolio Project 1 "Sport Spotters"

## Purpose
"Sport Spotters" was constructed as a requirement for Code Institute's Diploma in Full Stack Software Development course. Its purpose is to show that I have achieved a basic command of HTML and CSS languages, and that I can combine the two to create a three-page static website.


In its imagined context, Sport Spotters is a service that connects people in London who are looking to take up sport at a social level with clubs or classes suited to their needs. Users are invited to fill out a sign-up form detailing their past sporting experience, availability, contact details, postcode, sport of interest, any relevant health conditions and willingness to travel. Sport Spotters would then connect them with an ideally suited sports club based on the information provided.


## Imagined User Stories Informing Purpose
This service would be primarily aimed at people who work full-time but want to be physically active, people who may have been active in sport before and want to revisit it, people who are new to London or people who simply want to try a new activity and don't know where to begin.


Working full-time in a major city is demanding and often requires spending significant amounts of time commuting. With many responsibilities  outside of work to take care of, taking the time to research where one could take up sport regularly can be difficult, even if one would really like to. In a city of London's size and population, it is also easy to be overwhelmed by too much information. These could be factors that may discourage someone from taking the leap into sport, even if they feel they may be lacking community outside of work or aren't physically active enough.


Moving to a new city is very daunting, and despite community-building being one of the most important factors in creating and maintaining wellbeing, it is something that can easily be neglected when one has to take care of a new home, new job, the new administrative responsibilities that accompany this and even simple problems like learning how to get around.


## Value Provided to Users by Sport Spotters
Sport Spotters would be a service to take care of those obstacles that prevent someone from joining a new sports club. If one is too tired or time-pressed from work, or is bamboozled by the sheer amount of choice in London, this service would remove the greater part of the mental energy, effort and research required to make a decision on where to start.


## Technologies Used
For this project I used GitHub to both host and deploy my repository. GitHub's built in code editor allowed me to make a primarily HTML site. I made an external style sheet in using CSS and linked it to the website's HTML files to style each webpage. Media queries were used in the CSS style sheet to make sure the website is responsive to differing screen sizes.


## Design


***Layout and General Structure***
To begin with, I had an initial rough mental image of how the three pages of the site would look as represented by the photos inserted here.


![Rough Layout of Home Page](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Home%20Page%20Layout.jpg)


![Rough Layout of Available Sports Page](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Available%20Sports%20Layout.jpg)


![Rough Layout of Sign Up Page](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Sign%20Up%20Layout.jpg)



Frankly, this was not a good approach. It would have been far more efficient to use a wireframing tool like Balsamiq. This would have allowed me to build a better defined structure that would have made styling and implementing media queries much simpler and more effective later on. However, I was not aware of this at the time.


***Colour Scheme***
I used primarily navy and white for the website. This was in order to make sure elements could be easily contrasted but without making the mood of the website too severe. The site aims to make users feel positive and lighthearted about sport after all. ![Screenshot of Sport Spotters Homepage](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Sport%20Spotters%20Home.png)


![Sport Spotters What We Do Section](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Sport%20Spotters%20What%20We%20Do.png)



***Fonts***
The fonts used were Lobster and Signika, both of which I took from Google Fonts. I used Lobster for the logo and headings as I wanted a font that felt lighthearted and friendly without seeming childish. Signika was a more appropriate neutral font for the rest of the text elements to make them easily legible.


***Grid and Flex Layouts***
I used grid and flex layouts to arrange images and text in a way that adds visual variety to the site while maintaining balance between visual elements. These layouts are also responsive to screen size. I've attached screenshots of some of these layouts below so you can see how they change depending on screen size.

![Availability Page Larger Grid Layout](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Available%20Page%20Large%20Grid.png)


![Availability Page Smaller Grid Layout](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Available%20Page%20Small%20Grid.png)


![Home Page Larger Grid Layout](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Home%20Page%20Large%20Grid.png)


![Home Smaller Grid Layout](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Home%20Page%20Small%20Grid.png)



***Images***
All the images for this project were taken from www.pexels.com. Using one source for images allowed me to choose images that were consistent in tone. It was important to me that images conveyed a sense of enjoyment in sport, and that they looked like they could at least potentially have been taken in London where Sports Spotters would be based.


## Project Features

Rather than listing item section by section, I will here list what I think the most important feature of the site are based on both function and visual appeal.

***Header***
The header is one of the most important parts of this site. It immediately states the site's colour scheme, contains the logo and contains the navigation elements. In terms of visual appeal, it also introduces the font for headings and each text element has a "grow" effect when hovered over. In terms of providing value to the user, it clearly sign posts the three pages of the website and states their purpose.


![Header](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Header.png)


***Vacancies Grid***
On the home page or "About Us" page, there is a grid displaying some sports clubs that currently have some vacancies. From the perspective of visual appeal, the grid layout and images are pleasing. There is a dark translucent background effect on the images created by using z-positioning to overlap a partially opaque black div with the images in the grid. This also allows a contrast between the background image and foreground text. The text also has a grow effect like the links in the header. In terms of adding value for a user, it alerts a user to the very possibility of enacting their purpose for visiting the site in the first place. Seeing what may be immediately available may bring them one step closer to joining a sport.


![Vacancies Grid on "About Us" Page](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Home%20Page%20Large%20Grid.png)


***Footer***
The footer contains icons which act as links to Sport Spotters would-be social media. Visually, the icons communicate much more economically than words. In terms of adding value for a user, they would allow the user to connect with the wider Sport Spotters community (if it existed).

![Footer](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Footer.png)


***Available Sports List***
The list of available sports acts as a starting point for someone who is interested in trying out sport but may be drawing a blank on where to start. The value of it for a user is that gives one ideas of what they might like if they don't already know. It also invites them to consider what might possibly be available. 



![Available Sports List](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Availability%20List.png)


***Spotify Playlist***
On the Sign Up page, there is a widget that allows one to play music from a Spotify playlist. I found a workout inspired playlist to fit in with the theme of the site. Truthfully, I do not think there is really a need for this in the website nor is it music I would want to listen to myself. I have included it because part of the learning objectives was to design a site where the user had control over playing video or audio. If we imagine a scenario where this might fit ideally into some part of an expanded Sport Spotters website, this may give the user some workout inspiration.


![Spotify Playlist](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Spotify%20Playlist.png)


***Sign-Up Form***
The sign-up form is an important feature of the site. In visual terms, it is consistent with the colour and font schemes. Using several different types of inputs, some required more styling than others, such as the checkboxes that indicate a user's availability or the radio boxes that indicate how far they might be willing to travel. The layout was achieved using grid dispaly again and the inputs are responsive to screen size. As this site is for learning purposes and I won't be handling any data, information from the submitted form will be sent to the Code Institute form dump from the Love Running walkthrough project. In terms of providing value to the user, it allows the user to provide the information that makes the Sport Spotters service actually possible, and it ensures that the service is catered specifically to them.


![Sign-Up Form](https://github.com/sonetto104/CI-PP1-Peter-Regan/blob/main/assets/README%20Images/Sign-Up%20Form.png)


***Aria Labels***
Almost all non-text elements have aria labels where appropriate in the site. This makes the site accessible to those who may be visually impaired.


## Testing ##









