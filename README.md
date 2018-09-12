Liquid Fire iOS [![npm version](https://badge.fury.io/js/liquid-fire-ios.svg)](http://badge.fury.io/js/liquid-fire-ios)
=================

[![Build Status](https://travis-ci.org/runspired/liquid-fire-ios.svg?branch=master)](https://travis-ci.org/runspired/liquid-fire-ios)
[![Ember Observer Score](http://emberobserver.com/badges/liquid-fire-ios.svg)](http://emberobserver.com/addons/liquid-fire-ios)
[![Discord](https://img.shields.io/discord/480462759797063690.svg?logo=discord)](https://discord.gg/zT3asNS)

Liquid-fire-ios provides additional transitions that are similar to the transitions found in native iOS
applications.

## Support, Questions, Collaboration

Join the Ember Community on [Discord](https://discord.gg/zT3asNS)

### Status

[Changelog](./CHANGELOG.md)

[![dependencies](https://david-dm.org/runspired/liquid-fire-ios.svg)](https://david-dm.org/runspired/liquid-fire-ios)
[![devDependency Status](https://david-dm.org/runspired/liquid-fire-ios/dev-status.svg)](https://david-dm.org/runspired/liquid-fire-ios#info=devDependencies)

## Usage

`ember install liquid-fire-ios`

This will run the default blueprint which additionally installs `liquid-fire`.

### Defining a Transition

```js
export default function() {
  this.transition(
    this.use('exit-right', { duration: 200 }),
    this.reverse('exit-left', { duration: 200 })
  );
}
```


## Contributing

Contributions are very welcome.

When making a PR try to use the following conventions:

**Commit Messages:**

`type(shortname): action based description`

Examples:

- chore(deps): bump deps in package.json and bower.json
- docs(component): document the `fast-action` component

**Branch Naming:**

`type/short-description`

Examples:

- chore/bump-deps
- docs/fast-action-component


