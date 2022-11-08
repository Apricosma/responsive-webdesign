# Testing basic responsive web-design 

Not much to say here, just testing some simple responsive design. Grid seems like a pain when it comes to the size of the content. `gap` likes to change the size of the grid content which I dislike, but I suppose it makes sense given you wouldn't want the container randomly changing sizes. 

[Check the page here](https://apricosma.github.io/responsive-webdesign)
## Todo

- Add placeholder images 
- Make the grid vertically responsive 
- Have content fill the grid evenly no matter what (no missing spaces)
- Make content in grid generate infinitely with scrolling
- Style the web-page better
- Maybe pivot to a youtube clone?
- Add a responsive navbar
- Add a modal
- Add a sidebar that slides out

## Centering divs for dummies

Alexa, how do I center the content inside of a div?
```CSS
.parent {
    height: 100px; /* just offsets it from the top of the page */
    display: flex;
    align-items: center;
    justify-content: center;
}
```