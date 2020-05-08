# MJML 4

<p align="center">
  <a href="https://mjml.io" target="_blank">
    <img width="250"src="https://mjml.io/assets/img/litmus/mjmlbymailjet.png">
  </a>
</p>

---

# Introduction

`MJML` is a markup language created by [Mailjet](https://www.mailjet.com/) and designed to reduce the pain of coding a responsive email. Its semantic syntax makes it easy and straightforward while its rich standard components library fastens your development time and lightens your email codebase. MJML’s open-source engine takes care of translating the `MJML` you wrote into responsive HTML.

<p align="center">
  <a href="https://mjml.io" target="_blank">
    <img width="75%" src="https://cloud.githubusercontent.com/assets/6558790/12450760/ee034178-bf85-11e5-9dda-98d0c8f9f8d6.png">
  </a>
</p>

# Installation

You can install `MJML` with `NPM` to use it with NodeJS or the Command Line Interface. If you're not sure what those are, head over to <a href="#usage">Usage</a> for other ways to use MJML.

```bash
npm install -g mjml
```

You can also run `yarn build:watch` to rebuild the package as you code.

# Usage

## Applications and plugins

MJML comes with an ecosystem of tools and plugins, check out:
- [Visual Studio Code plugin](https://github.com/attilabuti/vscode-mjml) (MJML is included)
- [Atom plugin](https://atom.io/users/mjmlio) (MJML needs to be installed separately)
- [Sublime Text plugin](https://packagecontrol.io/packages/MJML-syntax) (MJML needs to be installed separately)

## Command line interface

> Compiles the file and outputs the HTML generated in `output.html`

```bash
mjml input.mjml -o output.html
```

You can pass optional `arguments` to the CLI and combine them.

argument | description | default value
---------|--------|--------------
`mjml -m [input]` | Migrates a v3 MJML file to the v4 syntax | NA
`mjml [input] -o [output]` | Writes the output to [output] | NA
`mjml [input] -s` | Writes the output to `stdout` | NA
`mjml -w [input]` | Watches the changes made to `[input]` (file or folder) | NA
`mjml [input] --config.beautify` | Beautifies the output (`true` or `false`) | true
`mjml [input] --config.minify` | Minifies the output (`true` or `false`) | false

See [mjml-cli documentation](https://github.com/mjmlio/mjml/blob/master/packages/mjml-cli/README.md) for more information about config options.

