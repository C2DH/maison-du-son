---
layout: page
title: How to ...
permalink: /readme
template: page
---

# Maison du Son

<!-- more -->

This Jekyll project is a collection of biographies of objects, written in a creative and engaging way, using a variety of media.

To work together, we use GitHub, a web-based platform for version control and collaboration. It is a place to store, manage, and track changes to files, including code and documents. It is used by developers, researchers, and many other professionals.

## Why use Github for this project?

**Collaboration**: Historians and scholars can work together on this research projects and see who did what at a glance.

**Version Control**: Track changes of any files and revert to previous versions.

**Documentation**: Detailed commit messages provide context for changes and give better understanding of the project and its evolution.

**Hosting**: any _push_ to master branch modify the website [Maison du Son](https://maison-du-son.netlify.app). Any _pull request_ to master branch publish a version of Maison du SOn website available to everyone to test your recent changes.

## How to add an object

In `_objects` folder, create a new file with the name of the object, in lowercase, with dashes instead of spaces and use `md`as extension. For example, if the object is a "Gramophone", the file name should be "gramophone.md".

In the file, add the following front matter:

```
---
title: "Gramophone"
authors:
  - alexander-grimm
---
```

The `title` is the name of the object, the `authors` is a list of the authors of the object biography. The authors are identified by their file name in the `_people` folder, without the extension. For example, if the author is "Alexander Grimm", the file name should be "alexander-grimm.md".

There are additional metadata that can be added to the front matter:

```
---
title: "Gramophone"
authors:
  - alexander-grimm
editors:
  - wilhelm-carl-grimm
translators:
  - jacob-ludwig-karl-grimm
date: 2020-01-01

object_start_date: 1877-10-01
object_end_date: 1877-11-30
object_date: October/November 1877



---
```
