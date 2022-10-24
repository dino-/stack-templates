# stack-templates


## Synopsis

My personal stack templates


## Description

Stack can use a template to scaffold up a new project and has a facility to
allow anyone to make and share templates. These are mine.

The `basic-` project templates create a basic Haskell project structure
The nix-based projects in this set all include `ghcid`, `hasktags` and `hlint`

    template name                   build system    uses nix
    --------------------------------------------------------------
    basic-stack.hsfiles             stack           no
    basic-stack-nix.hsfiles         stack           optional, flakes
    basic-stack-nix-shell.hsfiles   stack           optional, nix-shell

## Development

To create a project with one of these templates

    $ stack new my-project github:dino-/basic-stack-nix


## Contact

### Authors

Dino Morelli <dino@ui3.info>
