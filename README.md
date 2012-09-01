# Heroku Buildpack for Static Files

This is a [Heroku Buildpack](http://devcenter.heroku.com/articles/buildpack) for static apps. 
It uses Apache to statically serve your content.

## Usage

Make sure to have `index.html` in the root of your repository or else Heroku will not detect your static buildpack. After that you can run the following command.

    heroku create --stack cedar --buildpack https://github.com/sjlu/heroku-buildpack-static.git

You can also have the choice to password protect your application by simply adding Heroku configuration variables. To do so, run the following commands.
