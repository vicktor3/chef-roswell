# chef-roswell
[![Build Status](https://circleci.com/gh/Rudolph-Miller/chef-roswell.svg?style=shield)](https://circleci.com/gh/Rudolph-Miller/chef-roswell)

- [Roswell](https://github.com/snmsts/roswell) is a project designed to be an environment manager for Common Lisp. Roswell allows the user to maintain seperate flavors and versions of Common Lisp efficiently.
- Chef cookbook for [Roswell](https://github.com/snmsts/roswell) is a collection of recipies, tips, and advice on using Roswell.
- In order to get started, make sure you have installed Roswell and Chef-Roswell, performed Roswell set up, and installed SBCL of the specific version.

## Attribues
- branch(default: "release"): Branch of Roswell.
- user(default: nil): User to install Roswell
- prefix(default: "/usr/local"): Prefix for ./configure
- version(default: nil): Version of SBCL

## Author of Roswell
SANO Masatoshi (snmsts@gmail.com)

## Author
Rudolph Miller (chopsticks.tk.ppfm@gmail.com)

## License
MIT
