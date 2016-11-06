# Starterkit Mustache Acidtest
Cross-platform acid tests for [Pattern Lab](http://patternlab.io/)

> **MAJOR KUDOS** to @c1rrus for the original idea of the Acid Test Starterkit. His README is included below, slightly modified.

This Starterkit exists as a means to reproduce combinations of Pattern Lab features across Pattern Lab PHP and Pattern Lab Node and ensure identical results.

The official Pattern Lab docs don't always categorically specify what should happen in those scenarios, so it wasn't clear if these are bugs or correct behavior. To aid discussion and investigation, it's useful to create some patterns that reproduce these situations as simply as possible and thus this project was born.

As these issues are clarified or fixed, this project can be updated accordingly and serve as a regression test to ensure they don't recur. Similarly, this project could be used as a compatibility test for the various Pattern Lab ports. Ideally, they should all produce the same results from the same input patterns.

Creation of this Starterkit [was voted on and passed](https://github.com/pattern-lab/the-spec/issues/23) to accomplish these goals.

## Adding Test Cases

__Draft__
To add more test cases to this Starterkit, first create an issue so it can be discussed. If there is spec ambiguity, or cross-platform parity concerns, it's a good candidate. Pattern Lab maintainers will work with you to attempt to reduce your sample to the smallest-possible test case. Then, submit a pull request with the needed files - ideally all contained within their own numbered folder under `_patterns`.

## Setup
Install this Starterkit via your preferred Pattern Lab platform. This project assumes you already have an edition setup.

### Node

[Importing Staterkits](https://github.com/pattern-lab/patternlab-node/wiki/Importing-Starterkits)

### PHP

To install a specific StarterKit from GitHub type:

`php core/console --starterkit --install pattern-lab/starterkit-mustache-acidtest
