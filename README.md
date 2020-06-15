# FIRST UK Simulator Documentation

This repository comprises the documentation for the different projects and repositories listed 
under the [FIRST UK organization][fruk-org]. We are a group of volunteers that are working to 
allow students and mentors to easily write, compile, and test code in a browser-based simulator.

Please read the documentation for more information.

## Running the Documentation

The documentation is rendered using [Docsify][docsify], a static site generator that is fast and 
resource-cheap. It provides a clean, professional view that can be customized and detail-oriented.

For local development, clone this repository and make sure to have either the `docsify` tool or 
`npx` Node tool installed.

### Via `docsify-cli`

```
# you may need sudo for this
npm i docsify-cli -g
```

You can then run 

```
docsify serve .
```

### Via `npx`

You can also run the service without needing to install it if you have `npx` installed. It should 
be installed by default on newer versions of NodeJs.

```
npx docsify-cli serve .
```

[fruk-org]: https://github.com/FRUK-Simulator