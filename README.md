# backstopjs-example
**Example BackstopJS test with a included Vagrantfile.**

[![Build Status](https://travis-ci.org/vergissberlin/backstop-example.svg?branch=master)](https://travis-ci.org/vergissberlin/backstop-example)

BackstopJS automates visual regression testing of your responsive web UI by comparing DOM screenshots over time.

**Features:**

- Preconfigured test environment to play araound with BackstopJS
- Example tests an references.
- Detailed in-browser reports.
- CI Integration with JUnit reports.

## Installation with Vagrant
I recommend this way, cause if you don't like it, you didn't mess up your system.

```sh
$ vagrant up
```

## Installation without Vagrant
If you don't wanna use Vagrant, you have to install the dependencies on your own. Please install _phantomjs_ and the node packages like that:

```sh
sudo npm i backstopjs phantomjs slimerjs -g
cd backstop-example && npm i
```


----


## Let's get testing
```sh
$ npm test
$ npm refenrences
```
 For furhter informations, take a look on the [BackstopJS GitHub page](https://github.com/garris/BackstopJS).
