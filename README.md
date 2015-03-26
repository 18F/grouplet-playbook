## Grouplet Playbook

A "Grouplet" (or "Working Group", or "Guild", or what-have-you) is a
self-organizing team of volunteers that aims to address a concern affecting a
broad segment of the organization. Grouplet leaders have no authority and
little if any direct resources; it is incumbent upon them to recruit
volunteers and make the best use of their time. 

This guide aims to provide aspiring Grouplet organizers with a "bag of tricks"
for:

- getting a Grouplet organized and productive very quickly,
- for maintaining team cohesion over time,
- for understanding the various forces at play in an organization, and
- for making the entire undertaking both high-impact and fun!

This guide is contains content also found in the [18F Automated Testing
Playbook](https://github.com/18F/automated-testing-playbook), which is based
on Mike Bland's [Unit Testing Perspectives](http://goo.gl/eE8IUw)
presentation, which is licensed under [CC BY
4.0](http://creativecommons.org/licenses/by/4.0/deed.en_US).

Mike's (very) long-form article [Goto Fail, Heartbleed, and Unit Testing
Culture](http://martinfowler.com/articles/testing-culture.html#culture-change)
contains many more details and examples regarding the Google Testing
Grouplet's effort to drive adoption of automated testing. His hour-long talk
[Large Scale Development Culture Change: Google and the US
Government](https://18f.gsa.gov/2014/12/11/large-scale-development-culture-change/)
is an attempt to relate many of these experiences to the effort to improve
federal government IT development practices.

This playbook is divided into three sections:

### [TL;DR](pages/tldr.md)

A high-level view of how 18F working groups are launched and paused.

### [Processes and Artifacts](pages/processes-and-artifacts.md)

Processes and artifacts that can help rapidly organize a grouplet, as well as
maintain momentum, productivity, and morale.

### [Education and Advocacy](pages/education-and-advocacy.md)

Models and strategies for driving adoption of best practices throughout a
development culture.

### Generating the site/hosting locally

You will need [Ruby](https://www.ruby-lang.org) ( > version 2.1.5 ). You may
also consider using a Ruby version manager such as
[rbenv](https://github.com/sstephenson/rbenv) to help ensure that Ruby version
upgrades don't mean all your [gems](https://rubygems.org/) will need to be
rebuilt.

To run your own local instance:

```
$ git clone git@github.com:18F/grouplet-playbook.git
$ cd grouplet-playbook
$ ./go init
$ ./go serve
```

This will check that your Ruby version is supported, install the [Bundler
gem](http://bundler.io/) if it is not yet installed, install all the gems
needed by the playbook, and launch a running instance on
`http://localhost:4000/grouplet-playbook/`.

After going through these steps, run `./go` to see a list of available
commands. The `serve` command is the most common for routine development.

### Contributing

1. Fork the repo ( https://github.com/18F/grouplet-playbook/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

Feel free to ping [@mbland](https://github.com/mbland) with any questions you
may have, especially if the current documentation should've addressed your
needs, but didn't.

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
