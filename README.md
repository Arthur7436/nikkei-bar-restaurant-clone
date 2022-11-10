# Nikkei bar restaurant clone
Hello friend! Thank you for having a look at one of my pet projects!

## About
Whenever I get the chance to eat out, I know that everytime I see a Japanese restaurant, I know I'm not going to be dissapointed. Especially if they have Japanese curry with katsu chicken with miso soup on a cold winter day.....(Daydream face). On a serious note, since I love asian cuisine, I thought to myself "Why not practice your HTML and CSS by cloning a restaurant that looks like it's fire?". And behold, the nikkei-bar-resaurant-clone repository was created. 

Please have a look at my project <a href="">here</a>.

Here is the original <a href="https://nikkeibar.com.au/">website</a>.

## Technologies used 
+ HTML
+ CSS
+ Bootstrap 5
+ Git
+ VSCode

## Challenges I faced when building this project
1. <b>Navbar hover movement:</b> Everytime I hovered over the main navbar section, the entire navbar along with the section with the main background image tends to move down slightly. To solve this, I looked into the dev tools on Google chrome and found out that the <code>a</code> tags within each navbar title had a <code>display value</code> of <code>block</code> due to Bootstrap 5 having <code>.nav-link</code> <code>display</code> as <code>block</code>. By changing the <code>display</code> to <code>inline</code>, the movement dissappeared everytime I hovered. 
2. <b>Four images at the bottom</b>: I had trouble trying to find ways toalign all four images at the bottom to stick to each other and all have the exact same height as the image with the guy doing the BBQ was smaller in height than the rest. I used <code>d-flex</code> and <code>flex-fill</code> so that the problem would be resolved. This also allowed images to stay together even when zooming out of the screen.

## Improvements/changes made on the original website
1. <b>Aquamarine</b>: To add some flare to this website clone I added aquamarine to make it stand out with the contrast background-color and background image.