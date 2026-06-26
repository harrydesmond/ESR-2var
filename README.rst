ESR-2var
========

A two-variable fork of `Exhaustive Symbolic Regression (ESR)
<https://github.com/DeaglanBartlett/ESR>`_.

ESR-2var extends ESR from a single independent variable (``x``) to two
(``x`` and ``y``). The modifications are confined to ``esr/generation/`` (the
function-library generator, simplifier and duplicate checker) and
``esr/fitting/`` (notably ``sympy_symbols.py``); everything else follows
upstream ESR.

For the method, installation, documentation, examples and citation details,
see the original ESR repository, which this fork tracks:

* Repository: https://github.com/DeaglanBartlett/ESR
* Documentation: https://esr.readthedocs.io
* Paper: https://arxiv.org/abs/2211.11461

The pre-computed two-variable function libraries are generated separately and
are not bundled in this repository.

Licence
-------

MIT (see ``LICENSE``).
