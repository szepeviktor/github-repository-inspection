# How to inspect a GitHub repository

[![theories](https://img.shields.io/badge/more-theories-purple)](https://github.com/stars/szepeviktor/lists/theory)

## Git version control

1. Each project should have a separate repository and GitHub Issues
1. Set repository details in top right corner: About :gear:
1. Set up environments: match branch and environment names
1. Make commits with proper email address registered here on GitHub

## The very first commit

If the project starts with a sample application or starter package
make the first commit with the same content and with commit message
"vendor-name/sample-app v1.2.3"
otherwise add `LICENSE` file (MIT) with message "Initial commit"

## Documents and configuration files

Check [community standards](https://github.com/szepeviktor/github-repository-inspection/community)

1. [Community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
1. Add [configuration files and documents](#naming-files-in-the-root-directory)
1. Include Requirements, Installation, Configuration,
    Usage sections in `README.md`
1. Set editor/IDE configuration in `.editorconfig`
1. List ignored files in `.gitignore`
    - Do not keep downloaded or generated code in the repository
    - List ignored OS, IDE and local environment files
        in `git config --global core.excludesFile ~/.gitignore`
1. List files not intended to be distributed (`export-ignore`)
    in ZIP archives and list
    [generated files and documentation](https://github.com/github/linguist/blob/master/docs/overrides.md#summary)
    in `.gitattributes`

## Application setup

1. Choose a coding standard (PSR-12, Laravel, custom) in `phpcs.xml`,
    include `Generic.PHP.RequireStrictTypes`
1. Keep namespaced PHP source code in `/src` directory
    as per [PSR-4](https://www.php-fig.org/psr/psr-4/)
1. Use Composer for class and function autoloading

## Daily work

1. Use Pull Requests to send code to the repository
1. Review Pull Requests even when working alone
1. Tag releases
1. Follow a release checklist

See also
[Cleaning Lady Check list :broom::woman::memo:](https://web.archive.org/web/20200831185120/https://tomasvotruba.com/cleaning-lady-checklist/)

## Naming files in the root directory

There are several things to consider in the root directory of a repository.

1. Keep only configuration files and documents in the root directory
2. Name `configuration files` with lowercase letters, these are for machines
3. Name `DOCUMENTS` with uppercase letters, these are for humans
4. Use as few dot `.files` as you can - e.g. `ls` command hides dot files by default

So your root will be clean,
and you can differentiate configuration files from documents at a glance.

## Support my work

Please consider supporting my work as these lists take years to compile.

[![Sponsor](https://github.com/szepeviktor/.github/raw/master/.github/assets/github-like-sponsor-button.svg)](https://github.com/sponsors/szepeviktor)

Thank you!

---

## Requirements

- runtime version
- other packages

## Installation

- using Composer
- other ways

## Configuration

- create .ini file
- adjust settings

## Usage

- how to start
- code samples
