The six inputs I'm most proud of were

p5.js
Encounter Card (Week 2- the basics)
Out of control blue ball (Week 3- structure)
Geo-pat (Week 4- patterns)

Touch Designer
Zoomy Hexagon (Week 8- translate, rotate)
Gwen Stacy (Week 10- SOPs and instancing)
Zagreus (Week 11- audio reactive patterns)

p5.js

I picked the Encounter card because not only does it look *awesome*, but because of the way I had to find a work around to achieve something I didn't yet (and still kind of don't) know how to do.
I originally tried to place rectangles on the card and rotate them, but found I was rotating the entire canvas. I experimented with the push() and pop() functions but still had no luck.
Eventually I figured out how to add quadrilaterals and code the individual points to where I wanted them to be (later learning how to use translate within push() pop() so I didn't have to recode the coordinates when I wanted to move it
The code makes use of the push() pop() functions to translate the quadrilaterals which have been overlaid by other shapes to build two crossed swords along with a background, border and text.
Since then I have learned how to use the rotate function, but I'm still figuring out if I can rotate it once rather than constantly.

I chose the blue ball because of the multiple failed attempts to execute my vision. The goal was to make the ball change colour every time it touched the sides. That... did not end up happening, but the attempts and adjustments I made to try and achieve that effect were hilariously wacky.
How does the code work? Technically, it doesn't. I added if statements and variables to try and make the ball change colour when it was in a certain section of the canvas, but right now it's just slamming itself into a wall. Kind of like me when I wrote it.
I know it's possible to achieve what I was going for, as one of my peers managed to execute it. I'll keep working on it.

Geo-pat was the result of "what if I did TWO barcodes, wait no what if I did THREE. And what if I made repeating circles at the back??"
The reason I chose this is because it was the first time I overcame a coding issue on my own. The barcodes went smoothly, but when I started trying to add the repeating circles, I kept getting infinite loops (even with noLoop in the code). Eventually I was able to work my way around it (though for the life of me I can't remember the exact fix), and I feel pretty proud of that.
The code works by using begin/endShapes and for loops to create repeating patterns that are restricted to certain ranges on the canvas (eg the top bar code is restricted to 0-200y so that it can't extend all the way across the canvas)
Going forward I want to see if I can fix the start and end points of the diagonal barcode to the corners of the canvas, to have a more consistent image without needing to refresh so often to get one I like.

Touch Designer

I picked the hexagon partially because of the unhinged cackling that became a staple of the coding process, but also because it's one of the rare times I created something fun without feeling the need to go overboard on the colours and effects. Even though the code is quite simple (looking), I put more focus on enjoying the process rather than trying to create something absurdly cool-looking.
The code works using a feedback loop and an LFO attached to the pivot of the hexagon to make it fly on and off the screen. I also attached the LFO channel to the scale of the smaller hexagons to create the rapid (or chill depending on the version) expansion and shrinking effect.
I'd like to keep experimenting with LFO channels and see what other shenanigans I can get up to by attaching them to different variables.

Gwen Stacy was picked because (first of all, she's awesome) it was the first time I really experimented with ramp and noise together. The goal was to create a white and pink noise background to match her colour scheme. But my issue with the noise was- it only had greyscale or multicolour. It was through experimentation with ramps that I figured out I could place a ramp *before* the noise and, if I kept my amplitude low, reduce the hues that I didn't want in the noise. I also got to mess around with the scale of the waveform, trying to make it stretch across the screen while maintaining the thinner indivual bars.
I'm really proud of all the experimentation I got to do and the code turned out exactly how I wanted it.
The code has an audio reaction attached to a geo created by a rectangle sop. I then used ramp and noise to create a white and pink background- one part being the noise that travels from the top of the screen down, and the other being the circles within the ramp function. I used absTime to change the phase of the circles, making them expand infinitely. I then composited the noise and the geo together and attached the audioinput to the moviefile out so you can hear the theme being played.
This project inspired me to keep doing character themes, and I want to keep developing those ideas.

Zagreus
ZAGREUSSS. The Hades obsession returns. The goal for this one was to have one, spiky kind of shape trapped within a sphere. I really struggled with the colours and lighting in this one- everything was so dim for some time. I had a hard time figuring out how to show the two geos together in the render- it felt like every time I connected them I ended up with one non-wireframe ugly blob :((
BUT we figured it out! (Turns out I hadn't added a material to the render tab in geo2)
This was a lot of experimentation, a lot of backtracking and a lot of "ooh what if I..."
I feel like I really pushed my technical and creative skills with this project, and in future I want to see how much I can expand on these ideas to create even more complex structures.


Click the pencil icon to edit text!
Then click "commit changes", then select "Commit directly to the main branch" and click "commit changes" again to save your text.
