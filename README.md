Of Mice and Men Rock Band.

User Centric Milestone Project-Code Institute.

This is my first front-end project for a rock band. This site is for audiences who are their fans and potential fans who want to see and hear clips and vidoes,
new material as it becomes available.The site has 3 main section where fans can listen to new music releses, watch latest clips and find information about 
band members.Also there is a contact form where fans can contact the band with question of availability to perform at events.
 
## UX

My goal in the design was to make it as easy as possible to access information on the site.That why I used parallax effect to achive smooth feel to the website.
For fans and potential fans, I wanted to provide them with material and brief overview of the band via user friendly design.
This way, they can get to know the band members, view latest material, news and ability to contact the band with any questions.

Before starting this project I have done wireframes witch are included in the project 'assets/wireframes/New Project.pdf.' They were created with Balsamiq.
 
## Features

This site uses parallax scrolling effect with "smooth scrolling" effect.
Also there is 'go to top' button made with Javascript.
In the navbar I have located social media links with fontawesome icons. It is a quick and easy way for user to obtain information/material about the band.
Links are also located in the navbar. Dropdown icon appears when size of the screen changes.
We also have audio controls, by clicking play we will hear song playing in the background.
At the bottom of the page I have placed contact form.By filling out the from user can cantact the band.

### Features Left to Implement

In the future, I would like to add new material music,vidoes etc. as they become available.

## Technologies Used

   HTML
   CSS
   Bootstrap (3.3.7)
   
## Testing

The navbar changes with size of the screen. On small devices we have dropdown insted of links in the navbar. It works and looks better on smaller devices.
On Ipad, laptops and large screens we have links located in the navbar when click will transfer user to it section on the page.

Fans are also able to view band social media profiles via clicking on the font awesome icons.

In the about me section, user can read background of the band with ability to contact the with any questions by filling out the contact form.
If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address.
Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit.
If all fields are filled user will be transferd to 'Thank You Page'.If an user is interesed in contacting the band, they will have to fill out all fields in order for the formt go through.

When 'Go to top' button is click, it will take user to the top of the page.This allows user to spend less time scrolling the page,and finding material they looking for.

This site was tested across multiple browsers (Safari,Chrome,Internet Explorer, FireFox ) and on multiple mobie devices (ipad,iPhone 6,7,8,Safari,Chrome,Samsung) to ensure compatibility and responsiveness.
During the testing, I relize that on Safari in iOS, the background photos appeared blurry and zoomed in.To fix this, the background-attachment: scroll property value was added 
insted of background-attachment: fixed.

## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch.

To run locally, you can clone this repository directly into the editor of your choice by pasting https://paulesz.github.io/Of-Mice-and-Men/.


## Credits

### Content
- The text for section 'About Us' was copied from the [Wikipedia article A](https://en.wikipedia.org/wiki/Of_Mice_%26_Men_(band)#cite_note-91)
- 

### Media
- The photos used in this site were obtained from Google images.
- The vidoes used in this site were obtained from YouTube.
    
### Acknowledgements

- The parallax effect was found through www.w3schools.com.
- Back to top button was found through www.w3schools.com.

This is for educational use.