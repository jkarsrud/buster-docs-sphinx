.. default-domain:: js
.. highlight:: javascript
.. _buster-assertions:

=================
buster-assertions
=================

Version:
    0.10.1 (2012-04-26)

Module:
    ``var assertions = require("buster-assertions");``

Browser:
    ``buster.assertions;``

A collection of assertions to be used with a unit testing framework. 
``buster-assertions`` works well with any CommonJS compliant testing framework
out of the box, and can easily be configured to work with most any testing framework.
See also :ref:`expectations if you like the alternative API (``expect(thing).toBe*`).

``buster-assertions`` contains lots of assertions. We strongly believe that high-level
assertions are essential in the interest of producing clear and intent-revealing tests,
and they also give you to-the-point failure messages.