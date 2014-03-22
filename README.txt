Zvan
Zvan Admin Panel Front-End.

Table of contents
Quick start
Bugs and feature requests
Documentation
Bootstrap community
Branches
Versioning
Author
Copyright and license
Quick start
Quick start options are available:

Download the latest release.
Clone the repo: git clone https://github.com/adalbertovargas/zvan.git.

*IMPORTANT:*A Web server (like XAMPP or any other) is required to run because of Jquery httprequest is bloqued while in local mode.
Read the Getting started page for information on the Bootstrap framework contents, templates and examples, and more.

What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

``` assets/ ├── css/ │ └── styles.min.css ├── demo/ │ ├── avatar │ ├── images │ └── variations ├── fonts/ │ ├── font-awesome │ └── glyphicons ├── img/ │ ├── logo.png │ └── logo-big.png ├── js/ │ └── images └── plugins/ ├── bootbox ├── bootstro.js ├── charts-chartjs ├── charts-flot └── .....

```

We provide compiled CSS and JS (file.*), as well as compiled and minified CSS and JS (file.min.*). Fonts from Glyphicons are included, as is the optional Bootstrap theme.

Bugs and feature requests
Have a bug or a feature request? please open a new issue.

Documentation
Bootstrap's documentation, included in this repo in the root directory, is built with Jekyll and publicly hosted on GitHub Pages at http://getbootstrap.com. The docs may also be run locally.

Running documentation locally

If necessary, install Jekyll (requires v1.x).
Windows users: Read this unofficial guide to get Jekyll up and running without problems. We use Pygments for syntax highlighting, so make sure to read the sections on installing Python and Pygments.
From the root /bootstrap directory, run jekyll serve in the command line.
Windows users: While we use Jekyll's encoding setting, you might still need to change the command prompt's character encoding (code page) to UTF-8 so Jekyll runs without errors. For Ruby 2.0.0, run chcp 65001 first. For Ruby 1.9.3, you can alternatively do SET LANG=en_EN.UTF-8.
Open http://localhost:9001 in your browser, and voil� .
Learn more about using Jekyll by reading its documentation.

Documentation for previous releases

Documentation for v2.3.2 has been made available for the time being at http://getbootstrap.com/2.3.2/ while folks transition to Bootstrap 3.

Previous releases and their documentation are also available for download.

Bootstrap Community
Keep track of development and community news.

Follow @twbootstrap on Twitter.
Read and subscribe to The Official Bootstrap Blog.
Chat with fellow Bootstrappers in IRC. On the irc.freenode.net server, in the ##twitter-bootstrap channel.
Implementation help may be found at Stack Overflow (tagged twitter-bootstrap-3).
Branches
Master: Website on *production
Beta: Beta release
Dev: Develop Current working.
Versioning
For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under the Semantic Versioning guidelines. Sometimes we screw up, but we'll adhere to these rules whenever possible.

Releases will be numbered with the following format:

<major>.<minor>.<patch>

And constructed with the following guidelines:

Breaking backward compatibility bumps the major while resetting minor and patch
New additions without breaking backward compatibility bumps the minor while resetting the patch
Bug fixes and misc changes bumps only the patch
For more information on SemVer, please visit http://semver.org/.

Author
Adalberto Vargas (ADL, ADLBEAT, ADALBERTOV)

http://www.adalbertovargas.com/
Copyright and license
Code and documentation copyright 2014 ADL NETWORKS, S.A. Code released under the MIT license. Docs released under Creative Commons.