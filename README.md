# Material for the FOSS4G-E 2025 in Mostar

https://terrestris.github.io/foss4g-e-2025/

## How to use locally

1. `git submodule update --init --recursive` to initialize the reveal.js submodule
1. `npm ci`
1. `npm start`


## Creating a PDF with decktape

1. `npm install -g decktape`
1. `decktape --size 1600x900 --pause 50 reveal http://localhost:5173/talks/your_talk.html slides.pdf`
