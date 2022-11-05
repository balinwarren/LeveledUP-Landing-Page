# Project-Landing-Page
Project: Landing Page from The Odin Project

I designed this page after a fake dnd store meant to be a one stop for all Game Masters
This project was a great challenge for me trying to get a real handle on the CSS and trying to understand every change I was making.
I also worked really hard to find the resources through normal means and avoid looking at what other students of the odin project created.
The result is something I am quite proud of, now I will layout the process and some challenges I faced along the way, mainly focusing on flex
boxes as that was the topic of the content before this assignment.

## NAVBAR:
For the navbar it was actually pretty simple to put together, it used 3 flex boxes.
- 1 box to hold the entire bar
- 1 box for each side of the bar, left and right

I used icons from font awesome to complete the graphics and justify-content: space-between; pulled off the split affect of that UI section.

## HERO SECTION:
This section was by for the most challenging for me. What I struggled with most is how to handle the text overflowing from the div.
I solved this particular issue by using flex-wrap so items within the flex box would stack, I did not get here with much frustration
though I assure you.

To build the section itself it used 4 flex boxes.
- 1 box to build the sections background area and to center the content
- 1 box to house the text and contact button
- 1 box to house the image
- 1 last box to hold all the content together and center it

## SERVICES SECTION:
This section was by far my favorite to design. I got to discover the object-fit option in css for the images. It allowed me
to take images of all different sizes and fit them all the same on the services cards. 

To build out the layout I used 3 flex boxes.
- 1 box to house the title and the card tray centered
- 1 box to lay out the cards in a row
- 1 box for each card to stack the image and the text

## TESTIMONIAL SECTION:
This section was pretty straight forward. 

To build out this section it used 2 flex boxes.
- 1 box to set the section with the background color and center the content
- 1 box to house the text together and set the gap between

## MODAL SECTION:
This section weirdly had more go into it than I anticipated but it was fun to work out.

To build out this section it used 4 flex boxes.
- 1 box to center the banner in the section
- 1 box to create the banner and center the content within as well as use justify-content: space-between; for the even layout
- 1 box for the text
- 1 box for the button which was made just by setting the background to match and using border/border radius to create an outline button effect
