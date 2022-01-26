# CSci 3601 Lab #1 - HTML and CSS Lab <!-- omit in toc -->

[![Check Markdown links](../../actions/workflows/link-check.yaml/badge.svg)](../../actions/workflows/link-check.yaml)

- [Setup Instructions](#setup-instructions)
- ["Running" your project](#running-your-project)
  - [Our Team's GitHub Pages URL](#our-teams-github-pages-url)
  - [Version Control Reminder](#version-control-reminder)
- [Resources](#resources)
  - [Good commit messages and pull requests](#good-commit-messages-and-pull-requests)
  - [Validating your code](#validating-your-code)
  - [Potentially useful resources](#potentially-useful-resources)
    - [General HTML](#general-html)
    - [General CSS](#general-css)
    - [Flexbox resources](#flexbox-resources)
    - [General design resources](#general-design-resources)

In this lab you will learn to alter the look of a simple HTML website using CSS,
following best practices and using validated code, all while using version control
to manage your changes. This lab is partly inspired by
[CSS Zen Garden](http://www.csszengarden.com/) which demonstrates
how CSS alone can greatly alter the
look and feel of a web page.

This lab also focuses on what's called _responsive design_, which allows
a single web page to look good on multiple screen sizes rather than
constructing multiple designs for each type of device. This is important
given the plethora of phones, tablets, and computers people use to
view web pages. One important tool, for example, is _flexbox_, which
helps make html elements scale
with screen size. This is useful for making a webpage usable for mobile devices
or small screens.

Your specific tasks for this lab can be found in the [LABTASKS.md](LABTASKS.md)
file in this repository.

## Setup Instructions

Clone your repository to your local working environment.

On GitHub, you'll need to visit the *settings* for your repository and change
the *GitHub Pages* settings. Under the "Source" section, you'll need to select
the branch `main`, leave everything else at their defaults, and save your settings.

> Doing this will 'host' your website, specifically the version that is on
> your `main` branch. This means that everything you push to `main`
> will, in a sense, be 'published' - hence it is important that you practice
> responsible version control and only push completed features to your `main`
> branch.
>
> When you publish your site to GitHub pages, GitHub will display the URL
> where you can find your published site. The primary repo we use to manage
> changes to this lab across semesters is published
> at <http://umm-csci-3601.github.io/3601-lab1_HTML-CSS/>;
> yours will be at a different URL but should look somewhat similar.
>
> :bangbang: Once you have that URL, please include it in the "Website" box in the
> description at the top of your GitHub project page. Click the "Edit" button on the
> right hand side (just under "Settings") and that should give you a "Description" and
> a "Website" box; paste the URL into the "Website" box. That will make it a lot easier
> for us to go through all the projects and see your work.

## "Running" your project

To view your website on your local computer,
you should be able to simply open the `index.html` file in your
browser of choice. (In most cases, 'double clicking' the file should do this. In Visual Studio Code,
you can right click on the file, choose "Copy Path", and paste that into the browser's URL bar.)

Remove this paragraph from your `README.md` file. Replace the URL in the next subsection with your
team's GitHub.io URL, which should look something like
this: <http://umm-csci-3601.github.io/3601-lab1_HTML-CSS/> but will not be identical.

### Our Team's GitHub Pages URL

> You should replace the link below with a link to *your* group's GitHub Pages
> URL. Remember to also add that to your project description at the top of
> your team's repo on GitHub. You can remove this note when you've done these
> things.

<http://umm-csci-3601.github.io/3601-lab1_HTML-CSS/>

### Version Control Reminder

Remember to practice good version control! New features should be developed in
feature branches, [commit messages should be in the present tense and provide
meaningful information](http://chris.beams.io/posts/git-commit/),
and you should use pull requests on GitHub to merge
changes from feature branches into your `main` branch.

## Resources

### Good commit messages and pull requests

Writing good commit messages:

- [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/) (from Chris Beams, 2014)

> It's worth noting that GitKraken helps you with at least the structure of your commit
> message. It has you provide a "title" (kind of a "subject line") and will fuss
> if that gets longer than 72 characters. (It doesn't check other things, though,
> like the verb tense and the absence of a period at the end of the title.) Behind
> the scenes the "body" of the commit message will then be separated from the title
> by a blank line and the lines will be wrapped to 72 characters. It can't make your
> content useful, however – that's up to you. :grinning:

Writing good pull requests:

- [How to write the perfect pull request](https://github.blog/2015-01-21-how-to-write-the-perfect-pull-request/) (from GitHub, 2015)
- [The anatomy of a perfect pull request](https://medium.com/@hugooodias/the-anatomy-of-a-perfect-pull-request-567382bb6067) (from Hugo Dias, 2018)
  - The info on the _size_ of pull requests is particularly useful here.
- [The (written) unwritten guide to pull requests
](https://www.atlassian.com/blog/git/written-unwritten-guide-pull-requests) (from Atlassian, 2019)

### Validating your code

- [HTML Validation](http://validator.w3.org/)
- [CSS Validation](http://jigsaw.w3.org/css-validator/)

### Potentially useful resources

#### General HTML

- [HTML Tutorial at W3 Schools](http://www.w3schools.com/html/default.asp)
- [HTML5 Specific Tutorial at W3 Schools](http://www.w3schools.com/html/html5_intro.asp)

#### General CSS

- [CSS tutorial at W3 Schools](http://www.w3schools.com/css/default.asp), particularly:
  - [A guide to font families](http://www.w3schools.com/cssref/css_websafe_fonts.asp)
  - [CSS Box Model](http://www.w3schools.com/css/css_boxmodel.asp)
  - [CSS Float](http://www.w3schools.com/css/css_float.asp)- How to position elements next to each other
  - [CSS Display and Visibility](http://www.w3schools.com/css/css_display_visibility.asp)
  - [CSS Media Queries](https://www.w3schools.com/css/css3_mediaqueries.asp) - Add breakpoints to better design for specific sized screens

#### Flexbox resources

Add responsive design to automatically scale elements with page size.

- [Basic Concepts of Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
- [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [A Visual Guide to CSS Flexbox](https://www.freecodecamp.org/news/do-you-even-flex-box-c16449cfca96/)
- [Flexbox playground](https://coding.imweb.io/demo/flex/index.html)

#### General design resources

- [CSS Zen Garden](http://www.csszengarden.com/)- Some fancy examples of CSS, all of which use the same HTML, but look wildly different
- [FontJoy](https://fontjoy.com/) - a nice tool for helping find combinations of fonts that work well together. (Google Fonts provides a similar feature as well.)
- [Colormind](http://colormind.io) – a cool tool for helping find color combinations that work well together
