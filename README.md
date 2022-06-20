# Repository template for Go 1.18

This repository template includes a basic setup for projects developed with Go 1.18.

> ❌ IMPORTANT ❌
>
> Don't forget to edit the module name and - if you're not me - the LICENSE.

## Content

| File                     | Description                                                                                               |
| ------------------------ | --------------------------------------------------------------------------------------------------------- |
| .editorconfig            | A simple editor configuration                                                                             |
| .gitattributes           | Set `text=auto` attribute for all files                                                                   |
| .gitignore               | A list of common ignored files and directories                                                            |
| go.mod                   | An empty go module file. Change the module name on the first commit                                       |
| LICENSE                  | A MIT license. If you're not me, switch to your preferred license or change the name in the © notice      |
| .github/dependabot.yml   | [Dependabot](https://github.com/dependabot) configuration to update GitHub Actions and Go modules version |
| .github/workflows/ci.yml | A basic GitHub Actions workflow for linting and testing when a Go file is updated                         |
