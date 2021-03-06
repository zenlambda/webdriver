# W3C WebDriver Specification

This repository contains the W3C specification
for the browser automation protocol known as _WebDriver_.

The current editor's draft of the specification can be read
at https://w3c.github.io/webdriver/webdriver-spec.html.
The main repository is at https://github.com/w3c/webdriver,
and bugs can be filed against the
[W3C bug tracker](https://www.w3.org/Bugs/Public/enter_bug.cgi?comment=&blocked=20860&short_desc=%5BWebDriver%20Spec%5D%3A%20&product=Browser%20Test%2FTools%20WG&component=WebDriver).

The specification can be read in `webdriver-spec.html`,
which is generated by executing:

    make

The numbers at the start of each file corresponds to sections in the spec
and will be included in the final document in that order.

And to validate the specification:

    make validate