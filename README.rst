Slides Agile
============

|gitpitch| |build_status| |code_climate| |github_tag| |test_coverage| |license|

Slides Agile

:Version: 0.0.0
:Web: https://github.com/hadenlabs/slides-agile
:Download: https://github.com/hadenlabs/slides-agile
:Source: https://github.com/hadenlabs/slides-agile
:Keywords: slides-agile

.. contents:: Table of Contents:
    :local:

Requirements
------------

.. code-block:: bash

   $ make setup

Actions Makefile
----------------

.. code-block:: bash

  λ make
      ༼ つ ◕_◕ ༽つ Makefile for Cookiecutter docker

      Usage:
          make environment               create environment with pyenv
          make install                   install dependences python by env
          make clean                     remove files of build
          make setup                     install requirements

          Docker:

              make docker.build         build all services with docker-compose
              make docker.down          down services docker-compose
              make docker.ssh           connect by ssh to container
              make docker.stop          stop services by env
              make docker.verify_network           verify network
              make docker.up             up services of docker-compose
              make docker.list           list services of docker

          Tests:

              test.lint                  Run all pre-commit
              test.syntax                Run all syntax in code

Changelog
---------

Please see `CHANGELOG <CHANGELOG.rst>`__ for more information what has
changed recently.

Contributing
------------

Please see `CONTRIBUTING <CONTRIBUTING.rst>`__ for details.

Credits
-------

Made with :heart: :coffee: and :pizza: by `hadenlabs <https://github.com/hadenlabs>`__

-  `All Contributors <AUTHORS>`__

.. |code_climate| image:: https://codeclimate.com/github/hadenlabs/slides-agile/badges/gpa.svg
  :target: https://codeclimate.com/github/hadenlabs/slides-agile
  :alt: Code Climate

.. |github_tag| image:: https://img.shields.io/github/tag/hadenlabs/slides-agile.svg?maxAge=2592000
  :target: https://github.com/hadenlabs/slides-agile
  :alt: Github Tag

.. |build_status| image:: https://travis-ci.org/hadenlabs/slides-agile.svg
  :target: https://travis-ci.org/hadenlabs/slides-agile
  :alt: Build Status Tag

.. |gitpitch| image:: https://gitpitch.com/assets/badge.svg
  :target: https://gitpitch.com/hadenlabs/slides-agile?grs=github&t=white
  :alt: GitPitch

.. |license| image:: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square
  :target: LICENSE
  :alt: License

.. |test_coverage| image:: https://codeclimate.com/github/hadenlabs/slides-agile/badges/coverage.svg
  :target: https://codeclimate.com/github/hadenlabs/slides-agile/coverage
  :alt: Test Coverage
