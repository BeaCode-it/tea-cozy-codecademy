# Codecademy Tea Cozy Project

### This project includes everything I learned so far in the **Front-end Developement Path** at *Codecademy*. It includes: 

- Semantic HTML
- HTML entity
- CSS reset properties
- class selectors and combinators
- Flexbox
- Positions, such as relative and fixed

### It contains the following files: 

- A wirefram PDF from figma
- HTML and CSS files
- Assests provided by Codecademy
- A redline to help dsign the project

## About the Project

After I designed the wireframe, it was easier to picture the boxes and the layers. Though, I struggled with the relationship of the elements. 

### The Nav Bar

In the navigation bar, I only placed the logo and the nav elements, they are clickable but they won't do anything. I decided to put the logo image in the HTML file instead of bringing it in the CSS. But there were times when some images were adjusted in the css due to 'position wars'. 

### The Hero

I added the hero image in the css file instead of html because giving it opacity was pretty challenging due to the 'position wars'.  I did not want anything else to have a z-index other than the nav bar. The headings are from the HTML and I did not reset any font sizes or weights in the CSS. I just followed the redline, instead of resetting nad using REM and em. 

I used the <main> tag here for the Hero as it is the biggest message that is at the top and covers almost all of the viewport. 

### Main Content and Location

I divided the rest of the webpage into the *main content* and the *locations* to keep things simple and comprehensive. I have used flexbox for my main and locations as well. For this, I put both in thier dedicated sections and created containers including a parent with children (items). I had to reduce containers at first because I created too many. THis really helped make my code simple to handle and go back to again and agian. 

### Footer 
I am glad I did not add footer in the locations section of the redline. Becaise I was going to. It would have made things even more complicated. Keeping everything in thier own dedicated sections was really helpful. Using semantic HTML was helpful as well. It easily created my div containers. 

### The CSS reset

I have not used much in the reset, just some basic properties. I made the margin and padding to zero in the body selector and also gave the body a standard font-family. This was availble in the redline. 

### Nav Bar 
The nav bar uses a flex box, once in the parent container and once for the navigation elements. It was quite simple compared to the rest of the web page. 

### The Hero
I got confused here with the parent and child relation and made a few errors. So here is how I prevented them from happening: 

1- I first made a few practice files (html & css) and worked on the sections there. Understanding the logic of positions and relationships of parents and children. 
2- One thing that really helped visualize things was drawing borders on parents in bright colors. So, this is going back to the  basics where I used to practic each lesson in different html and css documents. 

### Opacity

Opacity is quite challenging, especially when it comes to positions. What worked for me (to avoid z-index) was give parent containers background images in CSS rather than HTML and then set the opacity. It also helped to get the 'overlay' effect if I gave the parent container a black color. Google and Firefox picked this up as well. But, I am not sure how the page will render on other people's computers and browsers. So, do let me know if you see the opacity with a black overlay. In my practice files, I did use ::before pseudo element, but that too made the layering difficult for me with opacity. Selecting the background image and color of the parent container from the CSS worked for me. Ergo, I still have to practice using ::before element and layering elements. 

### Locations

This time, the practice and problem solving was making things faster and seamless. I am still worried how other computers will render my page but so far, it is working for me. I don't know much about grid but there was a time when there was too much gap between the flex items in the second row (and I thought may be grid would be more suitable here?). So I had to try a few "justify-content" and "align-items" values and add "gap" between the items to make them look like the redline. A lot of learning and problem solving here. 

## Conclusion

The footer was a breeze compared to the rest of the contianers and sections. I am sure with practice and use-cases I will learn to have a better handle on things. Comments really help when going back and forth to check the code. Even though I used flexboxes almost everywhere, there are still items that use different coding on them. Especially in the begining of the document. 

I am sure of one thing: Coding requires constant practicing. And it did take a toll on my eyes and shoulder girdle as they are weak because of Rheumatoid Arthritis. I pulled it off with the help of codecademy documentation, my own notes, Mozilla documents and Stack Overflow. As it turns out, there were a few quesitons on Stack Overflow that were very similar to my challenges. I have completed the project and made it look as close to the redline as possible. I hope that it renders the same on other browsers. Fingers crossed! 



