# Atomist 'rug-koans-editors'

[![Build Status](https://travis-ci.org/atomist-rugs/rug-koans-editors.svg?branch=master)](https://travis-ci.org/atomist-rugs/rug-koans-editors)
[![Slack Status](https://join.atomist.com/badge.svg)](https://join.atomist.com)

> ***"Rugs to teach Rug using Rug."***

A set of editors for getting to grips with [Rug][rug]. Typically applied to a project generated from the Rug [Koans Project generator][rug-koans-project].

[rug]: http://docs.atomist.com/
[rug-koans-project]: https://github.com/atomist-rugs/rug-koans-project

## Usage

Typically you would first run the [Rug Koans Project generator](https://github.com/atomist-rugs/rug-koans-project) and that will then lead you on the journey of executing these editors against your project as you explore the features of Rug.

## Rugs

If you like you can run the Rugs here outside of the Koans journey that begins with the [Rug Koans project generator](https://github.com/atomist-rugs/rug-koans-project). Here we describe each of the individual Rugs and what they will attempt to do to your own projects.

### Step1

The Step1 editor creates the files that are the starting point for this first step on the Rug Koans journey.

#### Prerequisites

There are no prerequisites to running this editor, although it is advised that ideally you should be working on the project generated by the [Rug Koans project generator](https://github.com/atomist-rugs/rug-koans-project).

#### Parameters

No parameters are required.

#### Running

Run this Rug editor as follows:

```
$ cd targetproject
$ rug edit atomist-rugs:rug-koans-editors:Step1
```

### Step1SeeSolution

The Step1SeeSolution editor populates a set of addition files that show how the solution to this step should look *without* overwriting your working files.

#### Prerequisites

There are no prerequisites to running this editor, although it is advised that ideally you should be working on the project generated by the [Rug Koans project generator](https://github.com/atomist-rugs/rug-koans-project).

#### Parameters

No parameters are required.

#### Running

Run this Rug editor as follows:

```
$ cd targetproject
$ rug edit atomist-rugs:rug-koans-editors:Step1SeeSolution
```

### Step1OverwriteWithSolution

The Step1OverwriteWithSolution editor overwrites your working files for this step with the solution.

#### Prerequisites

There are no prerequisites to running this editor, although it is advised that ideally you should be working on the project generated by the [Rug Koans project generator](https://github.com/atomist-rugs/rug-koans-project).

#### Parameters

No parameters are required.

#### Running

Run this Rug editor as follows:

```
$ cd targetproject
$ rug edit atomist-rugs:rug-koans-editors:Step1Step1OverwriteWithSolution
```

## Development

You can build, test, and install the project locally with
the [Rug CLI][cli].

[cli]: https://github.com/atomist/rug-cli

```
$ rug test
$ rug install
```

To create a new release of the project, simply push a tag of the form
`M.N.P` where `M`, `N`, and `P` are integers that form the next
appropriate [semantic version][semver] for release.  For example:

[semver]: http://semver.org

```
$ git tag -a 1.2.3
```

The Travis CI build (see badge at the top of this page) will
automatically create a GitHub release using the tag name for the
release and the comment provided on the annotated tag as the contents
of the release notes.  It will also automatically upload the needed
artifacts.

## Support

General support questions should be discussed in the `#support`
channel on our community Slack team
at [atomist-community.slack.com][slack].

If you find a problem, please create an [issue][].

[issue]: https://github.com/atomist-rugs/spring-boot-rest-service/issues

---
Created by [Atomist][atomist].
Need Help?  [Join our Slack team][slack].

[atomist]: https://www.atomist.com/
[slack]: https://join.atomist.com/
