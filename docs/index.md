# _magpie
_magpie is a framework for building psychological online experiments that run in the participants' browser.

It is composed of three parts:

 * server-side part that allows managing and configuring experiments and stores experiment results
 * a client-side part that runs in the participant's browser and provides
   * a technical and conceptual framework for building experiments
   * a catalogue of components that can be used in experiments
   
You can use the same server instance for running multiple experiments.

## Features
Some features of _magpie include:

 * Declarativeness: Define your experiments in an easily extendable, HTML-based language (the Vue templating language)
 * Ease of use: There are many built-in screens to use for quickly building simple and advanced experiments
 * Composability: Build custom behavior by picking from and combining a wide range of components, built-in and external (any Vue-compatible library is supported)
 * Interactivity: Allow participants to interact with each other with support for interactive experiments built in

This site serves the manual, which will guide you through the various features.

There is also [the _magpie reference](https://magpie-reference.netlify.app/), a comprehensive documentation
of _magpie's components and their interfaces.
