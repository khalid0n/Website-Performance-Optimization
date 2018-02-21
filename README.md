# Website Performance Optimization portfolio project
+ This project is part of [udacity's front-end developer nanodegree](https://udacity.com/course/front-end-web-developer-nanodegree--nd001).
+ The project's aim is to optimize performance of an already given web application. where I made the needed tweaks and enhancments for the code to achieve a high page speed using [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/).
+ Also making the web application renders at 60 fps.

#### How to:
Download the project's directory & run `index.html` in your favorite browser.

##### Speed wise Optimizations:
1- Optimized images. And resized _"pizzeria.jpg"_.\
2- Add media type _“print”_.\
3- Deleted unnecessary comments.\
4- inlined CSS.\
5- removed Google Fonts link.\
6- make JS scripts that don't modify DOM & CSSOM async.\
7- Removed some unnecessary CSS rules.\
8- Minified some files.\


### Results:
###### Before
* _Mobile:  69/100_.
* _Desktop: 30/100_.
###### After
* _Mobile:  99/100_.
* _Desktop: 96/100_.

#### Rendering at 60 fps Omptimizations: 
- deleted `determineDx()` function.
- Re-implemented `changePizzaSizes()` function.
- plus a general enhancments to the code where possible.
- removed `querySelector()` & `querySelectorAll()` to more faster functions.
- reduced the burden of the script by moving some DOM queries & other variables out of loops.
- reduced number of pizzas to be based on browser window resolution.
- using `requestAnimationFrame()` to make JS run as early as possible in each frame.
- using `will-change: transform` & `transform: translateZ(0)` to tell the browser to expect visual property.
