## Website Performance Optimization portfolio project

### Methodology

####CSS
Took all of the CSS and made it 'productoin' inline quality
Used media= where accpetable. For mobile.css was still receiving an issue and so I simple styled it inline at the beginning as a 'gut check'

####JS
Made all of the javascript async
Attempted to utilize javascript for on the move rendering and it took my page speed down from high 80's to low 60s.

####Browser Caching
Because of how everything seemed to be working utilizing .htaccess (file included) seemed not to work with github (since I don't have access to the server proper) and localhost appears to not be properly setup to take it. I did follow instructions as best I could.

###Project Speed

(Analysis of Demo page)[https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fqtheninja.github.io%2Fportfolioproject%2F]

### Pizza SITE

#####Record the information
Using Google Chrome Dev tools. I recorded info and started tackling the JS file. 
I then tackled as many of the dom manipulation issues as possible. 
Some of my attempts such as using async font loading caused major performance issues. 
I console.logged all of the for loops and noted all info that was the 'same' I then made a variable that was stored outside of the for loop. 

Any functions that had a forloop with a function...I made a local variable outsid eof the loop so that js/browser isn't searching for the original function. 

I compressed the images prettyaggressively



## Citations

https://www.addthis.com/blog/2014/11/04/pagespeed-insights-removing-render-blocking-css/#.VcZTz_lViko
http://stackoverflow.com/questions/9262861/css-background-image-to-fit-width-height-should-auto-scale-in-proportion

