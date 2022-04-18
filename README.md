**[MVP](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93presenter)** is a derivation of the model–view–controller architectural pattern, and is used mostly for building user interfaces. In MVP, the presenter assumes the functionality of the "middle-man". In MVP, all presentation logic is pushed to the presenter.</br>

[![Swift Version](https://img.shields.io/badge/Swift-2.2--4.x-F16D39.svg?style=flat)](https://developer.apple.com/swift)

### How do I get set up? ###

# Installation

**Add template in your** [Rambafile](https://github.com/rambler-digital-solutions/Generamba/wiki/Rambafile-Structure)**:**
```
templates:
 - {name: swift-mvp-injection, git: 'https://github.com/mihailsalari/swift-mvp-injection.git'}
```

**Install template:**
```
generamba template install
```
# Usage
```
generamba gen [MODULE_NAME] [TEMPLATE_NAME]
```
**Example:**

To create Splash module:

```
generamba gen Splash swift-mvp-injection
```

It will create the Login module in your project target, as well as in your tests target.

### Contribution guidelines ###

* Feel free to contribute.

### Question? ###
If you have a general question and hesitate to submit an issue at GitHub, you can feel free to ask the question at [Stack Overflow](http://stackoverflow.com/). The author of this module MVP tag there to answer as quickly as possible.

* info@mihailsalari.com
