# FIRST UK Simulator Documentation

This collection comprises the documentation for the different projects and repositories listed 
under the [FIRST UK organization][fruk-org]. We are a group of volunteers that are working to 
allow students and mentors to easily write, compile, and test code in a browser-based simulator.

## Goals

The overarching goal of these projects is to provide a learning platform where students can 
explore and learn the practical challenges involved with using programming to control a robot. 
Learning to code with some real world constraints will provide the necessary motivation and 
challenges to make the process interesting. The tool is intended to be used in a classroom setting 
with exercises for learning. Additionally the tool should allow students to experiment freely.

### Key Points

* Aimed at middle school & high school students.
* Browser based (chrome, firefox).
* Should require coding knowledge to the same level as the existing First UK Tech challenge for the same age group.
* Software should be able to run on cheap laptops and classroom PCs.

## Status

**The associated projects in this organization are still very much in flux and in development.** If 
you are interested in contributing, please read our [Contributing Guide](contributing.md) for 
how you can get involved. We are always open to new ideas and contributions as long as they are 
agreed upon by our maintainers.


## What is *FIRST*?

[*FIRST* (*For Inspiration and Recognition of Science and Technology*)][first] is the world's 
leading youth-serving non-profit advancing STEM education. It provides students across all grade 
levels the ability to gain key skills that will help them the rest of their lives.

> *FIRST* is more than robots. The robots are a vehicle for students to learn important life skills. 
> Kids often come in not knowing what to expect - of the program nor of themselves. They leave, 
> even after the first season, with a vision, with confidence, and with a sense that they can 
> create their own future,
>
> \- Dean Kamen, Founder of *FIRST*

---

## Run Documentation Locally

The documentation is rendered using [Docsify][docsify], a static site generator that is fast and 
resource-cheap. It provides a clean, professional view that can be customized and detail-oriented.

For local development, [clone this repository][repository] and make sure to have either the 
`docsify` tool or `npx` Node tool installed.

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

[docsify]: http://docsify.js.org/
[first]: https://www.firstinspires.org/
[fruk-org]: https://github.com/FRUK-Simulator
[repository]: https://github.com/FRUK-Simulator/Documentation