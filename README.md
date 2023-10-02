---
layout: page
title: How to ...
permalink: /readme
template: page
---

# Maison du Son

<!-- more -->

This Jekyll project is a collection of biographies of objects, written in a creative and engaging way, using a variety of media.

## Why do we use Github for this project?

To work together, we use GitHub, a web-based platform for version control and collaboration. It is a place to store, manage, and track changes to files, including code and documents:

**Collaboration**: Historians and scholars can work together on this research projects and see who did what at a glance.

**Version Control**: Track changes of any files and revert to previous versions.

**Documentation**: Detailed commit messages provide context for changes and give better understanding of the project and its evolution.

**Simpler markup**: Every webpage is written in Markdown, "a lightweight markup language for creating formatted text using a plain-text editor." See [Markdown page on Wikipedia](https://en.wikipedia.org/wiki/Markdown)

**Hosting**: any _push_ to master branch modify the website [Maison du Son](https://maison-du-son.netlify.app). Any _pull request_ to master branch publish a version of Maison du SOn website available to everyone to test your recent changes.

Relevant documentation:

- introduciton on git and GitHub by [SwCarpentry: Version Control with Git](https://swcarpentry.github.io/git-novice/)
- a now retired version of [Programming Historians: Getting Started with Github Desktop](https://programminghistorian.org/en/lessons/retired/getting-started-with-github-desktop)
- a [Markdown cheatsheet for Github](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## How to join the project

Join the [C2DH/maison-du-son/discussions](https://github.com/C2DH/maison-du-son/discussions) thread to be added as project members, or feel free to clone this repository and do a pull request from your own version.

## How to add a person bio

The authors are identified by their file name in the `_people` folder, without the extension. For example, if the author is "Alexander Grimm", the file name should be "alexander-grimm.md".
The minimal version of an author markdown file:

```md
---
title: Jacob Ludwig Karl Grimm
---
```

The `title` is the fullname of the author. Add the author bio right after the last `---` for example:

```md
---
title: Jacob Ludwig Karl Grimm
---

Jacob Ludwig Karl Grimm was a German philologist, jurist, and mythologist. He is known as the discoverer of Grimm's law (linguistics), the co-author with his brother Wilhelm of the monumental Deutsches Wörterbuch, the author of Deutsche Mythologie and, more popularly, as one of the Brothers Grimm and the editor of Grimm's Fairy Tales.
```

Once committed, the author bio will be available at the following URL: `https://maison-du-son.netlify.app/people/jacob-ludwig-karl-grimm`

## How to add an object

In `_objects` folder, create a new file with the name of the object, in lowercase, with dashes instead of spaces and use `md`as extension. For example, if the object is a "Gramophone", the file name should be "gramophone.md".

In the file, add the following front matter:

```md
---
title: 'Gramophone'
authors:
  - alexander-grimm
---
```

The `title` is the name of the object, the `authors` is a list of the authors of the object biography, identified by their file name in the `_people` folder (see above).
There are additional metadata that can be added to the front matter:

```md
---
title: 'Gramophone'
abstract: The Gramophone, an iconic symbol of bygone eras, holds a special place in the annals of music history.
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
object_wikidata_id: Q7112808
---

A nice introduction to your object.

## Your first Subheading

```

