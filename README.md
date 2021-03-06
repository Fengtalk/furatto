# [Furatto v1.0.1](https://github.com/IcaliaLabs/furatto)

Furatto is a flat, fast and powerful front-end framework for 
rapid web development, created and maintained by [Abraham Kuri](https://twitter.com/kurenn) from [Icalia Labs](http://twitter.com/icalialabs). It is based on other frameworks as a start point, such as [Twitter Bootstrap](http://twitter.github.io/bootstrap/), [Foundation](http://foundation.zurb.com/).


To get started, checkout:

### [http://icalialabs.github.io/furatto/](http://icalialabs.github.io/furatto/) !


## Quick start

Three quick start options are available:

* [Download the latest release](http://icalialabs.github.io/furatto/).
* Clone the repo: `git clone git@github.com:IcaliaLabs/furatto.git`.


## Bug tracker

Have a bug or a feature request? [Please open a new issue](https://github.com/IcaliaLabs/furatto/issues). Before opening any issue, please search for existing issues and read the [Issue Guidelines].

##Community

Keep track of new feautres, development issues and community news.

* Follow [@ifuratto](https://twitter.com/ifuratto)
* Have a question about anything, email us at weare@icalialabs.com


## Compiling CSS and JavaScript

Furatto includes a makefile to compile all the Sass code and start working with the framework. Before getting started you need to add the necessary dependencies:

```console
	$ gem install compass
```

More information about [Compass](http://compass-style.org/install/)

As furatto uses node.js to compile the assets, you need to add the locally:

```console
	$ npm install
```

When you are done, you should be able to run the makefile provided:

####build - `make`

We decided to switch from [CodeKit](http://incident57.com/codekit/) as some people would not want to pay for it, and just use open source.

## Using Rails?

Thanks to [@kurenn](https://twitter.com/kurenn) the [furatto-rails](https://github.com/IcaliaLabs/furatto-rails) gem makes it easy to integrate Furatto with a Rails app.

## Contributing

Please submit all pull requests against a separate branch. Please follow the standard for naming the variables, mixins, etc.

Thanks!


## Authors

**Abraham Kuri**

+ [http://twitter.com/kurenn](http://twitter.com/kurenn)
+ [http://github.com/kurenn](http://github.com/kurenn)


## Copyright and license

Copyright 2012 Icalia Labs, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

  [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
