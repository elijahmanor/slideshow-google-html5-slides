
## Slide Show (S9) Template Pack - Google HTML5 Rocks

Google's [html5-slides](http://code.google.com/p/html5-slides) code bundled up into a Slide Show (S9) template pack.

See the original [HTML5 Rocks](http://slides.html5rocks.com) slides in action or
see the [Slide Show (S9) Tutorial](http://slideshow.rubyforge.org/tutorial.html5.html) slides generated using this template pack.
 
 
## Try It Yourself - How To Use the Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ slideshow -f http://github.com/geraldb/slideshow-google-html5-slides/raw/master/g5.txt

To check if the new template got installed, use the `-l/--list` switch/command:

    $ slideshow -l

Listing something like:

    Installed templates include:
       g5.txt (/home/gerald/.slideshow/templates/g5/g5.txt)

Now you're ready to use it using the `-t/--template` switch. Example:

    $ slideshow -t g5.txt tutorial

That's it. 

## Troubleshooting 

Trouble downloading? Do you have a direct internet connection? If not, configure your proxy using
the `HTTP_PROXY` environment variable. Sample:

    HTTP_PROXY=http://234.445.454:4341

Or with user credentials (that is, login and password):

    HTTP_PROXY=http://gerald:topsecret@234.445.454:4341

If all fails, you can always download the template pack on your own (using lets say `git` itself)
and than move the souces into your templates folder (that is, `~/.slideshow/templates`).

## Questions? Comments?

Questions? Comments? Send them along to the [Free Web Slide Show Alternatives (S5, S6, S9, Slidy And Friends) Forum/Mailing List](http://groups.google.com/group/webslideshow). Thanks!