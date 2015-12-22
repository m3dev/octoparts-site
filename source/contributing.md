---
title: Contributing
nav_order: 110
---

## Octoparts Contributor Guidelines

### Funny names

If you look around our codebase, you may find places where we use the word "part" to refer to what we call a "backend endpoint" in most of our documentation. This is bad naming, but one with historical reasons: when we started building Octoparts, it was with the intention of grabbing "parts" of a page from other services, thus an endpoint corresponded roughly with a "part".

We *do* plan on renaming our models and references but until then, stay alert!

### Reporting Issues

If you wish to report an issue for Octoparts, please ensure you have done the following things:

* If it is a documentation issue with a simple fix, don't raise an issue, just edit the documentation yourself directly in GitHub and submit a pull request. *Note* the documentation repository is [https://github.com/m3dev/octoparts-site](https://github.com/m3dev/octoparts-site)
* If you have a feature request, please raise an issue in the Github Issues tracker first.  It may be that Octoparts already provides something to achieve what you want to achieve, and raising an issue first allows us to catch that before you waste your time implementing something.
* If you think you have found a bug, please raise an issue.  Please be as specific as possible, including sample code that reproduces the problem, stack traces if there are any exceptions thrown, and versions of Octoparts, OS, JVM, etc.

### Contributor Workflow

This is the process for a contributor to contribute to Octoparts.

0. Fork this repository.
1. Follow [Gitflow procedures](http://nvie.com/posts/a-successful-git-branching-model/).
2. Ensure that your contribution meets the following guidelines:
    1. Live up to the current code standard:
        - Not violate [DRY](http://programmer.97things.oreilly.com/wiki/index.php/Don%27t_Repeat_Yourself).
        - [Boy Scout Rule](http://programmer.97things.oreilly.com/wiki/index.php/The_Boy_Scout_Rule) needs to have been applied.
    2. Regardless if the code introduces new features or fixes bugs or regressions, it must have comprehensive tests.
    3. The code should be well documented, and where sensible, include Scaladocs.
    4. Implementation-wise, the following things should be avoided as much as possible:
        * Global state
        * Public mutable state
        * Implicit conversions
        * ThreadLocal
        * Locks
        * Casting
        * Introducing new, heavy external dependencies
3. Submit a pull request.

If the pull request does not meet the above requirements, then it will be rejected until it does.

### Licence

By contributing your code, you agree to license your contribution under the terms of the [Apache Licence v2](http://www.apache.org/licenses/LICENSE-2.0.html)
