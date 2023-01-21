Hi,

I'm Luc, a full-stack software engineer from Voerendaal, the Netherlands.
I started working as a freelance software engineer and scrum master under the company name cofx in 2022: https://cofx.nl.
I'm not afraid of picking up any language or technology, but most of my experience is with Java, Clojure, and React-based front ends.

I wrote some blog posts for Kabisa, one of my previous employers, which are available on their [tech blog](https://www.kabisa.nl/tech/). 
Hopefully, I'll pick up blogging again in the near future.
Visit [blog.cofx.nl](https://blog.cofx.nl) to see whether we've already reached the near future.

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

# Musical quiz

Top 10 is a musical quiz where the participants have to guess who is who based on their taste in music.
The front end is a [re-frame](https://github.com/day8/re-frame) app written in ClojureScript.
The back end uses [Vert.x](https://vertx.io/) for Java.

* Repo: https://github.com/ljpengelen/top10
* On-line version: https://top10.cofx.nl

# Wish lists

Lijstje is a small app for creating and sharing wish lists.
It's available in Dutch only at the moment.
There were already a lot of apps with similar functionality before I started working on this one.
I couldn't shake the thought that there should be one more.
Now, exactly the right number of wish list apps exist.

* Repo: https://github.com/ljpengelen/lijstje
* On-line version: https://lijstje.cofx.nl

# JavaScript

## Prefix commit message

Many projects that I worked on had the requirement that each commit message should contain a reference to a JIRA-ticket.
Because typing those JIRA identifiers over and over again is no fun, I wrote a small script that takes the JIRA identifier from the name of the current branch.

Repo: https://github.com/ljpengelen/prefix-commit-message
NPM package: https://www.npmjs.com/package/prefix-commit-message?activeTab=readme

## Indoor positioning plugin for Cordova

For Kabisa, I created a Cordova plugin for Signify's indoor positioning SDK.

* Repo: https://github.com/kabisa/indoor-positioning-cordova-plugin

# Python

## Markdown to PDF

I wrote a blogpost about [creating good looking PDF with Markdown and CSS](https://blog.cofx.nl/pdfs-from-markdown-and-css.html) after I stumbled upon the excelent [WeasyPrint](https://weasyprint.org/) by coincidence.
The blogpost comes with a Python script that shows how this would work in practice.

* Repo: https://blog.cofx.nl/pdfs-from-markdown-and-css.html

# Various small contributions

* https://github.com/borkdude/quickblog
* https://github.com/cryogen-project/cryogen-docs
* https://github.com/tggreene/integrant-repl-autoreload
* https://github.com/cryogen-project/cryogen
* https://github.com/dpa99c/cordova-plugin-firebasex
* https://github.com/NimaSoroush/differencify
* https://github.com/mimischi/dokku-dockerfile
* https://github.com/kabisa/maji-extras
