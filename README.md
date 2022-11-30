# stack-templates


## Synopsis

My personal stack templates


## Description

Stack can use a template to scaffold up a new project and has a facility to
allow anyone to make and share templates. These are mine.

The `basic-` project templates create a basic Haskell project structure
The nix-based projects in this set all include `ghcid`, `hasktags` and `hlint`

    template name             uses nix
    ----------------------------------------------
    basic.hsfiles             no
    basic-nix.hsfiles         optional, flakes
    basic-nix-shell.hsfiles   optional, nix-shell

## Development

To create a project with one of these templates

    $ stack new my-project github:dino-/basic-nix


## Contact

### Authors

Dino Morelli <dino@ui3.info>

The templates here that integrate Stack with (optional) Nix were adapted from
insights I gather from an excellent blog post from Tweag:

[Smooth, non-invasive Haskell Stack and Nix shell integration]<https://www.tweag.io/blog/2022-06-02-haskell-stack-nix-shell/>
