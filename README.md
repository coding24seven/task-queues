# task-queues

## Purpose

This repository demonstrates that (in the browser):

1. consecutive microtasks running one after another prevent viewport repaints and user interaction till they are completed
1. consecutive macrotasks running one after another allow viewport repaints and user interaction between each task

## Getting started

### Running locally

1. in `index.html` comment or uncomment each of two main '...tasks' functions to let each of them run without other one interfering
1. open `index.html` in browser
1. open browser console
1. watch background color change
1. on next runs, try and interact with button on page
