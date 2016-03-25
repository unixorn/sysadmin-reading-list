# sysadmin-reading-list

[![Build Status](https://travis-ci.org/unixorn/sysadmin-reading-list.png)](https://travis-ci.org/unixorn/sysadmin-reading-list)

A reading list for the larval stage sysadmin. This list is focused on the UNIX family of OSes.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [sysadmin-reading-list](#sysadmin-reading-list)
  - [Books to Read](#books-to-read)
  - [Languages](#languages)
    - [Bash](#bash)
    - [Ruby](#ruby)
  - [Tools](#tools)
    - [Regular Expressions](#regular-expressions)
    - [Sed & Awk](#sed-&-awk)
    - [Source control](#source-control)
      - [Git](#git)
    - [SSH](#ssh)
    - [Text Editors:](#text-editors)
      - [Vim](#vim)
      - [Emacs](#emacs)
      - [Visual Editors and IDEs](#visual-editors-and-ides)
  - [Blogs and Podcasts](#blogs-and-podcasts)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

So you've got your first sysadmin job. Congratulations, it's going to be an interesting ride.

## Books to Read

* [The Phoenix Project](http://smile.amazon.com/Phoenix-Project-DevOps-Helping-Business-ebook/dp/B00AZRBLHO) - know why your projects are important to the business
* [Time Management for System Administrators](http://smile.amazon.com/Management-System-Administrators-Thomas-Limoncelli/dp/0596007833), by Tom Limoncelli. You're going to be pulled in a dozen different directions, if you can't manage your time you're going to suffer.
* [UNIX-Linux-System-Administration-Handbook](http://smile.amazon.com/UNIX-Linux-System-Administration-Handbook/dp/0131480057) by Nemeth is a great book, this book is targeted to larger system deployments and real world large systems.

## Languages

### Bash

Every sysadmin needs to know Bash.

* [Learning the Bash Shell](http://shop.oreilly.com/product/9780596009656.do) - hard to go wrong with an O'Reilly reference on anything, really.
* [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls) - Greg Wooledge has a great list of unpleasant surprises in Bash

### Ruby

If you're in a Ruby shop, you'll want these:

* [The Ruby Programming Language](http://shop.oreilly.com/product/9780596516178.do)
* [Ruby Best Practices](http://shop.oreilly.com/product/9780596523015.do)


## Tools

### Cloud

#### AWS

* [AWSCli](https://github.com/aws/aws-cli) provides a unified command line interface to Amazon Web Services. Wean yourself off of the webui if you want to be truly productive
* [S3cmd](http://s3tools.org/s3cmd) is a free command line tool and client for uploading, retrieving and managing data in Amazon S3 and other cloud storage service providers that use the S3 protocol, such as Google Cloud Storage or DreamHost DreamObjects.

### Configuration Management

Quite simply, if you aren't using configuration management, you're doing it wrong.

You don't want to manually configure any servers - no matter how hard you try, they won't end up truly identical and having meat typing in commands takes far too long per server, doesn't scale, and the manual labor will discourage you from standing up new VMs for testing.

There are several good options:

* [Ansible](http://www.ansible.com/) is designed to be minimal in nature, consistent, secure, and highly reliable. Was recently purchased by Red Hat.
* [Chef](http://www.opscode.com/chef/) is written in Ruby and Erlang and uses a Ruby DSL to describe system configuration
* [Puppet](http://puppetlabs.com/) makes it easy to automate the provisioning, configuration and ongoing management of your machines and the software running on them. Make rapid, repeatable changes and automatically enforce the consistency of systems and devices – across physical and virtual machines, on premise or in the cloud.
* [Salt](http://www.saltstack.com/) orchestrates the build and ongoing management of your infrastructure.

### Regular Expressions

You're going to want your regular expressions to be like:

![xkcd 208](http://imgs.xkcd.com/comics/regular_expressions.png),

but in reality they're going to be a lot more like at first:

![xkcd 1171](http://imgs.xkcd.com/comics/perl_problems.png) some days.

But seriously, you're going to find regexes very useful for handling logs.

* [Regular Expressions Cookbook](http://shop.oreilly.com/product/0636920023630.do)
* [Introducing Regular Expressions](http://shop.oreilly.com/product/0636920012337.do)

### Sed & Awk

* [sed and awk Pocket Reference](http://shop.oreilly.com/product/9780596003524.do) presents a concise summary of regular expressions and pattern matching, and summaries of sed and awk and how to use them to edit files and convert data from one format to another.

### Source control

#### Git

Whether or not your shop uses git internally, you're going to end up needing to use it for the many useful things on GitHub.

* [Pro Git](https://git-scm.com/book/en/v2) is a great resource.

### SSH

* [SSH, The Secure Shell: The Definitive Guide, 2nd Edition](http://shop.oreilly.com/product/9780596008956.do)

### Text Editors:

Don't get involved in the Editor Wars.  Just.  Don't.  Your choice of tool does not need defending.  Nor does anyone else's choice.

However, you should care about your tools.  You should be able to use them efficiently.

#### Vim

Vim is a reality of life for SysAdmins.  It is the one editor you can be sure is installed in even the most minimal install. You must be able to do at least basic edits with it.  You don't need to love it, but you will have to use it.

* [vi and Vim Editors Pocket Reference, 2nd Edition](http://shop.oreilly.com/product/0636920010913.do)
* [Damian Conway, "More Instantly Better Vim" - OSCON 2013](https://www.youtube.com/watch?v=aHm36-na4-4)

#### Emacs

Many people like Emacs.  You might be one of them.  Don't be afraid to try it out.

#### Visual Editors and IDEs

Use tools with which you are productive.  If you want to use a GUI Text Editor or IDE, don't let anyone give you a hard time about that.

There are GUI versions of vim and emacs that have ardent followers.

[Atom](https://atom.io/) is a fairly new editor with significant traction and plugin ecosystem.
[Sublime Text](http://sublimetext.com) is another editor with an extensive plugin ecosystem and arguably one of the inspirations for Atom.

## Blogs and Podcasts

* [Arrested Devops](https://www.arresteddevops.com/) is hosted by Matt Stratton, Trevor Hess, and Bridget Kromhout. ADO is the podcast that helps you achieve understanding, develop good practices, and operate your team and organization for maximum DevOps awesomeness.
* [Code as Craft](http://codeascraft.com/) is Etsy's ops blog and is full of well written examples of dealing with real-world problems at scale.
* [Kitchen Soap](http://www.kitchensoap.com/) - John Alspaw is the CTO at Etsy and writes a great blog about web operations and operating at scale and other things that are interesting to ops types.
