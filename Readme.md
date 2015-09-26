```
        _               _
       | |             | |
     __| | _____   __  | |__   _____  __
    / _` |/ _ \ \ / /  | '_ \ / _ \ \/ /
   | (_| |  __/\ V /   | |_) | (_) >  <
    \__,_|\___| \_/    |_.__/ \___/_/\_\
                                | |
   _____  ____ _ _ __ ___  _ __ | | ___  ___
  / _ \ \/ / _` | '_ ` _ \| '_ \| |/ _ \/ __|
 |  __/>  < (_| | | | | | | |_) | |  __/\__ \
  \___/_/\_\__,_|_| |_| |_| .__/|_|\___||___/
                          | |
                          |_|
```

# Dev Box Examples

A collection of development boxes based on Vagrant and Docker.

## Setup

```
git clone https://github.com/alphabetum/dev-box-examples.git --recursive
```

The cloned repository with initialized submodules is about 300 MB.

## Layout

- [`./--`](https://github.com/alphabetum/dev-box-examples/tree/master/__)
  - All submodules. All of the project references in the other directories are
    symbolic links to the relevant project submodule in this directory.
- [`./vagrant`](https://github.com/alphabetum/dev-box-examples/tree/master/vagrant)
  - Projects with a Vagrantfile.
- [`./docker`](https://github.com/alphabetum/dev-box-examples/tree/master/docker)
  - Projects with a Dockerfile.
- [`./apps`](https://github.com/alphabetum/dev-box-examples/tree/master/apps)
  - Projects that are applications with Vagrantfiles and Dockerfiles, rather
    than generic development boxes.
- [`./go`](https://github.com/alphabetum/dev-box-examples/tree/master/go),
  [`./misc`](https://github.com/alphabetum/dev-box-examples/tree/master/misc),
  [`./nodejs`](https://github.com/alphabetum/dev-box-examples/tree/master/nodejs),
  [`./python`](https://github.com/alphabetum/dev-box-examples/tree/master/python),
  [`./ruby`](https://github.com/alphabetum/dev-box-examples/tree/master/ruby),
  etc.
  - Projects by primary programming language.
