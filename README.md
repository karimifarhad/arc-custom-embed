# Custom Embed Reference Implementation and Testing Tool

## Overview

This project contains:
  * several reference implementations of Arc Custom Embeds
  * a "blank" custom embed implementation for quick-start
  * a host application for testing without using Ellipsis

## Documentation

For Arc users with PageBuilder Fusion running, we recommend walking through the process of building an embed first.

[Getting Started with Custom Embeds](./docs/getting-started.md)

Whether you're using Fusion or not, it may help to look at our starter code or reference implementations.

[Starter Code](./public/blank)

[Reference Implementations](./public/)

For all users, we suggest running the testing tool:

[Testing Tool Docs](./docs/testing.md)

For more information, see the complete embed specification:

[Custom Embed Specification](./docs/reference.md)

## Bugfixes

A previous version of this example contained a bug that would result in spaces being decoded as plus (+) symbols. This
was corrected on Sept 26th, 2019, but any work built off of an earlier version of this repo should be reviewed and
modified if necessary. See [the following pull request](https://github.com/washingtonpost/arc-custom-embed/pull/6) for
the changes applied.
