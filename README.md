# Introduction

This script is intended to printout a nice default page if it is included/present in the current directory.

## RULE 1

If so, update(s) is/are made within sub-directorie(s)[^1]  present(s) in this directory.

## RULE 2

If you go within one of these sub-directorie(s) then, it becomes current directory and RULE 1 is applied and so on and so fourth!

## FILE README.POD

By default only README.pod[^3] is interpreted in the current directory[^2].

# Technical prerequisites

    It is needed to have script interpreter installed at server side.

    It is needed to install some more dependencies[^4]...

    Modification within *index.cgi* need to be made:

```
my %pathOS = ( 'linux' => '/home/sdo/public_html/','darwin' => '/Users/sdo/Sites/');
```

- Deprecated link on repo was made.

# What else to say? Just click me!

Daily [dem](https://youtu.be/sYGizBhjti4) is there for the time being! :-(

# FYI

It is still unstable portage is not over yet. Tested on Linux (Fedora, Ubuntu), Mac OS X (Venture 13.1).

[^1]: The initial script is copied in that sub-directory that's how it is updated.
[^2]: Only one README.pod file per directory but that directory can have as many as *.pod file as you want!
[^3]: [Pod](https://perldoc.perl.org/perlpod) syntax.
[^4]: [Dependecies](https://www.cpan.org/). 
