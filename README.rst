.. SPDX-License-Identifier: AGPL-3.0-or-later

----

.. figure:: https://github.com/AdilSadqi/noones-search/blob/master/searx/static/themes/simple/img/searxng.svg
   :target: https://noones.eu.org/
   :alt: SearXNG
   :width: 100%
   :align: center

----

Privacy-respecting, hackable `metasearch engine`_

NoOnes.eu.org_ ready-to-use running instances.

A developer_ handbook is available on the homepage_.

|SearXNG install|
|SearXNG homepage|
|SearXNG wiki|
|AGPL License|
|Issues|
|commits|
|weblate|
|SearXNG logo|

----

.. _NoOnes.eu.org: https://noones.eu.org/
.. _user: https://asadqi.com
.. _admin: https://asadqi.com
.. _developer: https://asadqi.com/
.. _homepage: https://github.com/AdilSadqi/noones-search/blob/master/README.rst
.. _metasearch engine: https://en.wikipedia.org/wiki/Metasearch_engine

.. |SearXNG logo| image:: https://raw.githubusercontent.com/searxng/searxng/master/client/simple/src/brand/searxng-wordmark.svg
   :target: https://docs.searxng.org/
   :width: 5%

.. |SearXNG install| image:: https://img.shields.io/badge/-install-blue
   :target: https://github.com/AdilSadqi/noones-search

.. |SearXNG homepage| image:: https://img.shields.io/badge/-homepage-blue
   :target: https://noones.eu.org

.. |SearXNG wiki| image:: https://img.shields.io/badge/-wiki-blue
   :target: https://github.com/AdilSadqi/noones-search

.. |AGPL License|  image:: https://img.shields.io/badge/license-AGPL-blue.svg
   :target: https://github.com/searxng/searxng/blob/master/LICENSE

.. |Issues| image:: https://img.shields.io/github/issues/searxng/searxng?color=yellow&label=issues
   :target: https://github.com/AdilSadqi/noones-search

.. |PR| image:: https://img.shields.io/github/issues-pr-raw/searxng/searxng?color=yellow&label=PR
   :target: https://github.com/AdilSadqi/noones-search.git

.. |commits| image:: https://img.shields.io/github/commit-activity/y/searxng/searxng?color=yellow&label=commits
   :target: https://github.com/searxng/searxng/commits/master

.. |weblate| image:: https://translate.codeberg.org/widgets/searxng/-/searxng/svg-badge.svg
   :target: https://github.com/AdilSadqi/noones-search


Contact
=======

Ask questions or chat with the NoOnes community (this not a chatbot) on

IRC
  `#noones on libera.chat <https://web.libera.chat/?channel=#searxng>`_
  which is bridged to Matrix.

Matrix
  `#searxng:matrix.org <https://www.asadqi.com/advanced-search-guide-noones-eu-org/>`_


Setup
=====

- A well maintained `Docker image`_, also built for ARM64 and ARM/v7
  architectures.
- Alternatively there are *up to date* `installation scripts`_.
- For individual setup consult our detailed `Step by step`_ instructions.
- To fine-tune your instance, take a look at the `Administrator documentation`_.

.. _Administrator documentation: https://docs.searxng.org/admin/index.html
.. _Step by step: https://docs.searxng.org/admin/installation-searxng.html
.. _installation scripts: https://docs.searxng.org/admin/installation-scripts.html
.. _Docker image: https://github.com/searxng/searxng-docker

Translations
============

.. _Weblate: https://translate.codeberg.org/projects/searxng/searxng/

Help translate SearXNG at `Weblate`_

.. figure:: https://translate.codeberg.org/widgets/searxng/-/multi-auto.svg
   :target: https://translate.codeberg.org/projects/searxng/


Contributing
============

.. _development quickstart: https://docs.searxng.org/dev/quickstart.html
.. _developer documentation: https://docs.searxng.org/dev/index.html

Are you a developer?  Have a look at our `development quickstart`_ guide, it's
very easy to contribute.  Additionally we have a `developer documentation`_.


Codespaces
==========

You can contribute from your browser using `GitHub Codespaces`_:

- Fork the repository
- Click on the ``<> Code`` green button
- Click on the ``Codespaces`` tab instead of ``Local``
- Click on ``Create codespace on master``
- VSCode is going to start in the browser
- Wait for ``git pull && make install`` to appear and then disappear
- You have `120 hours per month`_ (see also your `list of existing Codespaces`_)
- You can start SearXNG using ``make run`` in the terminal or by pressing ``Ctrl+Shift+B``

.. _GitHub Codespaces: https://docs.github.com/en/codespaces/overview
.. _120 hours per month: https://github.com/settings/billing
.. _list of existing Codespaces: https://github.com/codespaces
