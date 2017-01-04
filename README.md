# A JavaScript Code Quality Guide

This document aims to be a comprehensive guide to JavaScript code quality.
It encompases principles, concepts, processes, conventions, standards and tooling.

_it is a live document. contributions are welcome. this is a first draft_

![](code-reviews-wtfs.png)

## Proper Build Process  
( sourcemaps, static asset management, cache busting hashes )

## Coding Style Guide ( eslint )

## Automated Tests  
( Unit, Functional/Non-Regression, E2E, Stress )

## Technology ( framework, language ) Conventions

## Team/Project Conventions

## Code Coverage Reports

## Good Documentation

## Keep dependencies up to date and secure
( read the modules code )

## Lock dependencies
( yarn.lock, npm-shrinkwrap.json )

## Peer Code Reviews

## Code Clean Principles
( descriptive naming and auto explanatory code, no javadoc )

## Code Notes
( TODO, FIXME ) https://github.com/stephenb/node-notes

## Remove event listeners on teardown

## Avoid Callback Hell

## Avoid Anonymous Functions
( arrow functions are ok )

## Avoid “too clever” code lines

## Prefer Pure Functions

## Avoid Blocking Code
( i/o, long computation)

## Thoughtful DOM updates
[ requestAnimationFrame, ShadowDOM ]

## Avoid Global Scope Abuse  
(  globals are evil )

## Proper Error Handling
( catch, logging strategy, error conventions, user feedback )

## Optimistic UI updates

## Use object and collection helpers
Eg. Lodash get and has methods

## Security
Prevent Cross Site Scripting and don't store sensitive data in the browser data stores

## Prevent Code Duplication
jsinspect and pmd

## Choose the Right Data Structure


---
Made with ♥ by [Gabo Esquivel](http://gaboesquivel.com) and [contributors](https://github.com/gaboesquivel/jscodequality/graphs/contributors)
