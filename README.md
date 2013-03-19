Code-Challenge-12G-Interactive
==============================

12g Code Challenge

Hi Maxime,

Here is my solution to the code challenge. This website contains three animations the ball, the shadow and this text box.
The ball is animated using css3 keyframes to describe it's path and to create the squash and stretch transforms.

The shadow animation is generated using JavaScript/jQuery. The position is calculated based on the x co-ordinate of the ball and the size and opacity of the shadow are calculated based on the y co-ordinate of the ball.

I have sucessfully Tested in ie10, Firefox and Chrome.

I have found an issue with Safari. Setting the “animation-play-state” to pause causes the page to reload. I did find reference to this problem here: 

http://stackoverflow.com/questions/14156523/safari-refreshes-the-page-on-setting-animation-play-state-to-paused

It appears to be the same problem as I checked my event viewer and it indicates it is WebKit2WebProcess.exe causing the problem.

Tested sucessfully on my Android phone in Firefox. I don't have access to an ipad/iphone but I did test in test sucessfully on iPad/peek. 

Brian
