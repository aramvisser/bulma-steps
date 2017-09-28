# Steps component for Bulma

This is an extensions for the [Bulma CSS Framework](http://bulma.io). It adds a `steps` component to
track progress in multi step forms or wizards.

[![Steps example for a checkout form](steps-example.png)](https://aramvisser.github.io/bulma-steps)

## Documentation

[Usage & Examples](https://aramvisser.github.io/bulma-steps)

I'm trying to keep this working with the latest available Bulma version. Currently tracking: **bulma
v0.5.3**. Other versions _should_ work, but no promises.

## Installation

### NPM

`npm install bulma-steps-component`

### Manually

There is no .css file available, only a .sass file. Make sure you are using the SASS version of
Bulma in your current workflow

- Download the `bulma-steps.sass` file
- Add `@import "bulma-steps.sass"` _after_ the `@import "bulma.sass"` statement in your own
  stylesheet

## Development

This repository doubles as the documentation page using Jekyll. You can easily see changes in the
documentation by running Jekyll locally.

- Install ruby and then install Jekyll with `gem install jekyll`
- Clone this repository
- Run `jekyll serve` inside the root directory of this repository
- Open the documentation page on [http://localhost:4000](http://localhost:4000)
- Make changes to the `bulma-steps.sass` file
- Reload the documentation page to see your changes

## Related Project

There is another steps extensions for Bulma available from
[Wikiki](https://github.com/Wikiki/bulma-steps). It even has the same name!
