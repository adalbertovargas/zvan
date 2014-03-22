# Zvan
[![Selenium Test Status](https://bootstrap.com/adalbertovargas/zvan/meta-src/status-bootstrap.svg)](https://saucelabs.com/u/bootstrap)


Zvan Admin Panel Front-End.

## Table of contents

 - [Quick start](#quick-start)
 - [Bugs and feature requests](#bugs-and-feature-requests)
 - [Documentation](#documentation)
 - [Bootstrap community](#bootstrap-community)
 - [Branches](#branches)
 - [Versioning](#versioning)
 - [Author](#author)
 - [Copyright and license](#copyright-and-license)

## Quick start

Quick start options are available:

- [Download the latest release](https://github.com/adalbertovargas/zvan/archive/v1.2.2.zip).
- Clone the repo: `git clone https://github.com/adalbertovargas/zvan.git`.

 **IMPORTANT:**A Web server (like XAMPP or any other) is required to run because of Jquery httprequest is bloqued while in local mode. 


Read the [Getting started page](http://getbootstrap.com/getting-started/) for information on the Bootstrap framework contents, templates and examples, and more.

### What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```
bootstrap/
├── css/
│   ├── styles.min.css
│   ├── bootstrap.min.css
│   ├── bootstrap-theme.css
│   └── bootstrap-theme.min.css
├── demo/
│   ├── bootstrap.js
│   └── bootstrap.min.js
├── fonts/
│   ├── bootstrap.js
│   └── bootstrap.min.js
├── img/
│   ├── bootstrap.js
│   └── bootstrap.min.js
├── js/
│   ├── bootstrap.js
│   └── bootstrap.min.js
└── plugins/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    └── glyphicons-halflings-regular.woff
```

We provide compiled CSS and JS (`file.*`), as well as compiled and minified CSS and JS (`file.min.*`). Fonts from Glyphicons are included, as is the optional Bootstrap theme.



## Bugs and feature requests

Have a bug or a feature request? 
[please open a new issue](https://github.com/adalbertovargas/zvan/issues/new).


## Documentation

Bootstrap's documentation, included in this repo in the root directory, is built with [Jekyll](http://jekyllrb.com) and publicly hosted on GitHub Pages at <http://getbootstrap.com>. The docs may also be run locally.

### Running documentation locally

1. If necessary, [install Jekyll](http://jekyllrb.com/docs/installation) (requires v1.x).
  - **Windows users:** Read [this unofficial guide](https://github.com/juthilo/run-jekyll-on-windows/) to get Jekyll up and running without problems. We use Pygments for syntax highlighting, so make sure to read the sections on installing Python and Pygments.
2. From the root `/bootstrap` directory, run `jekyll serve` in the command line.
  - **Windows users:** While we use Jekyll's `encoding` setting, you might still need to change the command prompt's character encoding ([code page](http://en.wikipedia.org/wiki/Windows_code_page)) to UTF-8 so Jekyll runs without errors. For Ruby 2.0.0, run `chcp 65001` first. For Ruby 1.9.3, you can alternatively do `SET LANG=en_EN.UTF-8`.
3. Open <http://localhost:9001> in your browser, and voilà.

Learn more about using Jekyll by reading its [documentation](http://jekyllrb.com/docs/home/).

### Documentation for previous releases

Documentation for v2.3.2 has been made available for the time being at <http://getbootstrap.com/2.3.2/> while folks transition to Bootstrap 3.

[Previous releases](https://github.com/twbs/bootstrap/releases) and their documentation are also available for download.


## Bootstrap Community

Keep track of development and community news.

- Follow [@twbootstrap on Twitter](http://twitter.com/twbootstrap).
- Read and subscribe to [The Official Bootstrap Blog](http://blog.getbootstrap.com).
- Chat with fellow Bootstrappers in IRC. On the `irc.freenode.net` server, in the `##twitter-bootstrap` channel.
- Implementation help may be found at Stack Overflow (tagged [`twitter-bootstrap-3`](http://stackoverflow.com/questions/tagged/twitter-bootstrap-3)).

## Branches


  * **Master:** Website on *production
  * **Beta:** *Beta* release 
  * **Dev:** *Develop* Current working.


## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under the Semantic Versioning guidelines. Sometimes we screw up, but we'll adhere to these rules whenever possible.

Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

- Breaking backward compatibility **bumps the major** while resetting minor and patch
- New additions without breaking backward compatibility **bumps the minor** while resetting the patch
- Bug fixes and misc changes **bumps only the patch**

For more information on SemVer, please visit <http://semver.org/>.


## Author

**Adalberto Vargas** (*ADL*, *ADLBEAT*,  *ADALBERTOV*)

- <http://www.adalbertovargas.com/>


## Copyright and license

Code and documentation copyright 2014 [ADL NETWORKS](https://www.adlnetworks.com), S.A. Code released under [the MIT license](LICENSE). Docs released under [Creative Commons](docs/LICENSE).
