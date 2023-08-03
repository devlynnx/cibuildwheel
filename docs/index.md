***/
matrix run :RUN MATRIX
---

# cibuildwheel

{%
   include-markdown "../README.md"
   start="<!--intro-start-->"
   end="<!--intro-end-->"
%}

To get started, head over to the [setup guide](setup.md).

How it works
------------

This diagram summarises the steps that cibuildwheel takes on each platform to build your package's wheels.

{%
   include-markdown "diagram.md"
%}

This isn't exhaustive, for a full list of the things cibuildwheel can do, check the [options](options.md) page.
