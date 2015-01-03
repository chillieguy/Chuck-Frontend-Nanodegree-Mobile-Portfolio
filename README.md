# Chuck Underwood Web Performance Optimization
### Udacity Nanodegree Project 4
This project was challenging to get started.  The PageSpeed Insights scores above 90 were not difficult to achieve, but the code is not what I would condsider readable.  I am able to understand what is going on since I am the one that made the modifications.  It also does not seem to match up with what was learned in Protject 1 that included proper formatting and seperation of html and css.  Further research needed to help determine the line between readable code and optimization.  Also checking pages online most sites were not even above 80, so my guess is that this was an exercise to show how we do it, but we need use our judgement on how to apply the knowledge.

All files included in Github repo even though they are duplicated with inline and minified versions for reference and future changes.

Steps I took to achieve a score above 90 on [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
* Optimized Images using compression
* Resized images to more appropriate to what is being displayed
* Move Javascript to end of HTML
* Add async to script tag
* Minified CSS
* Add Minified CSS inline

Steps I took to optimize main.js in pizza.html (changes commented in code)
* Changed sliding pizza to transform.translateX
* Moved code out of loops to reduce calculations
* Add code at end of file to allow for async call in HTML

Resources used while completing the project
* Information about image optimization:
http://addyosmani.com/blog/image-optimization-tools/
* Minimize jpg file size:
http://www.jpegmini.com/
* Minimize png file size:
http://pngquant.org/
* CSS Minifier
http://cssminifier.com/
* JavaScript Minifier
http://javascript-minifier.com/
* Optimizing Performance https://developers.google.com/web/fundamentals/performance/
* Analyzing the Critical Rendering Path https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html
* Optimizing the Critical Rendering Path https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html
* Avoiding Rendering Blocking CSS https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html
* Optimizing JavaScript https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html
* Piazza https://piazza.com/ Project 4 discussions

***
Leaving the below information for reference
***
## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository, inspect the code,

### Getting started

Some useful tips to help you get started:

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ngrok 8080
  ```

1. Copy the public URL ngrok gives you and try running it through PageSpeed Insights! [More on integrating ngrok, Grunt and PageSpeed.](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/)

Profile, optimize, measure... and then lather, rinse, and repeat. Good luck!

### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>

### Sample Portfolios

Feeling uninspired by the portfolio? Here's a list of cool portfolios I found after a few minutes of Googling.

* <a href="http://www.reddit.com/r/webdev/comments/280qkr/would_anybody_like_to_post_their_portfolio_site/">A great discussion about portfolios on reddit</a>
* <a href="http://ianlunn.co.uk/">http://ianlunn.co.uk/</a>
* <a href="http://www.adhamdannaway.com/portfolio">http://www.adhamdannaway.com/portfolio</a>
* <a href="http://www.timboelaars.nl/">http://www.timboelaars.nl/</a>
* <a href="http://futoryan.prosite.com/">http://futoryan.prosite.com/</a>
* <a href="http://playonpixels.prosite.com/21591/projects">http://playonpixels.prosite.com/21591/projects</a>
* <a href="http://colintrenter.prosite.com/">http://colintrenter.prosite.com/</a>
* <a href="http://calebmorris.prosite.com/">http://calebmorris.prosite.com/</a>
* <a href="http://www.cullywright.com/">http://www.cullywright.com/</a>
* <a href="http://yourjustlucky.com/">http://yourjustlucky.com/</a>
* <a href="http://nicoledominguez.com/portfolio/">http://nicoledominguez.com/portfolio/</a>
* <a href="http://www.roxannecook.com/">http://www.roxannecook.com/</a>
* <a href="http://www.84colors.com/portfolio.html">http://www.84colors.com/portfolio.html</a>