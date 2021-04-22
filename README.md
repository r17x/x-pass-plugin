# x-pass-plugin
> Xbar plugin for [the standard unix password manager](https://www.passwordstore.org/)

<p align="center">
<img 
src="https://github.com/ri7nz/x-pass-plugin/blob/master/README.png?raw=true" alt="password store preview" />
</p>

## Table of Content
<!-- vim-markdown-toc GFM -->

* [Features](#features)
  * [Prerequisite](#prerequisite)
  * [How to Install](#how-to-install)
    * [Use with `curl` or `wget`](#use-with-curl-or-wget)
    * [Browse in Plugin](#browse-in-plugin)
* [License](#license)

<!-- vim-markdown-toc -->
   
## Features

* [x] Show list of `pass list` in menu bar 
* [x] Copy to Clipboard by click an item in showing list

### Prerequisite
   
* [x] [Xbar](https://xbarapp.com) (_Required_) 
* [x] [the standard unix password manager](https://www.passwordstore.org/) (_Required_)
* [ ] [pinentry-mac](https://formulae.brew.sh/formula/pinentry-mac) (_Recommended_)
   
### How to Install
#### Use with `curl` or `wget`
```shell
> curl https://github.com/ri7nz/x-pass-plugin/blob/master/pass.sh\?raw=true \
  -o ~/Library/Application\ Support/xbar/plugins/pass.sh 

> # OR

> wget https://github.com/ri7nz/x-pass-plugin/blob/master/pass.sh\?raw=true -O \
  ~/Library/Application\ Support/xbar/plugins/pass.sh 

```
#### Browse in Plugin
1. Open menu _**Xbar -> "Plugin Browser"**_
2. Select _**"Tools"**_
3. Find _**"x-pass-plugin"**_
4. Click Install

## License
[LICENSE](./LICENSE)
