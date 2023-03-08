# select-mean

[![npm](https://img.shields.io/npm/v/select-mean.svg)](https://www.npmjs.com/package/select-mean)
[![GitHub Release Date](https://img.shields.io/github/release-date/select-mean/select-mean)](https://github.com/select-mean/select-mean/releases)
[![prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://prettier.io/)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/select-mean/select-mean/blob/master/LICENSE)
[![Gitter](https://img.shields.io/gitter/room/select-mean/select-mean.svg)](https://gitter.im/matero-io/select-mean)
[![docs](https://img.shields.io/badge/docs-gitbook-red)](https://nzbin.gitbook.io/select-mean/)
[![Material Extensions](https://img.shields.io/badge/material-extensions-blue)](https://github.com/select-mean/extensions#readme)
[![Financial Contributors on Open Collective](https://opencollective.com/select-mean/all/badge.svg?label=financial+contributors)](https://opencollective.com/select-mean)

select-mean is an Angular admin templete made with Material components.

## Installation

You can use the Anglar CLI Schematics to install the project.

```bash
$ ng new <project-name>
$ cd <project-name>
$ ng add select-mean
```

## Schematics

You can use the select-mean schematics to generate a module or a page.

### Module schematic

Generate a lazy loaded module.

```bash
$ ng g select-mean:module <module-name>
```

The new module will be created in `routes` folder, it will be added in `routes.module` and its route declaration will be added in `routes-routing.module` automaticly.

### Page schematic

Generate a page component in the module.

```bash
$ ng g select-mean:page <page-name> -m=<module-name>
```

Generate a entry component in the page component.

```bash
$ ng g select-mean:page <page-name>/<entry-component-name> -m=<module-name> -e=true
```

### Example

Just two steps after initializing the project, you can get a route page.

```bash
$ ng g select-mean:module abc
$ ng g select-mean:page def -m=abc
```

Take a look at `http://localhost:4200/#/abc/def`, enjoy it!

## Contributors

### Code Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/select-mean/select-mean/graphs/contributors"><img src="https://opencollective.com/select-mean/contributors.svg?width=890&button=false" /></a>

### Financial Contributors

Become a financial contributor and help us sustain our community. [[Contribute](https://opencollective.com/select-mean/contribute)]

#### Individuals

<a href="https://opencollective.com/select-mean"><img src="https://opencollective.com/select-mean/individuals.svg?width=890"></a>

#### Organizations

Support this project with your organization. Your logo will show up here with a link to your website. [[Contribute](https://opencollective.com/select-mean/contribute)]

<a href="https://opencollective.com/select-mean/organization/0/website"><img src="https://opencollective.com/select-mean/organization/0/avatar.svg"></a>
<a href="https://opencollective.com/select-mean/organization/1/website"><img src="https://opencollective.com/select-mean/organization/1/avatar.svg"></a>
<a href="https://opencollective.com/select-mean/organization/2/website"><img src="https://opencollective.com/select-mean/organization/2/avatar.svg"></a>
<a href="https://opencollective.com/select-mean/organization/3/website"><img src="https://opencollective.com/select-mean/organization/3/avatar.svg"></a>
<a href="https://opencollective.com/select-mean/organization/4/website"><img src="https://opencollective.com/select-mean/organization/4/avatar.svg"></a>
<a href="https://opencollective.com/select-mean/organization/5/website"><img src="https://opencollective.com/select-mean/organization/5/avatar.svg"></a>
<a href="https://opencollective.com/select-mean/organization/6/website"><img src="https://opencollective.com/select-mean/organization/6/avatar.svg"></a>
<a href="https://opencollective.com/select-mean/organization/7/website"><img src="https://opencollective.com/select-mean/organization/7/avatar.svg"></a>
<a href="https://opencollective.com/select-mean/organization/8/website"><img src="https://opencollective.com/select-mean/organization/8/avatar.svg"></a>
<a href="https://opencollective.com/select-mean/organization/9/website"><img src="https://opencollective.com/select-mean/organization/9/avatar.svg"></a>

## License

MIT
