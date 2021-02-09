# sysadmin-reading-list

[![GitHub stars](https://img.shields.io/github/stars/unixorn/sysadmin-reading-list.svg)](https://github.com/unixorn/sysadmin-reading-list/stargazers)
[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Funixorn%2Fsysadmin-reading-list%2Fbadge&style=flat)](https://actions-badge.atrox.dev/unixorn/sysadmin-reading-list/goto)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/unixorn/sysadmin-reading-list/master.svg)](https://github.com/unixorn/sysadmin-reading-list)

A reading list for the larval stage sysadmin. This list is focused on the UNIX family of OSes, mainly because that is my area of expertise, but PRs about other OSes are welcome.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Articles and Books to Read](#articles-and-books-to-read)
- [Languages](#languages)
  - [Awk](#awk)
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
    - [Perl Books](#perl-books)
    - [Toolchain](#toolchain)
    - [Web](#web)
    - [Modules](#modules)
    - [Blog Posts](#blog-posts)
- [Tools](#tools)
  - [Cloud](#cloud)
    - [Multi-Platform](#multi-platform)
    - [AWS](#aws)
    - [Azure](#azure)
    - [Google Cloud](#google-cloud)
    - [OpenStack](#openstack)
  - [Configuration Management](#configuration-management)
  - [Docker](#docker)
    - [Installing Docker](#installing-docker)
    - [Learning Docker](#learning-docker)
  - [Kubernetes](#kubernetes)
    - [Tutorials](#tutorials)
    - [Utilities](#utilities)
  - [Monitoring](#monitoring)
    - [Articles/Tutorials](#articlestutorials)
  - [Regular Expressions](#regular-expressions)
  - [Sed & Awk](#sed--awk)
  - [Serverless](#serverless)
  - [Source control](#source-control)
    - [Git](#git)
  - [SSH](#ssh)
  - [Testing](#testing)
    - [Test Harnesses](#test-harnesses)
  - [Text Editors](#text-editors)
    - [Vim](#vim)
    - [Emacs](#emacs)
    - [Visual Editors and IDEs](#visual-editors-and-ides)
- [Blogs and Podcasts](#blogs-and-podcasts)
- [Online Communities](#online-communities)
- [Windows Administration](#windows-administration)
- [Other Resources](#other-resources)
  - [Free Services](#free-services)
  - [Miscellanea](#miscellanea)
  - [Career](#career)
  - [Communication](#communication)
  - [Finance/Salary](#financesalary)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

So you've got your first sysadmin/sre job or internship. Congratulations, it's going to be an interesting ride.

## Articles and Books to Read

- [A Few Ops Lessions We All Learn the Hard Way](https://www.netmeister.org/blog/ops-lessons.html) - A collection of lessons that everyone in Ops inevitably learns. You may not personally experience all of them, but they'll ring true after you're in ops for a while.
- [Clean Code](https://smile.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) - Every year, countless hours and significant resources are lost because of poorly written code. But it doesn't have to be that way. Martin has teamed up with his colleagues from Object Mentor to distill their best agile practice of cleaning code "on the fly" into a book that will instill within you the values of a software craftsman and make you a better programmer-but only if you work at it.
- [Continuous Delivery](https://smile.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912) - A book that has rapidly become *the* guide to planning and implementing build pipelines.
- [Effective DevOps](http://shop.oreilly.com/product/0636920039846.do) - A practical guide for creating affinity among teams and promoting efficient tool usage in your company.
- [Git Magic (free ebook)](http://www-cs-students.stanford.edu/~blynn/gitmagic/) - `git` is a version control Swiss army knife. A reliable versatile multipurpose revision control tool whose extraordinary flexibility makes it tricky to learn, let alone master.
- [Hello DNS](https://github.com/ahupowerdns/hello-dns) - Every sysadmin/sre needs to know how DNS works. Start with [DNS Basics](https://github.com/ahupowerdns/hello-dns/blob/master/basic.md) it's a good introduction.
- [Lean Startup](https://smile.amazon.com/Lean-Startup-Entrepreneurs-Continuous-Innovation/dp/0307887898) or [Lean Enterprise](https://smile.amazon.com/Lean-Enterprise-Performance-Organizations-Innovate/dp/1449368425) - This pair describes the process surrounding implementation and use of Lean principles in Startup and Enterprise organizations. There are a number of companion pieces that extend the principles to specific fields of study and implementation, such as [Lean Analytics](https://smile.amazon.com/Lean-Analytics-Better-Startup-Faster/dp/1449335675).
- [LinkedIn's School of SRE](https://github.com/linkedin/school-of-sre) - Linkedin is using this curriculum for onboarding non-traditional hires and new college grads into the SRE role.
- [Site Reliability Engineering](http://shop.oreilly.com/product/0636920041528.do) - How Google Runs Production Systems. This can be read online for free at Google's SRE [site](https://landing.google.com/sre/book/index.html).
- [Systems Performance: Enterprise and Cloud](https://smile.amazon.com/Systems-Performance-Enterprise-Brendan-Gregg/dp/0133390098) by Brendan Gregg, this book is an award winner and a favorite of many a sysadmin and SRE, it addresses systems performance at scale.
- [The Art of Capacity Planning](https://smile.amazon.com/Art-Capacity-Planning-Scaling-Resources-ebook/dp/B0026OR2Y0) - John Allspaw's book is a hands-on and practical guide to planning for such growth, with many techniques and considerations to help you plan, deploy, and manage web application infrastructure.
- [The Art of Monitoring](https://artofmonitoring.com/) - James Turnbull's book on the art of modern application and infrastructure monitoring and metrics.
- [The DevOps Handbook: How to Create World-Class Agility, Reliability, and Security in Technology Organizations](https://smile.amazon.com/DevOps-Handbook-World-Class-Reliability-Organizations/dp/1942788002) - The results of a multi-user case study on DevOps and the practical-oriented sequel to [The Phoenix Project](http://smile.amazon.com/Phoenix-Project-DevOps-Helping-Business-ebook/dp/B00AZRBLHO).
- [The Goal](https://smile.amazon.com/Goal-Process-Ongoing-Improvement/dp/0884271951/ref=zg_bs_10020725011_1) - A foundational novel on the Theory of Constraints and many other operational concerns.
- [The Phoenix Project](http://smile.amazon.com/Phoenix-Project-DevOps-Helping-Business-ebook/dp/B00AZRBLHO) - know why your projects are important to the business.
- [The Practice of Cloud System Administration](https://smile.amazon.com/Practice-Cloud-System-Administration-Distributed/dp/032194318X), by Tom Limoncelli. Focuses on “distributed” or “cloud” computing and brings a DevOps/SRE sensibility to the practice of system administration. Includes case studies and examples from Google, Etsy, Twitter, Facebook, Netflix, Amazon, and other industry giants are explained in practical ways that are useful to all enterprises.
- [Time Management for System Administrators](http://smile.amazon.com/Management-System-Administrators-Thomas-Limoncelli/dp/0596007833), by Tom Limoncelli. You're going to be pulled in a dozen different directions, if you can't manage your time you and your job performance are going to suffer.
- [UNIX-Linux-System-Administration-Handbook](http://smile.amazon.com/UNIX-Linux-System-Administration-Handbook/dp/0131480057) by Evi Nemeth is a great book, this book is targeted to larger system deployments and real world large systems.
- [Web Operations: Keeping the Data on Time](https://smile.amazon.com/Web-Operations-Keeping-Data-Time-ebook/dp/B0043M4Z34) - A collection of essays and interviews, with web veterans such as Theo Schlossnagle, Baron Schwartz, and Alistair Croll that will teach you strategies for designing your web site to scale up smoothly to web-scale load.
- [Wizard Zines](https://wizardzines.com/) - Julia Evans has a great set of zines she's published about many topics useful to a starting (or even an experienced) sysadmin/SRE.

## Languages

The **Dev** part of **DevOps** means you're going to inevitably end up writing some code. Here's a list of [free programming books](https://github.com/EbookFoundation/free-programming-books/) for many languages.

Here are some of the scripting languages you're most likely to see in your infrastructure, with links to some good references and tutorials.

### Awk

The `awk` family (`awk`, `gawk`, `nawk` and I'm sure I've missed other implementations) of scripting languages is one of the oldest - the first version of `awk` was written in 1977, but it's on pretty much any unix (even minimal variants that might not have `perl`, `python` or `ruby`) and is still very useful.

I still use it frequently for pulling columns out of tabular output because by default (and unlike `cut` where you have to count spaces) it treats consecutive runs of whitespace characters as a delimiter, so for example you can pipe things to `awk '{print $3}'`, but it's Turing-complete - people can and have written complex programs in it.

Here are some good references to get you started:

- [Bite Size Command Line](https://wizardzines.com/comics/awk/)
- [Scripting Tutorial: Awk](https://github.com/darkn3rd/script-tut/tree/master/gen_scripts/awk)
- [Serious Shell Programming](https://freebsdfrau.gitbook.io/serious-shell-programming/basics/regex/awk)

### Bash

`bash` is objectively a terrible programming language. All variables default to being globals, there is no module system built into the language, dealing with hashes is horrible, and there are other horrors resulting from it trying to be backward compatible with `sh`.

That said, it is on every system, so every *NIX sysadmin needs to know `bash`.

Here are some useful resources to help you step up your shell scripting game:

- [The Art of the Command Line](https://github.com/jlevy/the-art-of-command-line) - A good set of notes and tips on using the command-line useful when working on Linux/Unix.
- [Advancing in the Bash Shell](http://samrowe.com/wordpress/advancing-in-the-bash-shell/) - Sam Rowe's `bash` as CLI tutorial.
- [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls) - Greg Wooledge has a great list of unpleasant surprises in `bash`.
- [Bash Guide](https://mywiki.wooledge.org/BashGuide) - Gives examples of good practice when writing `bash` scripts. It is targeted at beginning users with no advanced knowledge.
- [Commandlinefu](https://www.commandlinefu.com/) - an extensive list of `bash` oneliners for almost every task you may need to accomplish.
- [Google's Shell Style Guide](https://google.github.io/styleguide/shell.xml) lists what Google's developers consider best practices for `bash` scripts.
- [Learning the Bash Shell](http://shop.oreilly.com/product/9780596009656.do) - It's hard to go wrong with an O'Reilly reference on anything, really.
- [Pure Bash Bible](https://github.com/dylanaraps/pure-bash-bible) - A collection of pure `bash` alternatives to external processes.
- [Safe Ways to do Things in Bash](https://github.com/anordal/shellharden/blob/master/how_to_do_things_safely_in_bash.md) - An excellent set of tips from the authors of [shellharden](https://github.com/anordal/shellharden).
- [shellcheck](https://github.com/koalaman/shellcheck) is a lint for `bash`. It'll help you find unused variables, deprecated syntax and other things that make your `bash` scripts less stable. You can install it with `apt-get`, `brew`, `cabal`, or `yum`.
- [shellharden](https://github.com/anordal/shellharden) - is a syntax highlighter and a tool to semi-automate the rewriting of scripts to ShellCheck conformance, mainly focused on quoting.
- [zshelldoc](https://github.com/zdharma/zshelldoc) - Documentation generator for Bash & ZSH, with call-trees, comment extraction, etc.

Finally, remember that `bash` is not `sh`. If you're writing a script in `bash`, and testing it with `bash`, don't put `#!/bin/sh` as the shebang. Firstly, because `bash` behaves differently when called as `sh`, and secondly, not all *NIX systems (and not even all linux distributions) use `bash` as their `/bin/sh` any more.

### Powershell

Often you'll find yourself in a Windows enviroment, like it or not. These resources might help you in those cases -

- [Best Practices and Style guide](https://github.com/PoshCode/PowerShellPracticeAndStyle)
- [Powershell Slack](http://poshcode.org) - Think of it as a virtual Powershell user's group.
- [PowerShell.org eBooks](https://leanpub.com/u/devopscollective/)
- [PS Cmdlets In Your Inbox](https://github.com/MaxAnderson95/Cmdlets_In_Your_Inbox) lets you schedule a task to get PowerShell Cmdlets via email daily or at the command line.

### Python

Python has much better support for string manipulation and system infrastructure than Bash. In addition, there is a rich library of modules supporting various tasks you can use in your scripts that are just a `pip3 install` away.

A couple of places to go into as training are:

#### Python Books

- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/), a free Book that helps you automate boring and repetitive tasks with Python.
- [Programming Python](http://shop.oreilly.com/product/9780596158118.do), a well-written O'Reilly book, short and concise.
- [Python 101 --- Introduction to Python](http://www.davekuhlman.org/python_101.html), a free book that introduces and explains many python concepts.
- [20 Python Libraries You Aren't Using (But Should)](http://www.oreilly.com/programming/free/20-python-libraries-you-arent-using-but-should.csp), a free Book by Caleb Hattingh published by O'Reilly (No real Email address needed.)

#### Tutorials @ Python

- [Google's Python Course](https://developers.google.com/edu/python/), an introduction to Python, assuming little programming experience.

#### Python & Sysadmin

- [The Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/scenarios/admin/), a neat place to see usage and examples of Python and not only for systems administration.
- [WSGI - Web Server Gateway Interface](http://uwsgi-docs.readthedocs.io/en/latest/WSGIquickstart.html), the Python implementation of web servers.

#### Python & Deployment Utils

- [WSGI + Flask tutorial](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
- [WSGI + Gunicorn tutorial](https://www.digitalocean.com/community/tutorials/how-to-deploy-python-wsgi-apps-using-gunicorn-http-server-behind-nginx)
- [WSGI + Pyramid tutorial](https://www.digitalocean.com/community/tutorials/how-to-deploy-pyramid-based-python-wsgi-web-applications)

### Ruby

Ruby also has a rich ecosystem of gems you can use in your programs, and like Python, much better string and data structure manipulation than Bash.

#### Ruby Books

If you're in a Ruby shop, you'll want these books:

- [Ruby Best Practices](http://shop.oreilly.com/product/9780596523015.do)
- [Ruby: Learn Ruby in 24 Hours or Less](https://smile.amazon.com/Ruby-Beginners-Learning-Programming-Course/dp/1533191611)
- [The Ruby Programming Language](http://shop.oreilly.com/product/9780596516178.do)

### Perl

Perl has a long history of being the system administrator's friend, bringing the best of `bash`, `sed` and `awk` together. It is also suitable for building tools for the system administrator to utilise in their work.

#### Perl Books

- [Programming Perl](http://shop.oreilly.com/product/9780596004927.do)
- [Learning Perl](http://shop.oreilly.com/product/9780596001322.do)
- [Perl Best Practices](http://shop.oreilly.com/product/9780596001735.do)

#### Toolchain

- [carton](https://metacpan.org/pod/Carton) - A dependency management tool.
- [cpanm](https://metacpan.org/pod/App::cpanminus) - An alternative and very friendly tool for installing modules from CPAN. This pairs well with perlbrew.
- [perlbrew](https://perlbrew.pl/) - A tool for managing one or more Perl installations, without needing to modify the system-level Perl.
- [pinto](https://metacpan.org/pod/Pinto) - A tool for managing a private CPAN repository.

#### Web

- [Mojolicious](https://metacpan.org/pod/Mojolicious) - A rich framework for doing all things web, from building web services and sites to building HTTP client applications.
- [Plack/PSGI](http://plackperl.org/) - The Perl implementation of WSGI, with many Plack servers available for use.

#### Modules

- [Task::Kensho](https://metacpan.org/pod/Task::Kensho) - A list of recommended modules for many purposes, including reading configuration files, connecting to databases, logging, sending email, web crawling and development, and handling XML.

#### Blog Posts

- [Perl on the Rise for Devops](https://scalability.org/2017/01/perl-on-the-rise-for-devops/)
- [A Perl Toolchain for Building Microservices at Scale](https://engineering.semantics3.com/a-perl-toolchain-for-building-micro-services-at-scale-8851626a4b1b)
- [Perl tricks for system administrators](https://opensource.com/life/16/7/perl-tricks-system-administrators)

## Tools

### Cloud

#### Multi-Platform

- [Terraform](https://www.terraform.io) is a tool that allows you to configure your infrastructure as code, just like Chef/Puppet/etc allow you to manage the configuration of individual machines as code, with all the benefits of being able to diff, code review, etc. Terraform works with (as of this edit) AWS, Google Cloud, Microsoft Azure, vSphere and many other systems.

#### AWS

- [AWSCli](https://github.com/aws/aws-cli) provides a unified command line interface to Amazon Web Services. Wean yourself off of the webui if you want to be truly productive.
- [og-aws](https://github.com/open-guides/og-aws) is an excellent resource to AWS written by and for engineers who use AWS extensively.
- [S3cmd](http://s3tools.org/s3cmd) is a free command line tool and client for uploading, retrieving and managing data in Amazon S3 and other cloud storage service providers that use the S3 protocol, such as Google Cloud Storage or DreamHost DreamObjects.

#### Azure

- [Az PowerShell Module](https://docs.microsoft.com/en-us/powershell/azure/new-azureps-module-az?view=azurermps-6.13.0) The cross-platform (i.e. PS Core) Azure PowerShell module. Replaces the `AzureRm` module and provides a migration path from it.
- [Azure CLI 2.0](https://github.com/Azure/azure-cli) new preview CLI interface for Azure (written in python).
- [Azure Code Samples](https://azure.microsoft.com/en-us/documentation/samples/) samples of code showing how to interact with Azure.
- [Azure Friday](https://azure.microsoft.com/en-us/documentation/videos/azure-friday/) "Just two engineers, a laptop and the cloud, solving problems".
- [Azure Quickstart Templates](https://github.com/Azure/azure-quickstart-templates) community contributed Azure Resource Manager templates for tons of things.
- [Azure Xplat CLI](https://github.com/Azure/azure-xplat-cli) cross platform CLI interface for Azure (written in nodejs).
- [Official Azure Documentation](https://azure.microsoft.com/en-us/documentation/) official documentation for all Azure services.

#### Google Cloud

- [Introduction](https://cloud.google.com/docs/overview/) official introduction and an overview.
- [GCP for AWS professionals](https://cloud.google.com/docs/compare/aws/) list equivalents for AWS products in GCP.
- [GCP for Azure professionals](https://cloud.google.com/docs/compare/azure/) list equivalents for Azure products in GCP.

#### OpenStack

- [Introduction](https://www.openstack.org/software/) The OpenStack project's official introductory overview.
- [Installing](https://www.openstack.org/software/project-navigator/deployment-tools) The list of tools you should consider if you want to install and operate OpenStack yourself.
- [Community](https://www.openstack.org/community/) Where to go and who to ask for help.
- [Planet OpenStack](http://planet.openstack.org) An aggregated feed from across the Internet of OpenStack-related content, including contributions from individuals.
- [Public Clouds](https://www.openstack.org/marketplace/public-clouds/) Similar to AWS, GCP or Azure, this is a list of providers who offer cloud services running on OpenStack.
- [SuperUser](https://superuser.openstack.org) SuperUser is an online 'publication' aggregating and editorialising content related to OpenStack and Open Infrastructure.
- [Stackalytics](https://www.stackalytics.com) Code contribution statistics to OpenStack and related projects.

### Configuration Management

Quite simply, if you aren't using configuration management, you're doing it wrong.

You don't want to manually configure any servers - no matter how hard you try, they won't end up truly identical and having meat typing in commands takes far too long per server, doesn't scale, and the manual labor will discourage you from standing up new VMs for testing.

Treating your configuration as something described in text files allows you to treat it like code. You can do pull-requests, get your changes reviewed by your team, view the differences between your configuration at different times, and almost most-importantly, find out who changed the configuration, when, and if they wrote good commit messages, why.

There are several good options:

- [Ansible](http://www.ansible.com/) is designed to be minimal in nature, consistent, secure, and highly reliable. Is owned & supported by Red Hat.
- [CFEngine](https://cfengine.com) has been in continuous development since 1993.  Unlike some of its peers on this list, it is written in C and is built with speed and scalability in mind.  It should be considered for very, very large systems and for very small (think embedded) systems.
- [Chef](http://www.opscode.com/chef/) is written in Ruby and Erlang and uses a Ruby DSL to describe system configuration.
- [Chocolatey](https://chocolatey.org/) a Windows software management tool.
- [Puppet](http://puppetlabs.com/) makes it easy to automate the provisioning, configuration and ongoing management of your machines and the software running on them. Make rapid, repeatable changes and automatically enforce the consistency of systems and devices – across physical and virtual machines, on premise or in the cloud.
- [Salt](http://www.saltstack.com/) orchestrates the build and ongoing management of your infrastructure.

### Docker

[Docker](https://www.docker.com/what-docker) is a tool for running and managing
containers. Containers are rapidly growing in popularity for local development (as an alternative to virtual machines), and can also run software in production with tools like [Kubernetes](https://kubernetes.io/) or [Amazon ECS](https://aws.amazon.com/ecs/).

#### Installing Docker

Follow the installation instructions for your preferred platform:

- [Docker CE for Mac](https://docs.docker.com/docker-for-mac/install/#download-docker-for-mac)
- [Docker CE for Linux](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/)
  - Linux usually requires a separate installation of [docker-compose](https://docs.docker.com/compose/install/)
- [Docker CE for Windows](https://docs.docker.com/docker-for-windows/install/)

#### Learning Docker

- [The Docker Book](https://www.dockerbook.com/) - An excellent resource for getting started with Docker. This book is quick & easy to read.

### Kubernetes

Kubernetes is a portable open-source container orchestration system used to automate deployment, scaling, and management of containerized applications.

#### Tutorials

There are many good tutorials at [kubernetes.io](https://kubernetes.io/docs/home/). I recommend you start with either the [minikube](https://minikube.sigs.k8s.io/docs/start/) walkthrough since it will get you a running test cluster quickly, or enable the kubernetes cluster option in [Docker Desktop](https://www.docker.com/products/docker-desktop).

If you want to understand everything that is involved in getting a Kubernetes cluster up and running, [Kubernetes the Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way) by Kelsey Hightower is hard to beat.

Ever wondered exactly what happens when you type something `kubectl run nginx --image=nginx --replicas=3` to make everything happen? [What happens when K8s...](https://github.com/jamiehannaford/what-happens-when-k8s/) is a guide that leads you through the full lifecycle of a request from the client to the kubelet, linking off to the source code where necessary to illustrate what's going on.

#### Utilities

- [krew](https://github.com/kubernetes-sigs/krew/) - Makes it easy to use [kubectl plugins](https://kubernetes.io/docs/tasks/extend-kubectl/kubectl-plugins/). `krew` helps you discover plugins, install and manage them on your machine. It is similar to tools like `apt`, `dnf` or `brew`. Today, over 70 `kubectl` plugins are available on `krew`.
- [kubectx](https://github.com/ahmetb/kubectx) - Provides the `kubectx` command, which makes it easy to switch between clusters specified in your `.kube/config`, and `kubens`, which helps you switch between Kubernetes namespaces smoothly.

### Monitoring

There are several good projects for monitoring.

- [Grafana](https://www.grafana.com) - Grafana allows you to query, visualize, alert on and understand your metrics no matter where they are stored. Create, explore, and share dashboards with your team and foster a data driven culture.
- [OSquery](https://osquery.readthedocs.io/en/stable/) for Windows, linux, OS X, and FreeBSD. Use SQL queries to look into items such as installed programs, running processes, and other events for inventory and monitoring.
- [Prometheus](https://www.prometheus.io/docs) - Prometheus is an open-source systems monitoring and alerting toolkit originally built at SoundCloud. Since its inception in 2012, many companies and organizations have adopted Prometheus, and the project has a very active developer and user community. It is now a standalone open source project and maintained independently of any company.

#### Articles/Tutorials

[Impactful Dashboards](https://jesswhite.co.uk/2018/04/09/impactfuldashboardspart1-post.html) - It's easy to make monitoring dashboards that are a jumble of poorly presented information, this article gives guidelines on making good dashboards.

### Regular Expressions

Inevitably you're going to find yourself in a situation where you have to look at logs to see what's going wrong with a service. When it's a multi-gigabyte logfile, that can be extremely painful.

Enter regexes and the `grep` family of tools.

When you have a multi-gigabyte logfile, it's a lot less painful to look at just the entries generated by the service that you got alerted about. Even better to only look at the error messages from the service, and something as basic as `grep -i yourservice < log | grep -i errorcode` can convert a potentially multi-hour ordeal into a quick minute or two task.

- [debuggex.com/](https://www.debuggex.com/) will visualize regular expressions graphically.
- [Introducing Regular Expressions](http://shop.oreilly.com/product/0636920012337.do)
- [Regex for Noobs](https://www.janmeppe.com/blog/regex-for-noobs/) - An illustrated guide to regex that aims to provide a gentle introduction for people who never have fiddled with regex, want to, but are kind of intimidated by the whole thing.
- [Regular Expressions Cookbook](http://shop.oreilly.com/product/0636920023630.do)

### Sed & Awk

- [sed and awk Pocket Reference](http://shop.oreilly.com/product/9780596003524.do) presents a concise summary of regular expressions and pattern matching, and summaries of sed and awk and how to use them to edit files and convert data from one format to another.

### Serverless

Serverless doesn't mean no sysadmins, even though there aren't instances to administer. We need to change common processes that we rely on to monitor and manage services that run on serverless platforms. There are not system level metrics to understand how our application is working.

Here are a few resources to help:

- [Building observability into a serverless application](https://vimeo.com/289905221) (Video) Yan Cui presents some guidelines to implementing observability into serverless on AWS. The patterns in this talk can be applied to other platforms as well.

### Source control

No matter what source control system you use (`git`, `hg`, `perforce`, whatever), you're going to have to write commit messages. Make them good. It may be obvious _today_ why you made the change, but in six months or a year you won't have that context.

Explain _why_ you made the change, not just _what_ you changed. And no, the diff is not an explanation. Always start your commit messages with a single line that explains what you were trying to do in general, then go into more detail in the body. Talk about what you intend the change to do and why more than how you did it. If there's an issue or ticket number, include that in your commit message too, it'll give more context to your coworkers (or you in a year).

Good commit messages help the rest of your team understand what you're trying to do and make it easier for them to find logic errors in your pull requests - the code may be technically correct, but if they understand what you're _trying_ to do, they can see when your code isn't actually doing what you say you want it to do, even when it is syntactically correct.

Here are a few articles that while focused on `git` apply to any source control system:

- [5 Useful Tips for a Better Commit Message](https://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message) is another good article on writing commit messages.
- [A Note About Git Commit Messages](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
- [Writing Good Commit Messages](http://chris.beams.io/posts/git-commit/) is a good article on writing coherent commit messages.

#### Git

Whether or not your shop uses `git` internally, you're going to end up needing to use it for the many useful things on GitHub and GitLab.

- [19 Git Tips for Everyday Use](http://www.alexkras.com/19-git-tips-for-everyday-use/) - a good set of starter tips for using git.
- [git-extra-commands](https://github.com/unixorn/git-extra-commands) - a collection of extra git helper scripts.
- [git-flight-rules](https://github.com/k88hudson/git-flight-rules) is Kate Hudson's guide to using `git` in specific situations.
- [git-tips/tips](https://github.com/git-tips/tips) is a collection of `git` tips
- [Pro Git](https://git-scm.com/book/en/v2) by Scott Chacon and Ben Straub is a great overall resource for `git`.
- [Why the Heck is Git so Hard? The Places Model](http://merrigrove.blogspot.com/2014/02/why-heck-is-git-so-hard-places-model-ok.html) - an article about moving from SVN/CVS to `git`.
- Ben Limmer's [Git Skills Talk](https://github.com/blimmer/1up-git-skills-talk) will help you understand using `git` (particularly with GitHub).

### SSH

- [awesome-ssh](https://github.com/moul/awesome-ssh) - A curated list of ssh apps, libraries and other resources.
- [SSH, The Secure Shell: The Definitive Guide, 2nd Edition](http://shop.oreilly.com/product/9780596008956.do)

### Testing

Testing is incredibly important and you should undertake this for your infrastructure as well as your applications.

#### Test Harnesses

- **Test Kitchen** [https://kitchen.ci](https://kitchen.ci) - Test your configuration management tooling. Was originally written to test chef cookbooks, but can be used for other configuration management systems as well.

### Text Editors

Don't get involved in the Editor Wars.  Just.  Don't.  Your choice of tool does not need defending.  Nor does anyone else's choice.

However, you should care about your tools.  You should be able to use them efficiently.

#### Vim

`vim` is a reality of life for SysAdmins.  It is the one editor you can be sure is installed in even the most minimal *NIX or linux install. You must be able to do at least basic edits with it.  You don't need to love it, but you _will_ have to use it.

- [Damian Conway, "More Instantly Better Vim" - OSCON 2013](https://www.youtube.com/watch?v=aHm36-na4-4)
- [vi and Vim Editors Pocket Reference, 2nd Edition](http://shop.oreilly.com/product/0636920010913.do)

#### Emacs

Emacs is an extremely extensible editor. In jest, it is frequently referred to as an operating system with a half-decent editor.

If you want to get a taste of what `emacs` can do, you can defer to Magnars and his excellent video tutorials/demos:

- [http://emacsrocks.com](http://emacsrocks.com/)

One of the biggest problems with `emacs` is that the defaults present a fairly different experience to what people are used to. Your first stop should be learning the basics using the built-in tutorial, followed by the mini-manual from tuhdo:

-Type `ctrl-h`, followed closely by `t` from within emacs to see the tutorial [http://tuhdo.github.io/index.html](http://tuhdo.github.io/index.html)

Emacs can be can be made to look and act relatively modern if that's your desire:

- [http://emacs.sexy/](http://emacs.sexy/)

If you're looking for `emacs` packages, the following online package index is the most popular, and tracks many:

- [http://melpa.org/](http://melpa.org/)

There are several excellent starter kits out there, with varying delineations of wizz-bang. Roughly sorted by wizz-bang, here are the starter kits that exist, with spacemacs being the most popular:

- [https://github.com/technomancy/better-defaults](https://github.com/technomancy/better-defaults)
- [https://github.com/hlissner/doom-emacs](https://github.com/hlissner/doom-emacs)
- [https://github.com/bbatsov/prelude](https://github.com/bbatsov/prelude)
- [https://github.com/syl20bnr/spacemacs](https://github.com/syl20bnr/spacemacs)

Here are some `emacs` configurations for inspiration:

- Magnar Sveen's very interesting and original `emacs` config! [https://github.com/magnars/.emacs.d](https://github.com/magnars/.emacs.d)
- Phil Hagelberg's config: [https://git.sr.ht/~technomancy/dotfiles/tree/master/.emacs.d](https://git.sr.ht/~technomancy/dotfiles/tree/master/.emacs.d)
- Steve Purcell's excellent config: [https://github.com/purcell/emacs.d](https://github.com/purcell/emacs.d)

#### Visual Editors and IDEs

Use tools with which you are productive.  If you want to use a GUI Text Editor or IDE, don't let anyone give you a hard time about that.

There are GUI versions of `vim` and `emacs` that have ardent followers.

- [Atom](https://atom.io/) is a fairly new editor with significant traction and plugin ecosystem.
- [Sublime Text](http://sublimetext.com) is another editor with an extensive plugin ecosystem and arguably one of the inspirations for Atom.
- [Visual Studio Code](https://code.visualstudio.com) is a cross platform editor that is gaining traction in the marketplace.

## Blogs and Podcasts

- [Arrested Devops](https://www.arresteddevops.com/) is hosted by Matt Stratton, Trevor Hess, and Bridget Kromhout. ADO is the podcast that helps you achieve understanding, develop good practices, and operate your team and organization for maximum DevOps awesomeness.
- [Code as Craft](http://codeascraft.com/) is Etsy's ops blog and is full of well written examples of dealing with real-world problems at scale.
- [Hey, Scripting Guy! Blog](https://blogs.technet.microsoft.com/heyscriptingguy/) is a blog that answers common (and some uncommon) PowerShell queries.
- [Julia Evans' Blog](http://jvns.ca/) - Julia writes a great blog where she dives into interesting ops topics and explains them clearly.
- [Kitchen Soap](http://www.kitchensoap.com/) - John Alspaw is the CTO at Etsy and writes a great blog about web operations and operating at scale and other things that are interesting to ops types.
- [PowerScripting Podcast](https://powershell.org/podcast/) is hosted by Jon Walz and Hal Rottenberg.

## Online Communities

- [DevOpsChat Slack](https://devopschat.co/) is another community of DevOps minded folk with a diverse set of topic specific chat rooms. Home to Arrested DevOps.
- [Hangops Slack](https://signup.hangops.com/) is a community of DevOps minded folk with many subject focused chat rooms.
- [PowerShell Slack](http://poshcode.org/) is a community of PowerShell enthusiasts and Windows centric DevOps topics.

## Windows Administration

Help wanted here.

## Other Resources

Packetlife has some great cheat sheets and posters [here](https://packetlife.net/library/cheat-sheets/) for a lot of applications (wireshark and tcpdump for example) and networking principles. Well worth a look, even if you think you know the apps in question.

### Free Services

- A [list](https://github.com/ripienaar/free-for-dev) of SaaS, PaaS and IaaS offerings that have free tiers of interest to devops and infradev.

### Miscellanea

- [awesome-scalability](https://github.com/binhnguyennus/awesome-scalability/) - An organized reading list for illustrating the patterns behind scalable, reliable, and performant large-scale systems.
- [awesome-sre](https://github.com/dastergon/awesome-sre) - A curated list of awesome [Site Reliability](https://www.usenix.org/conference/srecon14/technical-sessions/presentation/keys-sre) and [Production](https://www.usenix.org/conference/srecon15/program/presentation/canahuati) Engineering resources.
- [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open-source sysadmin resources.
- [devops-exercises](https://github.com/bregman-arie/devops-exercises) - Questions and exercises on various technical topics, sometimes related to DevOps and SRE.
- [devops-resources](https://github.com/bregman-arie/devops-resources) - Another repository of useful resources and information about DevOps.
- [nohello](https://www.nohello.com/) - Why you shouldn't just say 'Hello' when you chat with someone. Make it easier for them to help you.
- [oncall-handbook](https://github.com/alicegoldfuss/oncall-handbook) - Alice Goldfuss' excellent oncall handbook, read this before your first oncall shift.
- [sre-interview](https://github.com/michael-kehoe/sre-interview) - A collection of questions to practice for interviews.
- [stack-on-a-budget](https://github.com/255kb/stack-on-a-budget) - A list of free/cheap tiers of services that you can use to learn the various cloud-based systems.
- [sysadvent](https://sysadvent.blogspot.com/) - Every year the sysadvent team publishes 24 good articles for sysadmins and SREs.
- [tools.tldr.run](https://tools.tldr.run/) - A curated list of security tools for Hackers and Builders.
- Etsy's [Debriefing Facilitation Guide](https://extfiles.etsy.com/DebriefingFacilitationGuide.pdf) is a great guide to conducting a blame-free debrief after an outage.
- Pēteris Ņikiforovs has a good blog post explaining what everything you see in top/htop output [here](https://peteris.rocks/blog/htop/).
- Dan Luu wrote an excellent article about the [Normalization of Deviance](https://danluu.com/wat/) that is good food for thought about engineering practices.
- Donne Martin maintains a great [System Design Primer](https://github.com/donnemartin/system-design-primer).

### Career

-Alice Goldfuss wrote an excellent article, [How to Get Into SRE](https://blog.alicegoldfuss.com/how-to-get-into-sre/), about her path to becoming an SRE.
-Alice also gave a great presentation - [Passing the Console: Fostering the Next Generation of Ops Professionals](https://www.usenix.org/conference/lisa16/conference-program/presentation/goldfuss) at LISA16.
-Julia Evans has a couple of great resources on making your 1-on-1's with your manager more effective. 1-on-1s should _not_ just be a status report on what you're working on - you should be using them to focus on more big picture goals (both yours and the organizations) and your career. Read her article on [1-on-1 ideas](https://jvns.ca/blog/2015/03/06/1-1-topic-ideas/), and I recommend buying her [Help, I have a Manager!](https://wizardzines.com/zines/manager/) zine.

### Communication

Writing good documentation and design docs is as important as writing code. The more senior you are, the more writing you're going to have to do - communication skills are a must.

- Email - Like it or not, you're going to write a _lot_ of email in the course of you work. Lazarus Lazaridis wrote a good article on [Composing Better Emails](https://iridakos.com/how-to/2019/06/26/composing-better-emails.html)
- Gergely Orosz wrote an excellent blog post about [Undervalued Software Engineering Skills: Writing Well](https://blog.pragmaticengineer.com/on-writing-well/).

### Finance/Salary

- Patrick McKenzie wrote a great blog post on [salary negotiation](https://www.kalzumeus.com/2012/01/23/salary-negotiation/). Salary negotiation is one of the few times in your life where a five minute conversation can earn you (or _cost_ you!) thousands of dollars - be prepared.
- Patrick also has a good podcast episode on salary negotiation - [Kalzumeus Podcast Episode 12: Salary Negotiation with Josh Doody](https://www.kalzumeus.com/2016/06/03/kalzumeus-podcast-episode-12-salary-negotiation-with-josh-doody/)  (there's a transcript too). You have to do it, it affects your life, you should do it well.
- [The Holloway Guide to Equity Compensation](https://www.holloway.com/g/equity-compensation) - Stock options, RSUs, job offers, and taxes — a detailed reference, including hundreds of resources, explained from the ground up.
- [What I Wish I'd Known About Equity Before Joining A Unicorn](https://gist.github.com/yossorion/4965df74fd6da6cdc280ec57e83a202d) - This is an excellent (though USA-centric) summary of how to value stock options and what the tax implications are and how to minimize potential tax. I heartily recommend reading it before you accept any offers involving stock or stock options as part of your compensation.

## License

This repository is copyright 2017-2020 Joseph Block under a [Attribution-NonCommercial-ShareAlike 4.0 International](#attribution-noncommercial-sharealike-40-international) license.
