# [jessesquires.com](https://www.jessesquires.com) ![CI](https://github.com/jessesquires/jessesquires.com/workflows/CI/badge.svg)

*Turing complete with a stack of `0xdeadbeef`*

![Logo](https://www.jessesquires.com/ico/favicon-180-precomposed.png)

## About

This is my personal site and blog. It is built with [Jekyll](https://jekyllrb.com) and [Bootstrap](https://getbootstrap.com), and hosted at [NearlyFreeSpeech](https://nearlyfreespeech.net).

## Requirements

- [Bundler](https://bundler.io)
- [NPM](https://www.npmjs.com)

## Dependencies

### Gems

- [jekyll](https://jekyllrb.com) ([Latest](https://github.com/jekyll/jekyll/releases/latest)) ([Cheat Sheet](https://learn.cloudcannon.com/jekyll-cheat-sheet/))
- [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)

#### Updating Gems

```bash
$ make update-bundle
```

### NPM packages

- [Bootstrap](https://getbootstrap.com) ([package](https://www.npmjs.com/package/bootstrap))
- [Bootstrap Icons](https://icons.getbootstrap.com) ([package](https://www.npmjs.com/package/bootstrap-icons))

#### Updating packages

```bash
$ make update-deps
```

### Other

- [GoatCounter Analytics](https://www.goatcounter.com)
- [Ubuntu Mono font](https://www.google.com/fonts/specimen/Ubuntu+Mono)

## Usage

### Installation

```bash
$ git clone https://github.com/jessesquires/jessesquires.com.git
$ cd jessesquires.com/
$ make install
```

### Building the site

```bash
$ make
```

### Previewing the site locally

```bash
$ make preview
```

### Verifying DNS setup

```bash
$ dig www.jessesquires.com +nostats +nocomments +nocmd
```

### Install software on NFSN

```bash
$ cd home/protected/      # preferred directory for installing
$ wget <URL-to-some-file> # download
$ tar -zxvf file.tar.gz   # extract
$ mkdir bin               # if needed

# follow any install instructions
# put binary in protected/bin/
# add `export PATH=$PATH:/home/protected/bin/` to your `.bash_profile`
```

## License

> **Copyright &copy; 2014-present Jesse Squires.**

⚠️ You **MAY NOT** reproduce or re-publish this site and its content in its entirety on your own, or otherwise rebrand or impersonate `jessesquires.com`. ⚠️

If you would like to use this site as a template for your own custom site, [use my designated template repo](https://github.com/jessesquires/template-jekyll-site) and refer to this site as an example.

<a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

All code is licensed under an [MIT License](https://opensource.org/licenses/MIT).

The *Ubuntu Mono* font is licensed under the [Ubuntu Font License](https://ubuntu.com/legal/font-licence).
