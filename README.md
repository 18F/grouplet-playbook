## Grouplet Playbook

"Grouplets" are self-organizing teams of volunteers that address concerns
affecting a broad segment of the organization. 18F currently has two types of
Grouplets.

This website is based upon the [18F Guides
Template](https://github.com/18F/guides-template/).

### Generating the site/hosting locally

You will need [Ruby](https://www.ruby-lang.org) ( > version 2.1.5 ). You may
consider using a Ruby version manager such as
[rbenv](https://github.com/sstephenson/rbenv) or [rvm](https://rvm.io/) to
help ensure that Ruby version upgrades don't mean all your
[gems](https://rubygems.org/) will need to be rebuilt.

On OS X, you can use [Homebrew](http://brew.sh/) to install Ruby in
`/usr/local/bin`, which may require you to update your `$PATH` environment
variable:

```shell
$ brew update
$ brew install ruby
```

To create a new guide and serve it locally, where `MY-NEW-GUIDE` is the name
of your new repository:

```shell
$ git clone git@github.com:18F/grouplet-playbook.git MY-NEW-GUIDE
$ cd MY-NEW-GUIDE
$ ./go init
$ ./go serve
```

This will check that your Ruby version is supported, install the [Bundler
gem](http://bundler.io/) if it is not yet installed, install all the gems
needed by the template, and launch a running instance on
`http://localhost:4000/guide/`. (Make sure to include the `/`! The built-in
Jekyll webserver doesn't redirect to it.) That page contains further
instructions on how to adapt the template to a new guide repository.

After going through these steps, run `./go` to see a list of available
commands. The `serve` command is the most common for routine development.

### Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in
[CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright
> and related rights in the work worldwide are waived through the [CC0 1.0
> Universal public domain
> dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication.
> By submitting a pull request, you are agreeing to comply with this waiver of
> copyright interest.
