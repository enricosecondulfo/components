[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/angular/components) 

# Official components for Angular
[![npm version](https://badge.fury.io/js/%40angular%2Fcdk.svg)](https://www.npmjs.com/package/@angular/cdk)
[![Build status](https://circleci.com/gh/angular/components.svg?style=svg)](https://circleci.com/gh/angular/components)
[![Gitter](https://badges.gitter.im/angular/components.svg)](https://gitter.im/angular/material2?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

The Angular team builds and maintains both common UI components and tools to help you build your
own custom components. The team maintains several npm packages.

| Package                   | Description                                                                         | Docs             |
| ------------------------- | ----------------------------------------------------------------------------------- | ---------------- |
| `@angular/cdk`            | Library that helps you author custom UI components with common interaction patterns | [Docs][cdk-docs] |
| `@angular/material`       | [Material Design][] UI components for Angular applications                          | [Docs][mat-docs] |
| `@angular/google-maps`    | Angular components built on top of the [Google Maps JavaScript API][]               | [Docs][map-docs] |
| `@angular/youtube-player` | Angular component built on top of the [YouTube Player API][]                        | [Docs][ytp-docs] |


#### Quick links
[Documentation, demos, and guides][mat-docs] |
[Frequently Asked Questions](FAQ.md) |
[Community Google group](https://groups.google.com/forum/#!forum/angular-material2) |
[Contributing](https://github.com/angular/components/blob/master/CONTRIBUTING.md) |
[StackBlitz Template](https://stackblitz.com/fork/components-issue)

## Getting started

See our [Getting Started Guide][getting-started] if you're building your first project with Angular
Material.


## Contributing

If you'd like to contribute, please follow our [contributing guidelines][contributing]. Please see
our [`help wanted`][help-wanted] label for a list of issues with good opportunities for
contribution.

## High level work planned for Q1 2020 (Jan - Mar):
* Date-range picker
* Finish remaining test harnesses for Angular Material components (four remaining as of January)
* Continuing to create new, API-compatible versions of the Angular Material components backed by
[MDC Web][] ([see @jelbourn's ng-conf talk](https://youtu.be/4EXQKP-Sihw?t=891)). There are five
remaining components to complete here as of January.
* Add support for density configuration for the new components based on MDC Web.
* Authoring benchmarks to collect performance metrics for Angular Material components. These
benchmarks will live inside Google's internal code repository for the time being, but we should
be able to publish the results.


## About the team
The Angular Components team is part of the Angular team at Google. The team includes both Google
employees and community contributors from around the globe.

Our team has two primary goals:
* Build high-quality UI components that developers can drop into existing applications 
* Provide tools that help developers build their own custom components with common interaction
patterns


What do we mean by "high-quality" components?
* Internationalized and accessible so that all users can use them.
* Straightforward APIs that don't confuse developers.
* Behave as expected across a wide variety of use-cases without bugs.
* Behavior is well-tested with both unit and integration tests.
* Customizable within the bounds of the Material Design specification.
* Performance cost is minimized.
* Code is clean and well-documented to serve as an example for Angular developers.

## Browser and screen reader support
The Angular Components team supports the most recent two versions of all major browsers:
Chrome (including Android), Firefox, Safari (including iOS), and IE11 / Edge.

We aim for great user experience with the following screen readers:
* **Windows**: NVDA and JAWS with IE11 / FF / Chrome.
* **macOS**: VoiceOver with Safari / Chrome.
* **iOS**: VoiceOver with Safari
* **Android**: Android Accessibility Suite (formerly TalkBack) with Chrome.
* **Chrome OS**: ChromeVox with Chrome.


[Material Design]: https://material.io
[Google Maps JavaScript API]: https://developers.google.com/maps/documentation/javascript/tutorial
[YouTube Player API]: https://developers.google.com/youtube/iframe_api_reference
[MDC Web]: https://github.com/material-components/material-components-web/
[cdk-docs]: https://material.angular.io/cdk/categories
[mat-docs]: https://material.angular.io
[map-docs]: https://github.com/angular/components/blob/master/src/google-maps/README.md
[ytp-docs]: https://github.com/angular/components/blob/master/src/youtube-player/README.md
[getting-started]: https://material.angular.io/guide/getting-started
[contributing]: https://github.com/angular/components/blob/master/CONTRIBUTING.md
[help-wanted]: https://github.com/angular/components/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22
