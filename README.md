IMDB Metadata
=============

A web application that returns a movie's or TV series' meta-data given its title. Build this to learn how to use [Scrapy](http://scrapy.org), [Flask](http://flask.pocoo.org), and [Heroku](https://www.heroku.com) proper.

### How it works

## References
* [Jinja Template Designer Documentation](http://jinja.pocoo.org/docs/templates/)
* [Google Python Style Guide](http://google-styleguide.googlecode.com/svn/trunk/pyguide.html)
  
## Problems and bugs encountered
Using virtualenv to install Scrapy:
Encountered this error: distutils.errors.DistutilsError: Setup script
exited with error: command 'cc' failed with exit status 1
[Fix](http://stackoverflow.com/questions/22703393/clang-error-unknown-argument-mno-fused-madd-wunused-command-line-argumen)
Accidentally adding venv to git
Fixed using `git reset HEAD^`
Pushing to Heroku:
Encountered error: distutils.errors.DistutilsError: Setup script exited with error: command 'gcc' failed with exit status 1
This error, similar to above, occured while I was trying to push the app to Heroku.
[Fix](http://stackoverflow.com/questions/22415725/problems-with-custom-libffi-heroku-buildpack)
For some reason `wget` is not on Heroku, so I had to modify my shell script to use `curl` instead.
