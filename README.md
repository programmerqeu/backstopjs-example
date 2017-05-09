# backstopjs-example
**Example BackstopJS test environment with a included Vagrantfile and Dockerfile for testing purpose.**

[![Build Status](https://travis-ci.org/vergissberlin/backstopjs-example.svg?branch=master)](https://travis-ci.org/vergissberlin/backstopjs-example)

_Say what?_ BackstopJS automates visual regression testing of your responsive web UI by comparing DOM screenshots over time.

**Features:**

- Preconfigured test environment to play araound with BackstopJS
- Example tests an references.
- Detailed in-browser reports.
- CI Integration with JUnit reports.

## Run with Vagrant
I recommend this way, cause if you don't like it, you didn't mess up your system.

```sh
vagrant up
```

## Run with Docker
May you prefer Dockern rather then Vagrant, then I recommend this way. Because if you don't like it, you didn't mess up your system.

```sh
docker run -it --rm -v "$PWD":/backstopjs-example --name backstopjs-example-container vergissberlin/backstopjs-example bash
```


## Installation without Vagrant and Docker
If you don't wanna use Vagrant, you have to install the dependencies on your own. Please install _phantomjs_ and the node packages like that:

```sh
sudo npm i backstopjs phantomjs slimerjs -g
cd backstop-example && npm i
```


----


## Let's get testing
```sh
backstopjs test
backstopjs references
```
 For furhter informations, take a look on the [BackstopJS GitHub page](https://github.com/garris/BackstopJS).
