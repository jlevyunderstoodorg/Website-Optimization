## Website Performance Optimization portfolio project

## Optimizations Made

####Part 1: Optimize PageSpeed Insights score for index.html
* Filled in content for meta description
* Filled in content for author
* Inlined the CSS
* Added media="print" to <link href="css/print.css" rel="stylesheet">
* Asynced the google analytics script
* Adjusted profilepic image
* Adjusted pizzeria image

####Part 2: Optimize Frames per Second in pizza.html
* Adjusted the changePizzaSizes and updatePositions functions
* Changed querySelector to getElementById
* Changed querySelectorAll to getElementsByTagName

####Running Instructions

####Part 1: Optimize PageSpeed Insights score for index.html

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
Then run PageSpeed analytics on the ngrok link.

####Part 2: Optimize Frames per Second in pizza.html
To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. You will find instructive comments in main.js. 

To run, open pizza.html on your computer.