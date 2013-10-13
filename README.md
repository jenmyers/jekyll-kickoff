# Jekyll Kickoff

A minimal beginner template for Jekyll projects.

## Includes

- basic site structure
- HTML5 Boilerplate index, 404, robots and humans files + favicon
- Compass + Susy starter stylesheets and configuration file
- local jQuery fallback

## Needs

- full directory structure

__[See gist for example →](https://gist.github.com/jenmyers/6692284)__

## Tools

- [Jekyll](http://jekyllrb.com/)
- [HTML5 Boilerplate](http://html5boilerplate.com/)
- [Compass](http://compass-style.org/)
- [Susy](http://susy.oddbird.net/)

## New to Jekyll?

That's cool! Check out the [Jekyll introduction](http://jekyllrb.com/docs/home/), then walk through the next steps to get up and running using this template.

1. You'll need [Ruby](https://www.ruby-lang.org/en/downloads/). If you're on a Mac, sweet, you're set. If you're on Windows, take a look at [Ruby Installer](http://rubyinstaller.org/). (Note - using Jekyll on Windows is challenging. [Be prepared to do some extra work.](http://www.madhur.co.in/blog/2011/09/01/runningjekyllwindows.html))
2. To install Jekyll, we use a gem, which is how Ruby packages up programs and libraries. Open up your [command line program](http://www.davidbaumgold.com/tutorials/command-line/) and type:

        $ gem install jekyll
3. For this template, we are also using Sass, Compass and Susy. We can install all of these with the following two gems:

        $ gem install compass
        $ gem install susy
4. Once these are installed, you can copy the Jekyll Kickoff files to your computer (choose "Clone to Desktop" or "Download .zip" on the right-hand side) and put them in your project folder.
5. Create the missing directories. You'll likely want a structure that looks something like this [directory example](https://gist.github.com/jenmyers/6692284).
6. Now we can fire up Jekyll. In your command line, type:
 
        $ jekyll serve --watch  
This starts the local server and tells it to automatically watch for changes you make.
7. Open a new command line window or tab and type:

        $ compass watch
This tells Compass to watch for changes you make to the Sass/SCSS. files and compile them to CSS.
8. Open your web browser and go to: __http://localhost:4000__. You should see the HTML5 Boilerplate welcome message and the Susy grid framework overlay.
9. Now you're ready to build! As you make changes to your HTML and Sass/SCSS, Jekyll will automatically rebuild the site and put all the compiled files into a folder called "_site." You can refresh your browswer window to see the changes displayed.

If you're also just getting started with [Sass](http://sass-lang.com/), [Compass](http://compass-style.org/) and [Susy](http://susy.oddbird.net/), check out their sites for more information. I've also created a list of [Sass/Compass tutorials and references](https://gist.github.com/jenmyers/9923d545c95ca747dec5).

Once you're done with your site, check out how to easily deploy it to [GitHub Pages](https://help.github.com/articles/using-jekyll-with-pages).