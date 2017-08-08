The purpose of this repository is to maintain frequently asked questions (FAQ)
and answers about using the GITLAB continuous integration (CI) services,
specifically for projects within the RNSD.

# FAQ


## How do I set up cool badges for my project?

The standard is to include the relevant code at the top of `README.md` file.

Check out this file's source for the two badges below.

The build status badge can be included like this [![build status](https://code.ornl.gov/ww5/rnsd-gitlab-faq/badges/master/build.svg)](https://code.ornl.gov/ww5/rnsd-gitlab-faq/commits/master).

The coverage status badge can be included like this [![coverage report](https://code.ornl.gov/ww5/rnsd-gitlab-faq/badges/master/coverage.svg)](https://code.ornl.gov/ww5/rnsd-gitlab-faq/commits/master).


## How do I enable CI for my project?

You need two things to get started.

1. A .gitlab-ci.yml file at your project root.

2. A Runner enabled on your test machine with a handshake to the project.

GITLAB's directions are pretty easy to follow.

Don't forget to use `run` to start the runner
```
gitlab-runner run
```
and you can get a lot of good info adding the `--debug` option.
```
gitlab-runner run --debug
```
