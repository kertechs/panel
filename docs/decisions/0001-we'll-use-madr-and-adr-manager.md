# We'll use MADR and adr-manager

* Status: proposed
* Deciders: Florent Massiera, Frederic Merad, Loyce Lechning, Laurent Cochet, Nassim Bennouna
* Date: 2022-05-23

Technical Story: Jira-0002358

## Context and Problem Statement

We are starting a new project and stated the documentation is central and has to be always up to date and in sync with the taken architecture decisions

## Decision Drivers

* find the tool that we'll match as best as possible different points of views (developer, architect, admin, po, ...)
* Easy to install, low maintenance
* extendable (PHP/JS, ..., Open Source)
* Very flexible

## Considered Options

* confluence
* notepad
* madr (different implementations but focusing on the concept behind)

## Decision Outcome

Chosen option: "madr", because flexible. easy to use. close to the project and yet can be sync with an external global source of knowledge with additional tooling

### Positive Consequences

* Improved and more accessible documentation

### Negative Consequences

* additional tooling
* might take some time and work for adoption and clean / smooth usage

## Links

* https://adr.github.io/
* https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions
* https://github.com/npryce/adr-tools
* https://github.com/adr/adr-manager
