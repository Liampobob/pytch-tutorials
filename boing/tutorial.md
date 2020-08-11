# Boing: Make a Pong-like game

In this tutorial we will make a version of the classic game
[Pong](https://en.wikipedia.org/wiki/Pong).  We are going to use the graphics,
and some of the ideas, kindly made available by the [Code the
Classics](https://wireframe.raspberrypi.org/books/code-the-classics1) book
published by the Raspberry Pi organisation.

{{< run-finished-project >}}

---

## Make the playing area

We first set up the _Stage_, which, like Scratch, is where the action takes
place.  We're going to use the same image as the version in _Code the Classics_.
We define a `class` which is based on the built-in `pytch.Stage`, and say what
_Backdrops_ we want it to have.  In Pytch we do this by giving a _list_ of
pairs.  The first thing in each pair is the name we want to be able to use to
talk about this backdrop in our code.  The second thing is where Pytch can find
the image file.

{{< commit add-stage-with-background >}}

