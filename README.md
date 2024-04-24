# [Effect Framework](https://effect.website/) Exploration
This repo contains my efforts learning the ins-and-outs of the `Effect` library. I will be documenting my experience in the code as well as in documents I write in this repo. All that will be linked in this `README.md` file.

---
- [Exploration Path](#exploration-path)
- [`Effect` Questions](#effect-questions)
   * [General & Tooling](#general-tooling)
   * [`Effect` bits & pieces](#effect-bits-pieces)
   * [Module Specific](#module-specific)
   * [Misc](#misc)
- [Conceptual Questions](#conceptual-questions)
   * [Category Theory](#category-theory)
   * [Functional Programming](#functional-programming)
- [Related Exploration](#related-exploration)
- [Guides](#guides)
   * [Core](#core)
   * [Advanced](#advanced)
   * [Lastly](#lastly)
- [Todos](#todos)
- [Links](#links)

## Exploration Path
- [ ] Create the project and get it installed and running
  - [ ] Decide if making a library or server
- [ ] Get it setup w/`rollup`
- [ ] Code quality tools
- [ ] Setup testing library

## `Effect` Questions

### General & Tooling
- Is there tree shaking?
  - i.e. Can I make my bundles smaller by importing only bits?
- Which testing library do people prefer?

### `Effect` bits & pieces
- Can someone explain [`Fibers`](https://effect.website/docs/other/glossary#fiber) better and how to use them or use cases? Examples preferred.
- Is there an IO module? i.e. File Reading
- Anything for `rx`?
- Package interop worries
  - [From this `Reddit` comment](https://www.reddit.com/r/typescript/comments/16w3iwn/opinions_about_effectts_do_you_recommend_using_it/k2uqc7d/)
- `generators` vs `async`/`await`
- Shared state?

### Module Specific
- `@effect/schema` Can do arbitrary schemas?

### Misc
- Validation
  - Data
  - Schema

## Conceptual Questions
### Category Theory
...

### Functional Programming
- Higher Kinded Types
  - Articles
    - [Kind (type theory)](https://en.wikipedia.org/wiki/Kind_(type_theory))
    - [Higher-Kinded Types](https://www.baeldung.com/scala/higher-kinded-types)
    - [A Guide to Scala's Higher Kinded Types](https://reintech.io/blog/guide-to-scalas-higher-kinded-types)
- Lenses
- Type Classes

## Related Exploration
- Dependency Injection / IoC
  - [Layers](https://effect-ts.github.io/effect/effect/Layer.ts.html)?
  - [Managing Services](https://effect.website/docs/guides/context-management/services)
  - [Managing Service Dependencies](https://effect.website/docs/guides/context-management/layers)
  - [Dependency Memoization](https://effect.website/docs/guides/context-management/dependency-memoization)
- Pattern Matching
- Utilities (see: [`Ramda`](https://ramdajs.com/docs/))

## Guides or Examples
### Core
- [ ] Configuration
- [ ] Error Management
- [ ] Pipelines
- [ ] Control Flow
- [ ] Context Management
- [ ] State Management
- [ ] Observability
### Advanced
- [ ] Batching & Caching
- [ ] Concurrency
- [ ] Resource Management
- [ ] Scheduling
- [ ] Streaming
- [ ] Dependency Injection
- [ ] Reactivity? 
### Lastly
- [ ] Testing
- [ ] Code Style

---

## Todos
- [ ] Decide on the path for my exploration
- [ ] 

---
## Links
GitHub
- [datner/effect-remix](https://github.com/datner/effect-remix/)
- [pigoz/effect-crashcourse](https://github.com/pigoz/effect-crashcourse)
- [effect-ts-app/boilerplate](https://github.com/effect-ts-app/boilerplate)

Misc
- [My impressions on Effect-TS](https://dnlytras.com/blog/effect-ts)
- [Solving the distributed schema problem with @effect/schema](https://www.youtube.com/watch?v=o-SvvUA7hik) (35min)
- [How to Sign for Effect @effect-ts](https://www.youtube.com/watch?v=4FZqme-z8SQ)
- [antoine-coulon/effect-introduction](https://github.com/antoine-coulon/effect-introduction)
- [Effect-ful computations with Fibers](https://www.youtube.com/watch?v=uwALExyq4NY&t=505s)
- [Effect for Beginners](https://www.youtube.com/watch?v=fTN8BX5qj6s&t=2s)
- [Effect: Typescript That Scales](https://www.youtube.com/watch?v=4ARWCmnjO0w)
- [Introduction to Effect 2022](https://www.youtube.com/watch?v=zrNr3JVUc8I)
- [Effect: Next-Generation Typescript](https://www.youtube.com/watch?v=SloZE4i4Zfk)
- [A bright future for Effect - DEV Community](https://dev.to/effect/a-bright-future-for-effect-455m)