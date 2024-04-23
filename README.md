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
- Are there any boilerplates?

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

## Guides
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
- [My impressions on Effect-TS](https://dnlytras.com/blog/effect-ts)