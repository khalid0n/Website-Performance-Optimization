# Website Performance Optimization portfolio project
+ The project's aim is to optimize performance of an already given web application. where I made the needed tweaks and enhancments for the code to achieve a high page speed using [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/).
+ Also making the web application run at 60 fps.

#### How to:
Download the project's directory & run `index.html` in your favorite browser.

##### Speed wise Optimizations:
1- optimized images. And resized _"pizzeria.jpg"_.
2- add media type _“print”_.
3- Deleted unnecessary comments.
4-inlined CSS.
5-put JS inlined at the end of `pizza.html` file.
5- removed Google Fonts link.
6- make JS scripts that don't modify DOM & CSSOM async.
7-removed unnecessary CSS rules.
8- Minified Everything.


### Results:
_Mobile: 99/100_
_Desktop: 94/100_


#### Rendering at 60 fps Omptimizations: 
- deleted `determineDx()` function.
- Re-implemented `changePizzaSizes()` function.
- plus a general enhancments to the code where possible.
- removed `querySelector()` & `querySelectorAll()` to more faster functions.