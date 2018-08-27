# sysadmin-reading-list

[![Build Status](https://travis-ci.org/unixorn/sysadmin-reading-list.png)](https://travis-ci.org/unixorn/sysadmin-reading-list)

A reading list for the larval stage sysadmin. This list is focused on the UNIX family of OSes, mainly because that is my area of expertise.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Articles and Books to Read](#articles-and-books-to-read)
- [Languages](#languages)
  - [Bash](#bash)
  - [Powershell](#powershell)
  - [Python](#python)
    - [Python Books](#python-books)
    - [Tutorials @ Python](#tutorials--python)
    - [Python & Sysadmin](#python--sysadmin)
    - [Python & Deployment Utils](#python--deployment-utils)
  - [Ruby](#ruby)
    - [Ruby Books](#ruby-books)
  - [Perl](#perl)
    - [Toolchain](#toolchain)
    - [Web](#web)
    - [Modules](#modules)
    - [Blog Posts](#blog-posts)
- [Tools](#tools)
  - [Cloud](#cloud)
    - [Multi-Platform](#multi-platform)
    - [AWS](#aws)
    - [Azure](#azure)
  - [Configuration Management](#configuration-management)
  - [Docker](#docker)
    - [Installing Docker](#installing-docker)
    - [Learning Docker](#learning-docker)
  - [Regular Expressions](#regular-expressions)
  - [Sed & Awk](#sed--awk)
  - [Source control](#source-control)
    - [Git](#git)
  - [SSH](#ssh)
  - [Testing](#testing)
    - [Test Harnesses](#test-harnesses)
  - [Text Editors:](#text-editors)
    - [Vim](#vim)
    - [Emacs](#emacs)
    - [Visual Editors and IDEs](#visual-editors-and-ides)
- [Blogs and Podcasts](#blogs-and-podcasts)
- [Online Communities](#online-communities)
- [Windows Administration](#windows-administration)
- [Other Resources](#other-resources)
  - [Miscellanea](#miscellanea)
  - [Career/Finance](#careerfinance)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

So you've got your first sysadmin job. Congratulations, it's going to be an interesting ride.

## Articles and Books to Read

* [Clean Code](https://www.amazon.es/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) - Every year, countless hours and significant resources are lost because of poorly written code. But it doesn't have to be that way. Martin has teamed up with his colleagues from Object Mentor to distill their best agile practice of cleaning code "on the fly" into a book that will instill within you the values of a software craftsman and make you a better programmer-but only if you work at it.
* [Continuous Delivery](https://smile.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912) - A book that has rapidly become *the* guide to planning and implementing build pipelines.
* [Effective DevOps](http://shop.oreilly.com/product/0636920039846.do) - A practical guide for creating affinity among teams and promoting efficient tool usage in your company.
* [Git Magic (free ebook)](http://www-cs-students.stanford.edu/~blynn/gitmagic/) - Git is a version control Swiss army knife. A reliable versatile multipurpose revision control tool whose extraordinary flexibility makes it tricky to learn, let alone master.
* [Hello DNS](https://github.com/ahupowerdns/hello-dns) - Every sysadmin/sre needs to know how DNS works. Start with [DNS Basics](https://github.com/ahupowerdns/hello-dns/blob/master/basic.md) is a good introduction.
* [Lean Startup](https://smile.amazon.com/Lean-Startup-Entrepreneurs-Continuous-Innovation/dp/0307887898) or [Lean Enterprise](https://smile.amazon.com/Lean-Enterprise-Performance-Organizations-Innovate/dp/1449368425) - This pair describes the process surrounding implementation and use of Lean principles in Startup and Enterprise organizations. There are a number of companion pieces that extend the principles to specific fields of study and implementation, such as [Lean Analytics](https://smile.amazon.com/Lean-Analytics-Better-Startup-Faster/dp/1449335675).
* [Site Reliability Engineering](http://shop.oreilly.com/product/0636920041528.do) - How Google Runs Production Systems. This can be read online for free at Google's SRE [site](https://landing.google.com/sre/book/index.html).
* [Systems Performance: Enterprise and Cloud](https://smile.amazon.com/Systems-Performance-Enterprise-Brendan-Gregg/dp/0133390098) by Brendan Gregg, this book is an award winner and a favorite of many a sysadmin, it addresses systems performance at scale.
* [The Art of Capacity Planning](https://smile.amazon.com/Art-Capacity-Planning-Scaling-Resources-ebook/dp/B0026OR2Y0) - John Allspaw's book is a hands-on and practical guide to planning for such growth, with many techniques and considerations to help you plan, deploy, and manage web application infrastructure.
* [The Art of Monitoring](https://artofmonitoring.com/) - James Turnbull's book on the art of modern application and infrastructure monitoring and metrics.
* [The DevOps Handbook: How to Create World-Class Agility, Reliability, and Security in Technology Organizations](https://smile.amazon.com/DevOps-Handbook-World-Class-Reliability-Organizations/dp/1942788002) - The results of a multi-user case study on DevOps and the practical-oriented sequel to The Phoenix Project
* [The Goal](https://smile.amazon.com/Goal-Process-Ongoing-Improvement/dp/0884271951/ref=zg_bs_10020725011_1) - A foundational novel on the Theory of Constraints and many other operational concerns.
* [The Phoenix Project](http://smile.amazon.com/Phoenix-Project-DevOps-Helping-Business-ebook/dp/B00AZRBLHO) - know why your projects are important to the business.
* [The Practice of Cloud System Administration](https://smile.amazon.com/Practice-Cloud-System-Administration-Distributed/dp/032194318X), by Tom Limoncelli. Focuses on “distributed” or “cloud” computing and brings a DevOps/SRE sensibility to the practice of system administration. Includes case studies and examples from Google, Etsy, Twitter, Facebook, Netflix, Amazon, and other industry giants are explained in practical ways that are useful to all enterprises.
* [Time Management for System Administrators](http://smile.amazon.com/Management-System-Administrators-Thomas-Limoncelli/dp/0596007833), by Tom Limoncelli. You're going to be pulled in a dozen different directions, if you can't manage your time you're going to suffer.
* [UNIX-Linux-System-Administration-Handbook](http://smile.amazon.com/UNIX-Linux-System-Administration-Handbook/dp/0131480057) by Evi Nemeth is a great book, this book is targeted to larger system deployments and real world large systems.
* [Web Operations: Keeping the Data on Time](https://smile.amazon.com/Web-Operations-Keeping-Data-Time-ebook/dp/B0043M4Z34) - A collection of essays and interviews, with web veterans such as Theo Schlossnagle, Baron Schwartz, and Alistair Croll that will teach you strategies for designing your web site to scale up smoothly to web-scale load.

## Languages

### Bash

Bash is objectively a terrible programming language. All variables default to being globals, there is no module system built into the language, dealing with hashes is horrible, and there are other horrors based on it trying to be backward compatible with `sh`.

That said, every *NIX sysadmin needs to know Bash. Here are some useful resources to help you step up your shell scripting game:

* [Advancing in the Bash Shell](http://samrowe.com/wordpress/advancing-in-the-bash-shell/) - Sam Rowe's bash as CLI tutorial.
* [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls) - Greg Wooledge has a great list of unpleasant surprises in Bash.
* [Google's Shell Style Guide](https://google.github.io/styleguide/shell.xml) lists what Google's developers consider best practices for bash scripts.
* [Learning the Bash Shell](http://shop.oreilly.com/product/9780596009656.do) - hard to go wrong with an O'Reilly reference on anything, really.
* [Pure Bash Bible](https://github.com/dylanaraps/pure-bash-bible) - A collection of pure bash alternatives to external processes.
* [Safe Ways to do Things in Bash(https://github.com/anordal/shellharden/blob/master/how_to_do_things_safely_in_bash.md) - Excellent set of tips from the authors of [shellharden](https://github.com/anordal/shellharden)
* [shellcheck](https://github.com/koalaman/shellcheck) is a lint for bash. It'll help you find unused variables, deprecated syntax and other things that make your bash scripts less stable. You can install it with `apt-get`, `brew`, `cabal`, or `yum`.
* [shellharden](https://github.com/anordal/shellharden/blob/master/how_to_do_things_safely_in_bash.md) - is a syntax highlighter and a tool to semi-automate the rewriting of scripts to ShellCheck conformance, mainly focused on quoting.

### Powershell

Often you'll find yourself in a Windows enviroment, like it or not. These might come help you in those cases -

* [Best Practices and Style guide](https://github.com/PoshCode/PowerShellPracticeAndStyle)
* [Powershell Slack](http://slack.poshcode.org) - Think of it as a virtual Powershell user's group
* [PowerShell.org eBooks](https://leanpub.com/u/devopscollective/)
* [PS Cmdlets In Your Inbox](https://github.com/MaxAnderson95/Cmdlets_In_Your_Inbox) lets you schedule a task to get PowerShell Cmdlets via email daily or at the command line.

### Python

Python has much better support for string manipulation and system infrastructure than Bash. In addition, there is a rich library of modules supporting various tasks you can use in your scripts that are just a `pip install` away.

A couple of places to go into as training would be:

#### Python Books

* [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/), a free Book that helps you automate boring and repetitive Tasks with Python.
* [Programming Python](http://shop.oreilly.com/product/9780596158118.do), a well-written O'Reilly book, short and concise.
* [20 Python Libraries You Aren't Using (But Should)](http://www.oreilly.com/programming/free/20-python-libraries-you-arent-using-but-should.csp), a free Book by Caleb Hattingh published by O'Reilly (No real Email address needed.)

#### Tutorials @ Python

* [Learn Python the Hard Way](http://learnpythonthehardway.org/book/), a rather comprehensive tutorial covering many aspects of the language.

#### Python & Sysadmin

* [The Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/scenarios/admin/), a neat place to see usage and examples of Python and not only for systems administration.
* [WSGI - Web Server Gateway Interface](http://uwsgi-docs.readthedocs.io/en/latest/WSGIquickstart.html), the Python implementation of web servers.

#### Python & Deployment Utils

* [WSGI + Flask tutorial](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
* [WSGI + Gunicorn tutorial](https://www.digitalocean.com/community/tutorials/how-to-deploy-python-wsgi-apps-using-gunicorn-http-server-behind-nginx)
* [WSGI + Pyramid tutorial](https://www.digitalocean.com/community/tutorials/how-to-deploy-pyramid-based-python-wsgi-web-applications)

### Ruby

Ruby also has a rich ecosystem of gems you can use in your programs, and like Python, much better string and data structure manipulation than Bash.

#### Ruby Books

If you're in a Ruby shop, you'll want these books:

* [Ruby Best Practices](http://shop.oreilly.com/product/9780596523015.do)
* [Ruby: Learn Ruby in 24 Hours or Less](https://smile.amazon.com/Ruby-Beginners-Learning-Programming-Course/dp/1533191611)
* [The Ruby Programming Language](http://shop.oreilly.com/product/9780596516178.do)

### Perl

Perl has a long history of being the system administrator's friend, bringing the best of bash, sed and awk together. It is also suitable for building tools for the system administrator to utilise in their work.

#### Toolchain

* [carton](https://metacpan.org/pod/Carton) - A dependency management tool.
* [cpanm](https://metacpan.org/pod/App::cpanminus) - An alternative and very friendly tool for installing modules from CPAN. This pairs well with perlbrew.
* [perlbrew](https://perlbrew.pl/) - A tool for managing one or more Perl installations, without needing to modify the system-level Perl.
* [pinto](https://metacpan.org/pod/Pinto) - A tool for managing a private CPAN repository.

#### Web

* [Mojolicious](https://metacpan.org/pod/Mojolicious) - A rich framework for doing all things web, from building web services and sites to building HTTP client applications.
* [Plack/PSGI](http://plackperl.org/) - The Perl implementation of WSGI, with many Plack servers available for use.

#### Modules

* [Task::Kensho](https://metacpan.org/pod/Task::Kensho) - A list of recommended modules for many purposes, including reading configuration files, connecting to databases, logging, sending email, web crawling and development, and handling XML.

#### Blog Posts

* [Perl on the Rise for Devops](https://scalability.org/2017/01/perl-on-the-rise-for-devops/)
* [A Perl Toolchain for Building Microservices at Scale](https://engineering.semantics3.com/a-perl-toolchain-for-building-micro-services-at-scale-8851626a4b1b)

## Tools

### Cloud

#### Multi-Platform

* [Terraform](https://www.terraform.io) is a tool that allows you to configure your infrastructure as code, just like Chef/Puppet/etc allow you to manage the configuration of individual machines as code, with all the benefits of being able to diff, code review, etc. Terraform works with (as of this edit) AWS, Google Cloud, Microsoft Azure and many other systems.

#### AWS

* [AWSCli](https://github.com/aws/aws-cli) provides a unified command line interface to Amazon Web Services. Wean yourself off of the webui if you want to be truly productive.
* [og-aws](https://github.com/open-guides/og-aws) is an excellent resource to AWS written by and for engineers who use AWS extensively.
* [S3cmd](http://s3tools.org/s3cmd) is a free command line tool and client for uploading, retrieving and managing data in Amazon S3 and other cloud storage service providers that use the S3 protocol, such as Google Cloud Storage or DreamHost DreamObjects.

#### Azure

* [Azure CLI 2.0](https://github.com/Azure/azure-cli) new preview CLI interface for Azure (written in python).
* [Azure Code Samples](https://azure.microsoft.com/en-us/documentation/samples/) samples of code showing how to interact with Azure.
* [Azure Friday](https://azure.microsoft.com/en-us/documentation/videos/azure-friday/) "Just two engineers, a laptop and the cloud, solving problems".
* [Azure Quickstart Templates](https://github.com/Azure/azure-quickstart-templates) community contributed Azure Resource Manager templates for tons of things.
* [Azure Xplat CLI](https://github.com/Azure/azure-xplat-cli) cross platform CLI interface for Azure (written in nodejs).
* [Official Azure Documentation](https://azure.microsoft.com/en-us/documentation/) official documentation for all Azure services.

### Configuration Management

Quite simply, if you aren't using configuration management, you're doing it wrong.

You don't want to manually configure any servers - no matter how hard you try, they won't end up truly identical and having meat typing in commands takes far too long per server, doesn't scale, and the manual labor will discourage you from standing up new VMs for testing.

Treating your configuration as something described in text files allows you to treat it like code. You can do pull-requests, get your changes reviewed by your team and view the differences between your configuration at different times.

There are several good options:

* [Ansible](http://www.ansible.com/) is designed to be minimal in nature, consistent, secure, and highly reliable. Was recently purchased by Red Hat.
* [Chef](http://www.opscode.com/chef/) is written in Ruby and Erlang and uses a Ruby DSL to describe system configuration
* [Puppet](http://puppetlabs.com/) makes it easy to automate the provisioning, configuration and ongoing management of your machines and the software running on them. Make rapid, repeatable changes and automatically enforce the consistency of systems and devices – across physical and virtual machines, on premise or in the cloud.
* [Salt](http://www.saltstack.com/) orchestrates the build and ongoing management of your infrastructure.

### Docker

[Docker](https://www.docker.com/what-docker) is a tool for running and managing
containers. Containers are rapidly growing in popularity for local development
(as an alternative to virtual machines), and can also run software in production
with tools like [Kubernetes](https://kubernetes.io/) or [Amazon
ECS](https://aws.amazon.com/ecs/).

#### Installing Docker

Follow the installation instructions for your preferred platform:

* [Docker CE for Mac](https://docs.docker.com/docker-for-mac/install/#download-docker-for-mac)
* [Docker CE for Linux](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/)
  * Linux usually requires a separate installation of [docker-compose](https://docs.docker.com/compose/install/)
* [Docker CE for Windows](https://docs.docker.com/docker-for-windows/install/)

#### Learning Docker

* [The Docker Book](https://www.dockerbook.com/) - An excellent resource for getting started with Docker. This book is quick & easy to read.

### Regular Expressions

Among the many places you're going to find regexes very useful for is handling logs. When you have a multi-gigabyte logfile, it's a lot less painful to look at just the entries generated by the service that you got alerted about.

* [Introducing Regular Expressions](http://shop.oreilly.com/product/0636920012337.do)
* [Regular Expressions Cookbook](http://shop.oreilly.com/product/0636920023630.do)

### Sed & Awk

* [sed and awk Pocket Reference](http://shop.oreilly.com/product/9780596003524.do) presents a concise summary of regular expressions and pattern matching, and summaries of sed and awk and how to use them to edit files and convert data from one format to another.

### Source control

No matter what source control system you use (git, hg, perforce, whatever), you're going to have to write commit messages. Make them good. Explain _why_ you made the change, not just _what_ you changed. And no, the diff is not an explanation. Always start with a single line that explains what you were trying to do in general, then a body that goes into more detail.

Good commit messages help the rest of your team understand what you're trying to do and make it easier for them to find logic errors in your pull requests - the code may be technically correct, but if they understand what you're _trying_ to do, they can see when your code isn't actually doing what you say you want it to do, even if it is technically correct.

Here are a few articles that while focused on git apply to any source control system you're using:

* [5 Useful Tips for a Better Commit Message](https://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message) is another good article on writing commit messages.
* [A Note About Git Commit Messages](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
* [Writing Good Commit Messages](http://chris.beams.io/posts/git-commit/) is a good article on writing coherent commit messages.

#### Git

Whether or not your shop uses git internally, you're going to end up needing to use it for the many useful things on GitHub.

* [19 Git Tips for Everyday Use](http://www.alexkras.com/19-git-tips-for-everyday-use/) - a good set of starter tips for using git.
* [git-flight-rules](https://github.com/k88hudson/git-flight-rules) is Kate Hudson's guide to using Git in specific situations.
* [git-tips/tips](https://github.com/git-tips/tips) is a collection of git tips
* [Pro Git](https://git-scm.com/book/en/v2) by Scott Chacon and Ben Straub is a great overall resource for git.
* [Why the Heck is Git so Hard? The Places Model](http://merrigrove.blogspot.com/2014/02/why-heck-is-git-so-hard-places-model-ok.html) - an article about moving from SVN/CVS to git.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - a collection of extra git helper scripts.
* Ben Limmer's [Git Skills Talk](https://github.com/blimmer/1up-git-skills-talk) will help you understand using git (particularly with GitHub)

### SSH

* [SSH, The Secure Shell: The Definitive Guide, 2nd Edition](http://shop.oreilly.com/product/9780596008956.do)

### Testing

Testing is incredibly important and you should undertake this for your infrastructure as well as your applications.

#### Test Harnesses

* [Test Kitchen](https://kitchen.ci) - Test your configuration management tooling.

### Text Editors:

Don't get involved in the Editor Wars.  Just.  Don't.  Your choice of tool does not need defending.  Nor does anyone else's choice.

However, you should care about your tools.  You should be able to use them efficiently.

#### Vim

Vim is a reality of life for SysAdmins.  It is the one editor you can be sure is installed in even the most minimal install. You must be able to do at least basic edits with it.  You don't need to love it, but you _will_ have to use it.

* [Damian Conway, "More Instantly Better Vim" - OSCON 2013](https://www.youtube.com/watch?v=aHm36-na4-4)
* [vi and Vim Editors Pocket Reference, 2nd Edition](http://shop.oreilly.com/product/0636920010913.do)

#### Emacs

Emacs is an extremely extensible editor. In jest, it is frequently referred to as an operating system with a half-decent editor.

If you want to get a taste of what emacs can do, you can defer to Magnars and his excellent video tutorials/demos:

* http://emacsrocks.com/

One of the biggest problems with Emacs is that the defaults present a fairly different experience to what people are used to. Your first stop should be learning the basics using the built-in tutorial, followed by the mini-manual from tuhdo:

* Type `ctrl-h`, followed closely by `t` from within emacs to see the tutorial
* http://tuhdo.github.io/index.html

Emacs can be can be made to look and act relatively modern if that's your desire:

* http://emacs.sexy/

If you're looking for emacs packages, the following online package index is the most popular, and tracks many:

* http://melpa.org/

There are several excellent starter kits out there, with varying delineations of wizz-bang. Roughly sorted by wizz-bang, here are the starter kits that exist, with spacemacs being the most popular:

* https://github.com/technomancy/better-defaults
* https://github.com/bbatsov/prelude
* https://github.com/hlissner/doom-emacs
* https://github.com/syl20bnr/spacemacs

Here are some emacs configurations for inspiration:

* Steve Purcell's excellent config: https://github.com/purcell/emacs.d
* Magnar Sveen's very interesting and original emacs config! https://github.com/magnars/.emacs.d
* Phil Hagelberg's config: https://github.com/technomancy/dotfiles/tree/master/.emacs.d

#### Visual Editors and IDEs

Use tools with which you are productive.  If you want to use a GUI Text Editor or IDE, don't let anyone give you a hard time about that.

There are GUI versions of vim and emacs that have ardent followers.

* [Atom](https://atom.io/) is a fairly new editor with significant traction and plugin ecosystem.
* [Sublime Text](http://sublimetext.com) is another editor with an extensive plugin ecosystem and arguably one of the inspirations for Atom.
* [Visual Studio Code](https://code.visualstudio.com) is a cross platform editor that is gaining traction in the marketplace.

## Blogs and Podcasts

* [Arrested Devops](https://www.arresteddevops.com/) is hosted by Matt Stratton, Trevor Hess, and Bridget Kromhout. ADO is the podcast that helps you achieve understanding, develop good practices, and operate your team and organization for maximum DevOps awesomeness.
* [Code as Craft](http://codeascraft.com/) is Etsy's ops blog and is full of well written examples of dealing with real-world problems at scale.
* [Hey, Scripting Guy! Blog](https://blogs.technet.microsoft.com/heyscriptingguy/) is a blog that answers common (and some uncommon) PowerShell queries.
* [Julia Evans' Blog](http://jvns.ca/) - Julia writes a great blog where she dives into interesting ops topics and explains them clearly.
* [Kitchen Soap](http://www.kitchensoap.com/) - John Alspaw is the CTO at Etsy and writes a great blog about web operations and operating at scale and other things that are interesting to ops types.
* [PowerScripting Podcast](https://powershell.org/podcast/) is hosted by Jon Walz and Hal Rottenberg.

## Online Communities

* [DevOpsChat Slack](https://devopschat.co/) is another community of DevOps minded folk with a diverse set of topic specific chat rooms. Home to Arrested DevOps.
* [Hangops Slack](https://signup.hangops.com/) is a community of DevOps minded folk with many subject focused chat rooms.
* [PowerShell Slack](http://slack.poshcode.org/) is a community of PowerShell enthusiasts and Windows centric DevOps topics.

## Windows Administration

Help wanted here.

## Other Resources

### Miscellanea

* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open-source sysadmin resources.
* Etsy's [Debriefing Facilitation Guide](https://extfiles.etsy.com/DebriefingFacilitationGuide.pdf) is a great guide to conducting a blame-free debrief after an outage.
* [oncall-handbook](https://github.com/alicegoldfuss/oncall-handbook) - Alice Goldfuss' excellent oncall handbook, read this before your first oncall shift.
* [stack-on-a-budget](https://github.com/255kb/stack-on-a-budget) - A list of free/cheap tiers of services that you can use to learn the various cloud-based systems.
* [sysadvent](https://sysadvent.blogspot.com/) - Every year the sysadvent team publishes 24 good articles for sysadmins.
* Pēteris Ņikiforovs has a good blog post explaining what everything you see in top/htop output [here](https://peteris.rocks/blog/htop/)

### Career/Finance

* Patrick McKenzie wrote a great blog post on [salary negotiation](https://www.kalzumeus.com/2012/01/23/salary-negotiation/). Salary negotiation is one of the few times in your life where a five minute conversation can earn you thousands of dollars - be prepared.
* Patrick also has a good podcast episode on salary negotiation - [Kalzumeus Podcast Episode 12: Salary Negotiation with Josh Doody](https://www.kalzumeus.com/2016/06/03/kalzumeus-podcast-episode-12-salary-negotiation-with-josh-doody/)  (there's a transcript too). You have to do it, it affects your life, you should do it well.
* [The Holloway Guide to Equity Compensation](https://www.holloway.com/g/equity-compensation) - Stock options, RSUs, job offers, and taxes—a detailed reference, including hundreds of resources, explained from the ground up.
* [What I Wish I'd Known About Equity Before Joining A Unicorn](https://gist.github.com/yossorion/4965df74fd6da6cdc280ec57e83a202d) - This is an excellent summary of how to value stock options and what the tax implications are and how to minimize potential tax (in a USA-centric way). I heartily recommend reading it before you accept any offers involving stock as part of your compensation.
