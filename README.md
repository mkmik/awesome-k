# Awesome K [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of resources around the k, q, kdb+ and similar languages.

## k

* https://kparc.com/
  * [ref](http://kparc.com/k.txt)
* [The K language](http://archive.vector.org.uk/art10010830): by Arthur Whitney, 2005

### Implementations

Commercial impls:
  * (kdb+/q)(https://kx.com/download): q comes with a k4 engine (just type `\` to enter k interpreter, undocumented)
  * [shakti](https://shakti.com/): k9 bleeding edge development version.

Open source implementations [table](https://bitbucket.org/ngn/k).

* [Ok](https://github.com/JohnEarnest/ok): opensource K5 impl in JS (MIT)
* [kuc](https://github.com/zholos/kuc): K5+ impl in C (GPLv3)
* [kona](https://github.com/kevinlawler/kona): opensource K3 impl in C (ISC)
* [ngn/k](https://bitbucket.org/ngn/k/src/master/readme.txt): K6 impl in C (AGPL)

### Shakti (k7-k9)

* https://kparc.io/: k7 resources
  * [ref] https://ref.kparc.io/
  * [kcc] https://kcc.kparc.io/

## q/kdb+

* [docs](https://code.kx.com/q/)
  * [Q for mortals](https://code.kx.com/q4m3/)
* [jupyterq](https://code.kx.com/v2/ml/jupyterq/)
* [Kdb qSQL vs standard SQL queries](http://www.timestored.com/b/kdb-qsql-query-vs-sql/)

## similar languages

* [klong](https://t3x.org/klong/index.html)
  * [klong vs k](https://t3x.org/klong/klong-vs-k.txt.html)
  
* [ktye/i](https://github.com/ktye/i)

## HN threads

* [Impending kOS](https://news.ycombinator.com/item?id=8475809)
* [The K language](https://news.ycombinator.com/item?id=11561573)

## Quotes

* https://news.ycombinator.com/item?id=22565659

```
K1 was never available outside of Morgan Stanley AFAIK, and I’ve never seen any docs of it. So ...
APL -> A+ : opinionated (vector indices always start at 0, for example) and “electric” GUI (deserves a whole post to describe)

A+ -> K2 : significantly simplified - only ascii, no multidimensional arrays (uses nested vectors instead), much smaller vocabulary but just as effective in the basics department (e.g. the Whitney where/replicate monastic operator replaces 6 or 7 APL operators), added simple dictionaries, workspaces, dropped a lot of math from language. Simpler electric GUI. Time and date native types (as floating point)

K2 -> K3 mostly dropped GUI afaik. Added integral time and date.

k3 -> K4/kdb+: simplifies language more, comprehensive dictionary, TSDB rolled deeply into language (was previously a product written in K), native 64 bit support.

K4->K6: still more simplification, I think k6 is the kOS language. Never left dev state.

K6->k7->k9: continuous simplification, now at shakti rather than kx/firstderivatives - and with much more community involvement.
```
