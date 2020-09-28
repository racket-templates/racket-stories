# web-app

This template is a the code used for the [Racket Stories](https://racket-stories.com) is a "submit and vote" web site. 

# How To Install

1. [Set your PATH environment variable](https://github.com/racket/racket/wiki/Set-your-PATH-environment-variable) 
so you can use `raco` and other Racket command line functions.
2. either look for `from-template` in the DrRacket menu **File|Package Manager**, or run the `raco` command:
```bash
raco pkg install from-template
```
3. 
```bash
raco new web-app <destination-dir>
```
If you omit `<destination-dir>`, the command will add copy the template to a folder called `web-app` in the current folder.

# How to use

This is working example that you can change to suit your needs, but does require some setup to get going.

This repo serves as an example of a small "in production" web-applications written in Racket and includes the base 
components of a web application including 
* modern front-end utilising jQuery, Popper and Bootstrap JS
* persistent database store
* user accounts and linking to github
* users adding content and validation - in this case stopping multiple submissions of the same link. 

For guidance about using this template please see https://racket-stories.com/about

To learn about writing this sort of web application please see https://github.com/soegaard/web-tutorial 
and https://docs.racket-lang.org/continue/index.html

See this code working at https://racket-stories.com/
