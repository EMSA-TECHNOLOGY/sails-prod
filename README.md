<h1>
<a href="https://github.com/EMSA-TECHNOLOGY/sails-prod">sails-prod.js</a>
(This framework is in working progress....)
</h1>

### [Website](https://github.com/EMSA-TECHNOLOGY/sails-prod)  &nbsp; [Getting Started](http://sailsjs.org/get-started) &nbsp;  [Docs](http://sailsjs.org/documentation)  &nbsp; [Blog](http://blog.sailsjs.org/) &nbsp; [Submit Issue](https://github.com/EMSA-TECHNOLOGY/sails-prod/issues)

[![NPM version](https://badge.fury.io/js/sails-prod.svg)](http://badge.fury.io/js/sails-prod) &nbsp; [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/emsa-technology/sails-prod)  &nbsp; [![Twitter Follow](https://img.shields.io/twitter/follow/sails-prod.svg?style=social&maxAge=3600)](https://twitter.com/sails-prod)


sails-prod (Ported from Sails.js 0.12.3) is a web framework that makes it easy to build custom, enterprise-grade Node.js apps. It is designed to resemble the MVC architecture from frameworks like Ruby on Rails, but with support for the more modern, data-oriented style of web app development. It's especially good for building realtime features like chat.

WHY WE DO THIS WHILE SAILS IS STILL THERE?

* Sails 1.x is a big breaking change and we have no time to migrate & Sails 0.12.x is no more continued/maintained.
* Our final purpose is to continue to develop/maintain this version for production based.
* All libraries shall be verified/re-selected to be conformed with real production.
* More tests shall be added.

## Installation &nbsp;
**With [node](http://nodejs.org) [installed](http://sailsjs.org/#!documentation/new-to-nodejs):**
```sh
# Get the latest stable release of Sails
$ npm install sails-prod -g
```

## Your First sails-prod Project

**Create a new app:**
```sh
# Create the app
$ sails-prod new testProject
```

**Start your app:**
```sh
# cd into the new folder
$ cd testProject

# fire up the server
$ sails-prod lift
```

**Generate a REST API:**

[![ScreenShot](http://i.imgur.com/Ii88jlhl.png)](https://www.youtube.com/watch?v=GK-tFvpIR7c)


## Compatibility

sails-prod is built on [Node.js](http://nodejs.org/), [Express](http://expressjs.com/), and [Socket.io](http://socket.io/).

sails-prod [controllers](http://sailsjs.org/documentation/concepts/controllers) are compatible with Connect middleware, so in most cases, you can paste code into Sails from an existing Express project and everything will work-- plus you'll be able to use WebSockets to talk to your API, and vice versa.

NO ORM i.e. [Waterline](https://github.com/balderdashy/waterline), --> we will remove completely this layer since we are not confident into this ORM layer, in stead of that we will create a db lib to allow to load your model and actual implementation for each database i.e. User.create -> then we will allow you to bind your create method with mongodb, mysql,...

<!-- Core adapter logos -->
<a target="_blank" href="http://www.mysql.com">
  <img width="75" src="http://www.mysql.com/common/logos/powered-by-mysql-125x64.png" alt="Powered by MySQL" title="sails-mysql: MySQL adapter for Sails"/>
</a>&nbsp; &nbsp; &nbsp; &nbsp;
<a target="_blank" href="http://www.postgresql.org/"><img width="50" title="PostgreSQL" src="http://i.imgur.com/OSlDDKv.png"/></a>&nbsp; &nbsp; &nbsp; &nbsp;
<a target="_blank" href="http://www.mongodb.org/"><img width="100" title="MongoDB" src="http://i.imgur.com/bC2j13z.png"/></a>&nbsp; &nbsp; &nbsp; &nbsp;
<a target="_blank" href="http://redis.io/"><img width="75" title="Redis" src="http://i.imgur.com/dozv0ub.jpg"/></a>&nbsp; &nbsp; &nbsp; &nbsp;
<!-- /core adapter logos -->

## Books
- [Sails.js in Action](https://www.manning.com/books/sails-js-in-action) by Mike McNeil and Irl Nathan (Manning Publications).  Available October 2016 _([estimated](https://www.manning.com/meap-program#section-faq-10))_.
- [Pro Express.js: Part 3](http://link.springer.com/chapter/10.1007%2F978-1-4842-0037-7_18) by Azat Mardan (Apress).
- [Sails.js Essentials](https://www.packtpub.com/web-development/sailsjs-essentials) by Shaikh Shahid (Packt)

## Support
Need help or have a question?
- [StackOverflow](http://stackoverflow.com/questions/tagged/sails-prod)
- [Professional/Enterprise Support](https://emsa-technology.com/contact-us/)


## Issue Submission
sails-prod is composed of a [number of different sub-projects](https://github.com/EMSA-TECHNOLOGY), many of which have their own dedicated repository. If you suspect an issue in one of these sub-modules, you can find its repo on the [organization](https://github.com/EMSA-TECHNOLOGY) page, or in [MODULES.md](https://github.com/EMSA-TECHNOLOGY).

## Feature Requests
If you have an idea for a new feature, please feel free to submit it as a pull request to the backlog section of the [ROADMAP.md](https://github.com/EMSA-TECHNOLOGY/sails-prod/blob/master/ROADMAP.md#feature-requests) file in this repository.

## Contribute
There are many different ways you can contribute to sails-prod:
- answering questions on [StackOverflow](http://stackoverflow.com/questions/tagged/sails-prod), [Gitter](https://github.com/EMSA-TECHNOLOGY), [Facebook](https://www.facebook.com/sails-prod), or [Twitter](https://twitter.com/search?f=tweets&vertical=default&q=%40sails-prod%20OR%20%23sails-prod%20OR%20sails-prod.js%20OR%20sails-prod&src=typd)
- improving the [documentation](https://github.com/EMSA-TECHNOLOGY/sails-prod/sails-prod-docs#contributing-to-the-docs) or [website](https://github.com/EMSA-TECHNOLOGY/www.sails-prod.org/issues)
- translating the [documentation](https://github.com/EMSA-TECHNOLOGY/sails-prod/sails-prod-docs/issues/580) to your native language
- writing [tests](https://github.com/EMSA-TECHNOLOGY/sails-prod/blob/master/test/README.md)
- writing a [tutorial](https://github.com/sails101/contribute-to-sails101), giving a [talk](http://lanyrd.com/search/?q=sails-prod), or supporting [your local sails-prod meetup](http://www.meetup.com/find/?allMeetups=false&keywords=sails-prod.js&radius=Infinity&sort=default)
- troubleshooting [reported issues](https://github.com/EMSA-TECHNOLOGY/sails-prod/search?q=&type=Issues)
- and [submitting patches](https://github.com/EMSA-TECHNOLOGY/sails-prod/blob/master/CONTRIBUTING.md).

Please carefully read our [contribution guide](https://github.com/EMSA-TECHNOLOGY/sails-prod/blob/master/CONTRIBUTING.md) and check the [master branch build status](https://github.com/EMSA-TECHNOLOGY/sails-prod/blob/master/MODULES.md) before submitting a pull request with code changes.


## Links
- [Website](https://emsa-technology.com/)
- [Official Documentation (ToBeUpdated)](http://sails-prod.org/documentation)
- [Twitter](https://twitter.com/emsatechnology)
- [Roadmap](https://github.com/EMSA-TECHNOLOGY/sails-prod/blob/master/ROADMAP.md)
- [Google Group](https://groups.google.com/forum/#!forum/sails-prod)
- [Facebook](https://www.facebook.com/emsatechnology)

## Team
sails-prod.js was continued and is actively maintained by [EMSA TECHNOLOGY LTD](https://emsa-technology.com) ([@emsatechnology](http://twitter.com/emsatechnology)).  Our core team consists of:

[![Thanh LE](https://gravatar.com/avatar/a40b5213d82bd6ba75047f5d5f30b7cc?s=200)](http://twitter.com/thanhlq214) |  [![Vu DO](https://gravatar.com/avatar/2612fc32e12b23c9922594b67baa7d3b?s=200)](https://twitter.com/emsatechnology) | [![Vinh PHAM](https://gravatar.com/avatar/908d2811073a5e1e3705a3f28c5c87da?s=200)](https://twitter.com/emsatechnology) | [![Bao NGUYEN](http://gravatar.com/avatar/3699fbf58b76122597e3c387013b3f45?s=200)](https://twitter.com/emsatechnology) | [![Khanh NGUYEN](https://gravatar.com/avatar/b57b887dfb474604e5da781726982fc0?s=200)](https://twitter.com/emsatechnology)
:---:|:---:|:---:|:---:|:---:
[Thanh LE](http://github.com/thanhlq) | [Vu DO](https://github.com/particlebananahttps://github.com/EMSA-TECHNOLOGY/sails-prod) | [Vinh PHAM](https://github.com/EMSA-TECHNOLOGY/sails-prod) | [Bao NGUYEN](https://github.com/irlnathanhttps://github.com/EMSA-TECHNOLOGY/sails-prod) | [Khanh NGUYEN](https://github.com/EMSA-TECHNOLOGY/sails-prod)


## License

[MIT License](http://sails-prod.mit-license.org/)  Copyright © 2019 EMSA TECHNOLOGY LTD.
