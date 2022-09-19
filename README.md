The actual website can be viewed at [https://petrelharp.github.io/course_website/](https://petrelharp.github.io/course_website/).

Quick link: the [schedule](https://petrelharp.github.io/course_website/schedule.html).


--------------------


This is a [jekyll](https://jekyllrb.com) website,
modified from Karl Broman's [simple site](http://github.com/kbroman/simple_site)
by way of [Cécile Ané](http://cecileane.github.io/computingtools/).


*Notes on installation/building:*

- To view a local version run `jekyll serve` or maybe `bundle exec jekyll serve`.

- To get this to build locally with Debian, I had to `aptitude remove jekyll`; `bundle update`; 
    then find where the executable is using `bundle info jekyll`; 
    and finally make a symlink for the `jekyll` executable to somewhere in my `PATH`.
