# Random-Background-Changing-Webpage
<br>

![Screenshot from 2022-03-12 08-05-31](https://user-images.githubusercontent.com/90546860/158000576-a74e3b7e-bf93-493d-b788-77d665f2bc49.png)


This webpage not only changes the color randomly, but also it has a large number of gradient color combinations also. 
In addition to it, the background images can also be changed if desired. It has a total of 80 images to set as background randomly.  
For changing the basic colors, I used math.random() function to select the random numbers and pass them to the rgb() values. 
Initially, it was not accepting the rgb value inside the javascript. Inside '...style.backgroundColor = " " ', it only accepts string values, which means I could pass only basic color names (blue, red, etc.). 
But then after googling, I came to know how to use the values inside "${}", and luckily it worked. Now it takes 3 random numbers from 0 to 255 and its combination creates a different color after every button click.  For using the gradient combination, 
I created 6 variables, 3 for both the colors in rgb(). The working is very similar to the first one,  the only difference is that it works inside "...style.backgroundImage = `linear-gradient()`". And at last, for changing the background image, I used different 80 images, named them numerically, and after every random number called  between 0 and 80, the image corresponding to that number will appear.
