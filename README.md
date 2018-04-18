# Final Project- Interactive Graphics and Critical Code

Name: Soren Chargois

Date: 18 April 2018

## Project: A Day in De Stijl

### Conceptual Description

I am going to be continuing with my interaction project from the second week of class. I want to bring this semester full circle by ending with a similar but more complex and interesting version of the first project. Originally, I was exploring the parallels between the era of De Stijl art in post-war Netherlands and the modern day tumultuous political climate. The Art Story website explains, "Like other avant-garde movements of the time, De Stijl, which means simply "the style" in Dutch, emerged largely in response to the horrors of World War I and the wish to remake society in its aftermath. Viewing art as a means of social and spiritual redemption, the members of De Stijl embraced a utopian vision of art and its transformative potential."

Originally this project was static, simply a strong visual representation of a coping mechanism in response to the toxic political and social climate in the United States. For the final project, I want to take the next step in using interaction to allow users to become a part of the art by partaking in a "create your own experience" artwork. Additionally, the intentionality of the user being able to control the colors on the screen relates to the often mindless scrolling people do on the web and social media. 

(from:http://www.theartstory.org/movement-de-stijl.htm)

### Interaction Description

So, for the final, I'm going to begin with the same general outline of the De Stijl piece found below. In an ideal world, the sketch would be displayed on a 12x8' screen that allowed users to touch different parts of the screen. However, since I am lacking time and resources, my final project will be on a normal computer screen, using mousepad scrolls and clicks as the interaction peice.  

Users will be able to hover over the colored boxes and they will change color in a rotation of red-blue-yellow. If the user clicks on the box with color, it will change to whatever color it is on the hover. The user will have the ability to change the color in the red-blue-yellow rotation on each click. Additionally, each of the white boxes will have the capability to change to black on every click, then back to white on the next click. 

The audience for this piece is every person who feels like they have experienced heartache or stress surrounding the political or social climate of their home country. 

### Extension 

As mentioned above, I am expanding on a work I started near the beginning of the school year. I'm adding all the interaction that will be a part of the final version that I mentioned in the "Interaction Description" above. The ways in which these extensions further develop the conceptual and interactive elements of A Day in De Stijl were descirbed in detail above. 

![Week 2 Piece](destijl.png?raw=true "Week2")

### Technical Details
//   
Here you should give an overview of the technical aspects of your project:
* p5.js
* Hosting Platform: Github pages
* I will be using Visual Studio Code to write and test code. I've been using this platform for the whole semester and it works well with the work I'm doing. 
//

You can include code snippets here:

```js
function setup(){
    
    createCanvas(900,900);
    rect_color = color("blue"); 
}

function draw(){
    background(255, 255, 255);
    strokeWeight(8);
    stroke(0, 0, 0)
    line(50, 50, 50, 800);
    line(50, 50, 800, 50);
    line(800, 800, 800, 50);
    line (50, 800, 800, 800);
}
 if(mouseX>154 && mouseX<496 && mouseY>54 && mouseY<196){
      fill("blue");
     rect(154, 54, 342, 142);
  }
```

Link to your project's full code in this repository:  [https://sorenchargois.github.io/ADayinDeStijl/](https://sorenchargois.github.io/ADayinDeStijl/)
