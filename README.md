
# [MobilityBee base API documentation](http://api.mobilitybee.com)

MobilityBee base API [documentation](http://api.mobilitybee.com) is an e-commerce API documentation (writen in [RAML](http://raml.org)) solving most common e-commerce problems.

## Table of contents
- [Quick start](#quick-start)
- [Building](#building)
- [Copyright and license](#copyright-and-license)

## Quick start

You can work with documentation using:

- [Online Plaftorm for APIs](https://anypoint.mulesoft.com/apiplatform), simplest way to edit and see output.
- [Sublime editor](http://www.sublimetext.com/) with [plugin](https://github.com/mulesoft/raml-sublime-plugin) for syntax highlight or any other editor you like.
- Or any other tool listed in [RAML site](http://raml.org/projects.html).

See compiled html [documentation](http://api.mobilitybee.com).

## Building

Dependencies:

- [raml2html](https://www.npmjs.com/package/raml2html)

Build:

	raml2html -i src/index.raml -o build/index.html

## Copyright and license

Code and documentation copyright 2015 MobilityBee and released under
[the MIT license](https://github.com/MobilityBee/API/blob/master/LICENSE).