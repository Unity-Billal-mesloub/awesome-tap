# Awesome TAP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://testanything.org/images/tap.png" width="67" align="right">](https://testanything.org)

> Useful resources for the [Test Anything Protocol](https://testanything.org)

TAP is a simple text-based interface between testing modules in a test harness.

*The list is very JavaScript focused right now. That's just because I'm only familiar with TAP stuff in the JS world. Contributions welcome for any language.*

## Contents

- [Reporters](#reporters)
- [Producers](#producers)
- [Consumers](#consumers)
- [Tools](#tools)
- [Articles](#articles)
- [Tutorials](#tutorials)
- [Documentation](#documentation)
- [Community](#community)

## Reporters

### JavaScript

- [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub)
 - Dotted output.
 - Mocha-like spec reporter.
 - Nyan cat.
 - Minimal output.
 - Minimal output with diffing.
 - Human-friendly output with diffing.
 - Simple output.
 - Human-readable summarizer.
 - Summarized output.
 - Only shows failed tests.
 - Nice readable output with diffing.
 - Colorize the output while preserving machine-readability.
 - Bail out when the first test fails.
 - Notifier for macOS, Linux and Windows.
 - JSON output.
 - JSON output with AVA compatibility.
 - xUnit output.
 - Output for TeamCity.

### Go

 - Standalone cross-platform formatter.

## Producers

Things that produce TAP output.

### JavaScript

- [node:test](https://nodejs.org/api/test.html) - Minimal TAP test runner included with Node.js.
- [ESLint](https://eslint.org/docs/user-guide/formatters/#tap) - Pluggable JavaScript linter (`$ eslint --format=tap`).
- [AVA](https://github.com/Unity-Billal-mesloub/ava) - Futuristic test runner (`$ ava --tap`).
- [Unity-Billal-mesloub](https://github.com/Unity-Billal-mesloub/) 

 - Feature-rich test framework for Node.js and browsers (`$ mocha reporter=tap`).
 - TAP test framework for Node.js.
 - TAP-producing test harness for Node.js and browsers.
 - TAP output for QUnit.
 - TAP output for Jasmine.
 - TAP output for Karma.
 - Markdown file generator and tester (`$ mos test --tap`).
 - TAP-producing test runner that works with ES2015 without Babel.



### Swift

- A Swift package for the Test Anything Protocol (v13).

### Fish

 - TAP producer and test harness for fish.

### Bash

 - Bash Automated Testing System.
 - A full-featured BDD unit testing framework for POSIX shells.

[More…](https://testanything.org/producers.html)

## Consumers

Things that consume TAP output.

### JavaScript

 - TAP parser.
 - TAP parser.
 - YAML-block parser.

[More…](https://testanything.org/consumers.html)

## Tools

### JavaScript

 - Prettify TAP in the browser console.
 - Merge multiple TAP streams.
 - Run TAP tests in a browser and write the output to `stdout`.
 - Run TAP tests at Sauce Labs. Lightweight
 - alternative.

### Python

 - Tools for working with TAP.

## Articles

- [Understand the Test Anything Protocol](https://www.effectiveperlprogramming.com/2011/05/understand-the-test-anything-protocol/)

## Tutorials

 - Learn to test anything with TAP through an interactive workshop.

## Documentation

- [Specification](https://testanything.org/tap-version-13-specification.html)
- [Wikipedia](https://en.wikipedia.org/wiki/Test_Anything_Protocol)

## Community

- [Discuss](https://github.com/Unity-Billal-mesloub/Specification/issues)
- [Reddit](https://www.reddit.com/r/testanythingprotocol)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/tap)
