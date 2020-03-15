---
title: Design System Breadth of Problems
description: "Spoiler: Successful Design Systems Often Need To Cover A Lot of Ground"
date: 2020-03-15
tags:
  - design systems
  - consulting
layout: layouts/post.njk
---

While this is far far from an exhaustive list of all of the different problems I’ve had to tackle as front-end architect over the past 4 years, here's this will shed some light into the breath and depth of knowledge required to keep a modern design system (and design system team!) operating as smoothly and as productively as possible.

## Validation
- How do you know if the options passed along to a component — either in Twig,  JavaScript, or both — are valid?

## Compatibility / Interoperability
- How do you make sure the design system’s Twig templates are as Drupal friendly as possible (ex. `attributes` support) 
- How do you make sure Drupal (or any Twig-compatible environment) supports any custom Twig extensions in use?

## Dependency Management
- How do you make sure the design system's interrelated dependencies all stay in sync?

## Cross-browser Support
- How do you use web component <slot>s if/when Shadow DOM isn't supported or can't be used?

## Progressive Enhancement / Server-side Rendering
- How do you server-side render (and subsequently hydrate) a web component without anyone flickering or layout thrashing?

## Documentation / Communications
- How do you handle documenting the current + previous versions of the design system?
- How do you make sure that the [design tokens|utility classes|component props| etc] documented *actually* match up with what currently exists?
- How do you succinctly communicate all of the different updates in a release?

## Tooling & Build Process
- As a developer, how do you compile the front-end code being shipped in the design system?

## Coding Standards
- Promote and enforce consistent coding standards?

## Workflow
- How do you *easily* review & test out the code from an incoming PR?

## Publishing
- How do you cut a new release of the design system?

## Testing
- How do you know if an incoming code change causes a visual regression?

## Performance
- How do you ship an entire design system's worth of components without slowing down the browser... or build process...?