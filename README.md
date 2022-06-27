# The Doors
(Developer: Vilayat Kleer)

[View the live website](https://vkleer.github.io/CI_PP1_TD)

## Table of Contents

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
3. [Design](#design)
4. [Technologies Used](#technologies-used)
5. [Features](#features)
6. [Testing](#validation)
8. [Bugs](#Bugs)
9. [Deployment](#deployment)
10. [Credits](#credits)

## Project Goals

### User Goals
- Find information about The Doors
- Find information about the band members
- Watch videos from The Doors
- Listen to music from The Doors

### Site Owner Goals
- Provide essential information about The Doors
- Promote The Doors’ music
- Provide an intuitive and responsive experience
- Provide users with a means of contacting site owner

## User Experience

### Target Audience
- People interested in The Doors
- The Doors tribute bands
- Music enthusiasts

### User Requirements and Expectations
- Structured website with clear sections
- Finding relevant information quickly
- Visually appealing and responsive website, no matter the device
- A way to contact the site owner
- Accessibility and readability

### User Stories

#### User
1. As a user, I want to learn what The Doors achieved as a band.
2. As a user, I want to learn who the band members are
3. As a user, I want to find out more about their music
4. As a user, I want to have control over the video and audio.
5. As a user, I want to easily find The Doors’ Spotify content
6. As a user, I want to learn about The Doors’ legacy
7. As a user, I want to know where The Doors recorded their music
8. As a user, I want to be able to contact the site owner
9. As a user, I want to know The Doors social media accounts so I can follow them.

#### Site owner
10. As the site owner, I want the purpose of the site to be clear immediately
11. As the site owner, I want to provide a responsive website for all devices.
12. As the site owner, I want users to be able to contact me for questions or suggestions
13. As the site owner, I want users to be able to go to any section of the page easily, no matter where they are
14. As the site owner, I want to embed API’s to enhance the user experience
15. As the site owner, I want to encourage users to explore The Doors’ music

## Design

### Design Choices
The site was designed to make learning about The Doors fun. A history site can easily become boring with walls of text - which is why I condensed all the core information and used a lot of imagery to go with the text. I made it a one-pager to make the site a journey, encouraging users to keep scrolling and learn more.

### Colour
Instead of using colours, I decided to use a grayscale theme. The Doors are a band from the 60's and a majority of their visual content is also in black and white, which I wanted to incorporate in the design. If a section has a lot of content, I split it up into two sections - one with a white background and the other with a black background.

### Fonts
To compliment the simplicity of the design I used only one font, with different font-weights: Josefin Sans, with a sans-serif fallback. The font is easy to read and suits the design well.

### Structure
The site is structured in a familiar and intuitive way. 
<br>
The navigation bar is sticky with a logo on the left and the links to the right. Since it's a one-pager, it's important to have the navigation visible at all times.
<br>
The content is split up into clear sections, divided by a parralax image to keep the design interesting. Each section is built in a different way so it doesn't feel repetitive.
<br>
The site consists of five main sections:
- A home section with a hero image and text, telling users what the site is about
- A band section, covering both the origin story as well as the individual band members
- A greatest hit section, covering their greatest hits and most played Spotify tracks
- A legacy section, informing users about their legacy
- A contact section where users can submit suggestions or questions and find the old office location of The Doors

### Wireframes
<details><summary>Home/The Band</summary>
<img src="docs/wireframes/home-the-band.png">
</details>
<details><summary>Greatest Hits</summary>
<img src="docs/wireframes/greatest-hits.png">
</details>
<details><summary>Legacy</summary>
<img src="docs/wireframes/legacy.png">
</details>
<details><summary>Contact</summary>
<img src="docs/wireframes/contact.png">
</details>

## Technologies Used

### Languages
- HTML
- CSS

### Tools
- Gitpod
- Github
- Git
- Balsamiq
- Google Fonts
- Adobe Photoshop
- Font Awesome
- https://grayscale.imageonline.co/

## Features
The site has a total of five sections and 12 features.

### Logo and Navigation bar
- The official The Doors logo is used and placed on the left as is conventional
- The navigation bar is sticky, meaning it will always be at the top of the page no matter how far you scroll down
- The navigation bar is responsive and works on all screen sizes - the menu turns into a mobile-friendly 'hamburger' menu on screens with a width of 850px and less
- Covers user story **8** and**13**

### Hero Image
- Shows a picture of the band to introduce them to users
- Picture changes depending on screen size, making sure all band members fit in on any screen size
- Features the following text on top of the image to clearly state the purpose of the site: "A tribute page to the legendary band: The Doors"
- Covers user story **10**

### Parallax Images
- To divide the different sections on the site, multiple background images have been used to keep the design interesting
- The images move at a different speed than the rest of the content when scrolling, creating an aesthetically pleasing effect
- The hero image is also a parallax image

### The Band
- Informs users about how and when the band came about
- Informs users about what set them apart from other bands at the time
- Informs users about the origin of the band name
- Covers user story **1** and **3**

### The Band Member Images
- Contains images of each band member along with their name in a <figcaption>
- Images increase their size and become slightly transparent when hovered over
- Images take users to their corresponding short biographies if clicked on
- Covers user story **2**

### The Band Members
- Sub-section of 'The Band'
- Uses black background to contrast the main section
- Informs users the band members and their role in the band
- Covers user story **2**

### Greatest Hits
 - Introduces users to The Doors' greatest hits with three Youtube videos and accompanying descriptions
 - The videos are placed within <figure> elements and have use <figcaption>'s to semantically organize them
 - Covers user story **3**, **4** and **15**
 
 ### Discover More Music
 - Sub-section of 'Greatest Hits'
 - Uses black background to contrast the main section
 - Has the Spotify API embedded to encourage users to listen to more songs than just The Doors' greatest hits
 - The Spotify logo can be clicked to open Spotify and take users to The Doors' Spotify page
 - Covers user story **4**, **5**, **14** and **15**

 ### Legacy
 - Introduces users to The Doors' legacy
 - Contains three notable events that contributed to The Doors' legacy
 - The three events have their own accompanying image and use a black background to contrast the main section
 - Covers user story **1** and **6**

### Contact
- Provides users with a way to contact the site owner
- Covers user story **8** and **12**

### The Doors Office and Recording Studio
- Sub-section of 'Contact'
- Uses black background to contrast the main section
- Has the Google Maps API embedded to show The Doors' old office and recording studio location
- Covers user story **7**

### Footer
- At the bottom of the page as is conventional, using the same color as the nagivation bar for consistency
- Contains social media links to The Doors' social media pages, with corresponding icons
- Covers user story **9**

### 404 Error Page
- Displays a custom 404 error page, keeping the user in the flow of the website
- Provides a means for the user to easily return to the main website

## Testing

## Bugs

## Deployment

## Credits
