Hi,

I'm Luc, a full-stack software engineer from Voerendaal, the Netherlands.
I started working as a freelance software engineer and scrum master under the company name cofx in 2022: https://cofx.nl.

I wrote some blog posts for one of my previous employers, which are available on their [tech blog](https://www.kabisa.nl/tech/). 
Hopefully, I'll pick up blogging again in the near future.
Visit https://blog.cofx.nl to see whether we've already reached the near future.

I'll use this personal README.md as an introduction to my most noteworthy open source work.
This is GitHub, after all.

# Clojure

## [WIP] Clojure for beginners

Clojure for beginners is collection of assignments that should help you to get to know Clojure and ClojureScript.
It is still a work in progress.

* Repo: https://github.com/ljpengelen/clojure-for-beginners
* On-line version: https://cfb.cofx.nl/

## Hashing assets

I created a Leiningen plugin and a hook for shadow-cljs that actually do the same thing: adding a hash to the filename of JS and CSS files before including them in `index.html`.

* Leiningen plugin: https://github.com/ljpengelen/lein-hash-assets
* Shadow-cljs hook: https://github.com/ljpengelen/shadow-cljs-hash-assets-hook

# JavaScript

## Prefix commit message

Many projects that I worked on had the requirement that each commit message should contain a reference to a JIRA-ticket.
Because typing those JIRA identifiers over and over again is no fun, I wrote a small script that takes the JIRA identifier from the name of the current branch.

Repo: https://github.com/ljpengelen/prefix-commit-message
NPM package: https://www.npmjs.com/package/prefix-commit-message?activeTab=readme

## Indoor positioning plugin for Cordova

For Kabisa, I created a Cordova plugin for Signify's indoor positioning SDK.

Repo: https://github.com/kabisa/indoor-positioning-cordova-plugin

# Various small contributions

* https://github.com/borkdude/quickblog
* https://github.com/cryogen-project/cryogen-docs
* https://github.com/tggreene/integrant-repl-autoreload
* https://github.com/cryogen-project/cryogen
* https://github.com/dpa99c/cordova-plugin-firebasex
* https://github.com/NimaSoroush/differencify
* https://github.com/mimischi/dokku-dockerfile
* https://github.com/kabisa/maji-extras
