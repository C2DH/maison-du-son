# maison-du-son

This Jekyll project is a collection of biographies of objects, written in a creative and engaging way, using a variety of media.

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
event_start_date: 1877-10-01
event_end_date: 1877-11-30
event_human_date: October/November 1877



---
```

## For developers

```

```
