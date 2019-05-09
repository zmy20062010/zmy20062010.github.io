# <center> Welcome to the Personal Page of Maoying Zhou </center>

---

## Overview

Maoying Zhou is now assistant professor in the Department of Mechanical
Engineering at Hangzhou Dianzi University. With an education background
in Mechanical Engineering (Bachelor's Degree in Mechanical Engineering
from Huazhong University of Science and Technology in 2010; PhD's Degree
in Mechanical Engineering from Zhejiang University in 2015; Start as
assistant professor in Hangzhou Dianzi University.), his research interest
focuses on the application of mathematics and physics into engineering 
practice, including the explanation of daily phenomena, the modeling of 
interesting behaviors, and the analysis of physical indications.

### Host anywhere

MkDocs builds completely static HTML sites that you can host on GitHub pages,
Amazon S3, or [anywhere][deploy] else you choose.

### Great themes available

There's a stack of good looking themes available for MkDocs. Choose between
the built in themes: [mkdocs] and [readthedocs], select one of the 3rd
party themes in the [MkDocs wiki], or [build your own].

### Preview your site as you work

The built-in dev-server allows you to preview your documentation as you're
writing it. It will even auto-reload and refresh your browser whenever you save
your changes.

### Easy to customize

Get your project documentation looking just the way you want it by customizing
the theme.

---

## Installation

### Install with a Package Manager

If you have and use a package manager (such as [apt-get], [dnf], [homebrew],
[yum], [chocolatey], etc.) to install packages on your system, then you may
want to search for a "MkDocs" package and, if a recent version is available,
install it with your package manager (check your system's documentation for
details). That's it, you're done! Skip down to [Getting Started](#getting-started).

### Manual Installation

In order to manually install MkDocs you'll need [Python] installed on your
system, as well as the Python package manager, [pip]. You can check if you have
these already installed from the command line:

```bash
$ python --version
Python 2.7.14
$ pip --version
pip 18.1 from /usr/local/lib/python2.7/site-packages/pip (python 2.7)
```

MkDocs supports Python versions 2.7.9+, 3.4, 3.5, 3.6, 3.7, and pypy.

---

## Getting Started

## Adding pages

Now add a second page to your documentation:


## Changing the Favicon Icon


## Building the site

That's looking good. You're ready to deploy the first pass of your `MkLorum`
documentation. First build the documentation:


This will create a new directory, named `site`. Take a look inside the
directory:



If you're using another source code control tool you'll want to check its
documentation on how to ignore specific directories.

After some time, files may be removed from the documentation but they will still
reside in the `site` directory. To remove those stale files, just run `mkdocs`
with the `--clean` switch.

```bash
mkdocs build --clean
```

## Other Commands and Options

There are various other commands and options available. For a complete list of
commands, use the `--help` flag:

```bash
mkdocs --help
```

To view a list of options available on a given command, use the `--help` flag
with that command. For example, to get a list of all options available for the
`build` command run the following:

```bash
mkdocs build --help
```

## Deploying

The documentation site that you just built only uses static files so you'll be
able to host it from pretty much anywhere. 

## Getting help

To get help with MkDocs, please use the [discussion group], [GitHub issues] or
the MkDocs IRC channel `#mkdocs` on freenode.



[deploy]: user-guide/deploying-your-docs/
[mkdocs]: user-guide/styling-your-docs/#mkdocs
[readthedocs]: user-guide/styling-your-docs/#readthedocs
[MkDocs wiki]: https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes
[build your own]: user-guide/custom-themes/
[Amazon S3]: https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html
[get-pip.py]: https://bootstrap.pypa.io/get-pip.py
[nav]: user-guide/configuration/#nav
[discussion group]: https://groups.google.com/forum/#!forum/mkdocs
[GitHub issues]: https://github.com/mkdocs/mkdocs/issues
[GitHub project pages]: https://help.github.com/articles/creating-project-pages-manually/
[pip]: https://pip.readthedocs.io/en/stable/installing/
[Python]: https://www.python.org/
[site_name]: user-guide/configuration/#site_name
[theme]: user-guide/configuration/#theme
