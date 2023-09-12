# Astro + View Transitions + Container Queries in TailwindCSS

> Inspired by Jack Herrington's video

- Using Container queries to make our only `Card.astro` Component adapt to whatever container size its in
  - We can define the container that will be the reference to its children by adding the `@container` class
  - just by adding `@` before the media query we can use it to specify that the size is relative to its parent container
