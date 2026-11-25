# Phases of Making Pottery

# Phases of Making Pottery

A small React and TypeScript app that turns the stages of making pottery into a
scrolly telling data visualization. As you move through each stage, the metrics
panel updates to show hydration, temperature, shrinkage, and other details.
Scroll length represents the relative duration of each stage; it is illustrative,
not a precise timescale.

[Watch a short demo](https://github.com/Vebop/epo-hw/blob/main/screen-clip-app.mov)

## What it does

- Uses `IntersectionObserver` to track the visible pottery stage.
- Updates the visualization as you scroll, focus, or select a stage.
- Shows hydration, temperature, and shrinkage with animated visual indicators.
- Respects the reduced-motion preference for visual transitions.

## Built with

React 19, TypeScript, Vite, CSS, and the browser's `IntersectionObserver` API.

## Run locally

```bash
git clone https://github.com/Vebop/epo-hw.git
cd epo-hw
npm install
npm run dev
```

To check the production build and lint the project:

```bash
npm run build
npm run lint
```

## Data note

The stage descriptions and values are for educational illustration, not
scientific measurement or pottery advice. Values are based on the references
below and may vary with clay, studio conditions, and firing practices.

[Stages of Clay](https://ceramicinfospot.com/what-is-greenware-in-ceramics-the-stages-of-clay-explained/)

[Preparing Clay for Throwing](https://ceramicinfospot.com/how-to-prepare-clay-for-throwing-the-complete-wedging-guide/)

[From Clay to Ceramics](https://openlearning.aalto.fi/pluginfile.php/93249/mod_resource/content/1/From%20Clay%20to%20Ceramics%20Aalto%202021.pdf])

<!-- ## Initial Idea

I had the vision of walking into my ceramics studio, focusing in on the different tasks that I do when I arrive, and how I spend my time. Along with these visuals (as if there was a go-pro on my forehead) the user would see the status of the clay in many different ways. I was originally considering having direction and guidance along with references to videos and other educational material for each step of the clay-making process. I imagined this web app would be a stepping off point to learn about each phase.

## Current Status

We currently stand at a two panel scrolly telling web app with a metrics section to the left, and placeholder cards scrolling by on the right.
-->
## License

This work is licensed under No License. This work is copyrighted by me, Vebop, the author.
