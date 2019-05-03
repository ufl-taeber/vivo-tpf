vivo-tpf
========

Another attempt at building a profile by using the TPF API of Vitro.

See https://github.com/mconlon17/vivo-tpf for Dr Conlon's work.

Currently this only works when you are on the University of Florida's network.

Note: there is a design requirement that the code under `src/` should be easy
for non-programmers to understand (simple) and support a wide-range of browsers
(namely, Internet Explorer 9) without any build tools. Dissimilarly, the code
under `tests/` is using Node and Mocha, so feel free to use all the arrow
functions and object destructuring you want.

Quickstart
----------

Open `src/person.html` in a browser.


To run the tests:

    $ npm install
    $ npm test

