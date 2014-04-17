# How to contribute

Third-party patches are essential for keeping puppet great. We simply can't
access the huge number of platforms and myriad configurations for running
puppet. We want to keep it as easy as possible to contribute changes that
get things working in your environment. There are a few guidelines that we
need contributors to follow so that we can have a chance of keeping on
top of things.

## Getting Started

* Make sure you have a [GitHub account](https://github.com/signup/free)
* Create a issue, assuming one does not already exist.
  * Clearly describe the issue including steps to reproduce when it is a bug.
  * Don't forget to say if it's about the `gedit` or `notepad++` syntax.
  * Make sure you fill in the earliest version that you know has the issue.
* Fork the repository on GitHub

## Making Changes

This is a small project, we will be working on `master` branch.

* Fork it
* Create a test file at `test/` that address your problem
* Make your fix
** If you are editing the gedit syntax, http://regex101.com/#PCRE[this] site may help.
* Test the highlight on files at `test`
* Make a pull request

## Making Trivial Changes

### Documentation

For changes of a trivial nature to comments and documentation, 
just edit the file and do a pull request, you can do it inside github.

# Additional Resources

* [General GitHub documentation](http://help.github.com/)
* [GitHub pull request documentation](http://help.github.com/send-pull-requests/)
* [gedit/gtksourceview](https://developer.gnome.org/gtksourceview/stable/lang-tutorial.html)
* [PCRE - Perl Compatible Regular Expressions](http://regex101.com/#PCRE)
