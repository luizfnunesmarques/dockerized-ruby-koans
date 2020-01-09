# Dockerized Ruby Koans [![CircleCI](https://circleci.com/gh/luizfnunesmarques/dockerized-ruby-koans.svg?style=svg)](https://circleci.com/gh/luizfnunesmarques/cokoans)

Ruby Koans with a container. No more dependency pain :-). Inspired by the work done on [Clojure](https://www.google.com), [Golang](https://github.com/cdarwin) and [Elixir](https://github.com/elixirkoans/elixir-koans).

## Pre dependencies (run on a terminal)
- A Docker setup working:
 `docker -v `
- Clone this repository:
 `https://github.com/luizfnunesmarques/dockerized-ruby-koans`

## Playing with Ruby
  - run the koans bash script
  `./ruby-koans`
- The files you edit on your machine are always reflected in the running container.

## Common issues
  * Permission denied when running the script:
    * Give it to it :rocket:
      * `chmod +x ruby-koans`

## Credits for the Koans
Ruby Koans: https://github.com/edgecase/ruby_koans
