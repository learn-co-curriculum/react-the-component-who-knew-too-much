# The Component Who Knew Too Much

## Objectives

1. Describe strategies for making components dumber
2. Explain why dumb components are preferable to ones that manage a lot of state

## Overview

This lesson is kind of just a meditation on how awesome dumb components can be.

We want students to start buying into this stuff, and my sense is that it might
be a little hard to sell. Questions come up like, "Why can't I just update
that DOM element directly?", and it's important that we give students space to
ask those questions — and that we provide them with some reasonable answers.

So this lesson kind of wants to show them how things can go wrong when we have
components that manage a lot of state. `setState()` calls that don't quite work,
inefficient updates, etc.

## Resources

- [Presentational and Container Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.ad9u8whos)
- [Smart and Dumb Components in React](http://jaketrent.com/post/smart-dumb-components-react/)
