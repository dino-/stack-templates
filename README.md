# stack-templates

## !!!!! ATTENTION !!!!!

This project has been permanently moved to Codeberg
([stack-templates](https://codeberg.org/dinofp/stack-templates)) and is no longer actively
maintained on Github. Do not use the Issues system on Github to report to us.
Don't bother forking or getting source from here as it will not be updated.

Microsoft is not a friend of open-source and we do ourselves a disservice
giving them this impressive power over our work.

Never forget 2020 when Github (a Microsoft product) removed the popular
open-source `youtube-dl` project, sparking enormous controversy. The issue is
not that pushback eventually prompted reinstatement - Github can and will act
like this against us at any time.

## !!!!! ATTENTION !!!!!

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
