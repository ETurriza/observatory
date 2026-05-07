# Observatory

Interactive portfolio built with Astro, JavaScript, CSS and Three.js.

The project presents academic and technical work as celestial objects inside a digital observatory. The main interface is a 2D control panel, while the 3D observatory works as an interactive deep-space experience.

## Live Site

https://eturriza.github.io/observatory/

## Overview

Observatory is a personal portfolio designed around a space exploration interface. Each project is represented as an object in the system, with summaries, tags and links to repositories or external pages.

The site includes:

- 2D control interface
- interactive project map
- project catalog
- 3D exploration mode
- automatic 3D tour
- project modals
- black hole 404 easter egg
- GitHub Pages deployment

## Featured Objects

- gaiatools
- Robot bombero
- Braingeneers
- DBSCAN paralelo
- Bases de Datos
- 1er lugar LIDERA
- UPF Barcelona

## Tech Stack

- Astro
- HTML
- CSS
- JavaScript
- Three.js
- WebGL
- GitHub Pages

## Project Structure

```txt
src/pages/
  index.astro      # 2D control interface
  space.astro      # 3D observatory
  objects.astro    # project catalog
  about.astro      # profile
  log.astro        # log page
  404.astro        # black hole 404 page

public/
  textures/        # 3D textures
