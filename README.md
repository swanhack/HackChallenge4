# Hack Challenge 4
This week you are tasked with trying to implement an edge detector. In the image below you can see the sort of thing to aim for. How simple or complex you make your implementation is up to you.

![Example of Edge Detection](https://github.com/swanhack/HackChallenge4/blob/master/example.png)

## Where to Start
- Try loading an image in the programming language of your choice. Change 1 pixels colour and then save the image.
- Gray-scaling your image before performing edge detection will make things easier.
- A really simple edge detector can be done with `if` statements. You want to check if a pixels colour is brighter or darker then it's neighbours.
- Look up more complex implementations: https://www.wikiwand.com/en/Edge_detection

## Extra ideas
- Integrate this with a discord bot. If a user uploads an image with the command as a comment then perform edge detection on the image.
- Look into reducing noise in the image before processing. This is typically done with blurs.
- Look into optimisations that will allow your edge detector to run faster (multi threading, scaling of image before processing)
