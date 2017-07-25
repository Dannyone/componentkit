<<<<<<< HEAD
# ComponentKit Documentation 

We use [Jekyll](http://jekyllrb.com/) to build the site using Markdown and host it on [Github Pages](https://pages.github.com/).

## Installation

To contribute to the site or add to the documentation, you will have to set up a local copy of the site on your development machine.

### Dependencies

Github Pages uses Jekyll to host a site and Jekyll has the following dependencies.

 - [Ruby](http://www.ruby-lang.org/) (version >= 1.8.7)
 - [RubyGems](http://rubygems.org/) (version >= 1.3.7)
 - [Bundler](http://gembundler.com/)

Mac OS X comes pre-installed with Ruby, but you may need to update RubyGems (via `gem update --system`).
Otherwise, [RVM](https://rvm.io/) and [rbenv](https://github.com/sstephenson/rbenv) are popular ways to install Ruby.
Once you have RubyGems and installed Bundler (via `gem install bundler`), use it to install the dependencies:

```sh
$ cd componentkit # Go to folder
$ bundle install # Might need sudo.
```

### Instructions

Use Jekyll to serve the website locally (by default, at `http://localhost:4000`):

```sh
$ cd componentkit # Go to folder
$ git checkout docs
$ bundle exec jekyll serve -w
$ open http://localhost:4000/
```
=======
# [![ComponentKit](http://componentkit.org/static/componentkit-hero-logo.png)](http://componentkit.org/)

[![Build Status](https://travis-ci.org/facebook/componentkit.svg)](https://travis-ci.org/facebook/componentkit)

ComponentKit is a view framework for iOS that is heavily inspired by React. It takes a functional, declarative approach to building UI. It was built to power Facebook's News Feed and is now used throughout the Facebook iOS app.

### Quick start

ComponentKit is available to install via [CocoaPods](http://cocoapods.org) or [Carthage](https://github.com/Carthage/Carthage). 

If you are using CocoaPods, add the following to your [Podfile](https://guides.cocoapods.org/using/the-podfile.html):

```ruby
pod 'ComponentKit', '~> 0.15'
```

If you are using Carthage, add the following to your [Cartfile](https://github.com/Carthage/Carthage/blob/master/Documentation/Artifacts.md#cartfile):

```
github "facebook/ComponentKit" ~> 0.15
```

### Opening the Xcode projects

If you want to try out ComponentKit just clone the GitHub repository and open the Xcode project. To get started with the example app:

```
open Examples/WildeGuess/WildeGuess.xcodeproj
```

Build and run the `WildeGuess` target to try it out!

If you're interested in viewing only the ComponentKit source code in Xcode:

```
open ComponentKit.xcodeproj
```

There is no need to run any special commands prior to opening either Xcode project.

### Learn more

* Read the [Getting Started guide](http://www.componentkit.org/docs/getting-started.html)
* Get the [sample projects](https://github.com/facebook/componentkit/tree/master/Examples/WildeGuess)
* Read the [objc.io article](http://www.objc.io/issue-22/facebook.html) by Adam Ernst
* Watch the [@Scale talk](https://youtu.be/mLSeEoC6GjU?t=24m18s) by Ari Grant

## Contributing

See the [CONTRIBUTING](CONTRIBUTING.md) file for how to help out.

## License

ComponentKit is BSD-licensed. We also provide an additional patent grant.

The files in the /Examples directory are licensed under a separate license as specified in each file; documentation is licensed CC-BY-4.0.
>>>>>>> df334c5cf202328407e0e26da3765497334ee24f
