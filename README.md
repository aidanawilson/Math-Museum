# ApogeeLab Mathematics Museum

Static site structure:

- `/index.html` — museum homepage
- `/e/index.html` — Museum of e
- `/pi/index.html` — test exhibit
- `/calculus/index.html` — test exhibit
- `/fourier/index.html` — test exhibit
- `/complex/index.html` — test exhibit
- `/chaos/index.html` — test exhibit
- `/probability/index.html` — test exhibit
- `/assets/museum.css` — shared museum theme

Each exhibit uses a folder containing an `index.html`. On Cloudflare Pages:

- `/e/index.html` is visited as `/e/`
- `/pi/index.html` is visited as `/pi/`
- and so on.

No framework or build process is required.
