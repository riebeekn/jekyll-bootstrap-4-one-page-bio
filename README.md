# Jekyll Bootstrap 4 one page bio / profile starter

This is a starter Jekyll project that can be used to create a one page bio / profile site, see [this blog post](https://experimentingwithcode.com/creating-a-profile-site-with-jekyll-and-bootstrap-4/) for a detailed explanation of how to customize and use the starter.  Condensed usage instructions are below.

This starter is an adaption of [https://github.com/chuckgroom/onepage-bio](https://github.com/chuckgroom/onepage-bio) and
[https://github.com/BlackrockDigital/startbootstrap-freelancer](https://github.com/BlackrockDigital/startbootstrap-freelancer).

The primary differences between this starter and the [Chuck Groom](https://github.com/chuckgroom) version:

* Updated to use Bootstrap 4.1.3.
* Updated to use FontAwesome 5.3.1.
* Removed the color variables from the config file so experimenting with different color schemes doesn't require a Jekyll restart.

The primary difference between this starter and both the [Chuck Groom](https://github.com/chuckgroom) and
[Startbootstrap-Freelancer](https://github.com/BlackrockDigital/startbootstrap-freelancer) versions:

* Replaced the contact section with a resume download section.
* Added links in the footer.

## Usage

### Grab the code
Clone, fork or download the repository from GitHub.

### Customize
For some great ideas around what you should be putting in your profile I suggest
reading the [Chuck Groom blog post](https://medium.com/@cgroom/a-software-engineers-one-page-portfolio-4f85ab8a20d1).
He has some great thoughts on what sort of content you should include and this post
was what inspired me to make my own profile / bio site.

Make the following changes in order to customize the starter:

* Update the `_config.yml` file, update the `site settings` and `link` sections.
* Replace `/assets/resume.pdf` with your own resume.
* Replace `/img/profile.png` with your profile photo.
* Update the .png files and .ico file in the root directory with your own favicon images (optional).
* Update the color scheme by altering the `/css/custom/_variables.scss` file (optional).
* Update the text in the following files: `/_includes/about.html`, `/_includes/interests.html`.

### Building the production version
In order for the `Download Resume` button to work both when running locally and on the production
instance the download URL is switched based on the JEKYLL_ENV setting.

**Therefore when preparing your build for producton run jekyll build as follows**

`JEKYLL_ENV=production jekyll build`

## Screenshots

![screenshot](https://raw.githubusercontent.com/riebeekn/jekyll-bootstrap-4-one-page-bio/master/_screenshot1.png)

##

![screenshot](https://raw.githubusercontent.com/riebeekn/jekyll-bootstrap-4-one-page-bio/master/_screenshot2.png)

##

![screenshot](https://raw.githubusercontent.com/riebeekn/jekyll-bootstrap-4-one-page-bio/master/_screenshot3.png)

## Jekyll

For more details on Jekyll, read the [documentation](http://jekyllrb.com/).
