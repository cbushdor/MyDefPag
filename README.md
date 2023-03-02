# Introduction

This script is intended to printout a nice default page if it is included/present in the current directory.

## RULE 1

If so, update(s) is/are made within sub-directorie(s) present(s) in this directory. The initial script is copied in that sub-directory that's how it is updated.

## RULE 2

If you go within one of these sub-directorie(s) then, it becomes current directory and RULE 1 is applied and so on and so fourth!

## FILE README.POD

By default only README.pod is interpreted in the current directory.  To write *.pod scripts go to https://perldoc.perl.org/perlpod. Only one README.pod file per directory is allowed but that directory can have as many as *.pod file as needed!

# Technical prerequisites

- It is needed to have script interpreter installed at server side.

- It is needed to install some more dependencies... To install these dependecies go to https://www.cpan.org/.

- Modification within *index.cgi* need to be made:

```
my %pathOS = ( 'linux' => '/home/sdo/public_html/','darwin' => '/Users/sdo/Sites/');
```

- Deprecated link on repo was made.

# What else to say? Just click me!

Daily [dem](https://youtu.be/sYGizBhjti4) is there for the time being! :-(

# FYI

It is still unstable portage is not over yet. Tested on Linux (Fedora, Ubuntu), Mac OS X (Venture 13.1).

