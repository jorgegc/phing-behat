Phing Behat
===========

## Overview

A collection of Behat targets for Phing.

## Installation

This project can be checked out with Composer.

```
"require": {
    "jorgegc/phing-behat": "*"
}
```

If you are already running a Phing build in an existing project why not
include these tasks as well with the following line in your build.xml:

```
<import file="vendor/jorgegc/phing-behat/build.xml" optional="true" />
```

We also provide some template files that should be added to the root
of your project. These files are:

* behat.yml
* behat.example.yml

## Usage

To get a list of tasks.

```
phing -l
```
